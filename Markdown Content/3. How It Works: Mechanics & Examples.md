# How It Works: Mechanics & Examples 

**Author:** Alexander Valentino Lukman
**Module:** Software & Symbolic AI

## 1. Learning Goals

By the end of this topic, a beginner should be able to:

1. Identify the two main components of an expert system: the Knowledge Base and the Inference Engine.
2. Explain how IF/THEN production rules process input facts to derive logical conclusions.
3. Describe a historical expert system, such as MYCIN or DENDRAL, and explain the problem it was designed to solve.

---

## 2. What Is an Expert System?

An **expert system** is a computer program designed to solve problems in a specialized domain by using stored knowledge and logical reasoning.

Traditional expert systems attempt to reproduce parts of a human expert's decision-making process. Instead of learning every rule from a large dataset, classic rule-based expert systems use knowledge explicitly represented by human experts or knowledge engineers.

A basic expert system has two main components:

### 2.1 Knowledge Base

The **Knowledge Base** stores the facts, rules, and relationships that the system uses to solve problems.

For example, a simple weather-related knowledge base might contain these facts:

- Fact 1: The temperature is above 30°C.
- Fact 2: The room has poor ventilation.

It might also contain these rules:

- Rule 1: IF the temperature is above 30°C, THEN the room is hot.
- Rule 2: IF the room is hot AND ventilation is poor, THEN recommend improving ventilation.

The Knowledge Base stores this information so that the system can use it during reasoning.

### 2.2 Inference Engine

The **Inference Engine** is the component responsible for applying rules to available facts to derive conclusions.

Its main tasks include:

1. Checking which rules match the available facts.
2. Selecting a rule to apply.
3. Applying the rule.
4. Adding or producing the resulting conclusion.
5. Continuing the reasoning process when additional rules can be applied.

The Inference Engine does not need to invent every rule itself. It uses the knowledge represented in the Knowledge Base.

### 2.3 How They Work Together

The Knowledge Base stores the knowledge, while the Inference Engine uses that knowledge to reason.

```text
       User Input
           |
           v
      Known Facts
           |
           v
+----------------------+
|   Inference Engine   |
|                      |
| 1. Match rules       |
| 2. Select a rule     |
| 3. Apply the rule    |
| 4. Derive a result   |
+----------------------+
           |
           v
+----------------------+
|     Knowledge Base   |
|                      |
| Facts, Rules, and    |
| Relationships        |
+----------------------+
           |
           v
   Conclusion or
   Recommendation
```

This is a simplified conceptual diagram. Actual expert-system architectures may differ.

---

## 3. Production Rules: How IF/THEN Statements Work

A **production rule** is a rule that specifies what conclusion or action follows when certain conditions are satisfied.

The general structure is:

`IF condition THEN conclusion`

For example:

`IF temperature > 30°C THEN room_status = "hot"`

This rule means that when the temperature is greater than 30°C, the system can infer that the room is hot.

Rules can also contain multiple conditions.

For example:

`IF temperature > 30°C AND ventilation = "poor" THEN recommendation = "improve ventilation"`

Both conditions must be satisfied for this rule to apply.

### 3.1 Worked Example: A Fictional Library Assistant

Imagine a library uses a simple expert system to help determine when a student should contact library staff.

The system has the following facts:

- `book_overdue = true`
- `renewal_limit_reached = true`

The Knowledge Base contains two rules.

**Rule 1**

`IF book_overdue = true THEN account_needs_attention = true`

**Rule 2**

`IF account_needs_attention = true AND renewal_limit_reached = true THEN recommendation = "contact library staff"`

Let's follow the reasoning process.

**Step 1: Read the initial facts.**

The system knows that the book is overdue and the renewal limit has been reached.

**Step 2: Check Rule 1.**

Rule 1 requires `book_overdue = true`.

This condition is satisfied, so the rule can fire.

The system derives a new fact:

`account_needs_attention = true`

**Step 3: Check Rule 2.**

Rule 2 requires two conditions:

- `account_needs_attention = true`
- `renewal_limit_reached = true`

Both conditions are now satisfied.

Therefore, Rule 2 can fire.

**Step 4: Produce the conclusion.**

The system recommends:

`contact library staff`

### Final Result

The system derived a recommendation by applying explicit rules to known facts.

Notice that the system did not learn these rules from the example. The rules were provided in advance, and the Inference Engine applied them.

This is the fundamental idea behind many traditional rule-based expert systems.

---

## 4. Forward Chaining and Backward Chaining

Expert systems need strategies for applying rules. Two common approaches are **forward chaining** and **backward chaining**.

### 4.1 Forward Chaining: Data-Driven Reasoning

Forward chaining begins with known facts and applies rules to derive additional facts or conclusions.

The process continues until a goal is reached or no further rules can be applied.

Using the library example:

1. The system starts with `book_overdue = true`.
2. Rule 1 fires and derives `account_needs_attention = true`.
3. The system checks whether the conditions of Rule 2 are satisfied.
4. Because `renewal_limit_reached = true` is also known, Rule 2 fires.
5. The system recommends contacting library staff.

Forward chaining is called **data-driven reasoning** because it starts with the available facts.

Its central question is:

**"What conclusions can I derive from the facts I already know?"**

Forward chaining can be useful when a system receives information and needs to determine which conclusions follow from it.

### 4.2 Backward Chaining: Goal-Driven Reasoning

Backward chaining starts with a goal or question and works backward to determine whether the available facts and rules support it.

Suppose the system wants to determine:

`Should the student contact library staff?`

Instead of starting with all the facts and deriving every possible conclusion, it works backward.

1. Identify a rule that can establish the goal.
2. Determine the conditions required by that rule.
3. Check whether those conditions are already known.
4. If a condition is not known, look for another rule that could establish it.
5. Continue until the required facts are found or the goal cannot be established.

Backward chaining is called **goal-driven reasoning** because the process starts with a particular question.

Its central question is:

**"What must be true for this goal to be supported?"**

### 4.3 Comparison

| Feature | Forward Chaining | Backward Chaining |
|---|---|---|
| Starting point | Known facts | A goal or question |
| Direction | Facts toward conclusions | Goal toward supporting facts |
| Reasoning style | Data-driven | Goal-driven |
| Main question | What follows from these facts? | Can this goal be established? |
| Typical use | Deriving conclusions from incoming information | Checking whether a particular conclusion is supported |

Both strategies can be useful. The better choice depends on the problem and how the system needs to reason.

---

## 5. Search Strategies: Depth-First and Breadth-First Search

Some AI problems require a system to explore multiple possible paths before finding a solution.

Two common search strategies are **Depth-First Search (DFS)** and **Breadth-First Search (BFS)**.

These are search strategies, whereas forward and backward chaining are inference strategies. They are related concepts, but they are not interchangeable.

### 5.1 Depth-First Search

Depth-First Search explores one branch as deeply as possible before returning to explore other branches.

Consider this search tree:

```text
            A
          /   \
         B     C
        / \   / \
       D   E F   G
```

If the system explores children from left to right, DFS may visit:

`A → B → D → E → C → F → G`

The system follows the left branch before moving to the right branch.

**Advantages:**
- Can use relatively little memory in certain search problems.
- Can find a solution quickly if the solution lies along the branch explored first.

**Limitations:**
- May spend a long time exploring an unhelpful branch.
- Does not generally guarantee the shortest solution.

### 5.2 Breadth-First Search

Breadth-First Search explores all nodes at one level before moving to the next level.

Using the same tree, BFS visits:

`A → B → C → D → E → F → G`

The system explores all immediate children of A before exploring the next level.

**Advantages:**
- Finds a shallowest solution when searching systematically in an unweighted tree.
- Does not immediately commit to one deep branch.

**Limitations:**
- Can require much more memory because it stores nodes waiting to be explored.

### 5.3 Comparison

| Feature | Depth-First Search | Breadth-First Search |
|---|---|---|
| Exploration | Goes deeper along one branch | Explores level by level |
| Memory | Often lower in tree-search settings | Can be considerably higher |
| Shortest solution | Not generally guaranteed | Finds a shallowest solution in an unweighted tree |
| Main risk | Exploring an unhelpful branch for too long | Memory consumption |

The choice depends on the structure of the search problem and the resources available.

---

## 6. Rule Conflict Resolution

Sometimes several rules match the available facts simultaneously.

A system needs a way to determine which rule should fire first. This is known as **rule conflict resolution**.

Common strategies include:

### 6.1 Priority

Rules can be assigned priorities. A rule with a higher priority may be selected before a lower-priority rule.

### 6.2 Specificity

A more specific rule may be preferred over a more general rule.

For example, a rule addressing a particular exception may take precedence over a broad default rule.

### 6.3 Recency

Some systems prioritize rules that use recently added facts.

### 6.4 Rule Order

A system may evaluate rules according to a defined order.

Different expert systems and rule engines can use different strategies.

Conflict resolution matters because the order in which rules fire can affect the reasoning process. The strategy should therefore be documented and tested.

---

## 7. Certainty Factors: Reasoning with Uncertainty

In real-world situations, information is not always complete or certain.

For example, a medical expert might consider a symptom to be evidence supporting one possible diagnosis without treating that diagnosis as absolutely certain.

Some expert systems therefore use methods for representing uncertainty.

**MYCIN used certainty factors** as part of its approach to reasoning with uncertain medical evidence.

A certainty factor represents a degree of support or doubt within a particular framework. It should not automatically be interpreted as an ordinary probability.

For example, saying that a system assigns a certainty factor of 0.8 does not, by itself, establish that the conclusion has an 80% probability of being correct.

The important idea is that an expert system can represent uncertainty instead of treating every conclusion as completely certain.

---

## 8. Ontologies and Taxonomy Hierarchies

Expert systems may organize knowledge using structured concepts and relationships.

An **ontology** represents concepts in a domain and defines relationships between them.

A **taxonomy** organizes concepts into categories, often using broader and narrower classes.

For example:

```text
Vehicle
  |
  +-- Car
        |
        +-- Electric Car
        |
        +-- Petrol Car
```

In this simplified hierarchy:

- An Electric Car is a type of Car.
- A Petrol Car is a type of Car.
- A Car is a type of Vehicle.

These relationships help a system organize information and reuse knowledge.

Real ontologies can represent more complex relationships than simple category hierarchies.

---

## 9. Historical Case Study: DENDRAL

**DENDRAL** was an early expert-system project developed in the 1960s.

It helped scientists infer plausible chemical structures from chemical evidence, including mass-spectrometry data.

### 9.1 The Problem

Chemists needed to determine which molecular structures could explain the available experimental evidence.

Many candidate structures could be considered, so the problem required domain knowledge and systematic analysis.

### 9.2 How DENDRAL Worked

At a high level, the system:

1. Received chemical evidence.
2. Considered candidate molecular structures.
3. Used domain knowledge and computational search to evaluate possible candidates.
4. Produced candidate structures for further scientific consideration.

This process illustrates how explicit knowledge can help narrow a complex problem.

### 9.3 Why DENDRAL Matters

DENDRAL demonstrated that an AI system could support specialized scientific work by combining domain knowledge with computational reasoning.

It became an important historical example of knowledge-based AI.

The description above is a simplified overview, not a complete account of DENDRAL's algorithms or chemical assumptions.

---

## 10. Historical Case Study: MYCIN

**MYCIN** was developed at Stanford University during the 1970s.

It was designed to assist with diagnosing certain bacterial infections and recommending antimicrobial treatments.

### 10.1 The Problem

Medical decisions can involve incomplete information, laboratory findings, and uncertainty about which organism is responsible for an infection.

MYCIN explored how expert knowledge could be represented as rules and applied to a specific medical domain.

### 10.2 How MYCIN Worked

At a high level:

1. The system received information about a case.
2. Its Knowledge Base represented medical knowledge using rules.
3. The Inference Engine evaluated which rules applied to the available information.
4. The system produced recommendations and represented uncertainty using certainty factors.

### 10.3 Why MYCIN Matters

MYCIN demonstrated how explicit domain knowledge and rule-based inference could be used to support specialized decision-making.

It also illustrated important limitations of expert systems.

Their results depend on the quality of their rules, the information provided, and the boundaries of their knowledge.

MYCIN is a historical research system, not a replacement for clinicians or a current medical tool.

### 10.4 Comparing DENDRAL and MYCIN

| Feature | DENDRAL | MYCIN |
|---|---|---|
| Domain | Chemistry | Medical diagnosis and treatment support |
| Main problem | Inferring candidate chemical structures | Supporting decisions about certain bacterial infections |
| General approach | Domain knowledge and computational search | Production rules and uncertainty representation |
| Historical significance | Demonstrated knowledge-based scientific problem-solving | Demonstrated rule-based expert reasoning in medicine |

Both systems illustrate how symbolic AI can use explicit domain knowledge to address specialized problems.

---

## 11. Symbolic Programming Languages and Rule Engines

Several programming languages and tools have been associated with symbolic AI and rule-based systems.

### 11.1 LISP

LISP became influential in AI research because its symbolic data structures and list-processing capabilities suited many AI programs.

### 11.2 PROLOG

PROLOG is a logic programming language in which facts and rules can be queried through logical inference and search.

A simplified PROLOG example is:

```prolog
human(socrates).

mortal(X) :- human(X).
```

The first line states that Socrates is human.

The second line states that X is mortal if X is human.

A query can ask:

```prolog
?- mortal(socrates).
```

Under these facts and rules, the query succeeds.

### 11.3 Drools

Drools is a modern business rule management system and rule engine.

It allows applications to represent and evaluate rules in a structured way.

For example, a business application might use rules to check eligibility, classify transactions, or evaluate policy conditions.

LISP, PROLOG, and Drools are related to symbolic or rule-based programming, but they are not interchangeable. Each has its own programming model and use cases.

---

## 12. Practice Activity

A fictional campus help system contains these facts:

- `student_has_ID = true`
- `library_fine_unpaid = true`

The Knowledge Base contains the following rules.

**Rule A**

`IF student_has_ID = true THEN identity_verified = true`

**Rule B**

`IF identity_verified = true AND library_fine_unpaid = true THEN refer_to_library_desk = true`

Answer the following questions.

1. Which component stores the facts and rules?
2. Which component applies the rules?
3. Which rule can fire first?
4. What conclusion follows after Rule B fires?
5. If the system uses forward chaining, where does reasoning begin?
6. If the system uses backward chaining to determine whether the student should be referred to the library desk, where does reasoning begin?

### Explained Answers

**Question 1: Which component stores the facts and rules?**

The Knowledge Base stores the facts and rules.

**Question 2: Which component applies the rules?**

The Inference Engine applies the rules to the available facts.

**Question 3: Which rule can fire first?**

Rule A can fire first because `student_has_ID = true` is already known.

**Question 4: What conclusion follows after Rule B fires?**

Rule A establishes `identity_verified = true`.

Rule B can then match both required conditions:

- `identity_verified = true`
- `library_fine_unpaid = true`

The system therefore derives:

`refer_to_library_desk = true`

**Question 5: If the system uses forward chaining, where does reasoning begin?**

It begins with the known facts and applies matching rules to derive further conclusions.

**Question 6: If the system uses backward chaining, where does reasoning begin?**

It begins with the goal:

`refer_to_library_desk = true`

The system then works backward to determine whether the facts and rules support that goal.

---

## 13. Summary

An expert system uses represented knowledge and an inference procedure to solve a specialized problem.

The Knowledge Base stores facts, rules, and relationships. The Inference Engine applies rules to available facts to derive conclusions.

Production rules use IF/THEN statements to connect conditions with conclusions.

Forward chaining begins with known facts, while backward chaining begins with a goal.

Depth-first and breadth-first search provide different ways to explore possible paths. Rule conflict resolution determines which matching rule is applied next.

Certainty factors can represent degrees of support or doubt, while ontologies and taxonomies help organize domain knowledge.

DENDRAL demonstrated the use of expert knowledge in chemical analysis, while MYCIN demonstrated rule-based reasoning for specialized medical decision support.

Together, these examples show how symbolic AI uses explicit representations and reasoning procedures to solve narrowly defined problems.

## 14. References

1. Buchanan, B. G., and Shortliffe, E. H. (Eds.). (1984). *Rule-Based Expert Systems: The MYCIN Experiments of the Stanford Heuristic Programming Project*. Addison-Wesley

2. Russell, S., and Norvig, P. *Artificial Intelligence: A Modern Approach*. Pearson.

3. Drools documentation: https://docs.drools.org/

4. SWI-Prolog documentation: https://www.swi-prolog.org/pldoc/
