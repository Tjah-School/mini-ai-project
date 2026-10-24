# Introduction to Software and Symbolic AI — Stage 1 Project Plan

## Team Information & Work Distribution

| Role | Team Member | Primary Responsibilities | Key Traits & Required Skills |
|---|---|---|---|
| CEO / Coordinator | Alexander Valentino Lukman / 吕孙鸿 / 1820262032 | Overall project management, timeline tracking, task delegation, team communication, risk management | Leadership & organization; strategic planning; time management; clear communication |
| CIO / Repository & Submission Lead | Victor Charlie / 李东财 / 1820262066 | GitHub repository setup, Markdown workflow control, version management, final file submission | Git / GitHub proficiency; file organization; technical diligence; system compliance |
| Quality Lead | Valiant Lim / 林盛旺 / 1820262320 | Peer review, checking against assignment rubrics, content accuracy verification, proofreading | High attention to detail; critical evaluation; quality assurance; rubric adherence |
| Visual Design & Video Lead | Said Aliyev / 李叶 / 1820262028 | PPT slide design, video production, audio editing, visual asset creation, recording coordination | Visual aesthetics; slide layout mastery; video/audio editing; creative storytelling |
| Content Lead | Rafael Tjahjono / 李文明 / 1820262082 | Research direction, core Markdown text drafting, Study Guide layout, scriptwriting, logic verification | Technical writing; research capability; topic structuring; educational clarity |

### Team Work Distribution Summary

| Metric | Details |
|---|---|
| Workload Principle | Equal substantive contribution from all members; roles represent primary coordination areas, not isolated work silos. |
| Core Artifacts | All members research and contribute to the shared Markdown foundation, Study Guide, PPT, and Video scripts. |
| Review Process | Drafts are pushed to GitHub, proofread by the Quality Lead, and finalized by the CIO prior to submission. |

---

## Project Title / Module Name

**Introduction to Software and Symbolic AI**

**Purpose:** This project creates an interactive learning module that introduces beginners and intermediate students to Symbolic AI, including logic, rules, and knowledge representation. It teaches undergraduate students how to build and use logic-based AI in software systems.

---

## 1. The Foundation of Software (Rafael)

### 1.1 Simple Learning Goals

By the end of your lesson, a beginner should be able to answer three basic questions:

1. **What is software?** Explain what software is and name the two main types (System like Windows vs. Application like web browsers).
2. **How does code run?** Explain how human code turns into binary (0s and 1s) so the computer hardware can run it.
3. **How do programs think?** Show how software uses simple rules (If/Else conditions and Loops) to process inputs into outputs.

### 1.2 Detailed vs. Brief (Scope Boundaries)

| Topic Area | Deep Focus (Explain in detail) | Quick Intro (1 slide / brief mention) |
|---|---|---|
| Software Basics | Difference between Hardware and Software; System Software vs. Application Software | History of early computers |
| How Code Works | High-level code → Binary (0s and 1s); simple logic steps (If/Else, Loops) | Deep OS details; hard coding math |
| Modern Tech | How developers use Git/GitHub | Cloud computing (SaaS); open source vs. paid software |

### 1.3 What to Say in the "Quick Intro" Parts (Brief Intro)

Keep these brief topics super simple:

- **How Code Translates:** Mention that code is translated to binary either all at once (Compiled like C++) or line-by-line (Interpreted like Python).
- **How Software is Built (SDLC):** State that building software follows steps: Plan → Design → Code → Test → Release.
- **Cloud Software:** Mention that modern software often runs on remote servers through the internet (like Google Docs) instead of installed CDs.
- **Open Source:** Explain that "open source" means the code is free for anyone to see and improve (like Linux or Python).

### 1.4 One-Sentence Plan Summary for Your Report

> "Our project teaches beginners what software is, how human code turns into computer instructions, and how basic program logic works, while giving a quick high-level overview of how modern software is built and delivered."

---

## 2. The Birth of Symbolic AI (Good Old-Fashioned AI) (Victor)

### 2.1 Simple Learning Goals

By the end of this subtopic, a beginner should be able to answer three basic questions:

1. **What is Symbolic AI?** Explain what Good Old-Fashioned AI (GOFAI) is in plain language.
2. **What is the Physical Symbol System Hypothesis?** State the foundational idea that human thinking can be reduced to manipulating abstract symbols.
3. **Why did early AI researchers focus on logic?** Explain why early pioneers believed intelligence was driven by explicit rules and formal reasoning rather than data.

### 2.2 Detailed vs. Brief (Scope Boundaries)

| Topic Area | Deep Focus (Explain in detail) | Quick Intro (1 slide / brief mention) |
|---|---|---|
| Foundations of GOFAI | Definition of Good Old-Fashioned AI (GOFAI); the Physical Symbol System Hypothesis (Newell & Simon); abstract symbols as representations of real-world concepts | The 1956 Dartmouth Conference (birthplace of AI research); early optimism of 1960s researchers |
| Historical Trajectory | Dominance of symbolic logic from 1950s to 1980s; shift from theoretical logic to practical expert systems | The first "AI Winter" (funding cuts due to overpromising); philosophical critiques (e.g., Searle's Chinese Room) |

### 2.3 What to Say in the "Quick Intro" Parts (Brief Intro)

- **The Dartmouth Conference:** Mention that symbolic AI began at a famous 1956 summer workshop where researchers believed every aspect of learning and intelligence could be precisely described so a machine could simulate it.
- **Early Optimism:** Briefly state that early successes in chess and math proofs led scientists to mistakenly believe that human-level intelligence was only a few years away.
- **The First AI Winter:** Explain that when these early systems failed to scale to real-world complexity, government funding dried up, leading to a period known as an "AI Winter."

### 2.4 One-Sentence Plan Summary

> "This subtopic teaches beginners how Symbolic AI originated as the first major AI paradigm, driven by the belief that intelligence is achieved through the formal manipulation of symbols and explicit logic."

---

## 3. How It Works: Mechanics & Examples (Alex)

### 3.1 Simple Learning Goals

By the end of this subtopic, a beginner should be able to answer three basic questions:

1. **What are the two main components of an Expert System?** Describe the roles of the Knowledge Base and the Inference Engine.
2. **How do Production Rules work?** Show how software uses IF/THEN statements to process input facts into logical conclusions.
3. **What is a real-world example of Symbolic AI?** Name a historical expert system (like MYCIN or DENDRAL) and explain what problem it solved.

### 3.2 Detailed vs. Brief (Scope Boundaries)

| Topic Area | Deep Focus (Explain in detail) | Quick Intro (1 slide / brief mention) |
|---|---|---|
| Core Architecture | Knowledge Base: explicit storage of facts and relationships; Inference Engine: the reasoning mechanism that executes rules; IF/THEN production rules in practice | Certainty Factors (adding probabilities to rigid rules); ontologies and taxonomy hierarchies |
| Search & Execution | Forward Chaining (data-driven: working from facts to goals); Backward Chaining (goal-driven: working from hypotheses to facts) | Depth-first vs. breadth-first search trees; rule conflict resolution strategies |
| Real-World Examples | DENDRAL (1965): analyzing chemical structures; MYCIN (1970s): diagnosing blood infections and prescribing treatments | PROLOG and LISP programming languages; commercial rule engines like Drools |

### 3.3 What to Say in the "Quick Intro" Parts (Brief Intro)

- **Forward vs. Backward Chaining:** Explain that forward chaining starts with known facts to find a result (like diagnosing symptoms), while backward chaining starts with a goal and works backward to verify if facts support it (like proving a theorem).
- **Certainty Factors:** Mention that expert systems used simple percentage scores (e.g., 80% certainty) to handle uncertain human judgments without complex math.
- **Symbolic Programming Languages:** Briefly note that languages like LISP and PROLOG were invented specifically to handle symbolic logic rather than standard numerical calculations.

### 3.4 One-Sentence Plan Summary

> "This subtopic teaches beginners the internal mechanics of symbolic systems, demonstrating how Knowledge Bases and Inference Engines process IF/THEN rules through historical examples like MYCIN and DENDRAL."

---

## 4. Symbolic AI vs. Modern Machine Learning (Rafael)

### 4.1 Simple Learning Goals

By the end of this subtopic, a beginner should be able to answer three basic questions:

1. **How do their approaches differ?** Contrast explicit rule-coding (Symbolic) with statistical learning from data (Machine Learning).
2. **Why is Symbolic AI transparent?** Explain why symbolic decisions are fully explainable while neural networks function as "black boxes."
3. **Why did Symbolic AI struggle with real-world tasks?** Explain why rigid rules fail when faced with noisy or ambiguous data like computer vision or voice recognition.

### 4.2 Detailed vs. Brief (Scope Boundaries)

| Topic Area | Deep Focus (Explain in detail) | Quick Intro (1 slide / brief mention) |
|---|---|---|
| Paradigm Shift | Top-down rule programming vs. bottom-up data learning; abstract symbols vs. high-dimensional vector embeddings; zero training data required vs. Big Data dependency | Symbolic execution speed vs. GPU-heavy ML training; memory efficiency differences |
| Strengths & Limitations | High explainability/auditability vs. "Black Box" predictions; deterministic accuracy vs. statistical probability; the Brittleness Problem: complete failure on edge cases | The Symbol Grounding Problem: connecting symbols to reality; the Knowledge Acquisition Bottleneck |

### 4.3 What to Say in the "Quick Intro" Parts (Brief Intro)

- **The Knowledge Acquisition Bottleneck:** Mention that hand-writing thousands of rules from human experts was extremely slow, expensive, and difficult to maintain.
- **The Symbol Grounding Problem:** Explain that computers don't know what a word actually means in the real world—they only know how it relates to other symbols in their code.
- **Data Requirements:** Briefly contrast how symbolic AI needs zero training data (just expert knowledge) while modern machine learning requires millions of data samples to recognize patterns.

### 4.4 One-Sentence Plan Summary

> "This subtopic compares top-down symbolic logic against bottom-up statistical machine learning, highlighting why symbolic AI excels at transparent reasoning but fails at handling messy, real-world perception."

---

## 5. The Modern Revival: Hybrid AI (Neuro-Symbolic AI) (Valiant)

### 5.1 Simple Learning Goals

By the end of this subtopic, a beginner should be able to answer three basic questions:

1. **What is Neuro-Symbolic AI?** Explain how hybrid systems combine neural networks with symbolic logic.
2. **Why do we need both paradigms?** Describe how neural networks handle perception while symbolic logic handles safety, reasoning, and rules.
3. **Where is Hybrid AI used today?** Give real-world examples such as self-driving cars or LLM guardrails/knowledge graphs.

### 5.2 Detailed vs. Brief (Scope Boundaries)

| Topic Area | Deep Focus (Explain in detail) | Quick Intro (1 slide / brief mention) |
|---|---|---|
| Hybrid Framework | The "Best of Both Worlds" philosophy; System 1 (Fast/Perception/Neural) vs. System 2 (Slow/Reasoning/Symbolic); neural perception fed into symbolic logic engines | Knowledge Graphs (RDF/OWL ontologies in modern web search); Graph Neural Networks (GNNs) |
| Real-World Applications | Self-driving vehicles: computer vision + deterministic safety rules; generative AI guardrails: LLMs + symbolic validation/RAG; regulated fields (healthcare, law, finance) requiring strict compliance | Formal code verification using symbolic execution; robotics manipulation and path planning |

### 5.3 What to Say in the "Quick Intro" Parts (Brief Intro)

- **System 1 vs. System 2 Thinking:** Mention Daniel Kahneman's framework—neural networks act like human intuition (fast, subconscious perception), while symbolic AI acts like deliberate logic (slow, step-by-step reasoning).
- **Knowledge Graphs in Search:** Briefly state that modern engines like Google search use Knowledge Graphs to connect facts and give accurate answers to explicit queries.
- **Formal Verification:** Mention that critical software (like aircraft controls) uses symbolic logic to mathematically prove code will never crash under unexpected conditions.

### 5.4 One-Sentence Plan Summary

> "This subtopic teaches beginners how modern AI overcomes the limitations of deep learning by pairing neural perception with symbolic logic to create reliable, safe, and explainable hybrid systems."

---

## Clear Purposes of Deliverables

### A. Study Guide

- **Target Audience:** Beginner and intermediate undergraduate students.
- **Core Purpose:** Serves as the comprehensive, self-paced reading material and reference handbook for the entire module.
- **Key Functions:**
  - Establishes explicit scope boundaries (separating what students must learn in detail vs. brief high-level concepts).
  - Provides detailed explanations, historical contexts, architecture diagrams, comparison tables (Symbolic vs. Machine Learning), and code/rule walkthroughs.
  - Includes end-of-chapter reflection questions and the test-bank material for self-assessment.

### B. Lecture Slides

- **Target Audience:** In-class presentation audience / visual learners.
- **Core Purpose:** Provides structured, visual-first scaffolding during lectures to guide student attention without cognitive overload.
- **Key Functions:**
  - Displays high-level diagrams (e.g., Knowledge Base vs. Inference Engine flow, System 1 vs. System 2 architecture, Software SDLC steps).
  - Highlights core definitions, key contrasts, and real-world case studies (MYCIN, DENDRAL, Self-Driving Guardrails).
  - Serves as an interactive roadmap for instructor explanations, reducing text density in favor of key takeaways.

### C. Mini-Lecture Videos

- **Target Audience:** Asynchronous learners, remote students, and review-phase students.
- **Core Purpose:** Delivers short, high-impact bite-sized video walkthroughs (5 minutes each) dedicated to individual core concepts.
- **Key Functions:**
  - Breaks down complex abstract logic into digestible, step-by-step visual explanations.
  - Allows students to pause, rewind, and re-watch foundational concepts (e.g., how code turns into binary, forward vs. backward chaining).
  - Reinforces real-world application by showing concrete software and AI examples in action.

---

## Mini-Lecture Plan: Core Focus & Concrete Teaching Approach

### Mini-Lecture 1 — How It Works: Mechanics & Examples (Alex)

**Mini-Lecture Title:** Inside an Expert System: Knowledge Base vs. Inference Engine

#### A. Single Important Idea Focus

**Core Concept:** An Expert System separates what the system knows (the Knowledge Base) from how the system reasons (the Inference Engine).

By isolating this single core concept, students learn that Symbolic AI does not mix domain rules with execution logic—allowing non-programmer domain experts (like doctors) to add rules while the engine handles the deduction.

#### B. Concrete Teaching Approach & Step-by-Step Delivery

**1. Hook & Real-World Analogy (1 Minute)**

- **Teaching Strategy:** Concrete Analogy (The Cookbook & The Chef)
- **Delivery:**
  - Compare an Expert System to a restaurant kitchen:
    - **Knowledge Base** = The Recipe Book (contains explicit facts and IF/THEN rules written by expert chefs).
    - **Inference Engine** = The Chef (follows the rules, reads incoming customer orders/facts, and decides what dish to prepare).
  - **Key Takeaway:** The chef doesn't rewrite the recipes; they just process incoming orders using the existing recipe book.

**2. Interactive Code/Rule Walkthrough (2 Minutes)**

- **Teaching Strategy:** Worked Example / Trace-Through Demonstration
- **Delivery:**
  - Show a simple medical diagnosis rule set on slide:
    - Rule 1: IF patient has fever AND sore throat THEN suspect Strep Infection.
    - Rule 2: IF Strep Infection THEN prescribe Antibiotic A.
  - Walk through Forward Chaining step-by-step with live visual toggles:
    - Fact Entered: Patient has a fever.
    - Fact Entered: Patient has a sore throat.
    - Engine Execution: Match facts to Rule 1 → Infer "Strep Infection" → Trigger Rule 2 → Output "Prescribe Antibiotic A".

**3. Historical Case Connection (1 Minute)**

- **Teaching Strategy:** Real-World Contextualization (MYCIN)
- **Delivery:**
  - Briefly highlight MYCIN (1970s) as the historical benchmark that used this exact IF/THEN production rule mechanism to diagnose blood infections and prescribe dosages as accurately as human specialists.

**4. Active Check for Understanding (1 Minute)**

- **Teaching Strategy:** Predict-the-Outcome Prompt
- **Delivery:**
  - Present a quick "What If?" scenario to the class: "If a new virus appears, do we need to rebuild the Inference Engine software, or do we just add new rules to the Knowledge Base?"
  - Explain the answer briefly to solidify the decoupling concept before concluding.

---

### Mini-Lecture 2 — The Foundation of Software (Rafael)

**Mini-Lecture Title:** From Human Code to Computer Logic: What is Software and How It Runs

#### A. Single Important Idea Focus

**Core Concept:** Software is the invisible bridge between human intent and computer hardware, translating human-readable instructions into binary (0s and 1s) and executing them using basic logical rules.

By focusing on this core concept, beginners learn that software isn't magic—it is simply a structured set of instructions that tells hardware what to do step-by-step.

#### B. Concrete Teaching Approach & Step-by-Step Delivery

**1. Hook & Real-World Analogy (1 Minute)**

- **Teaching Strategy:** Concrete Analogy (The Chef and the Instruction Manual)
- **Delivery:**
  - Compare computer hardware to a brand-new kitchen filled with appliances, and software to the instruction manual written by a human.
  - Without the manual (software), the appliances (hardware) just sit there doing nothing. Software gives them purpose and direction.

**2. Walkthrough: From High-Level Code to Binary & Logic (2 Minutes)**

- **Teaching Strategy:** Worked Example / Code Trace-Through
- **Delivery:**
  - Show a simple human-readable condition on screen:

    ```python
    if user_score >= 50:
        print("Pass")
    else:
        print("Fail")
    ```

  - Explain how this high-level text is translated (either compiled all at once or interpreted line-by-line) into the computer's native language—binary (0s and 1s) representing electric switches turning on and off.
  - Show how the computer uses this simple If/Else logic to process inputs and generate outputs.

**3. Real-World Context: System vs. Application Software (1 Minute)**

- **Teaching Strategy:** Visual Categorization
- **Delivery:**
  - Contrast the two main types of software using a building analogy:
    - **System Software** (e.g., Windows, macOS, Linux): The foundation, plumbing, and electricity of the building—managing the physical hardware.
    - **Application Software** (e.g., Web Browsers, Microsoft Word): The furniture and rooms built on top that users actually interact with daily.

**4. Active Check for Understanding (1 Minute)**

- **Teaching Strategy:** Predict-the-Outcome Prompt
- **Delivery:**
  - Pose a quick scenario to the class: "If your web browser freezes while watching a video, is that a failure of System Software or Application Software?"
  - Briefly explain the answer to reinforce the structural boundary between managing hardware and running user programs.

---

## Master Task List

**Master Task List — Introduction to Software and Symbolic AI**

### AI Documentation

| Name / Chinese Name / Student ID | AI Evidence File |
|---|---|
| Rafael Tjahjono / 李文明 / 1820262082 | AI Use Evidence \| Rafael Tjahjono |
| Alexander Valentino Lukman / 吕孙鸿 / 1820262032 | AI USE EVIDENCE ALEX |
| Said Aliyev / 1820262028 / 李叶 | AI USE EVIDENCE |
| Valiant Lim / 林盛旺 / 1820262320 | AI Evidence - Valiant |
