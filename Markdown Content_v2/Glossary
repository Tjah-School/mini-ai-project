# Symbolic AI

## A

**A\* Search** — An informed search that orders the frontier by f(n) = g(n) + h(n). It is optimal when h is admissible (tree search) or consistent (graph search). Weakness: high memory use. [5.5]

**Action** — Something an agent can do in a state, described with preconditions and effects. [5.2]

**Add List** — In STRIPS, the facts that become true after an action is applied. [5.8]

**Admissible Heuristic** — A heuristic h(n) that never overestimates the true remaining cost to the goal. Straight-line distance is an example. [5.5]

**Adversarial Search** — Search used when another agent opposes the agent's actions, as in two-player games such as chess. [5.6]

**Agent (Semantic Role)** — The participant who performs an action. In "The cat chased the mouse," the agent is *cat*. [6.4]

**Alpha-Beta Pruning** — An optimization of minimax that returns the same decision while skipping branches that cannot affect it. A branch is cut when α ≥ β. [5.6]

**Ambiguity** — A sentence or word that has more than one valid interpretation (for example, "I saw the man with the telescope"). A central difficulty for rule-based NLP. [6.3]

**Antecedent** — The "if" part (premise p) of an implication p → q. [2.2.4]

**Artificial Intelligence Winter (AI Winter)** — The late-1980s to 1990s collapse in funding after expert systems proved costly to maintain and brittle. [1.2]

---

## B

**Backtracking Search** — A CSP method that assigns variables one at a time and undoes (backtracks) an assignment when a constraint is violated. [5.9]

**Backward Chaining** — Goal-driven reasoning that starts from a hypothesis and checks whether the facts support it. Like a doctor asking "could it be flu?" [1.3, 4.1.4]

**Backward (Regression) Search** — A planning strategy that starts from the goal and finds actions that could produce it, replacing the goal with their preconditions. [5.8]

**Biconditional (p ↔ q)** — "p if and only if q." True when p and q have the same truth value. [2.2.4]

**Boolean Operators** — AND (∧), OR (∨), and NOT (¬), used to combine propositions. [2.2.2]

**Boolean Query** — An information retrieval query that combines terms with AND, OR, and NOT. [6.10]

**Branching Factor (b)** — The number of actions available in each state. [5.2]

**Breadth-First Search (BFS)** — Expands the shallowest unexpanded node first, using a queue. Complete, and optimal when all steps cost the same, but memory-hungry. [5.4]

**Brittleness** — The tendency of a system to fail outside its narrow domain or when input differs slightly from what its rules expect. [4.4, 6.12]

---

## C

**Certainty Factor** — A number expressing how confident a system is in a conclusion, used by MYCIN (for example, "organism is E. coli, certainty 0.7"). [4.2.3]

**Chart Parsing (CYK, Earley)** — A parsing approach that stores partial results in a table so that no sub-phrase is parsed twice. Worst-case time is cubic in sentence length. [6.3]

**Chomsky Hierarchy** — Chomsky's (1956) classification of formal grammars by power: regular, context-free, context-sensitive, and unrestricted. [6.3]

**Classical Planning** — Planning under the assumptions that the world is deterministic, fully observable, static, discrete, and has a single agent. [5.8]

**Closed List** — See *Explored Set*.

**Closed-World Assumption** — In STRIPS, anything not listed as true is assumed false. [5.8]

**Combinatorial Explosion** — The rapid growth in the number of states to examine (about b^d) as depth grows, making large searches intractable. [5.3]

**Commonsense Knowledge** — Obvious everyday knowledge that humans have but that is hard to write down as rules (the Cyc project tried for decades). [3.5, 6.12]

**Completeness** — A search property: if a solution exists, the algorithm is guaranteed to find it. [5.3]

**Compositional Semantics** — Building the meaning of a sentence from the meanings of its parts, following the parse structure. [6.4]

**Conflict Resolution** — How an inference engine chooses among several rules that can fire at once, by priority, specificity, or recency. [4.1.4]

**Consequent** — The "then" part (conclusion q) of an implication p → q. [2.2.4]

**Consistent Heuristic** — A heuristic where h(n) ≤ c + h(n') for every step from n to n' with cost c. Consistency implies admissibility. [5.5]

**Constraint** — A rule restricting which combinations of variable values are allowed in a CSP. [5.9]

**Constraint Propagation** — Removing values that can no longer work (for example forward checking, arc consistency) to detect dead ends early. [5.9]

**Constraint Satisfaction Problem (CSP)** — A problem defined by variables, a domain of values for each, and constraints on combinations. Map colouring is the standard example. [5.9]

**Context-Free Grammar (CFG)** — A grammar whose rules have a single symbol on the left side. The standard workhorse of syntactic parsing. [6.3]

---

## D

**Dartmouth Conference (1956)** — The meeting that named the field "artificial intelligence." [1.2]

**De Morgan's Laws** — ¬(p ∧ q) ≡ ¬p ∨ ¬q and ¬(p ∨ q) ≡ ¬p ∧ ¬q. [2.2.3]

**Deep Blue** — The IBM chess system that beat world champion Garry Kasparov in 1997 using deep alpha-beta search, special hardware, and a hand-built evaluation function. [5.1, 5.6]

**DENDRAL** — A 1960s system that worked out organic molecule structures from mass spectrometer data. Often called the first expert system. [1.2, 4.2.3]

**Delete List** — In STRIPS, the facts that become false after an action is applied. [5.8]

**Depth (d)** — The number of steps to the shallowest goal. [5.2]

**Depth-First Search (DFS)** — Expands the deepest unexpanded node first, using a stack or recursion. Small memory use but not optimal. [5.4]

**Depth-Limited Search** — DFS with a cutoff depth l, which avoids endless descent. [5.4]

**Dependency Grammar** — A grammar that links each word to its head word. [6.3]

**Discourse and Pragmatics** — The level of language analysis concerned with context and intent (for example, "Can you pass the salt?" is a request). [6.1, 6.2]

**Domination (of heuristics)** — Heuristic h2 dominates h1 if h2(n) ≥ h1(n) for all n while staying admissible, so h2 expands fewer nodes. [5.5]

**Double Negation** — The equivalence ¬(¬p) ≡ p. [2.2.3]

---

## E

**ELIZA** — A 1966 chatbot by Weizenbaum that used keyword spotting and decomposition and reassembly rules to imitate a psychotherapist. [1.2, 6.11]

**Evaluation Function** — A heuristic score for a game position, used when the search stops at a depth limit (for chess, material count and piece positions). [5.6]

**Existential Generalization (EG)** — From P(c) ∧ Q(c) for a specific c, conclude ∃x(P(x) ∧ Q(x)). Always safe. [2.3.6]

**Existential Instantiation (EI)** — From ∃x(P(x) ∧ Q(x)), name a specific element c that satisfies it. The name c must be new. [2.3.5]

**Existential Quantifier (∃)** — "There exists": true for at least one element in the domain. [2.3.2]

**Expanding a Node** — Generating all of a node's children. [5.2]

**Expert System** — An AI system that emulates the decision-making of a human expert in one specific domain. [4.2]

**Explainability** — The ability to trace and show how a system reached a conclusion. A key strength of symbolic AI. [1.1.3]

**Explored Set (Closed List)** — States already expanded, kept so that the search does not loop. [5.2]

---

## F

**Forward Chaining** — Data-driven reasoning that starts from known facts and moves toward conclusions. Like a detective collecting clues. [1.3, 4.1.4]

**Forward (Progression) Search** — A planning strategy that starts at the initial state and applies applicable actions toward the goal. [5.8]

**Frame** — A data structure for a stereotypical object or situation, with slots (properties), values, and default values. [3.2.3]

**Frame Problem** — The difficulty of stating everything that does *not* change when an action occurs. [5.8]

**Frontier (Open List)** — Nodes that have been generated but not yet expanded. [5.2]

---

## G

**General Problem Solver (GPS)** — A 1957 program that attempted general-purpose problem solving and introduced means-ends analysis. [1.2, 5.1]

**Global Maximum** — The best state anywhere in the state-space landscape. [5.7]

**GOFAI (Good Old-Fashioned AI)** — Another name for symbolic AI. [1.1.1]

**Goal State** — The desired state a plan or search tries to reach. [5.1]

**Goal Test** — How to recognize that a state is a goal. [5.2]

**Greedy Best-First Search** — Orders the frontier by f(n) = h(n) only. Fast but neither optimal nor complete. [5.5]

**Gazetteer** — A list of known names, places, or organizations used alongside patterns in information extraction. [6.6]

---

## H

**Heuristic** — A rule of thumb or domain knowledge used to guide search. It is not a guarantee. [5.3, 5.5]

**Heuristic Function h(n)** — An estimate of the cost of the cheapest path from node n to a goal. [5.5]

**Hierarchical Task Network (HTN)** — A planning approach that breaks high-level tasks into subtasks using expert-written methods. [5.8]

**Hill Climbing** — A local search that always moves to a better neighbor and stops when none is better. It can get stuck at local maxima, ridges, and plateaus. [5.7]

**Hypernym / Hyponym** — In WordNet, a more general word (*mammal* for *cat*) and a more specific word (*cat* for *mammal*). [6.4]

---

## I

**Implication (p → q)** — "If p, then q." False only when p is true and q is false. [2.2.4]

**Inference Engine** — The reasoning program that applies rules to facts to derive conclusions. [1.3, 4.1.1]

**Inference Rule** — A pattern that lets us derive new conclusions from known statements (for example Modus Ponens). [2.2.5]

**Informed (Heuristic) Search** — Search that uses domain-specific knowledge to expand the most promising nodes first. [5.5]

**Information Extraction (IE)** — Identifying specific entities and relationships in unstructured text using predefined patterns. [6.6]

**Information Retrieval (IR)** — Finding relevant documents in large collections. [6.10]

**Initial State** — Where the agent starts. [5.2]

**Iterative Deepening Search** — Runs depth-limited search with l = 0, 1, 2, ... until a goal is found. Combines BFS's completeness with DFS's small memory. [5.4]

---

## K

**Knowledge Acquisition Bottleneck** — The slow, expensive process of extracting knowledge from experts and writing it down as rules. [1.4, 3.5]

**Knowledge Base** — The stored facts and rules of a symbolic system. [1.3]

**Knowledge Engineer** — The person who builds the knowledge base from an expert's expertise. [4.2.2]

**Knowledge Graph** — Entities and labeled relations, used for question answering and retrieval. A modern descendant of ontologies and semantic networks. [3.2.5, 6.5]

**Knowledge Representation** — How an AI system stores knowledge in a form it can reason with. [3.1]

---

## L

**Lexicon** — A dictionary of words with part of speech, forms, and features. [6.5]

**LISP** — The main AI programming language for decades, created by John McCarthy in 1958. [1.2]

**Local Maximum** — A state better than all its neighbors but not the best overall. [5.7]

**Local Search** — Search that keeps a single current solution and moves to neighboring ones. Used when only the final state matters. [5.7]

**Logic Theorist** — A 1956 program (Newell, Simon, Shaw) that proved mathematical theorems using heuristic search. [1.2]

**Logic-Based Representation** — Knowledge written as propositional logic or first-order logic. [3.2.1]

**Logical Equivalence (≡)** — Two statements that have the same truth value in every situation. [2.2.3]

**Logical Form** — A formal representation of a sentence's meaning, such as `Chased(cat1, mouse1)`. [6.4]

---

## M

**MAX / MIN** — The two players in minimax. MAX tries to maximize the score and MIN tries to minimize it. [5.6]

**Means-Ends Analysis** — A planning method that compares the current state with the goal, picks an action that reduces the difference, and makes its preconditions new subgoals. [5.8]

**Minimax** — An adversarial search that passes values up a game tree, with MAX taking the largest child value and MIN the smallest. It assumes the opponent plays its best move. [5.6]

**Modus Ponens** — From p → q and p, conclude q. [2.2.5]

**Modus Tollens** — From p → q and ¬q, conclude ¬p. [2.2.5]

**Morphological Analysis** — Finding word structure and base forms (chased = chase + past tense). [6.1]

**MYCIN** — A 1970s expert system that diagnosed bacterial blood infections using roughly 600 rules and certainty factors. [1.2, 4.2.3]

---

## N

**Natural Language Processing (NLP)** — The field concerned with computers understanding, interpreting, and generating human language. [6.1]

**Negation (in sentiment rules)** — A rule that flips polarity, as in "not good." [6.8]

**Neuro-Symbolic AI** — Approaches that combine symbolic reasoning with neural networks. [1.2, 6.12]

**Node** — A state plus bookkeeping such as parent node, action taken, and path cost so far. [5.2]

---

## O

**Ontology** — A formal representation of the concepts in a domain and their relationships, giving a shared vocabulary. [3.2.5]

**Open List** — See *Frontier*.

**Optimality** — A search property: the algorithm finds the lowest-cost solution. [5.3]

**Optimal Solution** — The solution path with the lowest path cost. [5.2]

---

## P

**Parse Tree** — A tree showing the hierarchical structure of a sentence according to a grammar. [6.3]

**Parsing** — Finding a parse tree for a sentence according to a grammar. Can be top-down, bottom-up, or chart-based. [6.3]

**Part-of-Speech (POS) Tagging** — Assigning each word a grammatical category such as noun or verb. [6.6]

**Partial-Order Planning** — A planning method that orders actions only where necessary ("least commitment"). [5.8]

**Patient (Semantic Role)** — The participant acted upon. In "The cat chased the mouse," the patient is *mouse*. [6.4]

**Path Cost** — A number measuring how good a path is, such as total distance. [5.2]

**PDDL (Planning Domain Definition Language)** — The standard language for describing planning problems, used in the International Planning Competition. [5.8]

**Plan** — A sequence of actions that transforms an initial state into a goal state. [5.1]

**Planning** — Finding a sequence of actions that reaches a goal state from an initial state. [5.1]

**Planning Graph (GraphPlan)** — A compact layered structure of what could be true at each step, from which a plan is extracted. [5.8]

**Plateau** — A flat area in the state-space landscape with no direction to move. [5.7]

**Precondition** — A fact that must hold for an action to be applicable. [5.8]

**Predicate** — A statement with variables that is true or false depending on their values, such as Even(x). [2.3.2]

**Predicate Logic (First-Order Logic)** — Logic that adds predicates, variables, and quantifiers to propositional logic. [2.3]

**Production Rule** — An IF-THEN rule with a condition and an action. [3.2.4, 4.1]

**Prolog** — A logic programming language that appeared in 1972. [1.2, 3.2.1]

**Proposition** — A declarative sentence that is either true or false, but not both. [2.2.1]

**Propositional Logic** — Logic about whole statements combined with Boolean operators. [2.2]

---

## Q

**Qualification Problem** — The difficulty of listing every condition that must hold for an action to work. [5.8]

**Quantifier** — A symbol (∀ or ∃) stating how many elements a predicate applies to. [2.3.2]

**Question Answering (QA)** — Systems that interpret a natural-language question and infer the answer, often from formal knowledge. [6.9]

---

## R

**Ramification Problem** — The difficulty of capturing the indirect effects of actions. [5.8]

**Relaxed Problem** — A simpler version of a problem with some rules removed. Its exact solution cost makes a good admissible heuristic. [5.5]

**Ridge** — A narrow slope that rises sideways, which single steps cannot climb. [5.7]

**Rule-Based System (Production System)** — A system that operates on a set of IF-THEN rules. [4.1]

---

## S

**Script** — A sequence of frames describing a typical chain of events, such as going to a restaurant. [3.2.3]

**Semantic Network** — A graph where nodes are concepts and links are relationships. [3.2.2]

**Semantic Role** — The part a participant plays in an event, such as agent or patient. [6.4]

**Semantics** — The meaning conveyed by words, phrases, and sentences in context. [6.4]

**Sentiment Analysis** — Determining the emotional tone (positive, negative, neutral) of text. [6.8]

**Sentiment Lexicon** — A list of words with polarity scores. [6.8]

**SHRDLU** — A 1972 system by Winograd that carried out typed commands in a simulated blocks world. [6.11]

**Simulated Annealing** — A local search that sometimes accepts worse moves with probability e^(−Δ/T), lowering the temperature T over time to escape local maxima. [5.7]

**State Space** — The set of all states reachable from the initial state by any sequence of actions. [5.2]

**State-Space Landscape** — A picture where each state has a height given by an objective function. [5.7]

**STRIPS** — A 1971 planner (Fikes and Nilsson) that describes actions by preconditions, a delete list, and an add list. [1.2, 5.8]

**Sub-Symbolic AI (Connectionist)** — AI that stores knowledge as numerical weights in a network and learns from data, such as neural networks. [1.1.3]

**Symbolic AI** — AI in which knowledge is written explicitly as symbols, rules, and logic, and the computer reasons by manipulating them. [1.1]

**Synset** — In WordNet, a set of synonyms. [6.4]

**Syntax** — The structure of language: how words and phrases form grammatical sentences. [6.3]

---

## T

**Terminal Test** — In a game, the check for whether the game is over. [5.6]

**Tokenization** — Splitting text into words and punctuation. [6.1]

**Transition Model** — The state that results from applying an action in a state. [5.2]

**Transposition Table** — A store of positions already evaluated, since different move orders can reach the same position. [5.6]

**Truth Table** — A table listing the truth value of a compound statement for every combination of inputs. [2.2.2]

---

## U

**Uniform-Cost Search (UCS)** — Expands the node with the lowest path cost g(n). It is BFS generalized to steps of different cost. [5.4]

**Uninformed (Blind) Search** — Search that uses no knowledge of the goal beyond the problem definition. [5.4]

**Universal Generalization (UG)** — From P(a) → Q(a), conclude ∀x(P(x) → Q(x)). Valid only if a is arbitrary. [2.3.6]

**Universal Instantiation (UI)** — From a statement about all x, conclude it for a specific element a. Always safe. [2.3.5]

**Universal Modus Ponens** — From ∀x(P(x)→Q(x)) and P(a), conclude Q(a). [2.3.8]

**Universal Modus Tollens** — From ∀x(P(x)→Q(x)) and ¬Q(a), conclude ¬P(a). [2.3.8]

**Universal Quantifier (∀)** — "For all": true for every element in the domain. [2.3.2]

**Utility** — The final score of a game outcome (for example +1 win, 0 draw, −1 loss). [5.6]

---

## W

**Well-Defined Problem** — A problem with five parts: initial state, actions, transition model, goal test, and path cost. [5.2]

**Word Sense Disambiguation** — Choosing the correct meaning of a word from context. [6.4]

**WordNet** — A symbolic lexical resource that groups words into synsets linked by relations such as hypernym and meronym. [6.4]

**Working Memory** — Holds the facts about the current case in a rule-based system. [4.1.1]

---

## X

**XCON / R1** — A 1980s expert system that configured computer orders for Digital Equipment Corporation. [1.2, 4.2.3]

---

## Z

**Zero-Sum Game** — A game in which one player's gain is exactly the other's loss. [5.6]
