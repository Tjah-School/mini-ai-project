# Cangcut Test Bank

# Part 1: Software

## 1.1 What is Software?

### True / False

**1.** Software is a set of intangible instructions, rules and data that tell hardware what to do.
**Answer:** True.

**2.** Software is a tangible component that you can touch, such as a chip or a circuit board.
**Answer:** False (software is intangible).

**3.** A device driver is an example of system software.
**Answer:** True.

**4.** Minecraft is system software because it uses a lot of graphics hardware.
**Answer:** False (a game serves a user's entertainment, so it is application software).

**5.** Application software depends on system software in order to run.
**Answer:** True.

### Multiple Choice

**1.** Which of these is system software?

- (a) Google Chrome
- (b) Spotify
- (c) an NVIDIA GPU driver
- (d) Microsoft Word

**Answer:** b.

**2.** Which statement best separates system from application software?

- (a) system software is free, application software is paid
- (b) system software manages hardware and resources, application software performs specific user tasks
- (c) application software runs in the background, system software is opened by the user
- (d) system software is only for servers

**Answer:** c.

**3.** Which pair is classified correctly?

- (a) Android: application, Firefox: system
- (b) macOS: system, Minecraft: application
- (c) Linux: application, Spotify: system
- (d) iOS: application, Word: system

**Answer:** b.

### Open-ended

**1.** Explain, with at least five named products, why hardware is not useful without software, and justify how you would classify each product as system or application software.
**Answer:** hardware = silent instruments; software supplies the instructions; five products correctly classified with the *who does it serve?* reasoning.

---

## 1.2 Operating Systems

### True / False

**1.** A process is a program in execution.
**Answer:** True.

**2.** In round-robin scheduling, each process runs for a fixed time slice before the CPU moves on to the next process.
**Answer:** True.

**3.** A page fault happens when the CPU executes an illegal instruction.
**Answer:** False (a page that is not in RAM was referenced).

**4.** In a batch system the user interacts directly with the job while it runs.
**Answer:** False (batch jobs run without interaction).

**5.** The OS must stop one process from overwriting another process's memory.
**Answer:** True.

### Multiple Choice

**1.** A process waiting for a disk read to finish is in which state?

- (a) running
- (b) ready
- (c) waiting / blocked
- (d) terminated

**Answer:** c.

**2.** With the round-robin example above (bursts 5, 3 and 2 ms, quantum 2 ms), which process finishes first?

- (a) P1
- (b) P2
- (c) P3
- (d) all at once

**Answer:** c.

**3.** Which technique keeps only the needed parts of a program in RAM and the rest on disk?

- (a) compilation
- (b) virtual memory
- (c) normalisation
- (d) recursion

**Answer:** b.

**4.** Which development let many users share one computer interactively by switching the CPU rapidly?

- (a) batch processing
- (b) time-sharing
- (c) cloud computing
- (d) version control

**Answer:** b.

**5.** Which statement about UNIX is correct?

- (a) single-user only
- (b) multi-user, multitasking, and influential on later systems
- (c) an application program
- (d) a compiler

**Answer:** b.

### Open-ended

**1.** Three apps (Weixin, a browser and a music player) run at the same time on one laptop. Explain how the OS uses processes, scheduling and memory management to make this work, and what would go wrong without memory protection.
**Answer:** one process per app; scheduler switches the CPU; each gets its own memory region; without protection one app's bug could corrupt another or the OS.

---

## 1.3 How Code Runs: Compiled vs Interpreted

### True / False

**1.** A CPU can directly execute Python source text without any translation.
**Answer:** False.

**2.** A compiler translates the whole source file into machine code before the program runs.
**Answer:** True.

**3.** An interpreted language must be fully compiled before its first line can run.
**Answer:** False (interpreters translate as they go).

**4.** Syntax errors can be detected during the translation step.
**Answer:** True.

**5.** In ASCII, the capital letter H is stored as the bit pattern 01001000.
**Answer:** True.

### Multiple Choice

**1.** Why must high-level code be translated?

- (a) it is written in a foreign language
- (b) CPUs process only binary electrical signals
- (c) it is too short
- (d) CPUs only understand graphical interfaces

**Answer:** b.

**2.** Which pair of languages is typically compiled?

- (a) Python and JavaScript
- (b) C++ and Rust
- (c) HTML and CSS
- (d) SQL and Excel formulas

**Answer:** b.

**3.** The main trade-off of interpreted languages is:

- (a) easier to test instantly, but usually slower raw execution
- (b) no syntax errors
- (c) larger binaries
- (d) cannot use variables

**Answer:** a.

**4.** The first stage of a typical compiler, which splits text into tokens, is:

- (a) code generation
- (b) lexical analysis
- (c) linking
- (d) debugging

**Answer:** b.

**5.** Java is best described as:

- (a) purely interpreted line by line
- (b) compiled to bytecode that runs on a virtual machine
- (c) assembled directly into one CPU's binary only
- (d) never translated

**Answer:** b.

### Open-ended

**1.** Compare compiled and interpreted languages (mechanism, speed, development workflow, example languages). Then trace how `print("Hello")` becomes something the CPU executes, and explain where a hybrid approach fits.
**Answer:** compile whole vs translate stepwise; build step vs instant edit; hybrids use bytecode plus a VM or JIT.

---

## 1.4 Programming Language and Program Logic

### True / False

**1.** Sequence, selection and iteration are sufficient to express any computable function.
**Answer:** True.

**2.** A 32-bit signed integer can store a maximum value of 2,147,483,647.
**Answer:** True.

**3.** In object-oriented programming, inheritance lets a class reuse the attributes and methods of another class.
**Answer:** True.

**4.** A while loop always runs its body once before testing its condition.
**Answer:** False (it tests first; a do-while runs once first).

**5.** Prolog is a typical imperative language.
**Answer:** False (Prolog is logic/declarative).

### Multiple Choice

**1.** Which paradigm groups data and the functions that use it into objects?

- (a) object-oriented
- (b) logic
- (c) assembly
- (d) functional only

**Answer:** a.

**2.** In a 32-bit signed integer holding 2,147,483,647, adding 1 typically causes:

- (a) a faster loop
- (b) overflow
- (c) a syntax error at compile time only
- (d) automatic conversion to text

**Answer:** b.

**3.** `IF room_temp > target THEN cool ELSE stop` is an example of:

- (a) iteration
- (b) selection
- (c) recursion
- (d) compilation

**Answer:** b.

**4.** Which language generation uses mnemonics such as MOV and ADD?

- (a) machine language
- (b) assembly language
- (c) 4GL
- (d) markup

**Answer:** b.

**5.** Which of these is declarative?

- (a) C
- (b) SQL
- (c) Java
- (d) assembly

**Answer:** b.

### Open-ended

**1.** Explain how if/else and loops can express a smart-thermostat controller, then discuss why an integer limit could break a game that tracks money, and how you would prevent it.
**Answer:** thermostat pseudocode with IF and WHILE; overflow beyond 2,147,483,647; prevent with limits, wider types (64-bit), checks.

---

## 1.5 Software Engineering

### True / False

**1.** In the SDLC, the Release step includes providing ongoing updates after deployment.
**Answer:** True.

**2.** The waterfall model is built around frequent short iterations with continuous customer feedback.
**Answer:** False (that describes agile).

**3.** The Agile Manifesto values working software over comprehensive documentation.
**Answer:** True.

**4.** Git is a purely centralised system that cannot work without a constant server connection.
**Answer:** False (Git is distributed).

**5.** Unit testing checks whether the fully integrated system meets the customer's acceptance criteria.
**Answer:** False (that is acceptance testing; unit tests check single functions).

### Multiple Choice

**1.** Who developed Git for Linux kernel development?

- (a) Dennis Ritchie
- (b) Linus Torvalds
- (c) Ken Carson
- (d) Erling Haaland

**Answer:** b.

**2.** A good module design has:

- (a) low cohesion, high coupling
- (b) high cohesion, low coupling
- (c) high cohesion, high coupling
- (d) low cohesion, low coupling

**Answer:** b.

**3.** Which model puts risk analysis in each loop?

- (a) waterfall
- (b) spiral
- (c) big bang
- (d) prototype-only

**Answer:** b.

**4.** Which step comes second in the five-step SDLC pipeline?

- (a) Test
- (b) Code
- (c) Design
- (d) Release

**Answer:** c.

**5.** A Git branch is mainly used to:

- (a) delete history
- (b) develop changes in isolation before merging
- (c) compile code
- (d) encrypt files

**Answer:** b.

### Open-ended

**1.** Compare waterfall and agile, then choose a model for a team building a new messaging app. Justify your choice using modularity, testing levels and version control.
**Answer:** waterfall = fixed requirements and heavy documentation; agile = changing requirements and fast feedback; modules enable parallel work; unit/integration/acceptance tests; branches and reviews.

---

## 1.6 Cloud Software and Software as a Service

### True / False

**1.** In SaaS, the application runs on the provider's cloud infrastructure and is accessed through a browser or program interface.
**Answer:** True.

**2.** NIST lists seven essential characteristics of cloud computing.
**Answer:** False (five).

**3.** In SaaS the customer normally manages the underlying servers and operating system.
**Answer:** False (the provider manages them).

**4.** Automatic updates are a commonly cited benefit of SaaS.
**Answer:** True.

**5.** Cloud services keep working at full function with no internet connection.
**Answer:** False.

### Multiple Choice

**1.** Which is an example of SaaS?

- (a) Google Docs
- (b) a local C++ compiler
- (c) a USB driver
- (d) a BIOS chip

**Answer:** a.

**2.** Which NIST characteristic means provider resources serve many consumers from a shared pool?

- (a) measured service
- (b) resource pooling
- (c) broad network access
- (d) rapid elasticity

**Answer:** b.

**3.** In PaaS, the consumer:

- (a) only uses a finished app
- (b) deploys their own applications onto the provider's platform
- (c) owns the data centre
- (d) writes the OS kernel

**Answer:** b.

**4.** Which NIST deployment model combines two or more distinct cloud infrastructures?

- (a) private
- (b) public
- (c) hybrid
- (d) offline

**Answer:** c.

**5.** Which is a genuine drawback of SaaS?

- (a) cannot be updated
- (b) depends on connectivity and the vendor
- (c) cannot be shared
- (d) cannot sync data

**Answer:** b.

### Open-ended

**1.** Compare installing Word from a disk with using Google Docs. Use NIST's terms to describe the cloud model, and discuss two benefits and two risks for a university department.
**Answer:** SaaS vs local install; five characteristics and service models; benefits (updates, sync, access) vs risks (outage, lock-in, privacy).

---

## 1.7 Open Source vs Proprietary Software

### True / False

**1.** Open source always means that nobody may charge money for the software.
**Answer:** False (the OSD requires free redistribution but does not forbid sales; "free" is about freedom).

**2.** Proprietary software users typically receive compiled binaries under a licence agreement.
**Answer:** True.

**3.** Making the source code viewable is by itself enough for software to qualify as open source.
**Answer:** False (ten criteria must be met).

**4.** The GPL is a copyleft licence: derivative works must remain under the same terms.
**Answer:** True.

**5.** Freeware is the same thing as open-source software.
**Answer:** False.

### Multiple Choice

**1.** Which is an open-source example?

- (a) Microsoft Windows
- (b) Adobe Photoshop
- (c) Linux
- (d) none of these

**Answer:** c.

**2.** The Open Source Definition is maintained by:

- (a) the Open Source Initiative
- (b) NIST
- (c) ISO only
- (d) Microsoft

**Answer:** a.

**3.** A permissive licence such as MIT:

- (a) forbids use in commercial products
- (b) allows reuse, including in closed products
- (c) requires paying the author
- (d) bans modification

**Answer:** b.

**4.** Which is a typical advantage of proprietary software?

- (a) public code review by anyone
- (b) vendor-provided support and accountability
- (c) guaranteed zero cost
- (d) freedom to fork

**Answer:** b.

**5.** Which statement is correct?

- (a) free software and freeware always mean the same
- (b) open source is defined by criteria such as free redistribution and access to source
- (c) proprietary code is always insecure
- (d) open source cannot be used commercially

**Answer:** b.

### Open-ended

**1.** A hospital must choose between an open-source and a proprietary patient-record system. Compare them on cost, transparency, support, security review and lock-in, and make a reasoned recommendation.
**Answer:** balanced comparison; recommendation tied to support needs, skills and regulations; no single correct answer.

---

## 1.8 Databases and SQL

### True / False

**1.** In the relational model, data is stored in tables of rows and columns.
**Answer:** True.

**2.** A primary key value may be repeated in two different rows of the same table.
**Answer:** False (primary keys are unique).

**3.** SQL is declarative: the user states what data is wanted rather than how to retrieve it.
**Answer:** True.

**4.** In the hierarchical model, a child record may have many parents.
**Answer:** False (hierarchical = one parent).

**5.** The WHERE clause filters which rows a query returns.
**Answer:** True.

### Multiple Choice

**1.** Which statement retrieves data?

- (a) INSERT
- (b) SELECT
- (c) DROP
- (d) GRANT

**Answer:** b.

**2.** A foreign key:

- (a) uniquely identifies its own row
- (b) refers to a primary key in another table
- (c) encrypts a column
- (d) sorts a table

**Answer:** b.

**3.** Which query lists names of students older than 20?

- (a) `SELECT age FROM Student WHERE name > 20;`
- (b) `SELECT name FROM Student WHERE age > 20;`
- (c) `UPDATE name FROM Student;`
- (d) `DELETE name WHERE age > 20;`

**Answer:** b.

**4.** `GROUP BY course` together with `COUNT(*)` is used to:

- (a) delete courses
- (b) count rows per course
- (c) rename a table
- (d) create an index only

**Answer:** b.

**5.** A transaction that fails half-way should leave the database:

- (a) with half the changes
- (b) as if it never ran
- (c) locked for ever
- (d) deleted

**Answer:** b (atomicity).

### Open-ended

**1.** Design a relational schema for a library (books, members, loans). Name the primary and foreign keys, write one JOIN query, and explain why normalisation helps.
**Answer:** tables Book, Member, Loan(book_id, member_id, date); keys identified; JOIN written; normalisation avoids repeating member details on every loan row.

---

# Part 2: Algorithm and Data Structure

## 2.1 Algorithms: Definition, Properties and Representation

### True / False

**1.** An algorithm and a program are the same thing, because an algorithm is always written in a particular programming language.
**Answer:** False (an algorithm is the language-independent idea; a program is one implementation of it).

**2.** An algorithm must stop after a finite number of steps, so a procedure built around `while true: ...` with no way out violates this property.
**Answer:** True.

**3.** The recipe step "add a bit more salt and stir until it feels done" satisfies the definiteness property.
**Answer:** False ("a bit more" and "feels done" are not precise).

**4.** If an algorithm gives the right answer on every test case you tried, this proves that it is correct for every valid input.
**Answer:** False (tests can show errors, not prove correctness for all inputs).

**5.** In a flowchart, a decision is drawn as a diamond with two exits (yes and no).
**Answer:** True.

### Multiple Choice

**1.** A procedure for computing 7! is written as: "while true: multiply the result by the next integer." Which algorithm property does it violate most clearly? (Select ONE)

- A. Input
- B. Finiteness
- C. Generality
- D. Definiteness

**Answer:** B. Finiteness.

**2.** Trace the following pseudocode for a = 48 and b = 18. What does it return? (Select ONE)

```text
while b ≠ 0:
    r ← a mod b
    a ← b
    b ← r
return a
```

- A. 6
- B. 12
- C. 18
- D. 36

**Answer:** A. 6 (48 mod 18 = 12; 18 mod 12 = 6; 12 mod 6 = 0; return 6).

**3.** Which form of representation is precise, independent of any programming language, has no standard syntax, and cannot be run directly by a computer? (Select ONE)

- A. Natural language
- B. Flowchart
- C. Pseudocode
- D. A Python program

**Answer:** C. Pseudocode.

**4.** Which flowchart symbol is used to read data or show a result? (Select ONE)

- A. Oval (terminator)
- B. Rectangle (process)
- C. Parallelogram (input/output)
- D. Diamond (decision)

**Answer:** C. Parallelogram (input/output).

**5.** Which of the following are properties that a procedure must have to count as an algorithm? (Select ALL that apply)

- A. Finiteness
- B. Definiteness
- C. It finishes in under one second
- D. Effectiveness
- E. It is written in Python

**Answer:** A, B, D.

### Open-ended

**1.** Explain the difference between an algorithm, a program and a data structure, using "find the largest number in a list" as the example.
**Answer:** algorithm = the idea or method (keep the biggest number seen so far); program = the algorithm written in a programming language so a computer can run it (the Python function `find_max`); data structure = how the data is organised in memory (the list of numbers stored in an array); one algorithm can be written as many programs.

---

## 2.2 Efficiency (Big-O) and Searching

### True / False

**1.** Big-O notation keeps only the fastest-growing term and ignores constant factors, so 3n² + 5n + 20 is O(n²).
**Answer:** True.

**2.** Binary search works correctly on any list, whether it is sorted or not.
**Answer:** False (the list must be sorted).

**3.** In the worst case, linear search for a target among n items needs n comparisons.
**Answer:** True.

**4.** An O(n²) algorithm is always slower than an O(n) algorithm, even for very small inputs.
**Answer:** False (for small n, constants can make the O(n²) one faster).

**5.** Binary search needs at most about 20 comparisons to search 1,000,000 sorted items.
**Answer:** True (log₂ 1,000,000 ≈ 20).

### Multiple Choice

**1.** The FindMax algorithm makes one comparison per item after the first and stores only a few variables. Which statement gives its time and extra space correctly? (Select ONE)

- A. O(n) time, O(1) extra space
- B. O(n²) time, O(n) extra space
- C. O(log n) time, O(1) extra space
- D. O(n) time, O(n) extra space

**Answer:** A.

**2.** Binary search (with `mid = (low + high) // 2`) looks for 23 in `[2, 5, 8, 12, 16, 23, 38, 56, 72, 91]` (indexes 0 to 9). How many times does it compare `items[mid]` with the target before finding it? (Select ONE)

- A. 1
- B. 2
- C. 3
- D. 8

**Answer:** C. 3 (mid = 4 gives 16 < 23, so low = 5; mid = 7 gives 56 > 23, so high = 6; mid = 5 gives 23, found).

**3.** You must search an unsorted list of 1,000 items exactly once. Which approach is cheapest? (Select ONE)

- A. Sort with merge sort, then use binary search
- B. Use linear search directly
- C. Sort with bubble sort, then use binary search
- D. Use binary search directly on the unsorted list

**Answer:** B.

**4.** At 10⁹ operations per second and n = 1,000,000, roughly how long do an O(n log n) algorithm and an O(n²) algorithm take? (Select ONE)

- A. About 0.02 seconds and about 17 minutes
- B. About 17 minutes and about 0.02 seconds
- C. About 1 second for both
- D. About 20 seconds and about 1,000 seconds

**Answer:** A (2 × 10⁷ operations ≈ 0.02 s; 10¹² operations = 1,000 s ≈ 17 min).

**5.** Which statements about binary search are correct? (Select ALL that apply)

- A. It requires the data to be sorted
- B. Its worst-case time is O(log n)
- C. It works equally well on a linked list, because it only needs the next pointer
- D. Using `mid = low + (high - low) // 2` avoids integer overflow in fixed-width languages
- E. It is always better than linear search for a single lookup in unsorted data

**Answer:** A, B, D.

### Open-ended

**1.** Compare linear search and binary search: what data each one needs, how it works, and its worst-case cost.
**Answer:** linear search checks each item in order, works on any list, O(n); binary search needs a sorted array, compares the target with the middle item and discards half each step, O(log n); for 1,000,000 items: up to 1,000,000 comparisons vs 20; for one search in unsorted data linear search is cheaper, for many searches sort once and then use binary search.

---

## 2.3 Sorting Algorithms

### True / False

**1.** Merge sort takes O(n log n) time in its best, average and worst cases.
**Answer:** True.

**2.** Quick sort is always O(n log n), whatever pivot is chosen.
**Answer:** False (a bad pivot gives O(n²)).

**3.** Insertion sort runs in about O(n) time on a nearly sorted list.
**Answer:** True.

**4.** Merge sort is an in-place algorithm that needs only O(1) extra memory.
**Answer:** False (it needs O(n) extra memory).

**5.** A stable sort keeps items with equal keys in their original relative order.
**Answer:** True.

### Multiple Choice

**1.** Bubble sort is applied to `[5, 2, 4, 1]`. What is the list after the first full pass? (Select ONE)

- A. `[2, 4, 1, 5]`
- B. `[1, 2, 4, 5]`
- C. `[2, 5, 4, 1]`
- D. `[1, 5, 4, 2]`

**Answer:** A (`[2, 5, 4, 1]` → `[2, 4, 5, 1]` → `[2, 4, 1, 5]`).

**2.** Insertion sort is applied to `[5, 2, 4, 1]`. The sorted prefix grows one item at a time (key = `a[1]` first). What is the list right after the key 4 has been inserted? (Select ONE)

- A. `[2, 5, 4, 1]`
- B. `[2, 4, 5, 1]`
- C. `[1, 2, 4, 5]`
- D. `[4, 2, 5, 1]`

**Answer:** B.

**3.** Why is merge sort O(n log n)? (Select ONE)

- A. It compares every pair of items
- B. The list is halved about log n times, and each level of merging does about n work
- C. It performs n swaps in each of n passes
- D. It builds a heap and extracts the minimum n times

**Answer:** B.

**4.** Writing to memory is very expensive on a device, so you want a simple sort that makes at most n − 1 swaps. Which sort fits best? (Select ONE)

- A. Bubble sort
- B. Selection sort
- C. Insertion sort
- D. Merge sort

**Answer:** B. Selection sort.

**5.** Which of these sorts are stable (as described in the guide)? (Select ALL that apply)

- A. Bubble sort
- B. Selection sort (usual array version)
- C. Insertion sort
- D. Merge sort
- E. Quick sort (usual version)

**Answer:** A, C, D.

### Open-ended

**1.** Explain how merge sort and quick sort work, and give the time cost and one weakness of each.
**Answer:** merge sort splits the list in half, sorts each half, then merges them; O(n log n) in every case and stable, but needs O(n) extra memory; quick sort picks a pivot, puts smaller items before it and larger items after, then sorts each side; O(n log n) on average and fast in practice, but O(n²) in the worst case (bad pivot, e.g. on sorted data) and usually not stable; a random or median-of-three pivot makes the worst case rare.

---

## 2.4 Iteration, Recursion, Design Strategies and Limits

### True / False

**1.** Every correct recursive function needs a base case that can be reached; without it the recursion never ends and the call stack overflows.
**Answer:** True.

**2.** The naive recursive function `fib(n) = fib(n-1) + fib(n-2)` runs in O(n) time.
**Answer:** False (it is exponential, about O(2ⁿ)).

**3.** Memoization speeds up a recursive function by changing its answers to cheaper approximate values.
**Answer:** False (it stores exact answers so they are not recomputed).

**4.** A greedy algorithm always returns an optimal solution; for example, making change for 6 with coins {1, 3, 4} greedily always gives the fewest coins.
**Answer:** False (greedy gives 4 + 1 + 1 = 3 coins; the optimum is 3 + 3 = 2 coins).

**5.** Some problems, such as the halting problem, cannot be solved by any algorithm in general.
**Answer:** True.

### Multiple Choice

**1.** How many calls to `factorial` are made (including the first call and the base-case call) when computing `factorial(4)`? (Select ONE)

```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)
```

- A. 4
- B. 5
- C. 6
- D. 24

**Answer:** B. 5 (n = 4, 3, 2, 1, 0).

**2.** A recursive function in Python never reaches its base case. What is the typical result? (Select ONE)

- A. An infinite loop that keeps returning values
- B. A stack overflow (a `RecursionError` in Python)
- C. The function returns 0
- D. The compiler rejects the program

**Answer:** B.

**3.** Which strategy is described by "solve overlapping subproblems once and store the answers"? (Select ONE)

- A. Brute force
- B. Greedy
- C. Dynamic programming
- D. Backtracking

**Answer:** C. Dynamic programming.

**4.** Which design strategy do both binary search and merge sort use? (Select ONE)

- A. Divide and conquer
- B. Brute force
- C. Greedy
- D. Dynamic programming

**Answer:** A. Divide and conquer.

**5.** Which statements about iteration and recursion are correct? (Select ALL that apply)

- A. Any recursive algorithm can be rewritten with a loop and an explicit stack
- B. Recursion needs extra memory proportional to the depth of the calls
- C. A loop always needs more memory than the equivalent recursion
- D. Recursion is often the clearest way to write tree and divide-and-conquer algorithms
- E. Recursion can never be written as a loop

**Answer:** A, B, D.

### Open-ended

**1.** Name the two parts of a recursive function, using factorial as the example, and give one advantage and one disadvantage of recursion compared with iteration.
**Answer:** base case (`if n == 0: return 1`) stops the recursion; recursive case (`n * factorial(n - 1)`) calls itself on a smaller problem; factorial(4) = 4 × 3 × 2 × 1 = 24; advantage: clearest for self-similar problems (trees, divide and conquer, Towers of Hanoi); disadvantage: every call uses a stack frame, O(depth) extra memory, and a missing base case causes stack overflow.

---

## 2.5 Arrays, Records and Linked Lists

### True / False

**1.** Accessing `a[i]` in an array takes O(1) time because the address is computed as base address + i × element size.
**Answer:** True.

**2.** Inserting an element in the middle of an array is O(1), because no other element has to move.
**Answer:** False (later elements must shift, so it is O(n)).

**3.** A record can group fields of different types under named fields, whereas an array stores elements of the same type accessed by index.
**Answer:** True.

**4.** In a singly linked list with only a head pointer, reaching the k-th node takes O(1) time.
**Answer:** False (you must follow k links, so it is O(k), O(n) in the worst case).

**5.** A Python list is implemented as a linked list of nodes.
**Answer:** False (it is a dynamic array).

### Multiple Choice

**1.** An array of 4-byte integers starts at address 1000. At which address is `a[5]` stored? (Select ONE)

- A. 1005
- B. 1015
- C. 1020
- D. 1024

**Answer:** C. 1020 (1000 + 5 × 4).

**2.** In the list 7 → 12 → 5 → 9, you insert a new node holding 8 after the node holding 12. Which order of steps is safe? (Select ONE)

- A. Set `node12.next = new`, then set `new.next = node5`
- B. Set `new.next = node5`, then set `node12.next = new`
- C. Delete node 5 first, then link the new node
- D. Either order works equally well

**Answer:** B.

**3.** Which structure is the best fit when you make frequent insertions and deletions at known positions and rarely need access by index? (Select ONE)

- A. Array
- B. Linked list
- C. Record
- D. Sorted array with binary search

**Answer:** B. Linked list.

**4.** After `reverse()` runs on the list 1 → 2 → 3, what does the list look like? (Select ONE)

```python
def reverse(self):
    prev, cur = None, self.head
    while cur is not None:
        nxt = cur.next
        cur.next = prev
        prev = cur
        cur = nxt
    self.head = prev
```

- A. 1 → 2 → 3 (unchanged)
- B. 3 → 2 → 1
- C. 2 → 1
- D. 3

**Answer:** B.

**6.** Which statements are correct? (Select ALL that apply)

- A. Arrays scan quickly in order because their items sit side by side in memory
- B. A linked list needs an extra pointer for every node
- C. In a singly linked list with only a head pointer, deleting a given node is O(1)
- D. In a doubly linked list, a known node can be deleted in O(1)
- E. Appending to a dynamic array is O(1) on average (amortized)

**Answer:** A, B, D, E.

### Open-ended

**2.** Compare an array and a linked list on access by position, inserting in the middle and memory use, and say when you would choose each.
**Answer:** access by position: array O(1), linked list O(n); insert in the middle: array O(n) (later items shift), linked list O(1) once the position is found; memory: array compact and contiguous, linked list needs an extra pointer per node and nodes are scattered; choose an array when reading by index dominates, a linked list for frequent insertions and deletions at known positions.

---

## 2.6 Stacks and Queues

### True / False

**2.** A stack removes items in last-in, first-out order, while a queue removes items in first-in, first-out order.
**Answer:** True.

**3.** Popping from an empty stack is called overflow.
**Answer:** False (it is underflow).

**4.** Using a plain Python list with `append` and `pop(0)` is a good O(1) queue, even for very large queues.
**Answer:** False (`pop(0)` is O(n) because every item shifts).

**5.** Breadth-first search uses a queue, while depth-first search uses a stack (or recursion).
**Answer:** True.

**7.** A priority queue always releases items in the order in which they arrived.
**Answer:** False (it releases the highest-priority item first).

### Multiple Choice

**3.** Starting from an empty stack: `push(1)`, `push(2)`, `push(3)`, `pop()`, `peek()`, `pop()`. What does the last `pop()` return? (Select ONE)

- A. 1
- B. 2
- C. 3
- D. The stack is empty (underflow)

**Answer:** B. 2.

**4.** Evaluate the postfix expression `5 3 + 8 2 - *` using a stack (for an operator, pop two values, apply it with the earlier-pushed value on the left, and push the result). (Select ONE)

- A. 16
- B. 40
- C. 48
- D. 64

**Answer:** C. 48 (5 + 3 = 8; 8 − 2 = 6; 8 × 6 = 48).

**5.** The stack-based `balanced()` check is run on `{[(])}`. What happens? (Select ONE)

- A. The text is reported as balanced
- B. A mismatch is found when `]` pops `(`
- C. No mismatch occurs but the stack ends non-empty
- D. Underflow occurs on the very first character

**Answer:** B.

**6.** Starting from an empty queue: `enqueue(A)`, `enqueue(B)`, `enqueue(C)`, `dequeue()`, `enqueue(D)`, `dequeue()`. What does the queue hold (front → rear)? (Select ONE)

- A. B, C, D
- B. C, D
- C. A, D
- D. D

**Answer:** B. C, D.

**8.** Which of these are natural applications of a stack? (Select ALL that apply)

- A. The call stack of function calls
- B. Undo history in an editor
- C. A print spooler serving jobs in arrival order
- D. Backtracking in a maze
- E. CPU scheduling in arrival order

**Answer:** A, B, D.

### Open-ended

**4.** Explain the difference between a stack and a queue, and give two applications of each.
**Answer:** stack = LIFO (last in, first out), push and pop at the top; queue = FIFO (first in, first out), enqueue at the rear, dequeue from the front; stack applications: undo, the call stack, balanced brackets, browser Back button, backtracking; queue applications: print spooler, CPU scheduling, buffers, breadth-first search.

---

## 2.7 Trees, Binary Trees and Binary Search Trees

The tree used in questions 2.7-MC1, 2.7-MC2 and 2.7-MC4 is the binary search tree built by inserting 8, 3, 10, 1, 6, 14, 4, 7, 13:

```text
          8
        /   \
       3     10
      / \      \
     1   6      14
        / \     /
       4   7   13
```

### True / False

**3.** A tree with n nodes has exactly n − 1 edges.
**Answer:** True.

**5.** Every binary tree is automatically a binary search tree.
**Answer:** False (a BST also needs left < node < right ordering).

**6.** An in-order traversal of a binary search tree visits the keys in sorted order.
**Answer:** True.

**7.** Searching a plain binary search tree always takes O(log n) time.
**Answer:** False (a skewed tree needs O(n)).

**9.** In a binary tree, every node must have exactly two children.
**Answer:** False (at most two children).

### Multiple Choice

**5.** In the tree shown above, what is the in-order traversal? (Select ONE)

- A. 8, 3, 1, 6, 4, 7, 10, 14, 13
- B. 1, 3, 4, 6, 7, 8, 10, 13, 14
- C. 1, 4, 7, 6, 3, 13, 14, 10, 8
- D. 8, 3, 10, 1, 6, 14, 4, 7, 13

**Answer:** B.

**6.** For the same tree (root 8), what is the pre-order traversal? (Select ONE)

- A. 8, 3, 1, 6, 4, 7, 10, 14, 13
- B. 1, 3, 4, 6, 7, 8, 10, 13, 14
- C. 1, 4, 7, 6, 3, 13, 14, 10, 8
- D. 8, 3, 10, 1, 6, 14, 4, 7, 13

**Answer:** A.

**7.** Keys 1, 2, 3, 4, 5 are inserted, in this order, into an empty plain BST. What is the result? (Select ONE)

- A. A perfect tree of height 2
- B. A degenerate (skewed) tree of height 4, in which search costs O(n)
- C. A balanced tree of height 3
- D. A tree of height 1

**Answer:** B.

**8.** In the tree shown above, node 3 (with children 1 and 6) is deleted. Which key takes its place, according to the "two children" rule? (Select ONE)

- A. 1
- B. 4
- C. 6
- D. 7

**Answer:** B. 4 (the in-order successor: the smallest key in 3's right subtree).

**10.** A perfect binary tree has height 3 (counting edges, root at height 0). Which statements are correct? (Select ALL that apply)

- A. It has 15 nodes
- B. It has 8 leaves
- C. It has 16 nodes
- D. Every node has 0 or 2 children
- E. Its height is n − 1, where n is the number of nodes

**Answer:** A, B, D (2⁴ − 1 = 15 nodes, 2³ = 8 leaves).

### Open-ended

**6.** Explain the rule that makes a binary tree a binary search tree, and why inserting the keys 1, 2, 3, 4, 5 in that order makes searching slow.
**Answer:** for every node, all keys in the left subtree are smaller and all keys in the right subtree are larger, so search works like binary search; sorted insertion gives a degenerate (skewed) tree where every node has one child, like a linked list (height 4), so search costs O(n) instead of O(log n); AVL or red-black trees keep the tree balanced.

---

## 2.8 Heaps, Graphs and Choosing a Data Structure

### True / False

**4.** In a min-heap, the smallest key is always stored at the root.
**Answer:** True.

**7.** A binary heap stored in an array is a fully sorted array.
**Answer:** False (only each parent is ≤ its children).

**8.** Breadth-first search finds a path with the fewest edges between two vertices of an unweighted graph.
**Answer:** True.

**9.** An adjacency matrix for a graph with V vertices uses O(V + E) space.
**Answer:** False (it uses O(V²); O(V + E) is the adjacency list).

**11.** A tree is a connected graph with no cycles.
**Answer:** True.

### Multiple Choice

**7.** A complete binary tree is stored in an array (indexes from 0). Where are the children of the node at index 3? (Select ONE)

- A. Indexes 6 and 7
- B. Indexes 7 and 8
- C. Indexes 4 and 5
- D. Indexes 3 and 4

**Answer:** B (2 × 3 + 1 = 7 and 2 × 3 + 2 = 8).

**8.** What is printed? (Select ONE)

```python
from collections import deque

graph = {"A": ["B", "C"], "B": ["A", "D"], "C": ["A", "E"],
         "D": ["B"], "E": ["C"]}

def bfs(start):
    visited, order = {start}, []
    queue = deque([start])
    while queue:
        node = queue.popleft()
        order.append(node)
        for nb in graph[node]:
            if nb not in visited:
                visited.add(nb)
                queue.append(nb)
    return order

print(bfs("A"))
```

- A. `['A', 'B', 'D', 'C', 'E']`
- B. `['A', 'B', 'C', 'D', 'E']`
- C. `['A', 'C', 'B', 'E', 'D']`
- D. `['E', 'D', 'C', 'B', 'A']`

**Answer:** B.

**9.** An operating system must repeatedly pick the task with the highest priority from a collection that changes constantly. Which structure is best? (Select ONE)

- A. Heap (priority queue)
- B. Plain array searched linearly each time
- C. Stack
- D. Record

**Answer:** A.

**10.** A road network has 10,000 intersections and about 15,000 roads. Which representation is more suitable, and why? (Select ONE)

- A. Adjacency matrix, because edge lookup is O(1) and the graph is dense
- B. Adjacency list, because the graph is sparse and the list needs only O(V + E) space
- C. Adjacency matrix, because it uses less memory for sparse graphs
- D. Neither; graphs cannot be stored in memory

**Answer:** B.

**12.** Which pairings of need and structure agree with the guide? (Select ALL that apply)

- A. Undo history → stack
- B. Printer jobs served in arrival order → stack
- C. Folder hierarchy → tree
- D. Social-network connections → graph
- E. Ordered data with fast search and insert → balanced binary search tree

**Answer:** A, C, D, E.

### Open-ended

**8.** Choose a data structure for each need and give the reason: (a) undo history, (b) printer jobs in arrival order, (c) always processing the most urgent task next, (d) a folder hierarchy, (e) a social network.
**Answer:** (a) stack, LIFO, the last action is undone first; (b) queue, FIFO, fair arrival order; (c) heap (priority queue), O(1) to read the top priority, O(log n) insert and extract; (d) tree, models hierarchies; (e) graph, models networks and connections.

---

# Part 3: Symbolic AI

## 3.1 Introduction, History and How Symbolic AI Works

### True / False

**5.** Symbolic AI stores knowledge as explicit symbols, rules and logic, and reasons by manipulating those symbols.
**Answer:** True.

**9.** Symbolic AI systems learn their rules automatically from large amounts of training data.
**Answer:** False (rules are written by human experts).

**10.** In a symbolic system, a conclusion can be traced back to the specific rules that produced it, which makes the system highly explainable.
**Answer:** True.

**11.** The 1956 Dartmouth Conference is where the field was named "artificial intelligence".
**Answer:** True.

**13.** Backward chaining starts from known facts and moves toward conclusions.
**Answer:** False (that is forward chaining; backward chaining starts from a goal).

### Multiple Choice

**9.** Which list names the three main parts of a symbolic AI system? (Select ONE)

- A. Knowledge base, inference engine, interface
- B. Training set, neural network, optimizer
- C. Compiler, linker, debugger
- D. Sensor, actuator, battery

**Answer:** A.

**10.** Which is the main reason funding for expert systems collapsed in the late 1980s ("AI winter")? (Select ONE)

- A. They were too easy to explain
- B. They were costly to maintain and brittle outside their narrow domain
- C. They could not use logic
- D. There was no programming language for them

**Answer:** B.

**11.** A system holds the rule `IF fever AND cough AND difficulty breathing THEN possible pneumonia`. The user reports all three symptoms, and the system adds "possible pneumonia". Which reasoning style is this? (Select ONE)

- A. Backward chaining (goal-driven)
- B. Forward chaining (data-driven)
- C. Gradient descent
- D. Random search

**Answer:** B.

**12.** What is the "knowledge acquisition bottleneck"? (Select ONE)

- A. Computers cannot store more than 1,000 rules
- B. Humans must write every rule by hand, which is slow and expensive
- C. Neural networks need too much data
- D. Rules cannot be edited after deployment

**Answer:** B.

**14.** Which are typical limitations of symbolic AI? (Select ALL that apply)

- A. It fails when a needed rule is missing (incomplete knowledge)
- B. Thousands of interacting rules become slow and hard to maintain
- C. It has difficulty with vague input such as "kind of tired"
- D. Its decisions cannot be traced to any rule
- E. It cannot learn new rules on its own

**Answer:** A, B, C, E.

### Open-ended

**10.** Name the three main parts of a symbolic AI system and explain how they work together in the pneumonia example, then give two strengths and two limitations of symbolic AI.
**Answer:** knowledge base stores the facts and rules; inference engine applies rules to facts (the user reports fever, cough and difficulty breathing, the pneumonia rule fires and adds "possible pneumonia"); interface lets users enter facts and receive answers with an explanation; strengths: interpretability, structured knowledge, flexibility (edit rules, no retraining); limitations: incomplete knowledge, scalability, uncertainty ("kind of tired"), no learning (knowledge acquisition bottleneck).

---

## 3.2 Propositional Logic

### True / False

**6.** The sentence "Is it raining?" is a proposition.
**Answer:** False (a question is neither true nor false).

**11.** The statement p ∧ q is true only when both p and q are true.
**Answer:** True.

**12.** The implication p → q is false only when p is true and q is false.
**Answer:** True.

**13.** ¬(p ∧ q) is logically equivalent to ¬p ∧ ¬q.
**Answer:** False (it is equivalent to ¬p ∨ ¬q).

**15.** From "p → q" and "q is false", we may conclude that p is false.
**Answer:** True (modus tollens).

### Multiple Choice

**11.** Both p and q are false. What are the values of p → q and p ↔ q? (Select ONE)

- A. p → q is True and p ↔ q is True
- B. p → q is False and p ↔ q is False
- C. p → q is True and p ↔ q is False
- D. p → q is False and p ↔ q is True

**Answer:** A.

**12.** Which expression is equivalent to ¬(rain ∧ windy) ("it is not both raining and windy")? (Select ONE)

- A. ¬rain ∧ ¬windy
- B. ¬rain ∨ ¬windy
- C. rain ∨ windy
- D. rain ∧ ¬windy

**Answer:** B.

**13.** Premises: "If the alarm is armed, then the door is locked." and "The door is not locked." Which conclusion is valid? (Select ONE)

- A. The alarm is armed
- B. The alarm is not armed
- C. Nothing can be concluded
- D. The door will lock itself

**Answer:** B (modus tollens).

**14.** Which of the following is not a proposition? (Select ONE)

- A. 2 + 2 = 4
- B. The sky is blue
- C. Close the door
- D. It is raining

**Answer:** C.

**16.** Which pairs are logically equivalent? (Select ALL that apply)

- A. ¬(¬p) and p
- B. ¬(p ∨ q) and ¬p ∧ ¬q
- C. p → q and q → p
- D. ¬(p ∧ q) and ¬p ∨ ¬q
- E. p ∧ q and p ∨ q

**Answer:** A, B, D.

### Open-ended

**12.** Explain modus ponens and modus tollens, giving the pattern and an everyday example of each.
**Answer:** modus ponens ("mode that affirms"): p → q and p is true, so q is true ("If it rains, the ground is wet"; it is raining, so the ground is wet); modus tollens ("mode that denies"): p → q and q is false, so p is false (the ground is dry, so it is not raining).

---

## 3.3 Predicate Logic

### True / False

**7.** Predicate logic can express a general statement such as "all cats are mammals", which propositional logic cannot express in a general way.
**Answer:** True.

**13.** The formula ∀x (Cat(x) → Mammal(x)) means "every cat is a mammal".
**Answer:** True.

**14.** In translations, ∃ usually pairs with → and ∀ usually pairs with ∧.
**Answer:** False (∀ pairs with → and ∃ pairs with ∧).

**15.** Showing P(a) for one particular element a does not prove ∀x P(x) unless a is arbitrary.
**Answer:** True.

**17.** In existential instantiation, the name c may be a constant that has already been used for another object.
**Answer:** False (c must be a new name).

### Multiple Choice

**13.** Which formula translates "Some birds can fly"? (Select ONE)

- A. ∃y (Bird(y) ∧ CanFly(y))
- B. ∀y (Bird(y) → CanFly(y))
- C. ∃y (Bird(y) → CanFly(y))
- D. ∀y (Bird(y) ∧ CanFly(y))

**Answer:** A.

**14.** Given ∀x (Human(x) → Mortal(x)) and ¬Mortal(Zeus), what follows? (Select ONE)

- A. Human(Zeus)
- B. ¬Human(Zeus)
- C. Mortal(Zeus)
- D. Nothing follows

**Answer:** B.

**15.** Which pair of rules is always safe, with no extra condition? (Select ONE)

- A. Universal instantiation and universal generalization
- B. Universal instantiation and existential generalization
- C. Existential instantiation and universal generalization
- D. Existential instantiation and existential generalization

**Answer:** B.

**16.** In the domain of integers, which statement is well formed but false? (Select ONE)

- A. ∃x (Even(x) ∧ Prime(x))
- B. ∀n Even(n)
- C. ∃x Even(x)
- D. ∃x (x > 10)

**Answer:** B (for example, 3 is not even).

**18.** Which statements are correct? (Select ALL that apply)

- A. Propositional logic has no quantifiers
- B. Predicate (first-order) logic is more expressive than propositional logic
- C. Predicate logic is simpler and easier to automate than propositional logic
- D. First-order logic is the basis of Prolog
- E. Propositional logic can say "all cats are mammals" in general form

**Answer:** A, B, D.

### Open-ended

**14.** Explain the universal quantifier (∀) and the existential quantifier (∃) with one example each, then translate "Some birds can fly" into predicate logic.
**Answer:** ∀ = true for all elements, e.g. ∀x (Cat(x) → Mammal(x)), every cat is a mammal; ∃ = true for at least one element, e.g. ∃x (Prime(x) ∧ x < 10), some prime number is less than 10; "Some birds can fly" = ∃y (Bird(y) ∧ CanFly(y)); tip: ∀ usually pairs with → and ∃ with ∧.

---

## 3.4 Knowledge Representation

### True / False

**8.** A semantic network is a graph in which nodes are concepts or entities and links are the relationships between them.
**Answer:** True.

**15.** A script is a data structure for one stereotypical object, with slots and default values.
**Answer:** False (that is a frame; a script is a sequence of events).

**16.** An ontology defines the concepts of a domain and their relationships, giving people and programs a shared vocabulary.
**Answer:** True.

**17.** First-order logic is cheap to compute, so it has no practical drawback compared with propositional logic.
**Answer:** False (it is more expensive to compute, and inference can be undecidable).

**19.** Exceptions such as "most birds fly, but penguins do not" are awkward for pure logic to handle.
**Answer:** True.

### Multiple Choice

**15.** A semantic network states: Cat is a Mammal; Mammal is an Animal; Mammal has Vertebra. What can be inferred by following the links? (Select ONE)

- A. A cat is an animal and has a vertebra
- B. A cat is a fish
- C. An animal is a cat
- D. Nothing, because links cannot be followed

**Answer:** A.

**16.** "Going to a restaurant: reservation → ordering → paying the bill" is an example of: (Select ONE)

- A. A script (a sequence of frames)
- B. A propositional formula
- C. A production rule
- D. An ontology of diseases

**Answer:** A.

**17.** Which approach is best for giving a whole organization one consistent vocabulary of "disease", "symptom" and "treatment"? (Select ONE)

- A. Ontology
- B. Propositional logic
- C. Hill climbing
- D. Bubble sort

**Answer:** A.

**18.** Which representation has "the meaning of links can be vague" as its main weakness? (Select ONE)

- A. Propositional logic
- B. Semantic networks
- C. Frames
- D. Ontologies

**Answer:** B.

**20.** Which are qualities of a good knowledge representation? (Select ALL that apply)

- A. Expressive: it captures what matters
- B. Inferable: new facts can be derived
- C. Efficient
- D. Understandable to humans
- E. Readable only by machines

**Answer:** A, B, C, D.

### Open-ended

**16.** Describe three knowledge representation approaches, giving an example and the main weakness of each.
**Answer:** any three, e.g. semantic network = graph of concepts and links (Cat is a Mammal, Mammal is an Animal), weakness: vague link meaning; frame = object with slots and default values ("Car" frame: make, model, year, color), weakness: rigid, struggles with exceptions; ontology = shared vocabulary of domain concepts and relations (medical: disease, symptom, treatment), weakness: costly to build; also first-order logic (computationally heavy) and rules (hard to maintain at scale).

---

## 3.5 Rule-Based Systems and Expert Systems

### True / False

**9.** In a rule-based system, the working memory holds the facts about the current case.
**Answer:** True.

**17.** Forward chaining is goal-driven: it starts from a hypothesis and looks for supporting facts.
**Answer:** False (forward chaining is data-driven; that describes backward chaining).

**18.** Every expert system is rule-based (or uses similar reasoning), but not every rule-based system is an expert system.
**Answer:** True.

**19.** MYCIN was used every day in hospitals as a standard clinical diagnosis tool.
**Answer:** False (it performed well in tests but was never used in routine clinical practice).

**21.** When several rules can fire at the same time, the engine chooses using criteria such as priority, specificity or recency.
**Answer:** True.

### Multiple Choice

**17.** Rule 1: IF engine won't start AND lights are dim THEN battery is weak. Rule 2: IF battery is weak THEN recommend charging or replacing it. Facts: engine won't start, lights are dim. What does forward chaining do? (Select ONE)

- A. Rule 2 fires first, then Rule 1
- B. Rule 1 fires and adds "battery weak"; then Rule 2 fires and gives the recommendation
- C. Neither rule fires
- D. Only Rule 1 fires and the system stops

**Answer:** B.

**18.** A doctor suspects flu, then checks the patient's symptoms one by one to see whether they support that hypothesis. Which reasoning style is this? (Select ONE)

- A. Forward chaining
- B. Backward chaining
- C. Random restart
- D. Minimax

**Answer:** B.

**19.** Which system worked out organic molecule structures from mass spectrometer data and is often called the first expert system? (Select ONE)

- A. DENDRAL
- B. XCON
- C. ELIZA
- D. SHRDLU

**Answer:** A.

**20.** Who turns a human expert's knowledge into the knowledge base of an expert system? (Select ONE)

- A. The end user
- B. The knowledge engineer
- C. The compiler
- D. The working memory

**Answer:** B.

**22.** Which are weaknesses of rule-based and expert systems? (Select ALL that apply)

- A. Brittle: they fail outside their narrow domain
- B. They cannot learn on their own
- C. Large rule sets are hard to maintain
- D. Their decisions are not explainable
- E. Building the knowledge base is expensive

**Answer:** A, B, C, E.

### Open-ended

**18.** Explain forward chaining and backward chaining using the car diagnosis example, and state how a rule-based system differs from an expert system.
**Answer:** forward chaining (data-driven): the facts "engine won't start" and "lights are dim" fire Rule 1 (battery is weak), which then fires Rule 2 (recommend charging or replacing it); backward chaining (goal-driven): start from the hypothesis "is the battery weak?" and check whether the facts support it; an expert system emulates a human expert in one specialised domain and adds knowledge engineering, a user interface and explanations; every expert system is rule-based, but not every rule-based system is an expert system (a thermostat vs MYCIN).

---

## 3.6 Problem Formulation and Uninformed Search

### True / False

**10.** A well-defined search problem has an initial state, actions, a transition model, a goal test and a path cost.
**Answer:** True.

**19.** With branching factor 10, going two levels deeper multiplies the number of nodes to examine by about 100.
**Answer:** True (10 × 10 = 100).

**20.** Depth-first search is guaranteed to find the shortest path to the goal.
**Answer:** False (DFS is not optimal).

**21.** Iterative deepening combines the completeness of breadth-first search with the small memory use of depth-first search.
**Answer:** True.

**23.** Breadth-first search keeps its frontier in a stack.
**Answer:** False (BFS uses a queue; DFS uses a stack).

### Multiple Choice

**19.** A tree: A has children B and C; B has children D and E; C has child F. The goal is F. Children are visited left to right. In which order does depth-first search expand nodes until it reaches F? (Select ONE)

- A. A, B, C, D, E, F
- B. A, B, D, E, C, F
- C. A, C, F
- D. F, C, A

**Answer:** B.

**20.** With branching factor b = 10 and a machine that checks 10⁶ nodes per second, about how long does a search to depth 8 (about 10⁸ nodes) take? (Select ONE)

- A. About 1 second
- B. About 100 seconds
- C. About 2.8 hours
- D. About 11.6 days

**Answer:** B (10⁸ ÷ 10⁶ = 100 s).

**21.** Which strategy keeps the frontier in a priority queue ordered by the path cost g(n) paid so far? (Select ONE)

- A. Breadth-first search
- B. Depth-first search
- C. Uniform-cost search
- D. Greedy best-first search

**Answer:** C.

**22.** Which uninformed strategy uses small memory, O(b·m), but is not optimal? (Select ONE)

- A. Breadth-first search
- B. Depth-first search
- C. Uniform-cost search
- D. Iterative deepening

**Answer:** B.

**24.** Which statements about breadth-first search are correct? (Select ALL that apply)

- A. It is complete when the branching factor is finite
- B. It is optimal when all step costs are equal
- C. Its time and space are both O(b^d)
- D. Its memory use is small, only O(b·d)
- E. It expands the shallowest unexpanded node first

**Answer:** A, B, C, E.

### Open-ended

**20.** Name the five components of a well-defined search problem using route finding as the example, then compare breadth-first search and depth-first search.
**Answer:** initial state (in city A); actions (drive to a neighboring city); transition model (driving from A to B leads to "in city B"); goal test (is the agent in city Z?); path cost (total distance in km); BFS uses a queue, expands the shallowest node first, is complete and optimal when step costs are equal, but needs O(b^d) memory; DFS uses a stack, goes as deep as possible first, needs little memory O(b·m), but is not optimal.

---

## 3.7 Informed, Adversarial and Local Search

### True / False

**11.** A\* search orders its frontier by f(n) = g(n) + h(n).
**Answer:** True.

**21.** A heuristic is admissible if it never overestimates the true remaining cost to the goal.
**Answer:** True.

**22.** Greedy best-first search is guaranteed to find the optimal path.
**Answer:** False (it uses only h(n) and ignores the cost paid so far).

**23.** Alpha-beta pruning can change the final minimax decision in order to save time.
**Answer:** False (it gives the same decision as minimax; it only skips branches that cannot matter).

**25.** Hill climbing can get stuck at a local maximum.
**Answer:** True.

### Multiple Choice

**21.** MAX has three moves. After each, MIN picks a reply. Leaf scores: move A → 3, 12, 8; move B → 2, 4, 6; move C → 14, 5, 2. Which move does MAX choose, and what is the game value? (Select ONE)

- A. Move A, value 3
- B. Move B, value 2
- C. Move C, value 14
- D. Move A, value 12

**Answer:** A (MIN values: A = 3, B = 2, C = 2; MAX takes 3).

**22.** For the same tree, with leaves examined left to right, how many of the 9 leaves does alpha-beta pruning evaluate? (Select ONE)

- A. 9
- B. 7
- C. 5
- D. 3

**Answer:** B. 7 (move A: 3 leaves, α = 3; move B: leaf 2 ≤ 3, prune after 1 leaf; move C: 14, 5, 2 all needed = 3 leaves; 3 + 1 + 3 = 7).

**23.** Edge costs: S→A = 1, S→B = 4, A→B = 2, A→G = 6, B→G = 3. Heuristic: h(S) = 5, h(A) = 4, h(B) = 3, h(G) = 0. What is the cost of the optimal path from S to G found by A\*? (Select ONE)

- A. 6
- B. 7
- C. 8
- D. 10

**Answer:** A. 6 (S → A → B → G = 1 + 2 + 3).

**24.** What does simulated annealing do at a high temperature T? (Select ONE)

- A. It accepts many worse moves, so it explores widely and can escape local maxima
- B. It never accepts a worse move
- C. It behaves exactly like hill climbing
- D. It stops immediately

**Answer:** A.

**26.** Which statements are correct? (Select ALL that apply)

- A. The number of misplaced tiles (h1) is admissible
- B. The Manhattan distance (h2) dominates h1
- C. h2 usually expands more nodes than h1
- D. The Manhattan distance is admissible
- E. A consistent heuristic is also admissible

**Answer:** A, B, D, E.

### Open-ended

**22.** Explain how A\* search chooses which node to expand, what an admissible heuristic is, and why A\* finds the cheapest path when greedy best-first search may not.
**Answer:** A\* expands the node with the lowest f(n) = g(n) + h(n), the cost paid so far plus the estimated cost still to go; admissible = h(n) never overestimates the true remaining cost (e.g. straight-line distance); A\* is optimal with an admissible heuristic; greedy best-first uses only h(n), so it is fast but ignores the cost already paid and can be misled (not optimal); worked example: S → A → B → G with cost 6.

---

## 3.8 Planning (STRIPS) and Constraint Satisfaction

### True / False

**12.** In STRIPS, the new state is (old state − delete list) ∪ add list.
**Answer:** True.

**23.** Classical planning assumes a deterministic, fully observable, static world.
**Answer:** True.

**24.** The frame problem is the difficulty of listing every condition that must hold for an action to work.
**Answer:** False (that is the qualification problem; the frame problem is stating what does not change).

**25.** A solution to a constraint satisfaction problem assigns a value to every variable without breaking any constraint.
**Answer:** True.

**27.** Under the STRIPS closed-world assumption, any fact that is not listed in the current state is assumed to be true.
**Answer:** False (it is assumed to be false).

### Multiple Choice

Actions for 3.8-MC1 and 3.8-MC2 (blocks world):

| Action | Preconditions | Delete list | Add list |
|---|---|---|---|
| Pickup(x) | Clear(x), OnTable(x), HandEmpty | OnTable(x), Clear(x), HandEmpty | Holding(x) |
| Stack(x,y) | Holding(x), Clear(y) | Holding(x), Clear(y) | On(x,y), Clear(x), HandEmpty |

Initial state: OnTable(A), OnTable(B), Clear(A), Clear(B), HandEmpty. Goal: On(A,B).

**23.** Which plan reaches the goal? (Select ONE)

- A. Stack(A,B), then Pickup(A)
- B. Pickup(A), then Stack(A,B)
- C. Pickup(B), then Stack(A,B)
- D. Stack(A,B) only

**Answer:** B.

**24.** Which fact is in the state right after Pickup(A) has been applied? (Select ONE)

- A. HandEmpty
- B. Holding(A)
- C. Clear(A)
- D. OnTable(A)

**Answer:** B.

**25.** Which problem is described by "moving a box also moves everything that is on it"? (Select ONE)

- A. The frame problem
- B. The qualification problem
- C. The ramification problem
- D. The halting problem

**Answer:** C.

**26.** In a map-colouring CSP with domain {red, green, blue} for every region, regions X and Y are neighbors. X is assigned red. After forward checking, what is the domain of Y? (Select ONE)

- A. {red, green, blue}
- B. {green, blue}
- C. {red}
- D. {}

**Answer:** B.

**28.** Which are assumptions of classical planning? (Select ALL that apply)

- A. Actions are deterministic
- B. The state is fully observable
- C. The world is static (it changes only when the agent acts)
- D. Several agents act at the same time
- E. States and time are discrete

**Answer:** A, B, C, E.

### Open-ended

**24.** Explain the three parts of a STRIPS action, then use the blocks-world example above to show the plan that achieves On(A,B) and the state after each step.
**Answer:** preconditions (facts that must hold), delete list (facts that become false), add list (facts that become true); new state = (old state − delete list) ∪ add list; plan: Pickup(A) gives OnTable(B), Clear(B), Holding(A); then Stack(A,B) gives OnTable(B), On(A,B), Clear(A), HandEmpty, so the goal holds.

---

## 3.9 Symbolic Natural Language Processing

### True / False

**13.** Symbolic NLP processes language with hand-written rules, grammars, lexicons and logic, rather than patterns learned from large text collections.
**Answer:** True.

**25.** Every rule of a context-free grammar has a single symbol on its left side.
**Answer:** True.

**26.** A sentence can have only one valid parse tree under a given grammar.
**Answer:** False (ambiguous sentences can have several).

**27.** In rule-based sentiment analysis, negation flips the polarity, so "not good" scores as negative.
**Answer:** True.

**29.** SHRDLU could understand unrestricted, open-ended English about any topic.
**Answer:** False (it worked only in a small blocks world).

### Multiple Choice

**25.** Which stage of the pipeline builds a representation such as `Chase(cat, mouse)` for "The cat chased the mouse"? (Select ONE)

- A. Tokenization
- B. Part-of-speech tagging
- C. Semantic interpretation
- D. Morphological analysis

**Answer:** C.

**26.** Grammar: `S → NP VP; NP → Det N; VP → V NP; Det → the; N → cat | mouse; V → chased`. Which sentence can this grammar generate? (Select ONE)

- A. the cat chased the mouse
- B. chased the cat the mouse
- C. the mouse the cat chased
- D. cat the chased mouse

**Answer:** A.

**27.** Lexicon: good = +2, bad = −2. "very" multiplies the score by 1.5. "not" flips the sign. What is the score of "The food was not very good"? (Select ONE)

- A. +3
- B. −2
- C. −3
- D. +1

**Answer:** C (very good = 2 × 1.5 = +3; not flips it to −3).

**28.** Facts: `parent(alice, bob).` `parent(alice, carol).` `parent(bob, dave).` Rule: `grandparent(X, Z) :- parent(X, Y), parent(Y, Z).` What does the query `grandparent(alice, W)` return? (Select ONE)

- A. W = bob
- B. W = carol
- C. W = dave
- D. false

**Answer:** C.

**30.** Which are typical weaknesses of symbolic NLP? (Select ALL that apply)

- A. Ambiguity: many valid parses and word senses
- B. Brittleness to slang, misspellings and new words
- C. Heavy manual effort to write grammars, lexicons and ontologies
- D. It needs very large training data sets
- E. Limited coverage, because language is open-ended

**Answer:** A, B, C, E.

### Open-ended

**26.** Name the stages of a symbolic NLP pipeline for "The cat chased the mouse", and explain ambiguity using "I saw the man with the telescope".
**Answer:** tokenization, morphological analysis, part-of-speech tagging, syntactic parsing, semantic interpretation (`Chase(cat, mouse)`), discourse and pragmatics; ambiguity: one sentence has two valid parses (I used a telescope to see him, or the man had a telescope), and the grammar alone cannot choose, so meaning and world knowledge are needed.
