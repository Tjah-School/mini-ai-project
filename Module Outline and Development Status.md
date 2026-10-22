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

# 1. Software and Symbolic AI: From Instructions to Conclusions

## 1.1 What is software?

**Software** is the collection of programs, instructions, and related data that tells a computer what tasks to perform. **Hardware** is the physical equipment, such as the processor, memory, keyboard, and storage. A computer system needs both: hardware performs physical operations, while software specifies the operations and how they should be coordinated.  

Two useful categories are:  

• **System software:** helps operate the computer and provides a platform for other programs. An operating system is a
common example.  

• **Application software:** helps a user perform a task, such as writing a document, editing a photo, or browsing the web.

## 1.2 How does a program run?
A programmer may write source code in a human-readable programming language. The computer cannot directly execute every form of source code as written. Depending on the language and implementation, the code may be compiled into machine code, translated into an intermediate form, interpreted, or processed using a combination of these methods.  

• **Source code:** instructions written by a programmer in a programming language.  

• **Compiler:** software that translates a program or part of it into another form, often machine code or an intermediate representation.  

• **Interpreter:** software that executes program instructions, often by processing them at runtime.  

• **Machine instructions:** low-level operations a processor is designed to execute.  

**A simplified:**  
1.  Programmer writes source code   
2. Translation / runtime processing  
3. Processor executes instructions  
4. Program produces output or changes state  
