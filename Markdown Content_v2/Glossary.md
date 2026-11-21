# Glossary: Software, Algorithms and Data Structures, Symbolic AI

---

| Part | Topic | Terms | Reference numbers |
| ----- | ----- | ----- | ----- |
| 1 | Software | 127 | none |
| 2 | Algorithms and Data Structures | 130 | 2.x |
| 3 | Symbolic AI | 172 | 3.x |

---

## Part 1: Software

Terms from the Software topic.

### 0-9

**32-Bit Signed Integer**: A signed integer format using 32 bits, capable of representing values up to `2,147,483,647` ($2^{31} - 1$).

**4GL (Fourth-Generation Language)**: Higher-level languages built for specific domains (such as database querying with SQL) that specify desired outcomes with less procedural boilerplate.

### A

**Abstraction**: Reducing complexity by hiding underlying implementation details and exposing only relevant concepts or interfaces.

**Acceptance Test**: Validation testing to confirm the software meets business or customer requirements before sign-off.

**ACID Properties**: Atomicity, Consistency, Isolation, and Durability: properties that ensure reliable database transaction processing.

**Agile**: An iterative, collaborative approach to software development emphasizing short release cycles, adaptability, and frequent feedback.

**Application Software**: Programs designed to perform specific tasks for end users, such as web browsers, word processors, media players, and video games, relying on system software to execute.

**ASCII**: A character encoding standard that maps characters (such as letters, digits, and punctuation) to numeric values and binary representations.

**Assembler**: A program that translates assembly language mnemonics into machine code.

**Assembly Language**: A low-level programming language closely tied to a processor's architecture that uses symbolic instructions instead of raw binary.

**Atomicity**: The transaction property ensuring all operations in a transaction succeed together or none take effect.

### B

**Batch System**: An early operating system model where jobs are grouped and run sequentially without interactive user input during execution.

**Binary**: A base-2 numeral system using `0` and `1`, corresponding to two electrical states (`OFF` and `ON`) in digital hardware.

**Bit**: A single binary digit (`0` or `1`), representing the basic unit of digital information.

**Black-Box Testing**: Testing software based on inputs and expected outputs without examining internal code structure.

**Branch**: An independent line of development in version control that allows isolated changes before merging.

**Bytecode**: An intermediate, lower-level representation of code designed to be executed efficiently by a virtual machine or runtime engine rather than directly by physical hardware.

### C

**Column (Attribute)**: A named field in a table representing a specific property or data element of each record.

**Commit**: A recorded snapshot of changes saved to a version control history along with metadata such as a message.

**Compiled Binaries**: Executable files produced by compiling source code, distributed without exposing the underlying human-readable source.

**Compiler**: A translator that converts an entire source program into target code (often machine code or bytecode) prior to execution.

**Context Switch**: The process of saving the execution state of a running process and loading the saved state of another process so the CPU can switch tasks.

**Control Structures**: Constructs (such as conditional branching and loops) that determine the order in which instructions execute.

**Copyleft Licence (e.g., GPL)**: A licensing approach requiring derivative or distributed works to remain under the same (or compatible) open license terms.

**CPU (Central Processing Unit)**: The primary processor that executes program instructions and performs arithmetic and logical operations.

### D

**Database**: A structured collection of organized data stored for efficient retrieval and management.

**Data Types**: Classifications that define what kind of values a piece of data can hold and what operations are valid on it.

**DBMS (Database Management System)**: Software that creates, stores, queries, updates, and administers databases while enforcing access and integrity rules.

**Declarative / Logic Programming**: A paradigm where programs express *what* result or relationship is desired rather than detailing explicit control flow.

**Deploy**: Pushing built software to target environments or servers so users can access or run it.

**Derivative Works**: Software created by adapting, modifying, or building upon existing software.

**Device Driver**: System software that enables the operating system to communicate with and control specific hardware peripherals, such as a graphics card or storage device.

**Distributed System**: A collection of independent computers connected over a network that coordinate to function as a cohesive system.

### E

**Encapsulation**: Bundling data and related methods within an object while restricting direct external access to internal state.

### F

**Foreign Key (FK)**: A column or set of columns in one table that references the primary key of another table to link records across tables.

**Fork**: Creating an independent copy of a codebase to pursue a separate development path.

**Freeware**: Software distributed at no monetary cost, though not necessarily open source or accompanied by source code rights.

**Functional Programming**: A paradigm emphasizing pure functions and immutable data while minimizing side effects and mutable state.

### G

**Git**: A widely used distributed version control system created for Linux kernel development.

**GPU (Graphics Processing Unit)**: Specialized hardware designed to accelerate graphics rendering, image processing, and parallel computations.

### H

**Hardware**: The physical components of a computing system, such as processors, memory chips, storage drives, and input/output devices.

**High Cohesion**: A design quality where elements within a module belong together and serve a single, well-defined responsibility.

**High-Level Code**: Human-readable programming code written with structured syntax and abstractions (such as Python, C++, or Java) rather than raw hardware instructions.

**Hybrid Cloud**: A deployment model combining two or more distinct cloud infrastructures (such as private and public) while preserving data and application portability.

### I

**IaaS (Infrastructure as a Service)**: A cloud service model providing fundamental compute, storage, and network resources on demand.

**If/Else (Selection)**: Conditional branching that chooses which code path to execute based on whether a condition evaluates to true or false.

**Imperative / Procedural Programming**: A paradigm focused on explicit step-by-step statements and procedures that change program state over time.

**Information Hiding**: Concealing internal module details behind a defined interface so external components do not depend on internal implementation.

**Inheritance**: An OOP mechanism allowing a class or object to derive attributes and behaviors from an existing parent class.

**Intangible**: Existing as digital information or rules rather than a physical object that can be touched.

**Integration Test**: Testing combined modules to verify their interactions and data exchange work as expected.

**Interpreter**: A translator that reads, analyzes, and executes source code step-by-step or line-by-line during runtime.

**Iterative / Incremental**: Developing a system in repeated cycles and/or progressive increments that add functionality over time.

### J

**JIT (Just-In-Time Compilation)**: Compiling portions of bytecode or interpreted code into native machine code during execution to improve runtime performance.

**JOIN**: A relational/SQL operation that combines rows from two or more tables based on related columns, typically keys.

### L

**Lexical Analysis (Tokens)**: The initial compilation phase that scans source text and groups characters into meaningful units called tokens.

**Linux Kernel**: The central core of a Linux operating system that manages hardware resources, memory, and processes.

**Loops (Iteration)**: Repeating a block of instructions while a condition holds or across a collection of items.

**Low Coupling**: A design quality where modules have minimal dependencies on one another, reducing ripple effects when changes occur.

### M

**Machine Code**: Low-level binary instructions directly executed by a CPU's hardware circuitry.

**Measured Service**: Monitoring, controlling, and reporting resource usage to provide transparency and usage-based billing.

**Memory Allocation**: Assigning regions of main memory to running processes.

**Memory Protection**: Hardware and OS enforcement preventing one process from reading or writing memory belonging to another process or the OS.

**Merge**: Integrating changes from one branch into another.

**Mnemonics**: Short symbolic names or abbreviations (such as `MOV` or `ADD`) representing low-level instructions in assembly language.

**Modularity**: Dividing a software system into distinct modules with clear boundaries to improve maintainability and parallel development.

**Multiprogramming / Multitasking**: Techniques that allow multiple programs to reside in memory and advance concurrently by rapidly switching execution across them.

### N

**Normalisation**: Structuring relational tables to minimize data redundancy and prevent update anomalies.

**NoSQL**: Non-relational database approaches designed for flexible schemas, distributed scale, or specialized data models beyond traditional tabular relations.

### O

**Object-Oriented Programming (OOP)**: A paradigm that organizes software around objects encapsulating state (data/attributes) and behavior (methods).

**Open-Source Software**: Software whose source code is made available under terms meeting open-source criteria, allowing inspection, modification, and redistribution.

**Operating System (OS)**: Core system software that coordinates hardware resources, manages processes and memory, and provides an interface for users and applications.

**Overflow**: A condition occurring when a calculation produces a value outside the representable range of a fixed-size numeric type, potentially causing wrap-around or errors.

### P

**PaaS (Platform as a Service)**: A cloud service model providing a managed platform and runtime environment where developers deploy and run their own applications.

**Page Fault**: An event triggered when a program accesses a memory page that is not currently loaded in physical RAM, requiring the OS to retrieve it from disk.

**Paging / Page**: Dividing virtual and physical memory into fixed-size blocks (pages) so memory can be mapped and swapped between RAM and disk.

**Paradigm**: A foundational style or methodology for structuring and writing programs (such as imperative, object-oriented, functional, or logic).

**Parsing (Syntax Tree)**: The compilation phase that analyzes token structure against grammar rules, typically building a syntax tree.

**Permissive Licence (e.g., MIT)**: A software license with minimal restrictions on reuse and modification, generally permitting inclusion in proprietary works.

**Polymorphism**: The ability for different entities or types to respond to the same interface or operation in type-specific ways.

**Primary Key (PK)**: A column or set of columns that uniquely identifies each row in a table.

**Process**: A program currently in execution, along with its runtime state and allocated resources.

**Proprietary (Closed-Source) Software**: Software whose source code remains privately owned and restricted by a vendor or organization, typically distributed as compiled binaries under a license.

**Pseudocode**: An informal, structured outline of an algorithm written in plain language mixed with code-like conventions.

### Q

**Quantum**: The fixed time slice allocated to a process in round-robin scheduling before it yields or moves to the back of the ready queue.

**Query**: A request or statement issued to a database to retrieve, insert, update, or delete data.

### R

**RAM (Random Access Memory)**: Fast, volatile main memory used to hold active programs and data currently being processed by the CPU.

**Rapid Elasticity**: The ability to scale computing resources up or down quickly (often automatically) to match changing demand.

**Recursion**: A technique in which a function calls itself to solve a problem by breaking it down into smaller subproblems.

**Redundancy**: Duplicating the same data across multiple places in a database.

**Relational Model / Relational Database**: A data model organizing information into tables (relations) of rows and columns with relationships established via keys.

**Repository (Repo)**: A storage location (local or remote) containing a project's files and version history.

**Resource Pooling**: Sharing provider computing resources across multiple consumers dynamically assigned and reassigned according to demand.

**Round Robin**: A CPU scheduling policy that assigns each ready process a fixed time slice in cyclic order.

**Row (Tuple)**: A single record within a table representing one instance of the entity.

### S

**SaaS (Software as a Service)**: A cloud service model where providers host and run applications centrally, and users access them via a client such as a web browser.

**Scheduler**: The OS component that selects which ready process is assigned to the CPU next.

**Schema**: The formal structure or blueprint defining tables, columns, data types, keys, and relationships in a database.

**SDLC (Software Development Life Cycle)**: The structured lifecycle for planning, designing, coding, testing, releasing, and maintaining software.

**Semantic Checks**: Verification stages that check logical validity and type/meaning rules beyond basic grammatical structure.

**Server**: A dedicated computer system that provides data, services, or hosted applications to other computers (clients) over a network.

**Software**: Intangible sets of digital instructions, rules, and data stored on hardware that direct how physical components operate.

**Software Licence**: Legal terms governing how software may be used, modified, distributed, or commercialized.

**Source Code / Source Text**: The original human-written code files before translation or compilation into executable form.

**Spiral Model**: A risk-driven process model that cycles through planning, risk analysis, engineering, and evaluation.

**SQL (Structured Query Language)**: A declarative language used to define, query, and manipulate data in relational databases.

**Synchronisation (Sync)**: Keeping data consistent across multiple devices or locations automatically.

**Syntax**: The formal rules governing the structure and valid arrangement of symbols and keywords in a programming language.

**System Architecture**: The high-level structural design defining a system's components, interfaces, data flow, and interactions.

**System Software**: Foundational software positioned between hardware and applications that manages core resources (such as memory, processor time, and storage) and provides a user interface.

**System Test**: End-to-end testing of the complete, integrated software system against specifications.

### T

**Table (Relation)**: A structured set of data organized into rows and columns representing an entity or relationship.

**The Cloud**: Pooled, remote computing resources (such as servers, storage, and networking) delivered over the internet.

**Time-Sharing**: A multi-user computing model where multiple users interact with a system simultaneously by sharing CPU time via rapid switching.

**Transaction**: A sequence of database operations executed as a single logical unit of work that either completes entirely or rolls back.

**Transistor**: A semiconductor switch inside a processor that toggles electrical states to represent and process binary signals.

### U

**Unit Test**: Automated or targeted testing of an individual function or smallest testable unit in isolation.

**UNIX**: A foundational multi-user, multitasking operating system that heavily influenced modern operating systems.

**Update Anomalies**: Inconsistencies or errors that arise during inserts, updates, or deletes when redundant data is not updated uniformly.

**User Interface (UI)**: The visual or interactive layer (such as windows, icons, menus, and controls) through which users interact with software.

### V

**Variables**: Named storage references in a program that hold values which can be read or updated during execution.

**Vendor Lock-In**: Dependency on a single provider's proprietary tools, formats, or ecosystem that makes switching providers costly or difficult.

**Version Control**: A system that tracks revisions to files over time, enabling history inspection, branching, and rollback.

**Virtual Machine (VM)**: A software-based execution environment that emulates a computer or runs bytecode independently of underlying hardware specifics.

**Virtual Memory**: A memory management technique that decouples logical address space from physical RAM, allowing programs to use more address space than physical RAM by storing inactive data on disk.

### W

**Waterfall Model**: A sequential software development model where each phase is completed before moving to the next.

**White-Box Testing**: Testing software with visibility into internal code paths, logic, and structure.

---

## Part 2: Algorithms and Data Structures

Brackets point to Topic 2 subtopics.

### A

**Abstract data type (ADT)**: A description of what a structure does (its operations), without saying how it is built. Example: A stack with push and pop, built from either an array or a linked list. [2.5.1]

**Adjacency list**: A way to store a graph: each vertex keeps a list of its neighbors. Example: A: [B, C]. [2.9]

**Adjacency matrix**: A way to store a graph: a V by V table where 1 means an edge exists. Example: Row A, column B holds 1 if A and B are connected. [2.9]

**Algorithm**: A finite, precise list of steps that turns an input into an output. Example: Euclid's method for the greatest common divisor. [2.1.1]

**Amortized cost**: The average cost per operation over many operations, even if a few are expensive. Example: Appending to a dynamic array is usually fast, with an occasional costly resize. [2.5.2]

**Array**: A fixed number of same-type items stored side by side in memory and reached by index. Example: `[10, 20, 30]`. [2.5.2]

**Average case**: The cost for a typical input. Example: Linear search finds a middle item after about n/2 checks. [2.1.4]

**AVL tree**: A self-balancing binary search tree whose subtree heights differ by at most 1. Example: Rotations restore balance after an insert. [2.8.2]

### B

**Backtracking**: Build a solution step by step and undo a step when it cannot work. Example: Sudoku, N-queens. [2.4.1]

**Balanced tree**: A tree whose sides have similar heights, so its height stays near log n. Example: AVL tree. [2.8.2]

**Base case**: The simplest case in a recursive function, answered directly so the recursion stops. Example: `factorial(0)` returns 1. [2.2]

**Best case**: The input that makes an algorithm fastest. Example: Target is the first item in linear search. [2.1.4]

**Big-O notation**: A way to describe how cost grows with input size n, ignoring constants. Example: 3n² + 5n is O(n²). [2.1.4]

**Binary search**: Find an item in a sorted array by halving the search range each step. Example: Finding 23 in 3 steps instead of up to 10. [2.3.1]

**Binary search tree (BST)**: A binary tree where every left key is smaller and every right key is larger than the node's key. Example: Insert 8, 3, 10, 1, 6. [2.8.2]

**Binary tree**: A tree where each node has at most two children (left and right). Example: An expression tree. [2.8.2]

**Breadth-first search (BFS)**: Visit a graph or tree level by level, using a queue. Example: From A: A, B, C, D, E. [2.9]

**Brute force**: Try every possibility until one works. Example: Linear search. [2.4.1]

**B-tree**: A balanced tree with many keys per node, designed for disks. Example: Database indexes. [2.8.2]

**Bubble sort**: Repeatedly swap neighboring items that are out of order. Example: `[5, 2, 4, 1]` becomes `[1, 2, 4, 5]`. [2.3.2]

### C

**Call stack**: The memory area that keeps track of active function calls, one frame per call. Example: `factorial(4)` waits on `factorial(3)` and so on. [2.2]

**Child**: A node directly below another node in a tree. Example: B is a child of A. [2.8.1]

**Circular linked list**: A linked list whose last node points back to the first. Example: A playlist that repeats. [2.6]

**Circular queue**: A fixed-size queue whose indexes wrap around to reuse space. Example: A keyboard buffer. [2.7.2]

**Comparison sort**: A sort that orders items only by comparing pairs; none can beat O(n log n) in the worst case. Example: Merge sort, quick sort. [2.3.2]

**Complete binary tree**: A binary tree with every level full except possibly the last, which fills left to right. Example: A heap. [2.8.2]

**Complexity**: How much time or memory an algorithm needs as the input grows. Example: O(n) time. [2.1.4]

**Constant time, O(1)**: The cost does not depend on the input size. Example: Reading `array[i]`. [2.1.4]

**Control structure**: A building block of an algorithm: sequence, selection or iteration. Example: `if`, `while`. [2.1.3]

**Correctness**: The algorithm gives the right output for every valid input. Example: A sort that works on empty lists too. [2.1.2]

**Counting sort**: A sort for small whole-number keys that counts values instead of comparing, O(n + k). Example: Sorting exam scores from 0 to 100. [2.3.2]

### D

**Data structure**: A way of organizing data so operations on it are efficient. Example: Array, stack, tree. [2.5.1]

**Definiteness**: Every step is precise and unambiguous. Example: "Add 2" is definite; "add a bit more" is not. [2.1.2]

**Degenerate tree**: A tree where each node has one child, so it behaves like a linked list. Example: Inserting 1, 2, 3, 4 into a BST. [2.8.2]

**Degree**: The number of children a node has. Example: A node with 3 children has degree 3. [2.8.1]

**Depth**: The number of edges from the root to a node. Example: A grandchild of the root has depth 2. [2.8.1]

**Depth-first search (DFS)**: Go as deep as possible along a path, then backtrack, using a stack or recursion. Example: From A: A, B, D, C, E. [2.9]

**Deque**: A double-ended queue: add and remove at both ends. Example: Python `collections.deque`. [2.7.2]

**Dequeue**: Remove and return the front item of a queue. Example: `dequeue()` returns A. [2.7.2]

**Dijkstra's algorithm**: Finds shortest paths in a weighted graph using a priority queue. Example: Route planning. [2.9]

**Divide and conquer**: Split a problem into smaller parts, solve each, then combine. Example: Merge sort. [2.4.1]

**Doubly linked list**: A linked list where each node points to both the next and the previous node. Example: Browser history. [2.6]

**Dynamic array**: An array that grows by moving into a bigger block when full. Example: Python `list`. [2.5.2]

**Dynamic programming**: Solve overlapping subproblems once and store the answers. Example: Memoized Fibonacci. [2.4.1]

### E

**Edge**: A connection between two vertices in a graph, or between a parent and child in a tree. Example: A to B. [2.8.1, 2.9]

**Effectiveness**: Each step is basic enough to be carried out exactly. Example: Using only addition and comparison. [2.1.2]

**Enqueue**: Add an item at the rear of a queue. Example: `enqueue(B)`. [2.7.2]

**Euclid's algorithm**: Finds the greatest common divisor by repeatedly taking remainders. Example: gcd(48, 18) = 6. [2.1.2]

**Exponential time, O(2ⁿ)**: The cost doubles each time n grows by 1, so it only works for tiny inputs. Example: Checking every subset of n items. [2.1.4]

### F

**FIFO**: First in, first out: the oldest item leaves first. Example: A queue. [2.7.2]

**Finiteness**: The algorithm stops after a finite number of steps. Example: A loop whose condition eventually becomes false. [2.1.2]

**Flowchart**: Control flow is visible at a glance. Example: Gets large and messy for complex algorithms. [Teaching, small decision logic]

**Flowchart**: A diagram of an algorithm using standard shapes and arrows. Example: Oval for start, diamond for a decision. [2.1.3]

**Frame (stack frame)**: The record on the call stack holding the variables of one function call. Example: One frame per `factorial` call. [2.2]

**Front**: The end of a queue from which items are removed. Example: The next person in line. [2.7.2]

**Full binary tree**: A binary tree where every node has 0 or 2 children. [2.8.2]

### G

**Generality**: The algorithm solves a whole class of problems, not one instance. Example: Sorts any list, not only `[3, 1, 2]`. [2.1.2]

**Graph**: Vertices joined by edges; it may have cycles and no root. Example: A road map, a social network. [2.9]

**Greedy algorithm**: At each step take the choice that looks best right now. Example: Making change with standard coins. [2.4.1]

### H

**Halting problem**: The question "will this program ever stop?", proven impossible to answer for all programs. Example: Turing, 1936. [2.1.2, 2.4.2]

**Hash table**: A structure that finds items in O(1) on average by computing an index from the key. Example: A Python dictionary. [2.3.1, 2.10.1]

**Head**: The first node of a linked list. Example: `head → 7 → 12`. [2.6]

**Heap**: A complete binary tree, stored in an array, that obeys the heap property. Example: A priority queue. [2.8.2]

**Heap property**: In a min-heap every parent is less than or equal to its children (reversed for a max-heap). Example: The smallest item sits at the root. [2.8.2]

**Heap sort**: Sort by repeatedly taking the smallest item from a heap, O(n log n). [2.3.2]

**Height**: The number of edges on the longest path from a node down to a leaf. Example: A single node has height 0. [2.8.1]

### I

**Index**: The position number of an array element, usually starting at 0. Example: `a[0]` is the first item. [2.5.2]

**In-order traversal**: Visit the left subtree, then the node, then the right subtree; gives sorted keys in a BST. Example: 1, 3, 4, 6, 7, 8, 10, 13, 14. [2.8.2]

**In-place**: Uses only a small, fixed amount of extra memory. Example: Quick sort, selection sort. [2.3.2]

**Insertion sort**: Grow a sorted prefix by sliding each new item into its place, like sorting cards in your hand. Example: Fast on nearly sorted data. [2.3.2]

**Internal node**: A tree node with at least one child. Example: The root of a tree with children. [2.8.1]

**Intractable problem**: A problem with no known efficient algorithm. Example: Traveling salesman for many cities. [2.4.2]

**Iteration**: Repeating steps with a loop. Example: `for`, `while`. [2.2]

### K

**Key**: The field used to compare, order or find records. Example: Student ID. [2.5.3, 2.8.2]

### L

**Leaf**: A tree node with no children. Example: E and F in a small tree. [2.8.1]

**Level-order traversal**: Visit a tree level by level, using a queue. Example: 8, 3, 10, 1, 6, 14, 4, 7, 13. [2.8.1, 2.8.2]

**LIFO**: Last in, first out: the newest item leaves first. Example: A stack. [2.7.1]

**Linear search**: Check items one by one until the target is found. Example: Works on unsorted lists. [2.3.1]

**Linear time, O(n)**: The cost grows in proportion to the input size. Example: Finding the largest item. [2.1.4]

**Linked list**: A chain of nodes, each holding a value and a reference to the next node. Example: `7 → 12 → 5 → 9`. [2.6]

**Logarithmic time, O(log n)**: The cost grows very slowly; doubling the input adds only one step. Example: Binary search. [2.1.4]

**Loop**: A structure that repeats a block of steps. Example: `for i in range(5)`. [2.2]

**Loop invariant**: A statement that stays true before and after every pass; used to prove a loop correct. Example: "`max` holds the largest item seen so far". [2.2]

### M

**Memoization**: Store the result of a call so it is not computed again. Example: `lru_cache` on Fibonacci. [2.2]

**Merge sort**: Split the list in half, sort each half, then merge; O(n log n) in every case. Example: `[38, 27, 43, 3, 9, 82]`. [2.3.2]

### N

**Natural language**: Easy for anyone to read. Example: Ambiguous, wordy. [First draft, explaining to non-programmers]

**Node**: The basic unit of a linked list or tree: a value plus references to other nodes. Example: A list node with `value` and `next`. [2.6]

### O

**Off-by-one error**: A loop runs once too many or too few, or an index is one position wrong. Example: Using `range(n)` when `range(n + 1)` is needed. [2.2]

**Overflow**: Pushing onto a stack that is already full (fixed-size stack). [2.7.1]

### P

**Parent**: The node directly above another node in a tree. Example: A is the parent of B. [2.8.1]

**Peek**: Read the top of a stack or front of a queue without removing it. [2.7.1, 2.7.2]

**Perfect binary tree**: A full binary tree with all leaves on the same level; it has 2^(h+1) − 1 nodes. Example: Height 3 gives 15 nodes. [2.8.2]

**Pivot**: The item quick sort partitions around. Example: The last item of the list. [2.3.2]

**Pointer (reference)**: A value that tells where another item is in memory. Example: `next` in a linked list node. [2.6]

**Pop**: Remove and return the top item of a stack. [2.7.1]

**Post-order traversal**: Visit the left subtree, the right subtree, then the node. Example: 1, 4, 7, 6, 3, 13, 14, 10, 8. [2.8.2]

**Pre-order traversal**: Visit the node, then the left subtree, then the right subtree. Example: 8, 3, 1, 6, 4, 7, 10, 14, 13. [2.8.2]

**Priority queue**: A queue where items leave by priority, not arrival order, usually built with a heap. Example: Task scheduling. [2.7.2, 2.8.2]

**Programming language**: Executable, testable. Example: Language details distract from the idea. [Final implementation]

**Pseudocode**: Precise but independent of any language. Example: No standard syntax; cannot be run. [Design and textbooks]

**Pseudocode**: Structured plain-language steps that are not tied to any programming language. Example: `for i ← 2 to n do`. [2.1.3]

**Push**: Add an item to the top of a stack. [2.7.1]

### Q

**Quadratic time, O(n²)**: The cost grows with the square of the input size. Example: Bubble, selection and insertion sort. [2.1.4]

**Queue**: A first-in, first-out collection: add at the rear, remove from the front. Example: A print queue. [2.7.2]

**Quick sort**: Pick a pivot, split items around it, then sort each side; average O(n log n), worst case O(n²). [2.3.2]

### R

**Random access**: Reaching any element directly in constant time. Example: `a[500]`. [2.5.2]

**Rear**: The end of a queue where items are added. Example: The back of the line. [2.7.2]

**Record**: A group of named fields, possibly of different types, describing one thing. Example: A `Student` with id, name, gpa. [2.5.3]

**Recursion**: A function solving a problem by calling itself on a smaller instance. Example: `factorial(n)` calls `factorial(n − 1)`. [2.2]

**Recursive case**: The part of a recursive function that shrinks the problem and calls itself. Example: `n * factorial(n − 1)`. [2.2]

**Red-black tree**: A self-balancing binary search tree that uses node colors. Example: Used in many library maps. [2.8.2]

**Root**: The top node of a tree, with no parent. Example: A. [2.8.1]

### S

**Search**: Finding the position of a target in a collection. Example: Linear or binary search. [2.3.1]

**Selection sort**: Repeatedly move the smallest of the unsorted items to the front. Example: `[29, 10, 14, 37, 13]`. [2.3.2]

**Sibling**: A node that shares the same parent as another node. Example: B, C, D under A. [2.8.1]

**Sorting**: Rearranging items into a chosen order. Example: Smallest to largest. [2.3.2]

**Space complexity**: How much extra memory an algorithm needs as n grows. Example: Merge sort needs O(n). [2.1.4]

**Stable sort**: A sort that keeps equal items in their original order. Example: Merge sort, insertion sort. [2.3.2]

**Stack**: A last-in, first-out collection: add and remove at the top. Example: Undo history. [2.7.1]

**Stack overflow**: The call stack runs out of space, often from recursion with no reachable base case. Example: Missing base case. [2.2]

**Struct**: The name for a record in C. Example: `struct Student { ... };`. [2.5.3]

**Subtree**: A node together with all of its descendants. Example: The subtree rooted at B. [2.8.1]

### T

**Tail**: The last node of a linked list (a tail pointer makes adding at the end O(1)). [2.6]

**Tail recursion**: A recursive call that is the last action of the function. [2.2]

**Time complexity**: How the number of steps grows with the input size. Example: O(n log n). [2.1.4]

**Traversal**: Visiting every item in a structure exactly once. Example: Pre-order, in-order, BFS. [2.8.1]

**Tree**: A hierarchy of nodes with one root and no cycles. Example: A folder structure. [2.8.1]

### U

**Underflow**: Popping an empty stack or dequeuing from an empty queue. [2.7.1, 2.7.2]

### V

**Vertex**: A node of a graph. Example: A city on a map. [2.9]

### W

**Worst case**: The input that makes an algorithm slowest, used as a guarantee. Example: Target is last or missing in linear search. [2.1.4]

### Big-O at a Glance

| Class | Name | Example |
| ----- | ----- | ----- |
| O(1) | Constant | Array access by index |
| O(log n) | Logarithmic | Binary search |
| O(n) | Linear | Linear search, find the largest |
| O(n log n) | Linearithmic | Merge sort |
| O(n²) | Quadratic | Bubble, selection, insertion sort |
| O(2ⁿ) | Exponential | Checking every subset |
| O(n!) | Factorial | Trying every ordering of n cities |

---

## Part 3: Symbolic AI

Brackets point to Topic 3 subtopics.

### A

**Action**: Something an agent can do in a state, described with preconditions and effects. [3.5.2]

**Add List**: In STRIPS, the facts that become true after an action is applied. [3.5.8]

**Admissible Heuristic**: A heuristic h(n) that never overestimates the true remaining cost to the goal. Straight-line distance is an example. [3.5.5]

**Adversarial Search**: Search used when another agent opposes the agent's actions, as in two-player games such as chess. [3.5.6]

**Agent (Semantic Role)**: The participant who performs an action. In "The cat chased the mouse," the agent is *cat*. [3.6.4]

**Alpha-Beta Pruning**: An optimization of minimax that returns the same decision while skipping branches that cannot affect it. A branch is cut when α ≥ β. [3.5.6]

**Ambiguity**: A sentence or word that has more than one valid interpretation (for example, "I saw the man with the telescope"). A central difficulty for rule-based NLP. [3.6.3]

**Antecedent**: The "if" part (premise p) of an implication p → q. [3.2.2.4]

**Artificial Intelligence Winter (AI Winter)**: The late-1980s to 1990s collapse in funding after expert systems proved costly to maintain and brittle. [3.1.2]

**A\* Search**: An informed search that orders the frontier by f(n) = g(n) + h(n). It is optimal when h is admissible (tree search) or consistent (graph search). Weakness: high memory use. [3.5.5]

### B

**Backtracking Search**: A CSP method that assigns variables one at a time and undoes (backtracks) an assignment when a constraint is violated. [3.5.9]

**Backward Chaining**: Goal-driven reasoning that starts from a hypothesis and checks whether the facts support it. Like a doctor asking "could it be flu?" [3.1.3, 3.4.1.4]

**Backward (Regression) Search**: A planning strategy that starts from the goal and finds actions that could produce it, replacing the goal with their preconditions. [3.5.8]

**Biconditional (p ↔ q)**: "p if and only if q." True when p and q have the same truth value. [3.2.2.4]

**Boolean Operators**: AND (∧), OR (∨), and NOT (¬), used to combine propositions. [3.2.2.2]

**Boolean Query**: An information retrieval query that combines terms with AND, OR, and NOT. [3.6.10]

**Branching Factor (b)**: The number of actions available in each state. [3.5.2]

**Breadth-First Search (BFS)**: Expands the shallowest unexpanded node first, using a queue. Complete, and optimal when all steps cost the same, but memory-hungry. [3.5.4]

**Brittleness**: The tendency of a system to fail outside its narrow domain or when input differs slightly from what its rules expect. [3.4.4, 3.6.12]

### C

**Certainty Factor**: A number expressing how confident a system is in a conclusion, used by MYCIN (for example, "organism is E. coli, certainty 0.7"). [3.4.2.3]

**Chart Parsing (CYK, Earley)**: A parsing approach that stores partial results in a table so that no sub-phrase is parsed twice. Worst-case time is cubic in sentence length. [3.6.3]

**Chomsky Hierarchy**: Chomsky's (1956) classification of formal grammars by power: regular, context-free, context-sensitive, and unrestricted. [3.6.3]

**Classical Planning**: Planning under the assumptions that the world is deterministic, fully observable, static, discrete, and has a single agent. [3.5.8]

**Closed List**: See *Explored Set*.

**Closed-World Assumption**: In STRIPS, anything not listed as true is assumed false. [3.5.8]

**Combinatorial Explosion**: The rapid growth in the number of states to examine (about b^d) as depth grows, making large searches intractable. [3.5.3]

**Commonsense Knowledge**: Obvious everyday knowledge that humans have but that is hard to write down as rules (the Cyc project tried for decades). [3.3.5, 3.6.12]

**Completeness**: A search property: if a solution exists, the algorithm is guaranteed to find it. [3.5.3]

**Compositional Semantics**: Building the meaning of a sentence from the meanings of its parts, following the parse structure. [3.6.4]

**Conflict Resolution**: How an inference engine chooses among several rules that can fire at once, by priority, specificity, or recency. [3.4.1.4]

**Consequent**: The "then" part (conclusion q) of an implication p → q. [3.2.2.4]

**Consistent Heuristic**: A heuristic where h(n) ≤ c + h(n') for every step from n to n' with cost c. Consistency implies admissibility. [3.5.5]

**Constraint**: A rule restricting which combinations of variable values are allowed in a CSP. [3.5.9]

**Constraint Propagation**: Removing values that can no longer work (for example forward checking, arc consistency) to detect dead ends early. [3.5.9]

**Constraint Satisfaction Problem (CSP)**: A problem defined by variables, a domain of values for each, and constraints on combinations. Map colouring is the standard example. [3.5.9]

**Context-Free Grammar (CFG)**: A grammar whose rules have a single symbol on the left side. The standard workhorse of syntactic parsing. [3.6.3]

### D

**Dartmouth Conference (1956)**: The meeting that named the field "artificial intelligence." [3.1.2]

**Deep Blue**: The IBM chess system that beat world champion Garry Kasparov in 1997 using deep alpha-beta search, special hardware, and a hand-built evaluation function. [3.5.1, 3.5.6]

**Delete List**: In STRIPS, the facts that become false after an action is applied. [3.5.8]

**De Morgan's Laws**: ¬(p ∧ q) ≡ ¬p ∨ ¬q and ¬(p ∨ q) ≡ ¬p ∧ ¬q. [3.2.2.3]

**DENDRAL**: A 1960s system that worked out organic molecule structures from mass spectrometer data. Often called the first expert system. [3.1.2, 3.4.2.3]

**Dependency Grammar**: A grammar that links each word to its head word. [3.6.3]

**Depth (d)**: The number of steps to the shallowest goal. [3.5.2]

**Depth-First Search (DFS)**: Expands the deepest unexpanded node first, using a stack or recursion. Small memory use but not optimal. [3.5.4]

**Depth-Limited Search**: DFS with a cutoff depth l, which avoids endless descent. [3.5.4]

**Discourse and Pragmatics**: The level of language analysis concerned with context and intent (for example, "Can you pass the salt?" is a request). [3.6.1, 3.6.2]

**Domination (of heuristics)**: Heuristic h2 dominates h1 if h2(n) ≥ h1(n) for all n while staying admissible, so h2 expands fewer nodes. [3.5.5]

**Double Negation**: The equivalence ¬(¬p) ≡ p. [3.2.2.3]

### E

**ELIZA**: A 1966 chatbot by Weizenbaum that used keyword spotting and decomposition and reassembly rules to imitate a psychotherapist. [3.1.2, 3.6.11]

**Evaluation Function**: A heuristic score for a game position, used when the search stops at a depth limit (for chess, material count and piece positions). [3.5.6]

**Existential Generalization (EG)**: From P(c) ∧ Q(c) for a specific c, conclude ∃x(P(x) ∧ Q(x)). Always safe. [3.2.3.6]

**Existential Instantiation (EI)**: From ∃x(P(x) ∧ Q(x)), name a specific element c that satisfies it. The name c must be new. [3.2.3.5]

**Existential Quantifier (∃)**: "There exists": true for at least one element in the domain. [3.2.3.2]

**Expanding a Node**: Generating all of a node's children. [3.5.2]

**Expert System**: An AI system that emulates the decision-making of a human expert in one specific domain. [3.4.2]

**Explainability**: The ability to trace and show how a system reached a conclusion. A key strength of symbolic AI. [3.1.1.3]

**Explored Set (Closed List)**: States already expanded, kept so that the search does not loop. [3.5.2]

### F

**Forward Chaining**: Data-driven reasoning that starts from known facts and moves toward conclusions. Like a detective collecting clues. [3.1.3, 3.4.1.4]

**Forward (Progression) Search**: A planning strategy that starts at the initial state and applies applicable actions toward the goal. [3.5.8]

**Frame**: A data structure for a stereotypical object or situation, with slots (properties), values, and default values. [3.3.2.3]

**Frame Problem**: The difficulty of stating everything that does *not* change when an action occurs. [3.5.8]

**Frontier (Open List)**: Nodes that have been generated but not yet expanded. [3.5.2]

### G

**Gazetteer**: A list of known names, places, or organizations used alongside patterns in information extraction. [3.6.6]

**General Problem Solver (GPS)**: A 1957 program that attempted general-purpose problem solving and introduced means-ends analysis. [3.1.2, 3.5.1]

**Global Maximum**: The best state anywhere in the state-space landscape. [3.5.7]

**Goal State**: The desired state a plan or search tries to reach. [3.5.1]

**Goal Test**: How to recognize that a state is a goal. [3.5.2]

**GOFAI (Good Old-Fashioned AI)**: Another name for symbolic AI. [3.1.1.1]

**Greedy Best-First Search**: Orders the frontier by f(n) = h(n) only. Fast but neither optimal nor complete. [3.5.5]

### H

**Hearst Patterns**: Text patterns that reveal is-a relations in information extraction, such as "animals such as cats" implying that a cat is an animal. [3.6.6]

**Heuristic**: A rule of thumb or domain knowledge used to guide search. It is not a guarantee. [3.5.3, 3.5.5]

**Heuristic Function h(n)**: An estimate of the cost of the cheapest path from node n to a goal. [3.5.5]

**Hierarchical Task Network (HTN)**: A planning approach that breaks high-level tasks into subtasks using expert-written methods. [3.5.8]

**Hill Climbing**: A local search that always moves to a better neighbor and stops when none is better. It can get stuck at local maxima, ridges, and plateaus. [3.5.7]

**Hybrid Approach**: Combining rule-based methods with statistical or neural models, for example a neural model that proposes entities and hand-written rules that validate them. [3.1.2, 3.6.12]

**Hypernym / Hyponym**: In WordNet, a more general word (*mammal* for *cat*) and a more specific word (*cat* for *mammal*). [3.6.4]

### I

**Implication (p → q)**: "If p, then q." False only when p is true and q is false. [3.2.2.4]

**Inference Engine**: The reasoning program that applies rules to facts to derive conclusions. [3.1.3, 3.4.1.1]

**Inference Rule**: A pattern that lets us derive new conclusions from known statements (for example Modus Ponens). [3.2.2.5]

**Information Extraction (IE)**: Identifying specific entities and relationships in unstructured text using predefined patterns. [3.6.6]

**Information Retrieval (IR)**: Finding relevant documents in large collections. [3.6.10]

**Informed (Heuristic) Search**: Search that uses domain-specific knowledge to expand the most promising nodes first. [3.5.5]

**Initial State**: Where the agent starts. [3.5.2]

**Iterative Deepening Search**: Runs depth-limited search with l = 0, 1, 2, ... until a goal is found. Combines BFS's completeness with DFS's small memory. [3.5.4]

### K

**Knowledge Acquisition Bottleneck**: The slow, expensive process of extracting knowledge from experts and writing it down as rules. [3.1.4, 3.3.5]

**Knowledge Base**: The stored facts and rules of a symbolic system. [3.1.3]

**Knowledge Engineer**: The person who builds the knowledge base from an expert's expertise. [3.4.2.2]

**Knowledge Graph**: Entities and labeled relations, used for question answering and retrieval. A modern descendant of ontologies and semantic networks. [3.3.2.5, 3.6.5]

**Knowledge Representation**: How an AI system stores knowledge in a form it can reason with. [3.3.1]

### L

**Lexicon**: A dictionary of words with part of speech, forms, and features. [3.6.5]

**LISP**: The main AI programming language for decades, created by John McCarthy in 1958. [3.1.2]

**Local Maximum**: A state better than all its neighbors but not the best overall. [3.5.7]

**Local Search**: Search that keeps a single current solution and moves to neighboring ones. Used when only the final state matters. [3.5.7]

**Logical Equivalence (≡)**: Two statements that have the same truth value in every situation. [3.2.2.3]

**Logical Form**: A formal representation of a sentence's meaning, such as `Chased(cat1, mouse1)`. [3.6.4]

**Logic-Based Representation**: Knowledge written as propositional logic or first-order logic. [3.3.2.1]

**Logic Theorist**: A 1956 program (Newell, Simon, Shaw) that proved mathematical theorems using heuristic search. [3.1.2]

### M

**MAX / MIN**: The two players in minimax. MAX tries to maximize the score and MIN tries to minimize it. [3.5.6]

**Means-Ends Analysis**: A planning method that compares the current state with the goal, picks an action that reduces the difference, and makes its preconditions new subgoals. [3.5.8]

**Minimax**: An adversarial search that passes values up a game tree, with MAX taking the largest child value and MIN the smallest. It assumes the opponent plays its best move. [3.5.6]

**Modus Ponens**: From p → q and p, conclude q. [3.2.2.5]

**Modus Tollens**: From p → q and ¬q, conclude ¬p. [3.2.2.5]

**Morphological Analysis**: Finding word structure and base forms (chased = chase + past tense). [3.6.1]

**MYCIN**: A 1970s expert system that diagnosed bacterial blood infections using roughly 600 rules and certainty factors. [3.1.2, 3.4.2.3]

### N

**Natural Language Processing (NLP)**: The field concerned with computers understanding, interpreting, and generating human language. [3.6.1]

**Negation (in sentiment rules)**: A rule that flips polarity, as in "not good." [3.6.8]

**Neuro-Symbolic AI**: Approaches that combine symbolic reasoning with neural networks. [3.1.2, 3.6.12]

**Node**: A state plus bookkeeping such as parent node, action taken, and path cost so far. [3.5.2]

### O

**Ontology**: A formal representation of the concepts in a domain and their relationships, giving a shared vocabulary. [3.3.2.5]

**Open List**: See *Frontier*.

**Optimality**: A search property: the algorithm finds the lowest-cost solution. [3.5.3]

**Optimal Solution**: The solution path with the lowest path cost. [3.5.2]

### P

**Parse Tree**: A tree showing the hierarchical structure of a sentence according to a grammar. [3.6.3]

**Parsing**: Finding a parse tree for a sentence according to a grammar. Can be top-down, bottom-up, or chart-based. [3.6.3]

**Partial-Order Planning**: A planning method that orders actions only where necessary ("least commitment"). [3.5.8]

**Part-of-Speech (POS) Tagging**: Assigning each word a grammatical category such as noun or verb. [3.6.6]

**Path Cost**: A number measuring how good a path is, such as total distance. [3.5.2]

**Patient (Semantic Role)**: The participant acted upon. In "The cat chased the mouse," the patient is *mouse*. [3.6.4]

**PDDL (Planning Domain Definition Language)**: The standard language for describing planning problems, used in the International Planning Competition. [3.5.8]

**Plan**: A sequence of actions that transforms an initial state into a goal state. [3.5.1]

**Planning**: Finding a sequence of actions that reaches a goal state from an initial state. [3.5.1]

**Planning Graph (GraphPlan)**: A compact layered structure of what could be true at each step, from which a plan is extracted. [3.5.8]

**Plateau**: A flat area in the state-space landscape with no direction to move. [3.5.7]

**Precondition**: A fact that must hold for an action to be applicable. [3.5.8]

**Predicate**: A statement with variables that is true or false depending on their values, such as Even(x). [3.2.3.2]

**Predicate Logic (First-Order Logic)**: Logic that adds predicates, variables, and quantifiers to propositional logic. [3.2.3]

**Production Rule**: An IF-THEN rule with a condition and an action. [3.3.2.4, 3.4.1]

**Prolog**: A logic programming language that appeared in 1972. [3.1.2, 3.3.2.1]

**Proposition**: A declarative sentence that is either true or false, but not both. [3.2.2.1]

**Propositional Logic**: Logic about whole statements combined with Boolean operators. [3.2.2]

### Q

**Qualification Problem**: The difficulty of listing every condition that must hold for an action to work. [3.5.8]

**Quantifier**: A symbol (∀ or ∃) stating how many elements a predicate applies to. [3.2.3.2]

**Question Answering (QA)**: Systems that interpret a natural-language question and infer the answer, often from formal knowledge. [3.6.9]

### R

**Ramification Problem**: The difficulty of capturing the indirect effects of actions. [3.5.8]

**Relaxed Problem**: A simpler version of a problem with some rules removed. Its exact solution cost makes a good admissible heuristic. [3.5.5]

**Ridge**: A narrow slope that rises sideways, which single steps cannot climb. [3.5.7]

**Rule-Based System (Production System)**: A system that operates on a set of IF-THEN rules. [3.4.1]

### S

**Script**: A sequence of frames describing a typical chain of events, such as going to a restaurant. [3.3.2.3]

**Search**: Exploring a state space to find a path from the initial state to a goal state. [3.5.2]

**Semantic Network**: A graph where nodes are concepts and links are relationships. [3.3.2.2]

**Semantic Role**: The part a participant plays in an event, such as agent or patient. [3.6.4]

**Semantics**: The meaning conveyed by words, phrases, and sentences in context. [3.6.4]

**Sentiment Analysis**: Determining the emotional tone (positive, negative, neutral) of text. [3.6.8]

**Sentiment Lexicon**: A list of words with polarity scores. [3.6.8]

**SHRDLU**: A 1972 system by Winograd that carried out typed commands in a simulated blocks world. [3.6.11]

**Simulated Annealing**: A local search that sometimes accepts worse moves with probability e^(−Δ/T), lowering the temperature T over time to escape local maxima. [3.5.7]

**State Space**: The set of all states reachable from the initial state by any sequence of actions. [3.5.2]

**State-Space Landscape**: A picture where each state has a height given by an objective function. [3.5.7]

**STRIPS**: A 1971 planner (Fikes and Nilsson) that describes actions by preconditions, a delete list, and an add list. [3.1.2, 3.5.8]

**Sub-Symbolic AI (Connectionist)**: AI that stores knowledge as numerical weights in a network and learns from data, such as neural networks. [3.1.1.3]

**Symbolic AI**: AI in which knowledge is written explicitly as symbols, rules, and logic, and the computer reasons by manipulating them. [3.1.1]

**Synset**: In WordNet, a set of synonyms. [3.6.4]

**Syntax**: The structure of language: how words and phrases form grammatical sentences. [3.6.3]

### T

**Terminal Test**: In a game, the check for whether the game is over. [3.5.6]

**Tokenization**: Splitting text into words and punctuation. [3.6.1]

**Transition Model**: The state that results from applying an action in a state. [3.5.2]

**Transposition Table**: A store of positions already evaluated, since different move orders can reach the same position. [3.5.6]

**Truth Table**: A table listing the truth value of a compound statement for every combination of inputs. [3.2.2.2]

### U

**Uniform-Cost Search (UCS)**: Expands the node with the lowest path cost g(n). It is BFS generalized to steps of different cost. [3.5.4]

**Uninformed (Blind) Search**: Search that uses no knowledge of the goal beyond the problem definition. [3.5.4]

**Universal Generalization (UG)**: From P(a) → Q(a), conclude ∀x(P(x) → Q(x)). Valid only if a is arbitrary. [3.2.3.6]

**Universal Instantiation (UI)**: From a statement about all x, conclude it for a specific element a. Always safe. [3.2.3.5]

**Universal Modus Ponens**: From ∀x(P(x)→Q(x)) and P(a), conclude Q(a). [3.2.3.8]

**Universal Modus Tollens**: From ∀x(P(x)→Q(x)) and ¬Q(a), conclude ¬P(a). [3.2.3.8]

**Universal Quantifier (∀)**: "For all": true for every element in the domain. [3.2.3.2]

**Utility**: The final score of a game outcome (for example +1 win, 0 draw, −1 loss). [3.5.6]

### W

**Well-Defined Problem**: A problem with five parts: initial state, actions, transition model, goal test, and path cost. [3.5.2]

**WordNet**: A symbolic lexical resource that groups words into synsets linked by relations such as hypernym and meronym. [3.6.4]

**Word Sense Disambiguation**: Choosing the correct meaning of a word from context. [3.6.4]

**Working Memory**: Holds the facts about the current case in a rule-based system. [3.4.1.1]

### X

**XCON / R1**: A 1980s expert system that configured computer orders for Digital Equipment Corporation. [3.1.2, 3.4.2.3]

### Z

**Zero-Sum Game**: A game in which one player's gain is exactly the other's loss. [3.5.6]
