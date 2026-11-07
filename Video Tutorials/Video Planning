# **VIDEO VOICEOVER SCRIPT**

## **Software & Symbolic AI**

**Team assignment \| Chapter 2 and Chapter 3**

---

# **VIDEO 01: ALGORITHMS AND DATA STRUCTURES**

**Slides 26–50 \| Estimated duration: 8–10 minutes**

### **Opening**

**Slide 26 – Algorithms: A Method, Not a Language**

Imagine that you are looking for a particular name in a phone book containing thousands of names. How would you find it? Would you check every single name, or would you use a smarter method?

This is exactly the kind of problem algorithms solve.

Think of an algorithm like a recipe. You have ingredients, a series of instructions, and a final result. In computing, we call these inputs, processing steps, and outputs.

It is important to distinguish an algorithm from a program. An algorithm describes the method, while a program is the actual implementation written in a programming language.

There is also a third component: the data structure, which determines how information is organized. As the famous computing principle suggests, algorithms and data structures work together to create programs.

### **What makes an algorithm?**

**Slide 27 – What Makes a Procedure an Algorithm?**

Not every set of instructions qualifies as a good algorithm.

A proper algorithm needs clearly defined inputs and outputs. Its instructions must be precise enough that a computer can execute them without guessing.

It must also eventually stop. Imagine an algorithm that keeps repeating forever. It would never deliver a final answer.

Finally, the algorithm must be effective and correct for the inputs it is designed to handle.

One example is Euclid's algorithm, which finds the greatest common divisor of two numbers by repeatedly calculating remainders. Each step makes the remaining problem smaller until the answer is reached.

**Slide 28 – Read a Flowchart**

Before writing code, we can represent an algorithm visually using a flowchart.

Notice the different shapes. An oval represents the beginning or end. A rectangle represents an operation, while a diamond represents a decision.

Let's imagine an algorithm that finds the highest score in a list.

First, we assume the first score is the highest. Then, we examine the next score. If it is higher, we update our maximum value. We repeat this process until every score has been checked.

The final maximum value is then displayed.

Notice how the diamond controls what happens next. This makes flowcharts useful for understanding decisions before translating them into code.

**Slide 29 – Control Flow: Sequence, Selection, Iteration**

Most algorithms are built using three fundamental control structures.

The first is sequence, where instructions execute one after another. For example, adding two numbers requires receiving the inputs, calculating the sum, and displaying the result.

The second is selection. This allows a program to choose between different actions based on a condition. An example would be checking whether a student has passed an examination.

The third is iteration, which means repeating instructions. For example, a program might inspect every item in a shopping list.

These three structures form the foundation of program logic.

### **Efficiency and searching**

**Slide 30 – Correctness and Efficiency Are Different Questions**

When evaluating an algorithm, we need to ask two separate questions.

First, does it produce the correct answer?

Second, how efficiently does it produce that answer?

An algorithm could produce the right result but take an unreasonable amount of time. Another could be extremely fast but consistently produce incorrect results.

Both qualities matter. In real applications, especially large systems, efficiency can determine whether a solution is practical.

**Slide 31 – Big-O Describes Growth**

How do we measure algorithm efficiency?

One common method is Big-O notation. Instead of measuring the exact time an algorithm takes on a particular computer, Big-O describes how its resource requirements grow as the input becomes larger.

For example, constant time, or O(1), means the operation takes approximately the same amount of work regardless of input size.

Linear time, O(n), grows proportionally with the number of items.

Quadratic time, O(n²), grows much faster because the amount of work can increase with the square of the input size.

The important thing is the general growth pattern, not the exact number of seconds.

**Slide 32 – Linear Search**

Let's start with a simple search algorithm.

Suppose we have four numbers: 4, 9, 2, and 7\. Our target is 7\.

Linear search checks each element from left to right.

First, we check 4\. It is not our target. Next comes 9, followed by 2\. Finally, we reach 7 and find the answer.

In this example, we needed four comparisons.

The main advantage of linear search is that the data does not need to be sorted. However, for very large lists, checking every item can become inefficient.

**Slide 33 – Binary Search**

What if we could eliminate half of the search area after every comparison?

That is the idea behind binary search.

However, there is one important requirement: the data must already be sorted.

Consider the sequence shown on screen. We want to find 15\.

We first inspect the middle element, which is 9\. Since 15 is greater than 9, we can discard the left half.

We then inspect the middle of the remaining section and find 15\.

Instead of examining every element, we found the target using only two comparisons.

This is why binary search has logarithmic time complexity, O(log n). It becomes particularly useful when working with large, sorted datasets.

### **Sorting algorithms**

**Slide 34 – Bubble Sort**

Searching is not the only problem algorithms can solve. Sometimes, we need to arrange information in a particular order.

Bubble sort is one of the simplest sorting algorithms.

It compares neighboring elements and swaps them whenever they are in the wrong order.

For example, starting with 5, 1, 4, and 2, we compare 5 and 1 and swap them. Then we compare 5 and 4, followed by 5 and 2\.

After the first pass, the largest value has moved to the end. Additional passes repeat the process until the entire list is sorted.

Bubble sort is easy to understand, but its typical time complexity is O(n²), making it inefficient for large datasets.

**Slide 35 – Selection Sort**

Selection sort approaches the same problem differently.

Rather than repeatedly swapping neighboring values, it searches for the smallest element in the unsorted section.

Using our previous numbers, 5, 1, 4, and 2, the smallest value is 1\. We move it into the first position.

Next, we find the smallest value among the remaining elements, which is 2, and move it into the second position.

We continue until the entire sequence is sorted.

Selection sort also has O(n²) time complexity, but it generally performs fewer swaps than bubble sort.

**Slide 36 – Insertion Sort**

Now imagine arranging playing cards in your hand.

You pick up one card at a time and insert it into the correct position among the cards you are already holding.

This is exactly how insertion sort works.

Suppose our sorted sequence is 2, 5, and 8\. We want to insert 4\.

Since 4 is smaller than 5 and 8, we shift those values to the right and place 4 after 2\.

Unlike some other simple sorting algorithms, insertion sort can perform particularly well on small or nearly sorted datasets.

**Slide 37 – Merge Sort**

Merge sort uses a strategy called divide and conquer.

Instead of sorting the entire list at once, it repeatedly divides the list into smaller sections.

Consider the sequence 8, 3, 5, and 1\.

We split it into two smaller groups: 8 and 3, and 5 and 1\. Each group is sorted individually.

We then combine the sorted groups by comparing their smallest available elements.

The final result is 1, 3, 5, and 8\.

Merge sort achieves O(n log n) time complexity, although it requires additional memory to combine the results.

**Slide 38 – Quick Sort**

Another divide-and-conquer algorithm is quick sort.

Instead of splitting the list into equal halves, quick sort selects a value called a pivot.

In this example, the pivot is 5\.

We divide the remaining values into two groups: those smaller than 5 and those greater than 5\.

The algorithm then sorts these smaller sections recursively.

Quick sort has an average time complexity of O(n log n), although poor pivot choices can lead to O(n²) performance in the worst case.

**Slide 39 – Comparing Sorting Methods**

So, which sorting algorithm should we choose?

There is no single answer.

Bubble sort, selection sort, and insertion sort are relatively simple but generally have quadratic time complexity.

Merge sort offers predictable O(n log n) performance, although it requires additional memory.

Quick sort is often effective in practice, but its performance depends on how the data is partitioned.

The best choice depends on the dataset, available memory, and the requirements of the application.

### **Recursion and algorithm design**

**Slide 40 – Iteration and Recursion**

There are two common ways to repeat a computation: iteration and recursion.

Iteration uses loops to repeat instructions until a condition is satisfied.

Recursion works differently. A function calls itself to solve a smaller version of the original problem.

However, recursion needs a base case. Without one, the function could continue calling itself indefinitely.

A simple example is counting down from five. We can use a loop, or we can make a function call itself with a smaller number until it reaches zero.

**Slide 41 – Recursion Can Repeat Work**

Recursion is useful, but it can also create unnecessary work.

Consider the Fibonacci sequence. In a basic recursive implementation, calculating a number may require calculating the same smaller Fibonacci values multiple times.

For example, the calculation of fib(3) can appear in more than one branch of the recursion tree.

This means the program repeats calculations that it has already completed.

A technique called memoization solves this problem by storing previously calculated results.

Instead of calculating the same value again, the program retrieves it from memory.

This is one example of dynamic programming, which trades additional memory for reduced computation.

**Slide 42 – Algorithm Design Strategies**

Programmers can approach problems using different design strategies.

Brute force tries every possible candidate until it finds a solution.

Divide and conquer breaks a large problem into smaller problems, as we saw with merge sort.

Greedy algorithms make the best-looking choice at each step.

Dynamic programming stores solutions to overlapping subproblems to avoid unnecessary repetition.

Backtracking explores possible solutions and reverses decisions when a particular path cannot work.

Each approach has its strengths. Choosing the right strategy depends on the structure of the problem.

### **Data structures**

**Slide 43 – Data Structures Shape the Cost**

Algorithms do not operate in isolation. They also depend on how information is organized.

A data structure determines how we store and access information.

For example, imagine managing thousands of student records.

We might frequently search for a student, add a new record, or remove an existing one.

Different data structures make these operations more or less efficient.

This is why choosing a suitable data structure is just as important as choosing the algorithm itself.

**Slide 44 – Arrays and Records**

Let's begin with arrays and records.

An array stores a sequence of elements, each associated with an index.

Because elements can be accessed directly using their positions, array indexing typically takes O(1) time.

However, inserting or deleting an element in the middle can require shifting other elements, which takes O(n) time.

Records serve a different purpose. They group related information into one item.

For example, a student record might contain an identification number, name, and age.

**Slide 45 – Linked Lists**

Unlike arrays, linked lists store information in separate nodes connected through references.

Each node contains data and a link to the next node.

This structure makes certain insertions and deletions efficient because we can simply change the links.

However, accessing an element by its position is slower. We may need to start at the beginning and follow each connection until we reach the desired node.

This means linked lists trade direct access for more flexible connections.

**Slide 46 – Stacks and Queues**

Two important data structures are stacks and queues.

A stack follows Last In, First Out, or LIFO.

Imagine stacking plates. The last plate you place on top is the first one you remove.

The main operations are push, which adds an element, and pop, which removes the top element.

A queue follows First In, First Out, or FIFO.

Think of people waiting in line. The person who arrives first is generally served first.

These structures appear in real applications, including undo history, function calls, and printer queues.

**Slide 47 – Trees Represent Hierarchy**

Not all information can be represented effectively using a simple sequence.

Trees are useful when information has hierarchical relationships.

A tree begins with a root node, which can connect to parent and child nodes.

Nodes without children are called leaves.

A familiar example is a computer's file system. Folders can contain other folders, which can contain files.

This structure makes it easier to represent relationships where one item belongs underneath another.

**Slide 48 – Binary Trees, BSTs and Traversals**

A binary tree is a tree in which each node has at most two children.

A Binary Search Tree, or BST, follows a specific ordering rule: values smaller than a node go to the left, while larger values go to the right.

This arrangement can make searching efficient.

For example, if we perform an in-order traversal, we visit the left subtree, the current node, and then the right subtree.

For the tree shown, the resulting sequence is 1, 3, 6, 8, and 12\.

A balanced BST can support O(log n) search operations, but an unbalanced tree may degrade to O(n).

**Slide 49 – Heaps and Graphs**

Two more structures deserve attention: heaps and graphs.

A heap is a special tree that maintains a particular ordering.

In a min-heap, each parent is smaller than or equal to its children. This means the smallest value is always available at the root.

Heaps are particularly useful when implementing priority queues.

Graphs represent something different. They consist of vertices connected by edges.

Unlike trees, graphs can represent more complicated relationships, such as roads between cities or connections between computers.

**Slide 50 – BFS and DFS Explore Graphs Differently**

Finally, let's look at two common graph traversal algorithms.

Breadth-First Search, or BFS, explores a graph level by level. It uses a queue to remember which nodes should be visited next.

Depth-First Search, or DFS, explores one path as deeply as possible before returning to explore other paths. It uses a stack or recursion.

An important advantage of BFS is that it finds the shortest path in an unweighted graph.

DFS, on the other hand, can be useful when exploring possible paths or searching through hierarchical structures.

**Closing**

We have now covered the foundations of algorithms and data structures.

The key takeaway is that solving a problem requires more than simply writing instructions. We need to choose a suitable algorithm, understand its efficiency, and organize the data in a way that supports the operations we need.

But how does a computer go beyond processing information and actually reason about it?

That brings us to the next chapter: Symbolic AI.

---

# **VIDEO 02: SYMBOLIC AI – LOGIC AND KNOWLEDGE REPRESENTATION**

**Slides 51–68 \| Estimated duration: 6–8 minutes**

### **Opening**

**Slide 51 – Symbolic AI: Intelligence Through Explicit Symbols**

Imagine telling a computer that Ada is human, and that all humans are mortal.

Could the computer conclude that Ada is mortal without being explicitly told?

This is the central idea behind Symbolic AI.

Instead of relying entirely on patterns learned from data, Symbolic AI represents knowledge using explicit symbols, facts, relationships, and logical rules.

The system then uses these representations to derive new conclusions.

In other words, it does not simply store information. It can reason with that information.

### **Background and comparison**

**Slide 52 – A Short History of Symbolic AI**

Symbolic AI played a major role in the early development of artificial intelligence.

The Dartmouth Conference in 1956 is widely recognized as an important starting point for AI as a research field.

During the following decades, researchers developed systems such as ELIZA, DENDRAL, and MYCIN.

These systems explored different ways of representing knowledge and solving problems through rules.

However, early AI also experienced periods known as AI winters, when expectations exceeded what the technology could realistically deliver.

Today, symbolic techniques remain useful in areas such as knowledge graphs, automated planning, and hybrid AI systems.

**Slide 53 – Symbolic vs Sub-symbolic AI**

There are two broad approaches worth comparing.

Symbolic AI uses explicit facts, concepts, and rules to represent knowledge.

Sub-symbolic AI, including neural networks, learns patterns from data through adjustable numerical weights.

For example, a neural network might recognize a cat after being trained on thousands of images.

A symbolic system could represent the explicit relationship that cats are mammals and mammals are animals.

Hybrid AI combines both approaches, allowing learned pattern recognition to work alongside explicit reasoning.

### **Logic and propositions**

**Slide 54 – Propositional Logic**

To understand how symbolic reasoning works, we first need to understand logic.

Propositional logic represents complete statements using variables.

For example, let P represent the statement that the room is hot, and Q represent the statement that the fan is on.

Each proposition has a truth value: either true or false.

We can then use logical operators to combine these statements and form more complex expressions.

**Slide 55 – Boolean Operators Combine Propositions**

The most common logical operators include NOT, AND, OR, and XOR.

NOT reverses the truth value of a proposition.

AND is true only when both propositions are true.

OR is true when at least one proposition is true, including when both are true.

XOR is different because it is true when exactly one proposition is true.

We can also use implication, represented by an arrow, to express relationships such as "if P, then Q."

These operators allow computers to evaluate logical conditions systematically.

**Slide 56 – Implication and Inference**

Now let's see how logical rules produce conclusions.

Suppose our rule says: if a robot detects an obstacle, it must stop.

We know that the robot has detected an obstacle.

Therefore, we can conclude that the robot must stop.

This is called modus ponens.

There is also modus tollens, which allows us to infer that P is false when P implies Q and Q is false.

However, be careful: the converse of a rule is not automatically valid. Just because the robot stops does not necessarily mean it detected an obstacle.

This distinction prevents incorrect conclusions.

**Slide 57 – Predicate Logic Describes a World of Objects**

Propositional logic treats an entire statement as one unit.

Predicate logic provides more detail by describing objects, their properties, and their relationships.

For example, Human(Ada) tells us that Ada has the property of being human.

Located(Book, Desk) represents a relationship between a book and a desk.

This is useful because intelligent systems need to represent more than isolated true-or-false statements.

They need to understand how different objects relate to one another.

**Slide 58 – Quantifiers: All or At Least One**

Predicate logic also allows us to describe how many objects a statement applies to.

The universal quantifier means "for all," while the existential quantifier means "there exists at least one."

For example, "Every student owns a laptop" is different from "There is one laptop that every student owns."

The first statement allows different students to own different laptops. The second describes a single laptop shared by all students.

The order and scope of quantifiers can completely change the meaning of a logical statement.

**Slide 59 – Translate Natural Language into Logic**

Let's combine what we have learned.

Suppose we know that all robots are machines.

We also know that R2 is a robot.

By applying the general rule to R2, we can conclude that R2 is a machine.

Notice that the conclusion was not directly provided as a fact. It was derived from two existing statements.

Here is a quick exercise.

How would you represent the statement "Some birds can fly"?

We use the existential quantifier to express that at least one object is both a bird and capable of flying.

**Slide 60 – Propositional vs Predicate Logic**

Let's summarize the difference.

Propositional logic represents complete statements using variables such as P and Q.

Predicate logic goes further by representing objects, properties, relationships, and variables.

For example, "It is raining" can be represented as a simple proposition.

But Rain(London) provides more specific information about where the rain is occurring.

Predicate logic is more expressive, although that additional detail also makes reasoning more complex.

### **Knowledge representation**

**Slide 61 – Knowledge Representation: Make Knowledge Usable**

Symbolic AI needs a way to store information so that it can actually be used.

This is called knowledge representation.

A knowledge base contains facts and rules about a particular domain.

For example, a robot might store information about rooms, objects, locations, and possible movements.

Different representation methods include logic, semantic networks, frames, scripts, rules, and ontologies.

The goal is to organize knowledge in a form that supports reasoning and problem-solving.

**Slide 62 – Semantic Networks: Knowledge as a Graph**

One method is a semantic network.

Instead of storing information as isolated statements, we represent concepts as nodes and relationships as labeled connections.

For example, a cat is a mammal, and a mammal is an animal.

From these relationships, the system can understand that a cat is also an animal.

Other connections can represent relationships such as "part of" or "has property."

However, real systems must also account for exceptions. Not every relationship can be applied blindly.

**Slide 63 – Frames and Scripts: Structured Situations**

Another way to represent knowledge is through frames and scripts.

A frame organizes information using slots and their corresponding values.

For example, a room frame might contain slots for temperature, objects, and people.

Scripts represent familiar sequences of events.

Think about visiting a library. We enter, search for a book, locate it, borrow it, and eventually return it.

These representations help systems understand common situations, although real events do not always follow the expected sequence.

**Slide 64 – Rules and Ontologies**

Rules and ontologies serve different purposes.

Rules describe what should happen when particular conditions are satisfied.

For example, if a robot detects an obstacle, it should stop.

An ontology, meanwhile, defines the concepts and relationships used within a particular domain.

For example, a robot ontology might define what counts as an obstacle, a room, or a movable object.

In simple terms, an ontology establishes the vocabulary, while rules use that vocabulary to reason and make decisions.

**Slide 65 – Compare Representation Methods**

Which knowledge representation method should we choose?

It depends on the problem.

Logic is useful when we need formal statements and logical conclusions.

Semantic networks are useful for representing relationships between concepts.

Frames help describe structured objects or situations.

Rules support conditional decisions, while ontologies establish shared definitions across a domain.

There is no universally best representation. The right choice depends on the type of information and the task being performed.

### **Rule-based systems**

**Slide 66 – Rule-Based Systems: IF–THEN Reasoning**

One important application of symbolic reasoning is the rule-based system.

It normally contains three main components.

First, the knowledge base stores facts and rules.

Second, working memory stores the facts currently known about a particular situation.

Third, the inference engine checks whether any rules match the available information.

When a rule is triggered, the system can produce a new fact or perform an action.

This process allows the system to reason step by step.

**Slide 67 – How an Inference Engine Reasons**

Let's use a simple thermostat as an example.

Suppose the room temperature is 29 degrees Celsius, which is higher than our target temperature.

Rule one checks this condition and concludes that cooling is needed.

That new fact enters working memory.

Rule two then detects that cooling is needed and activates the fan.

Notice the sequence: the original observation triggers one rule, and the result triggers another.

This is how rule-based systems can build conclusions from existing information.

**Slide 68 – Expert Systems Package Specialist Knowledge**

A more specialized application is an expert system.

An expert system attempts to provide decision support within a particular area of expertise.

It combines a knowledge base, an inference engine, and an interface through which users can provide information.

Some systems also include an explanation facility that shows how a particular conclusion was reached.

However, building these systems is not easy. One major challenge is collecting and maintaining accurate knowledge from human experts.

A system is only as useful as the quality of the knowledge it contains.

**Closing**

We have now explored how symbolic AI represents knowledge, uses logic, and derives conclusions through rules.

But reasoning alone is not enough. An intelligent system also needs to decide which actions to take and how to reach a particular goal.

That leads us to search algorithms, automated planning, and natural language processing.

---

# **VIDEO 03: AI SEARCH, PLANNING AND THE ROBOT CHALLENGE**

**Slides 69–90 \| Estimated duration: 9–11 minutes**

### **Search and planning**

**Slide 69 – Planning Begins by Defining the Problem**

Imagine that our robot is standing near a door, and we want it to retrieve a book from a desk.

Before it can move, we need to define the problem.

First, we describe the initial state: where the robot is, where the book is, and which obstacles are present.

Next, we define the actions available to the robot, such as moving, picking up the book, and putting it down.

Finally, we define the goal: the book must reach the user.

This gives us the foundation for automated planning.

**Slide 70 – Uninformed Search: BFS, DFS and UCS**

Search algorithms help us explore possible paths toward a goal.

Uninformed search means that the algorithm does not use an estimate of how far it is from the goal.

Breadth-First Search explores the shallowest nodes first, moving level by level.

Depth-First Search explores deeply along one path before returning to other possibilities.

Uniform Cost Search chooses the path with the lowest accumulated cost.

The difference lies in which unexplored option each algorithm selects.

BFS works well for finding the shortest path in an unweighted graph, while UCS is useful when different paths have different costs.

**Slide 71 – Heuristics Guide Informed Search**

Informed search improves decision-making by using a heuristic.

A heuristic is an estimate of how far a particular state is from the goal.

Greedy Best-First Search selects the option with the lowest estimated remaining cost, represented by h of n.

A\* search uses two values.

The first is g of n, which represents the cost already accumulated.

The second is h of n, which estimates the remaining cost.

A\* combines both values using f of n equals g of n plus h of n.

This allows it to consider both the progress already made and the distance remaining.

*Slide 72 – A in a Small Map*\*

Let's apply A\* to the example on screen.

We have two possible candidates, A and B.

For A, the accumulated cost is 2 and the estimated remaining cost is 5, giving a total estimated cost of 7\.

For B, the accumulated cost is 4 and the estimated remaining cost is 1, giving a total of 5\.

Since B has the lower estimated total cost, A\* expands B first.

The important idea is that A\* evaluates more than just the distance already travelled.

Its ability to find an optimal solution depends on the properties of the heuristic and the search problem.

**Slide 73 – Adversarial Search: When Another Agent Opposes You**

Not every search problem involves finding a route through a map.

In competitive situations, another player may actively try to prevent us from achieving our goal.

This is where adversarial search becomes useful.

A common method is minimax.

MAX represents our player, who tries to obtain the highest possible score.

MIN represents the opponent, who chooses a response that produces the lowest score for MAX.

The algorithm examines possible moves and assumes that both players make the best decisions available to them.

This approach is widely associated with two-player strategic games.

**Slide 74 – Automated Planning: Actions Have Preconditions and Effects**

Search helps us find possibilities, but automated planning also needs to understand how actions change the world.

Consider the Blocks World example.

Suppose a robot wants to pick up a block from a table.

Before performing the action, certain conditions must be satisfied. For example, the robot's hand must be empty, and the block must be on the table.

After the action, the robot is holding the block, and the block is no longer on the table.

These are called preconditions and effects.

A planner uses them to construct a sequence of actions that transforms the initial state into the desired goal state.

### **Natural language processing**

**Slide 75 – Symbolic NLP: Language as Structured Input**

Symbolic techniques can also help computers process human language.

A typical pipeline begins with tokenization, which separates text into individual words or tokens.

Next, part-of-speech tagging identifies the grammatical role of each word.

Parsing then analyzes how those words are connected.

Finally, the system interprets the resulting structure to determine meaning.

For example, consider the sentence shown on screen.

A parser can identify the adjectives, nouns, verb, and prepositional phrase.

This structure helps a computer analyze a sentence rather than simply treating it as an unorganized collection of words.

**Slide 76 – Rules Can Tag and Extract Information**

Rules can also identify important information within text.

For example, a system might recognize names, organizations, dates, or locations using predefined patterns.

Consider the sentence: "Dr. Chen joined Acme Ltd."

A rule-based system can identify Dr. Chen as a person and Acme Ltd. as an organization.

However, simple rules are not always reliable.

For example, words ending in "-ing" are often verbs, but the word "ceiling" clearly shows that this pattern has exceptions.

This illustrates an important limitation of rule-based language processing: language is more complicated than a collection of simple patterns.

**Slide 77 – Meaning Can Be Represented as Relations**

Understanding language requires more than identifying individual words.

We also need to understand how words relate to one another.

Semantic roles help identify who performs an action and who receives it.

For example, in a sentence about a cat chasing a mouse, the cat is the agent and the mouse is the patient.

Lexical databases such as WordNet organize words according to their meanings and relationships.

For example, car and automobile are synonyms, while a wheel is part of a car.

Context is also important. The word "bank" can refer to a financial institution or the side of a river.

**Slide 78 – Symbolic NLP Can Infer Unstated Facts**

One interesting ability of symbolic systems is that they can answer questions using information that was never directly stored as a single fact.

Imagine a knowledge base containing family relationships.

A rule can connect two parent relationships to derive a grandparent relationship.

When a user asks who someone's grandparent is, the system searches through the facts, applies the rule, and produces an answer.

In our example, the inferred answer is Dave.

This demonstrates the difference between simply retrieving stored information and deriving a new fact through reasoning.

However, remember that an incorrect input can still produce an incorrect conclusion, even when the logical inference itself is valid.

**Slide 79 – Rule-Based Sentiment Analysis**

Symbolic techniques can also estimate the emotional tone of written text.

One method uses sentiment lexicons, which assign positive or negative values to words.

For example, the word "good" might receive a positive score of plus two.

An intensifier such as "very" can increase that score, while a word such as "not" can reverse its meaning.

However, sarcasm remains difficult.

Consider the sentence: "Oh great, another delay."

A simple system might interpret the word "great" as positive, even though the entire sentence expresses frustration.

This shows why context matters when analyzing human language.

### **Limitations and hybrid AI**

**Slide 80 – Why Symbolic Systems Struggle**

Despite its advantages, Symbolic AI has several limitations.

First, building a complete knowledge base can be expensive and time-consuming.

Second, rules can fail when unexpected situations or exceptions occur.

Third, natural language contains ambiguity, making interpretation difficult.

Finally, search problems can become extremely large, creating what we call combinatorial explosion.

For example, a robot may have difficulty recognizing a book from a camera image using symbolic rules alone.

These limitations explain why other AI approaches are often needed.

**Slide 81 – Hybrid and Neuro-Symbolic AI**

One possible solution is to combine neural networks with symbolic reasoning.

A neural model can process sensory information and recognize objects from images.

A symbolic system can then represent facts about those objects, apply rules, and plan appropriate actions.

Consider our room-cleaning robot.

A vision model identifies a book. The knowledge base represents where the book is located, and the planning system determines how to reach it.

This combination is known as hybrid or neuro-symbolic AI.

Rather than relying entirely on one approach, it combines different methods to handle different parts of a problem.

### **Integration: The robot challenge**

**Slide 82 – Capstone: Send the Robot to Fetch a Book**

Now let's bring everything together.

Our challenge is to design a robot that can find a book and deliver it to a user.

However, the robot must deal with several constraints, including obstacles, people, and battery limitations.

It needs to sense its surroundings, represent the information, reason about the situation, plan a route, and finally act.

Let's examine how the different parts of our module contribute to this task.

**Slide 83 – Step 1: Identify the Software Stack**

First, we need the software that controls the robot.

Its sensors and motors are physical hardware components.

Drivers allow the operating system to communicate with these devices, while the operating system manages processes and memory.

On top of this, the robot application coordinates the actual task.

An optional cloud service could provide additional computing or data storage, but the robot may also need to operate when network access is unavailable.

**Slide 84 – Step 2: Represent the Room**

Next, the robot needs a representation of its environment.

We can use a graph to represent the room.

Each vertex represents a location, such as a door, hallway, desk, or table.

Each edge represents a possible connection between two locations.

We can also assign costs to these edges to represent distance or movement difficulty.

Alongside this graph, the robot stores facts such as the location of the book and its own current position.

**Slide 85 – Step 3: Reason with Explicit Facts**

Now the robot needs to reason about the information it receives.

Suppose a sensor detects an obstacle along a particular path.

A rule can translate this observation into a new fact: that path is blocked.

Another rule might tell the robot to prefer shorter routes when its battery is low.

However, these conclusions depend on the accuracy of the sensor observations.

If the sensor provides incorrect information, the robot may make a poor decision.

**Slide 86 – Step 4: Choose a Route**

Once the room has been represented, the robot needs to select a suitable route.

There are several possible search algorithms.

BFS finds the route with the fewest edges, assuming each edge has equal cost.

UCS searches for the route with the lowest accumulated movement cost.

A\* combines the cost already travelled with an estimate of the distance remaining.

If different corridors have different lengths, UCS or A\* would generally be more suitable than BFS.

**Slide 87 – Step 5: Execute, Monitor and Recover**

Finding a route does not guarantee that the robot will successfully reach its destination.

The robot must execute its movement commands and continuously compare sensor feedback with the expected state.

Suppose a new obstacle appears after the route has been calculated.

The robot needs to update its information, identify that the original route is no longer suitable, and plan again.

Safety rules must also remain active throughout the process.

This is why intelligent systems need monitoring and recovery, not just an initial plan.

**Slide 88 – Final Challenge: Design the Hybrid Robot**

Now it is your turn.

Imagine that you are part of the engineering team responsible for designing this robot.

Think about three questions.

First, what technology could help the robot recognize the book?

Second, how could it represent the connections between different locations in the room?

Third, which reasoning and search methods would help it choose a safe and efficient route?

Pause the video and discuss your answers with a partner.

\[Allow 60–90 seconds for discussion.\]

Try to identify at least one possible limitation of your proposed system as well.

**Slide 89 – Model Answer: One System, Several Kinds of Intelligence**

Let's compare your ideas with one possible solution.

A neural model can identify the book using visual information.

A graph can represent the room and the connections between different locations.

A symbolic knowledge base stores facts and rules, such as identifying blocked paths.

UCS or A\* can then determine an appropriate route, while the robot's software executes the movement commands.

Finally, sensor feedback allows the system to monitor its progress and re-plan when necessary.

Notice that no single component performs the entire task. The robot succeeds because all of these components cooperate.

**Slide 90 – From Code to Intelligent Decisions**

We have now reached the end of our module.

Throughout these chapters, we explored three major foundations of intelligent systems.

Software provides the instructions and infrastructure that allow a computer to operate.

Algorithms solve computational problems, while data structures organize the information needed to perform those operations efficiently.

Finally, Symbolic AI represents knowledge through facts, relationships, and logical rules, allowing systems to reason and plan.

When combined with learned perception and real-world feedback, these methods can support increasingly capable intelligent systems.

So, returning to our opening question: how does a robot fetch a book?

It does not happen through one magical AI algorithm. It happens because software, algorithms, data structures, perception, and reasoning work together.

And that is the central idea of this module.

---

## **END OF VIDEO SCRIPT**

**References slide:** Display the selected references at the end of the presentation for approximately 5–8 seconds. No additional narration is necessary.
