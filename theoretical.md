# Theoretical CS Resource List

Theoretical CS is a branch of computer science that focuses on the mathematical aspects of CS.
In contrast to applied CS, that focuses more on solving real-life problems
and evaluates techniques mostly by experimentation, theoretical CS models problems abstractly
and gives mathematical proofs of efficiency of techniques.
For example, theoretical CS generally looks at worst-case time complexity of an algorithm
whereas most real-life applications worry about the average running time of an implementation of the algorithm.

TCS covers a wide variety of topics including
algorithms, data structures, computational complexity, parallel and distributed computation,
quantum computation, automata theory, information theory, cryptography,
program semantics and verification and theory of machine learning.

## Mathematical foundations for theoretical CS

- [MIT course on 'Math for CS'](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/):
    - This course covers the mathematical background required for studying algorithms
    (and theoretical CS in general).
    Topics covered are proof techniques, graph theory, combinatorics, recurrences and probability.
    - You should read the [lecture notes (pdf)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/readings/)
    and optionally watch the [video lectures](https://www.youtube.com/playlist?list=PLB7540DEDD482705B).

- Linear Programming: Must-know for people who want to study advanced algorithms or approximation algorithms
or those who want to do research in theoretical CS.
    - Lecture notes by Tim Roughgarden:
        - [lecture 1](http://timroughgarden.org/w16/l/l7.pdf): Introduction and Applications
        - [lecture 2](http://timroughgarden.org/w16/l/l8.pdf): Linear Programming Duality (Part 1)
        - [lecture 3](http://timroughgarden.org/w16/l/l9.pdf): Linear Programming Duality (Part 2)
        - [lecture 4](http://timroughgarden.org/w16/l/l10.pdf): The Minimax Theorem and Algorithms for Linear Programming
    - [How to find the dual of a complex linear program](http://www.cs.columbia.edu/coms6998-3/lpprimer.pdf):
        Useful if your linear program is hard to express in standard form.

## Theory of Computation

- \[book\] Elements of the Theory of Computation by Lewis and Papadimitriou:
    - The first 3 chapters: languages, finite automata and context-free languages
    (and probably the fourth chapter - on Turing machines) are very useful.
    - For the last 2 chapters, there are better alternatives in books on computational complexity.
    - The first 3 chapters are prerequisites for a course on compilers and
    they are also given more weight in BITS Pilani's Theory of Computation course.
    - This book is more mathematically rigorous than some other popular books on the same subject
    (which I think is a good thing, but YMMV).

## Algorithms

- \[book\] CLRS: Introduction to Algorithms by Cormen, Leiserson, Rivest, Stein:
    - The first 5 chapters will give you the bare-minimum foundation for understanding and analyzing algorithms.
    - Chapters 6 to 12, chapter 15 and 16 and the chapters on graph algorithms present
    well-known and frequently-used algorithms.
    These will familiarize you with techniques commonly used in designing and analyzing algorithms.
    - Solving the exercise problems is strongly recommended.
    Also, many of these problems (or their variants) are common interview questions.
    - You may read additional chapters as per you interest and need.
    - People interested in cryptography and competitive programming
    can read the chapter on number-theoretic algorithms.
    People interested in advanced algorithms and complexity theory should read the last 2 chapters:
    NP-completeness and approximation algorithms.

## Computational Complexity

- \[book\] [Computional Complexity by Arora and Barak](https://theory.cs.princeton.edu/complexity/book.pdf):
Great for taking a deep dive in complexity theory.
If you're only interested in NP-completeness and basic complexity classes,
the first 3 chapters will be sufficient.

## Others

- [TheoremDep](https://sharmaeklavya2.github.io/theoremdep/):
Large list of theorems commonly required in theoretical computer science.
- [Competitive programming](competitive.md) is a good way to hone your algorithmic problem-solving skill.
- Facility in linear algebra and probability is required for advanced algorithms
(see [maths.md](maths.md)).
- [Cryptography](cryptography.md) is also considered a part of theoretical CS.
- http://jroweboy.github.io/c/asm/2015/01/26/when-is-main-not-a-function.html
