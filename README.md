---
title: Hocbigg - Logic
description: Path to a free self-taught education in Logic!
---

## Introduction

Logic is the systematic study of valid inference, formal languages, and mathematical truth. Positioned at the intersection of philosophy, mathematics, and theoretical computer science, it provides rigorous tools to determine whether a conclusion follows from its premises, to formalize thought without the ambiguities of natural language, and to discover the fundamental limits of computation and deductive systems. Self-directed learners study logic to sharpen analytical reasoning, understand the foundational architecture of mathematics, or engage deeply with programming language theory and automated verification.

This curriculum establishes the foundational core that every student of modern logic should master before specializing. It assumes no prior background in higher mathematics, formal philosophy, or symbolic notation. The sequence begins with natural-language argumentation and informal fallacies, transitions through basic proof techniques and naive set theory, and systematically constructs classical symbolic logic from the ground up.

Because this guide focuses strictly on core literacy, it centers on classical propositional and first-order predicate logic alongside their metalogical properties. Specialized extensions—such as modal and non-classical logics, advanced model theory, categorical logic, and algorithmic verification—are deliberately left for later study once these foundations are solid.

### Navigating the Curriculum

Unlike modular disciplines where topics can be studied in arbitrary order, formal logic is strictly cumulative. Each subject in this curriculum builds directly on the conceptual vocabulary and techniques of the preceding one:

- **Informal Logic and Critical Reasoning** develops the baseline skills of dissecting natural-language arguments, reconstructing implicit premises, distinguishing deductive validity from inductive strength, and detecting fallacies.
- **Mathematical Foundations for Logic** introduces proof methods (such as direct proof, contradiction, and induction) and naive set theory (sets, relations, functions), providing the mathematical toolkit necessary to understand formal syntax and proofs about logical systems.
- **Propositional Logic** formalizes truth-functional reasoning, covering formal syntax, truth tables, semantic validity, and natural deduction derivations where simple sentences serve as atomic building blocks.
- **First-Order Predicate Logic** deepens this apparatus by analyzing internal sentence structure, introducing variables, predicates, and quantifiers, and formalizing semantics through model-theoretic interpretations.
- **Metatheory of First-Order Logic** shifts perspective from proving theorems *within* a formal system to proving mathematical theorems *about* the system itself, establishing essential properties including Soundness, Completeness, and Compactness.
- **Computability and Gödel's Incompleteness Theorems** concludes the core curriculum by examining the mathematical boundaries of formal systems, connecting Turing computability to formal arithmetic and showing that sufficiently powerful axiomatic systems cannot prove their own consistency or decide every mathematical truth.

Work through the curriculum in this strict order. When studying, prioritize solving exercises, constructing formal derivations, and writing out proofs by hand; formal logic cannot be absorbed passively through reading alone.

### Beyond the Core

Completing this sequence provides the intellectual scaffolding needed to explore the broader logical landscape across this guide series:

- Explore [Advanced Topics](advanced_topics.md) to pursue specialized tracks in model theory, non-classical and modal logics, automated theorem proving, or categorical logic and type theory.
- Work through [Projects](projects.md) to apply your knowledge practically by programming SAT solvers, constructing automated theorem provers, or verifying proofs interactively in proof assistants like Lean or Coq.
- Study seminal primary texts and landmark monographs by Frege, Gödel, Turing, Tarski, and Kripke in [Readings](extras/readings.md).
- Reinforce your understanding with recorded university lectures and specialized masterclasses via [Courses](extras/courses.md).

### Communities

- Forums:
    - [The Philosophy Forum (Logic and Philosophy of Mathematics section)](https://thephilosophyforum.com/categories/10/logic-philosophy-of-mathematics)
    - [Physics Forums (Set Theory, Logic, Probability, Statistics)](https://www.physicsforums.com/forums/set-theory-logic-probability-statistics.78/)
- Subreddits: [r/logic](https://www.reddit.com/r/logic/)
- You can also interact through [GitHub issues](https://github.com/hocbigg/logic/issues). If there is a problem with a course, or a change needs to be made to the curriculum, this is the place to start the conversation. Read more [here](/CONTRIBUTING.html).

## Curriculum

Study this curriculum in the order presented below:

1. Informal Logic and Critical Reasoning
2. Mathematical Foundations for Logic
3. Propositional Logic
4. First-Order Predicate Logic
5. Metatheory of First-Order Logic
6. Computability and Gödel's Incompleteness Theorems

### Informal Logic and Critical Reasoning

Introduces the core concepts of argument analysis in natural language, focusing on identifying premises and conclusions, evaluating deductive validity and inductive strength, and recognizing common informal fallacies.

[Critical Reasoning: A Romp Through the Foothills of Logic (University of Oxford Podcasts / Marianne Talbot)](https://podcasts.ox.ac.uk/series/critical-reasoning-romp-through-foothills-logic) - A free introductory audio and video lecture series that guides absolute beginners through argument reconstruction, validity, and fallacy detection.

[Think Again I: How to Understand Arguments (Coursera / Duke University)](https://www.coursera.org/learn/understanding-arguments) - An interactive MOOC alternative to the Oxford lectures that provides structured exercises in converting ordinary language into clear standard-form arguments.

[Understanding Arguments: An Introduction to Informal Logic (Cengage / Walter Sinnott-Armstrong & Robert Fogelin)](https://books.google.com/books?isbn=9781285197364) - The comprehensive textbook corresponding to the Think Again course series, recommended if you prefer thorough, written treatments of conversational dynamics and fallacy analysis.

[A Concise Introduction to Logic (Cengage / Patrick J. Hurley & Lori Watson)](https://books.google.com/books?isbn=9781305958098) - A widely used college textbook alternative to Sinnott-Armstrong and Fogelin, offering extensive exercise banks covering informal fallacies before introducing formal methods.

[Logic: A Very Short Introduction (Oxford University Press / Graham Priest)](https://books.google.com/books?isbn=9780198811701) - A concise conceptual primer to read alongside your main course to understand the philosophical motivations, historical puzzles, and paradoxes behind logical theory.

### Mathematical Foundations for Logic

Covers naive set theory, operations on relations and functions, and rigorous proof techniques required to understand and construct proofs in formal logic and metatheory.

[How to Prove It: A Structured Approach (Cambridge University Press / Daniel J. Velleman)](https://books.google.com/books?isbn=9781108439534) - The primary textbook for self-directed learners, systematically explaining how to structure direct proofs, proofs by contradiction, and mathematical induction.

[Naive Set Theory (D. Van Nostrand / Paul R. Halmos)](https://archive.org/details/naivesettheory0000halm) - A short, classic prose-based text that serves as a conceptual alternative or companion to Velleman for learning set operations, relations, and transfinite numbers.

[Mathematics for Computer Science (MIT OpenCourseWare / Tom Leighton & Marten van Dijk)](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/) - A complete university lecture series with video and assignments; work through Unit 1 (Proofs, Induction, and Sets) as an interactive companion to Velleman.

### Propositional Logic

Covers the formal syntax, truth-functional semantics, truth-table evaluations, and deductive proof systems of sentential logic.

[forall x: Calgary: An Introduction to Formal Logic (Open Logic Project / P. D. Magnus, Tim Button, Aaron Thomas-Bolduc, & Richard Zach)](https://forallx.openlogicproject.org/) - An open-access textbook covering truth-functional syntax, translations from natural language, truth tables, and Fitch-style natural deduction proofs.

[An Introduction to Formal Logic (Logic Matters / Peter Smith)](https://www.logicmatters.net/ifl/) - A freely downloadable alternative textbook to forall x that provides exceptionally clear explanations, detailed proof strategies, and insightful philosophical commentary.

[Introduction to Logic (Coursera / Stanford Online / Michael Genesereth)](https://www.coursera.org/learn/logic-introduction) - An interactive online course offering immediate automated feedback on propositional formalization, truth assignments, and proofs to use alongside either textbook.

[Logic I (MIT OpenCourseWare / Ephraim Glick)](https://ocw.mit.edu/courses/24-241-logic-i-fall-2009/) - A complete set of university lecture notes, handouts, and exams; work through the sentential logic units to test your formal deduction skills at university caliber.

### First-Order Predicate Logic

Expands formal systems to predicate logic, introducing quantifiers, variable binding, multi-place relations, model-theoretic structures, and first-order natural deduction.

[forall x: Calgary: An Introduction to Formal Logic (Open Logic Project / P. D. Magnus et al.)](https://forallx.openlogicproject.org/) - Continue into Parts IV through VII of this text to learn quantifier translation, first-order interpretations, and quantifier derivation rules in natural deduction.

[Language, Proof and Logic (CSLI Publications / Dave Barker-Plummer, Jon Barwise, & John Etchemendy)](https://books.google.com/books?isbn=9781575866321) - A standard alternative textbook that uses intuitive visual world-modeling to teach formal interpretations, counter-models, and first-order proofs.

[Introduction to Logic (Coursera / Stanford Online / Michael Genesereth)](https://www.coursera.org/learn/logic-introduction) - Complete the relational logic units of this course as an interactive digital companion to practice formalizing quantifiers and checking proofs.

[Logic I (MIT OpenCourseWare / Ephraim Glick)](https://ocw.mit.edu/courses/24-241-logic-i-fall-2009/) - Complete the predicate logic handouts and derivation problem sets from this course to solidify your technical mastery of models and formal derivations.

### Metatheory of First-Order Logic

Investigates the meta-logical properties of formal systems using mathematical proof methods, establishing the Soundness, Completeness, Compactness, and Löwenheim-Skolem theorems.

[Sets, Logic, Computation: An Open Introduction to Metalogic (Open Logic Project / Richard Zach et al.)](https://slc.openlogicproject.org/) - The primary open-access textbook for intermediate logic, designed to follow forall x with accessible, step-by-step proofs of soundness and Henkin completeness.

[A Mathematical Introduction to Logic (Academic Press / Herbert B. Enderton)](https://books.google.com/books?isbn=9780122384523) - A standard, rigorous alternative textbook for students who prefer a traditional, mathematically compact presentation of first-order metalogic and model theory.

[Logic I (MIT OpenCourseWare / Ephraim Glick)](https://ocw.mit.edu/courses/24-241-logic-i-fall-2009/) - Work through the final units on mathematical induction over formulas and the Soundness Theorem to bridge the transition from introductory logic to formal metalogic.

### Computability and Gödel's Incompleteness Theorems

Explores the formal limits of computation and deductive mathematical systems, covering Turing machines, the Halting Problem, formal arithmetic, Gödel numbering, and the First and Second Incompleteness Theorems.

[An Introduction to Gödel's Theorems (Logic Matters / Peter Smith)](https://www.logicmatters.net/igt/) - The primary open-access textbook for this stage, providing a patient, detailed, and mathematically rigorous walkthrough of formal arithmetic and both incompleteness theorems.

[Computability and Logic (Cambridge University Press / George S. Boolos, John P. Burgess, & Richard C. Jeffrey)](https://books.google.com/books?isbn=9780521701464) - A canonical alternative textbook that integrates computability theory, recursive functions, Turing machines, and incompleteness into a unified curriculum.

[Gödel's Proof (NYU Press / Ernest Nagel & James R. Newman)](https://books.google.com/books?isbn=9780814758373) - A compact conceptual overview to read before diving into the full technical proofs, outlining Hilbert's program and Gödel's core argumentative strategy.

[Theory of Computation (MIT OpenCourseWare / Michael Sipser)](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/) - A complete video lecture series covering Turing machines, decidability, and the Church-Turing thesis, establishing the computational framework underlying Gödelian incompleteness.

[Logic II (MIT OpenCourseWare / Vann McGee)](https://ocw.mit.edu/courses/24-242-logic-ii-spring-2004/) - A set of advanced lecture notes and problem sets examining computability, Robinson arithmetic, and Gödel's theorems from a formal logical and philosophical perspective.
