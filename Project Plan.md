# **Cangcut — Project Plan**

# **A. Team Information and Responsibilities**

## **A1. Team members and roles**

| Role | Team member (roster name / student ID) | Primary responsibilities | Key traits and skills (strengths / skills to develop) |
| :---- | :---- | :---- | :---- |
| CEO / Coordinator | **Alexander Valentino Lukman** 吕孙鸿 1820262032 | Overall project management, timeline tracking, task delegation, team communication, risk management | Leadership and organization Strategic planning Time management Clear communication |
| CIO / Repository & Submission Lead | **Victor Charlie** 李东财 1820262066 | GitHub repository setup, Markdown workflow control, version management, final file submission | Git / GitHub proficiency File organization Technical diligence System compliance |
| Quality Lead | **Valiant Lim** 林盛旺 1820262320 | Peer review, checking against assignment rubrics, content accuracy verification, proofreading | High attention to detail Critical evaluation Quality assurance Rubric adherence |
| Visual Design & Video Lead | **Said Aliyev** 李叶 1820262028 | PPT slide design, video production, audio editing, visual asset creation, recording coordination | Visual aesthetics Slide layout mastery Video/audio editing Creative storytelling |
| Content Lead | **Rafael Tjahjono** 李文明 1820262082 | Research direction, core Markdown text drafting, Study Guide layout, scriptwriting, logic verification | Technical writing Research capability Topic structuring Educational clarity |

## **A2. How we use strengths and share the workload fairly**

**Principle.** Every member makes an equal, substantive contribution. Roles describe primary coordination duties, not exclusive areas of work. Everyone studies the whole module, writes and reviews content, and must be able to explain the team's core content.

> * **Content is split into 16 content units** (Table A3), so every member owns 2–4 units of research, Markdown drafting, test-bank questions and slides, whichever role they hold.  
> * **Roles add coordination work on top**: the CEO tracks the schedule, the CIO controls the repository and submissions, the Quality Lead runs review, the Visual Lead leads design and video, and the Content Lead leads the Markdown standard and scripts. The units were sized so that members with heavier coordination duties own fewer or smaller units.  
> * **Every unit has an author and a different reviewer**, so each member also reviews others' work. Contribution is evidenced by GitHub commits, pull requests, review comments and personal logs.  
> * **Topic leads** keep each topic consistent: Rafael (Software), Valiant (Algorithms & Data Structures), Alex (Symbolic AI). We rebalance if the task list shows uneven load (see risks in Section D).

## **A3. Content units, owners and reviewers**

| Unit | Content (source slides) | Topic | Owner | Reviewer | Size |
| :---- | :---- | :---- | :---- | :---- | :---- |
| S1 | System vs. application software; operating systems (evolution, process and memory management) (chap3, slide 2\) | 1\. Software | Rafael | Said | Medium |
| S2 | Programming languages: evolution, categories, features (chap3, slide 2\) | 1\. Software | Rafael | Said | Medium |
| S3 | Software engineering: process models, modularity, quality assurance (chap3, slide 2\) | 1\. Software | Victor | Rafael | Medium |
| S4 | Databases: database models, relational databases, SQL (chap3, slide 2\) | 1\. Software | Said | Victor | Medium |
| A1 | Algorithms: features, representation (chap3, slide 3\) | 2\. Algorithms & Data Structures | Valiant | Victor | Small |
| A2 | Basic algorithms (sorting, searching); iteration and recursion (chap3, slide 3\) | 2\. Algorithms & Data Structures | Valiant | Victor | Medium |
| A3 | Linear data structures: arrays, records, linked lists, stacks, queues (chap3, slide 3\) | 2\. Algorithms & Data Structures | Said | Valiant | Medium |
| A4 | Non-linear data structures: trees, binary trees, graphs (chap3, slide 3\) | 2\. Algorithms & Data Structures | Said | Valiant | Medium |
| Y1 | Introduction to Symbolic AI; propositional and predicate logic, inference rules (chap4, slides 3–20) | 3\. Symbolic AI | Victor | Alex | Large |
| Y2 | Knowledge representation: logic, semantic networks, frames/scripts, rules, ontologies (chap4, slides 21–28) | 3\. Symbolic AI | Alex | Valiant | Medium |
| Y3 | Rule-based and expert systems: production rules, forward/backward chaining, conflict resolution, certainty factors, DENDRAL and MYCIN, LISP/PROLOG/Drools (chap4, slides 29–32; draft “How It Works: Mechanics & Examples”) | 3\. Symbolic AI | Alex | Valiant | Medium (+ mini lecture) |
| Y4 | Planning and problem solving: state space, uninformed/informed/adversarial/local search (chap4, slides 33–40) | 3\. Symbolic AI | Valiant | Said | Medium |
| Y5 | Symbolic NLP: grammars, semantics, rule-based processing, applications (chap4, slides 41–49) | 3\. Symbolic AI | Rafael | Alex | Medium |

# **B. Project Scope and Learning Goals**

## **B1. Target learners and assumed background**

Our learners are first- or second-year undergraduate students (beginner to intermediate) taking an introductory computing/AI course. We assume:

> * everyday experience using computers, apps and the internet;  
> * basic school-level mathematics and reasoning (true/false, simple algebra, sets);  
> * **no** prior programming, data structure or AI knowledge. Short code and pseudocode examples are introduced step by step (Python-style pseudocode).

Terminology is defined at first use, and every abstract idea is paired with an everyday example (e.g., a recipe for an algorithm, a stack of plates for a stack).

## **B2. Learning goals**

After using our materials, a beginner should be able to:

| Topic | Learners should be able to… |
| :---- | :---- |
| 1\. Software | **Explain** the difference between system and application software and give examples (e.g., UNIX, a messaging app such as Weixin). **Describe** what an operating system does (processes, memory) and **compare** programming-language categories (low/high level, compiled/interpreted). **Explain** how software is built (development process models, modularity, quality assurance) and **describe** what a relational database and a basic SQL query (SELECT … FROM … WHERE) do. |
| 2\. Algorithms & Data Structures | **Define** an algorithm, list its key features and **represent** one with pseudocode or a flowchart. **Trace by hand** linear search, binary search and a simple sort, and **compare** iteration with recursion on a small example (e.g., factorial). **Choose and justify** a data structure (array, record, linked list, stack, queue, tree, graph) for a simple problem and **trace** push/pop, enqueue/dequeue and a breadth-first traversal. |
| 3\. Symbolic AI | **Explain** what Symbolic AI (GOFAI) is in plain language, including its benefits and limitations. **Represent** simple knowledge with propositional/predicate logic, semantic networks, frames and IF–THEN rules, and **apply** modus ponens/modus tollens. **Trace** forward chaining in a small rule-based system, and **explain** the roles of the knowledge base, inference engine and user interface. **Describe** planning and problem solving as searching over a state space. **Explain** the Physical Symbol System Hypothesis and why early AI relied on logic. **Contrast** Symbolic AI with machine learning (transparency vs. brittleness and data needs), and describe what neuro-symbolic (hybrid) AI is and why it combines both. |

## **B3. Content outline**

| Topic | Major topics and subtopics |
| :---- | :---- |
| 1\. Software (S1–S4) | What is Software? Software overview: system software vs. application software; examples (add Cloud Software and SaaS) Operating systems: evolution, process management, memory management; case study: UNIX Programming languages: evolution, categories, key features, compiled vs. interpreted Software engineering: development  process models, modularity, quality assurance Databases: database models, relational databases, SQL basics |
| 2\. Algorithms & Data Structures (A1–A4) | Algorithms: definition, features, representation (pseudocode, flowchart) Basic algorithms: searching (linear, binary), sorting (e.g., bubble, selection) Iteration and recursion Linear data structures: arrays, records, linked lists, stacks, queues Non-linear data structures: trees, binary trees, graphs; breadth-first search as a worked example |
| 3\. Symbolic AI (Y1–Y8) | Introduction: GOFAI, example rule (fever AND cough AND difficulty breathing → pneumonia), applications, benefits, limitations Foundations and history: Physical Symbol System Hypothesis, why early researchers focused on logic, the 1956 Dartmouth Conference, early programs (Logic Theorist, GPS, LISP, ELIZA, SHRDLU), early optimism, the first AI Winter, the Chinese Room and symbol grounding, legacy Logic and reasoning: propositions, AND/OR/NOT, implication, logical equivalences, modus ponens/tollens; predicates, quantifiers and inference Knowledge representation: logic-based, semantic networks, frames and scripts, production rules, ontologies Rule-based and expert systems: condition–action rules, knowledge base, inference engine, user interface; forward and backward chaining, rule conflict resolution, certainty factors, ontologies; case studies DENDRAL and MYCIN; LISP, PROLOG and Drools Planning and problem solving: state space, actions, goal; uninformed (BFS, DFS, uniform-cost), informed (A\*, greedy), adversarial (minimax), local search Symbolic NLP: syntax (formal grammars), semantics, rule-based processing, applications Symbolic AI vs. modern machine learning: top-down rules vs. bottom-up data learning, symbols vs. vector embeddings, data and compute trade-offs, explainability vs. the black box, brittleness, the knowledge acquisition bottleneck, the symbol grounding problem Hybrid (neuro-symbolic) AI: why it is called a modern revival, how neural and symbolic parts are integrated, comparison with traditional AI, applications (healthcare, robotics, language models, finance, science), advantages and limitations |

## 

## 

## **B4. Scope boundaries**

| Topic | Detailed explanation (examples, traces, activities) | Brief introduction (1 slide / short paragraph) |
| :---- | :---- | :---- |
| 1\. Software | System vs. application software What an OS does: process and memory management (concepts) Language categories; compiled vs. interpreted Development process models, modularity, QA basics Relational tables and basic SQL queries | History and evolution of operating systems and languages Advanced OS internals (scheduling algorithms, paging details) Other database models, normalization, advanced SQL |
| 2\. Algorithms & Data Structures | Algorithm features and representation Linear/binary search; one or two simple sorts Iteration vs. recursion Array, linked list, stack, queue, binary tree, graph basics and their typical operations | Complexity (Big-O): intuition only Efficient sorts (merge, quick sort): idea only Balanced trees, hash tables, graph shortest-path algorithms |
| 3\. Symbolic AI | What Symbolic AI is; benefits and limitations Propositional logic, modus ponens/tollens; predicates and quantifiers at a working level Knowledge representation methods and their trade-offs Expert systems: knowledge base vs. inference engine; forward and backward chaining; DENDRAL and MYCIN case studies Search for planning: BFS, DFS, A\* The Physical Symbol System Hypothesis and why early AI used logic Symbolic AI vs. machine learning: explainability, brittleness, data needs What neuro-symbolic AI is and why it combines both approaches | Formal proof rules for quantifiers (instantiation/generalization details) Ontologies in depth Adversarial and local search (minimax, hill climbing) Symbolic NLP: grammar, sentiment analysis, question answering, retrieval (overview only) Dartmouth 1956, early programs (Logic Theorist, GPS, ELIZA, SHRDLU), the first AI Winter, the Chinese Room Certainty factors, rule conflict resolution, LISP/PROLOG/Drools Neuro-symbolic integration approaches and application examples (overview only) |

## **B5. Uncertainties to discuss with the teacher**

> * Is the expected depth for predicate logic (quantifier inference rules) “explain and apply simple cases”, or only an overview?  
> * Should code examples use a specific language (we propose Python-style pseudocode), and is Big-O complexity expected or optional?  
> * Is the amount of Symbolic NLP and adversarial/local search we plan as brief coverage appropriate?  
> * Which topics are on the mini-lecture topic menu, and may we use our proposed topic?

# **C. Planned Learning Resources and Mini Lecture**

## **C1. Shared Markdown content (the single source of truth)**

All teaching content is first written and verified in Markdown in the GitHub repository. The Study Guide, slides, test bank and video scripts are derived from it.

> * **Structure:** /content/01-software, /content/02-algorithms-data-structures, /content/03-symbolic-ai; one file per unit (e.g., s1-system-and-application-software.md), plus /glossary.md, /references.md and /assets for diagrams.  
> * **Standard unit template:** header (unit ID, author, reviewer, version, “used in” list for study guide/slides/video/test bank) → learning goals → key terms → explanation in plain language → worked example → activity / check-your-understanding → common mistakes → references.  
> * **Versions:** v0.x \= draft, v1.0 \= reviewed and frozen for production, v2.0 \= final after Stage 3 revisions.

## **C2. Study Guide and Test Bank**

> * **Purpose:** self-paced reading and reference for the whole module.  
> * **Structure:** how to use this guide → three parts (Software, Algorithms & Data Structures, Symbolic AI), each with a short map, one chapter per unit (goals, explanation, worked example, summary box), cross-links between topics (e.g., graph traversal ↔ search in AI), glossary and references.  
> * **Study and practice:** each chapter ends with “check yourself” questions and a mini exercise (e.g., trace a binary search, write a rule, trace forward chaining).  
> * **Test bank:** at least 8 items per unit: multiple-choice, short-answer and trace/apply questions. Every item has a correct answer, a short explanation and a tag for the learning goal it tests. Items are written by the unit owner and checked by the Quality Lead. The quiz and practice questions already in the Symbolic AI drafts (Y3, Y6) are reused as starting items.

## **C3. PPT Slides**

> * About 12–15 slides per topic: one key idea per slide, minimal text, consistent template designed by the Visual Lead; speaker notes link back to the Markdown unit.  
> * **Planned diagrams and worked examples:** software layers (hardware → OS → applications); compile vs. interpret flow; development process model diagram; relational table with a SQL query result; step-by-step binary search and bubble sort; linked list pointer diagram; stack/queue animations; tree and graph drawings with BFS order; truth tables; semantic network; knowledge base \+ inference engine \+ user interface diagram; search tree for BFS/DFS/A\*.

## **C4. Video Tutorials**

Six short tutorials (about 4–6 minutes each) for topics that benefit from narration and step-by-step demonstration:

| \# | Tutorial | Why narration/demo helps |
| :---- | :---- | :---- |
| V1 | What happens when you run a program? (source code → translation → OS → hardware) | A process that is easier to follow as an animated sequence |
| V2 | Relational databases and your first SQL query | Screen demonstration of a table and query results |
| V3 | Searching and sorting step by step | Learners watch each comparison and swap happen; can pause and predict |
| V4 | Stacks, queues and linked lists in action | Visual pointer and push/pop animation |
| V5 | BFS vs. DFS on a tree/graph | Order of visiting is clearer when animated; links data structures to AI search |
| V6 | Forward chaining in a rule-based system | Trace of facts matching rules is best shown step by step |

Scripts are written from the Markdown units; slides are reused as visuals so that content stays consistent.

## **C5. Live Mini Lecture**

| Item | Plan |
| :---- | :---- |
| Proposed topic | **Inside an expert system: how does a rule-based system reach a conclusion?** (Knowledge base vs. inference engine, with forward chaining.) \[confirm against the official topic menu\] |
| Focused question | How can a program “reason” without learning from data? Answer: facts \+ IF–THEN rules \+ an engine that applies them. |
| Why it is important | It shows the core idea of Symbolic AI, uses logic, rules and knowledge representation from Y1–Y3, and gives learners a transparent, explainable example that contrasts with data-driven AI. |
| Initial teaching idea | **Hook / analogy (1 min):** recipe book \= knowledge base; chef \= inference engine. **Worked example (3 min):** rule “IF fever AND cough AND difficulty breathing THEN pneumonia suspected” (from our course slides); add facts one by one and trace which rule fires. **Audience activity (2 min):** predict-the-outcome: “A new rule is needed. Do we change the engine or add a rule to the knowledge base?” (poll / show of hands). **Wrap-up (1 min):** one-sentence takeaway and link to the Study Guide and video V6. |
| Presenter / backup | Alexander (presenter, owner of Y3); all members rehearse and can present. Backup topic: “How do BFS and DFS find a path?” (Valiant). |

## **C6. How the three resources support one another**

The **Markdown content** is the common foundation: the Study Guide expands it for independent study, the slides condense it into visuals for classroom teaching, and the videos narrate its hardest step-by-step processes for review. The **test bank** is tagged to the same learning goals, so learners can move from reading to watching to practising. The **mini lecture** reuses one Markdown unit, its slides and its video, so it also tests whether our materials work in front of a real audience. A correction to the Markdown is traced to every resource that uses it (see D6).

# **D. Workflow, Schedule and Coordination**

## **D1. Stage deadlines and internal deadlines**

| Stage | Official deadline | Internal deadline(s) | Main outputs |
| :---- | :---- | :---- | :---- |
| Stage 1 | Oct 24, 2026 | Oct 19: plan draft complete Oct 20–22: review and corrections Oct 23: submitted by Submission Lead | Approved project plan, task list, repository, concept lists and pilot Markdown units |
| Stage 2 | Nov 7, 2026 | Oct 30: Markdown v1.0 (all 16 units) reviewed and frozen Nov 3: slides, Study Guide, test bank first versions Nov 4–5: rehearsals and consistency review Nov 6: submitted | First versions of Study Guide, test bank, slides, video(s), and live mini lecture |
| Stage 3 | Nov 28, 2026 | Nov 18: all corrections applied to all deliverables Nov 22–24: videos and polish done Nov 25: final review Nov 26: submitted | Revised and final deliverables, final logs and documentation |

Live class presentation dates follow the announced class schedule; rehearsals are placed before them.

## **D2. How members study and investigate the content**

> * Each member starts from the course slides (Chap 3 and Chap 4\) for their units, then uses at least two additional reliable sources (textbook, university course notes, official documentation). Sources are recorded in /references.md.  
> * Each owner writes a concept list, and then gives a 10-minute peer briefing so that everyone understands all topics, not only their own.  
> * Case materials (e.g., UNIX, a familiar app, a BFS example) from the course's sample learning materials are used as concrete examples.

## **D3. Markdown development and checking**

> * Draft (author) → self-check against the template → peer review by the assigned reviewer → Quality Lead checks accuracy and rubric alignment → Content Lead checks terminology and consistency across topics → **content freeze at v1.0**.  
> * Full production (slides, videos, test bank) starts for a unit only after its Markdown is v1.0. A pilot unit for each topic (T16–T18) tests the workflow before scaling up.

## **D4. GitHub use and contribution tracking**

> * One repository with the structure in C1. Work happens on branches named by task (e.g., unit-y3-draft); changes go to main only through a pull request reviewed by someone other than the author.  
> * GitHub Issues and a GitHub Projects board hold the task list; commit messages and pull requests mention the task ID (e.g., “T16: draft S1 translation section”).  
> * Commit history, pull requests and review comments are our contribution evidence; each member also keeps a personal log. The CIO checks regularly that everyone's contributions are visible.

## **D5. Communication, meetings and peer review**

> * Team chat group for daily coordination; one 30–45 minute meeting twice a week (plus a short check-in before each deadline), with notes saved in /docs/meetings.  
> * Review requests are posted as pull requests with a due date; reviewers respond within 48 hours. Disagreements are settled in the next meeting by the topic lead and CEO.

## **D6. Making sure corrections reach every deliverable**

> * Corrections are made in Markdown first. Each correction is a GitHub issue labelled “correction” that lists the unit and its “used in” items (Study Guide, test bank, slides, video script/video).  
> * The issue gets a checklist with one box per affected deliverable and can be closed only when all boxes are ticked and the Quality Lead has verified them. A change log in the repository records what changed and why.

## **D7. Testing, rehearsal and feedback**

> * Mini lecture: script and activity finished by Nov 3; rehearsal 1 (timed, team feedback) Nov 4; rehearsal 2 with one or two people outside the team to test the activity Nov 5\.  
> * Test bank and exercises: a person outside the unit owner solves them to check clarity and answer keys.  
> * Videos and slides: draft screening by at least two other members, using a short feedback checklist (accuracy, clarity, pacing, readability). Teacher and peer feedback after Stage 2 goes into the issue list for Stage 3\.

## **D8. Main risks and responses**

| Risk | Early sign | Response |
| :---- | :---- | :---- |
| Scope too large (16 units, three topics) | Units not at v0.x by internal deadline | Keep brief topics brief; Content Lead and topic lead cut or reduce detail; ask the teacher if unclear |
| Uneven workload | Task list or commits show some members overloaded or inactive | Weekly check of the Projects board by CEO; reassign tasks or pair members |
| Unfamiliar tools (Git/GitHub, video editing, SQL demo) | Members stuck or avoiding the tool | CIO runs a short Git session; Visual Lead shares a video template; pairing on first use |
| Content errors or inconsistencies between topics | Reviewer finds mistakes; terms differ across files | Reviewer plus Quality Lead check; glossary; consistency review before each deadline |
| Delays or exam clashes | Task not “in progress” 3 days before deadline | Early notice in chat; internal deadlines set 1–2 days before official ones; backup person per unit |
| Over-reliance on AI or AI errors | Unverified claims, unclear explanations | Verify AI output against course slides and sources; record AI use; every member must be able to explain what was submitted |
| Mini lecture runs overtime | Timed rehearsal over limit | Cut content to one example and one activity; practise with a timer |

# **E. Master Task List**

[Master Task List - Introduction to Software and Symbolic AI](https://docs.google.com/spreadsheets/u/0/d/1tA46ZVVZuWtVgIuuV7opHbw1nkgHvL28NNQzwHOvJtY/edit)

# **F. AI documentation**

Significant AI assistance used in planning and task breakdown is recorded in each member's AI evidence file, following Section 6 of the Shared Assignment Rules. Members can explain and justify every part of this plan.

| Name / Chinese name / Student ID | AI evidence file |
| :---- | :---- |
| Rafael Tjahjono / 李文明 / 1820262082 | [AI Use Evidence \| Rafael Tjahjono](https://docs.google.com/document/u/0/d/1kTyab4VeZT3CGYrV2u24D2w6-ST9X2PtYYb0Z-nBqmg/edit) |
| Alexander Valentino Lukman / 吕孙鸿 / 1820262032 | [AI USE EVIDENCE ALEX](https://docs.google.com/document/d/103ptQCPxojI3TY6eEpjjW_ghWJW1KVd8-AaDAGawBEw/edit?usp=sharing) |
| Victor Charlie / 李东财 / 1820262066 | [AI Evidence - Valiant](https://docs.google.com/document/d/16RjlO0waODmkGdFqqIqd2ojPajHSM5Hi_4_knRHT-1Y/edit?usp=sharing) |
| Said Aliyev / 李叶 / 1820262028 | [AI USE EVIDENCE](https://docs.google.com/document/d/1LvqSd_UfcM9xChg9PRTuFcVps2HuV8ReHzCJ2Rto-P4/edit?usp=sharing)  |
| Valiant Lim / 林盛旺 / 1820262320 | [AI use Evidence - Victor](https://docs.google.com/document/d/1QRPjC_VlxVWS89elP_CFVk3QFdZdYzCYPtbyuWgLgIU/edit?tab=t.0) |

## 

## **Pre-submission checklist**

☐ Team information complete; every member understands their responsibilities  
☐ Learning goals describe what beginners can explain or do  
☐ Outline gives meaningful coverage with a manageable level of detail  
☐ Study Guide, slides and videos have clear purposes and share the Markdown foundation  
☐ Mini lecture focuses on one idea with a concrete teaching approach  
☐ Schedule includes review, production, testing, feedback and revision before each deadline  
☐ Tasks have outcomes, owners, internal deadlines and statuses  
☐ Workload is balanced; dependencies and risks are considered  
☐ Links work and all members have reviewed the plan  
☐ Significant AI use is documented
