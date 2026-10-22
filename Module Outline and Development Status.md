# Module Outline and Development Status

**Module:** How Software and Symbolic AI Work  
**Intended learners:** Beginners with no assumed AI background  
**Prerequisites:** Basic familiarity with computers; no programming or AI experience required.

## Learning sequence

| Section | Topics and planned teaching approach | Status | Gaps / checks needed |
|---|---|---|---|
| 1. Software foundations | Define software; hardware/software relationship; system vs application software; examples | Drafted | Team should review examples for clarity |
| 2. How programs execute | Source code, compiler/interpreter, machine instructions; simple input-process-output model | Drafted at overview level | Avoid implying every language follows one identical pipeline |
| 3. Symbolic AI foundations | Symbols, facts, rules, knowledge base, inference engine | Drafted | Verify terminology against cited sources |
| 4. Rule-based reasoning | IF–THEN rules; trace a fact through a rule to a conclusion | Drafted with worked example | Peer review needed |
| 5. Inference strategies | Forward chaining and backward chaining; when each begins and what it seeks | Outline + brief explanation | Expand if time permits |
| 6. Search and planning | Explain that some systems explore possible states/actions to find a path to a goal | Outline only | Add a simple state-space example if included in final scope |
| 7. Case study | MYCIN as a historical rule-based medical expert system; strengths and limitations | Outline only | Check original/credible sources before including performance claims |
| 8. Symbolic and neural AI | Compare explicit human-readable rules with patterns learned from data; introduce neuro-symbolic approaches | Brief draft | Keep comparison introductory and avoid claiming either approach is universally superior |
| 9. Review and application | Short quiz, rule-tracing activity, answer explanations | Drafted for Section 4 | Team should test the questions with a beginner |

## Scope boundaries

### Deep focus
- What software is and its relationship to hardware.
- High-level understanding of how source code is executed.
- Symbolic AI's use of explicit symbols, facts, rules, and inference.
- A step-by-step rule-tracing example.
- Basic forward vs backward chaining.
- Introductory comparison with neural AI.

### Brief introduction only
- Early computer history.
- Operating-system internals and low-level CPU details.
- Advanced theorem proving, search algorithms, and mathematical logic.
- Detailed neural-network mathematics.
- Software development lifecycle, Git/GitHub, cloud software, and open-source licensing.
- Historical case studies such as MYCIN.

## Content status definitions
- **Outline only:** section planned but not yet written as learner-facing content.
- **Drafted:** a first version exists but has not completed peer review.
- **Checked:** another member has reviewed the content and the review outcome is recorded.
- **Needs revision:** review identified a specific issue to correct.

**Current status warning:** “Drafted” does not mean verified. No peer-review outcome or GitHub evidence is asserted in this package; add it only after the team actually completes those steps.

# 1. Software and Symbolic AI: From Instructions to Conclusions

## 1.1 What is software?

**Software** is the collection of programs, instructions, and related data that tells a computer what tasks to perform. **Hardware** is the physical equipment, such as the processor, memory, keyboard, and storage. A computer system needs both: hardware performs physical operations, while software specifies the operations and how they should be coordinated.

Two useful categories are:

- **System software:** helps operate the computer and provides a platform for other programs. An operating system is a common example.
- **Application software:** helps a user perform a task, such as writing a document, editing a photo, or browsing the web.

## 1.2 How does a program run?

A programmer may write source code in a human-readable programming language. The computer cannot directly execute every form of source code as written. Depending on the language and implementation, the code may be compiled into machine code, translated into an intermediate form, interpreted, or processed using a combination of these methods.

- **Source code:** instructions written by a programmer in a programming language.
- **Compiler:** software that translates a program or part of it into another form, often machine code or an intermediate representation.
- **Interpreter:** software that executes program instructions, often by processing them at runtime.
- **Machine instructions:** low-level operations a processor is designed to execute.

A simplified view is:
1. Programmer writes source code
2. Translation / runtime processing
3. Processor executes instructions
4. Program produces output or changes state

This is a high-level model, not a universal pipeline. For example, some implementations compile source code to bytecode and then interpret or just-in-time compile it. The key idea is that software gives the computer structured instructions, and the computer executes those instructions using its hardware.

## 1.3 What is symbolic AI?

**Artificial intelligence (AI)** is a broad field concerned with building systems that perform tasks associated with abilities such as reasoning, learning, perception, or decision-making.

**Symbolic AI** represents information using explicit symbols and structured relationships. A rule-based system might store facts and IF–THEN rules, then apply those rules to infer a conclusion. Its reasoning steps can often be inspected directly.

Important terms:

- **Symbol:** a representation of an object, category, property, or concept, such as `fever` or `battery_low`.
- **Fact:** a statement the system currently treats as true, such as `fever(patient_1)`.
- **Rule:** a conditional statement describing when a conclusion may follow, often written as `IF condition THEN conclusion`.
- **Knowledge base:** the collection of facts and rules available to the system.
- **Inference engine:** the mechanism that checks which rules apply and derives conclusions from the available facts.
- **Inference:** deriving a new conclusion from existing facts and rules.

A symbolic system does not necessarily _“understand”_ a fact as a person does. It manipulates representations according to the system's formal rules. Whether the result is useful depends on the quality of the knowledge, the correctness of the rules, and the context in which the system is used.

## 1.4 Worked example: applying an IF–THEN rule

Imagine a simple fictional troubleshooting assistant for a toy robot. This is an educational example, not a real diagnostic system.

**Known facts**
1. `battery_low = true`
2. `robot_will_not_move = true`

**Rules**
- Rule A: IF `battery_low = true`, THEN suggest `check_or_charge_battery`.
- Rule B: IF `robot_will_not_move = true` AND `battery_low = true`, THEN conclude `battery_may_be_the_cause`.

**Step-by-step trace**

1. The system stores the two known facts in its working set.
2. The inference engine checks Rule A. Its condition is satisfied because `battery_low = true`.
3. The system adds `suggest_check_or_charge_battery` as a recommendation.
4. The engine checks Rule B. Both conditions are satisfied, so it adds `battery_may_be_the_cause`.
5. The system presents the conclusion and the rule that supported it.

The conclusion is deliberately cautious: the low battery **may** be the cause. Other faults could also stop a robot from moving. A rule-based system can only draw conclusions supported by its rules and available facts; it does not automatically know every possible cause.

### Example the reasoning path
**FACTS**   
battery_low = true  
robot_will_not_move = true  
**↓**   
**RULE CHECK**   
Rule A: battery is low  
Rule B: robot will not move AND battery is low  
**↓**   
**INFERRED OUTPUT**    
Suggest checking/charging battery  
Battery may be the cause  

## 1.5 Forward chaining and backward chaining

Two common ways to organize rule-based reasoning are:

- **Forward chaining (data-driven):** begin with known facts, find rules whose conditions match, and derive new facts. Continue until a goal is reached or no more rules apply.
- **Backward chaining (goal-driven):** begin with a question or possible conclusion, then look for rules that could support it. The system checks whether the required conditions can be established.

For the toy-robot example, forward chaining begins with the facts about the battery and movement. Backward chaining might begin with the question “Could the battery be the cause?” and then check whether the facts required by Rule B are known.

Neither method is automatically better in every situation. The appropriate method depends on the task, the number of rules, and whether the system is exploring consequences of known data or checking a specific goal.

## 1.6 Symbolic AI and neural AI: a first comparison

| Aspect | Symbolic AI | Neural-network AI |
|---|---|---|
| Main representation | Explicit symbols, facts, rules, and relationships | Numerical parameters and learned representations |
| How results are produced | Applies encoded rules or other symbolic procedures | Computes outputs using patterns learned during training |
| Inspectability | Individual rules can often be read and traced | The internal basis for a result may be harder to interpret |
| Knowledge source | Often explicitly encoded by people or imported into structured form | Commonly learned from training data |
| Typical limitation | Rules may be incomplete, brittle, or expensive to maintain | May need substantial data and can produce errors that are hard to explain |

This is a simplified comparison. Modern systems can combine neural and symbolic methods; neither category is one single design. **Neuro-symbolic AI** broadly refers to approaches that combine neural learning with symbolic representations or reasoning. The goal and design of the combination vary across research systems.

## 1.7 Learner activity

A library robot uses these facts:

- `obstacle_ahead = true`
- `path_is_clear = false`

It has the following rules:

- Rule 1: IF `obstacle_ahead = true`, THEN `stop_moving`.
- Rule 2: IF `path_is_clear = true`, THEN `continue_forward`.

**Questions**
1. Which rule can fire from the facts given?
2. What output should the system produce?
3. Can it conclude `continue_forward`? Explain why.
4. What additional fact would make Rule 2 applicable?

### Answer and explanation

1. Rule 1 can fire because `obstacle_ahead = true` is known.
2. The system should produce `stop_moving`.
3. No. Rule 2 requires `path_is_clear = true`, but the given fact is `path_is_clear = false`. The condition is not satisfied.
4. The system would need the fact `path_is_clear = true`. In a realistic system, that fact should come from a suitable sensor or another trusted information source; it should not be invented just to make the rule fire.

The activity checks whether learners can distinguish a rule's condition from its conclusion and whether they can avoid inferring something unsupported.

## 1.8 Limitations and responsible use

A rule-based system is only as reliable as its facts, rules, and assumptions. If a relevant rule is missing, the system may fail to reach a useful conclusion. If a fact is wrong, the resulting inference may also be wrong. Real-world systems therefore need testing, review, clear limits, and appropriate human oversight—especially in high-impact domains such as health, safety, or finance.

## References

1. McCarthy, J. (1959). *Programs with Common Sense*. Proceedings of the Teddington Conference on the Mechanization of Thought Processes. Author-hosted PDF: https://www-formal.stanford.edu/jmc/mcc59.pdf
2. Newell, A., & Simon, H. A. (1976). Computer Science as Empirical Inquiry: Symbols and Search. *Communications of the ACM, 19*(3), 113–126. https://doi.org/10.1145/235333.235334
3. Newell, A. (1980). Physical Symbol Systems. *Cognitive Science, 4*(2), 135–183. https://doi.org/10.1207/s15516709cog0402_2
4. Shortliffe, E. H. (1976). *Computer-Based Medical Consultations: MYCIN*. Elsevier. (Historical example; do not use a performance statistic without checking the original evaluation.)
5. Hitzler, P., et al. (2022). Neuro-symbolic artificial intelligence: The state of the art. *Artificial Intelligence Review*. https://pmc.ncbi.nlm.nih.gov/articles/PMC9166567/
