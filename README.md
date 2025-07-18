# Formal Analysis of Real-World Security Protocols

This repository contains lecture slides from the course *Formal Analysis of Real-World Security Protocols*, originally offered at Saarland University in the 24/25 winter semester.

## Course book

David Basin, Cas Cremers, Jannik Dreier, and Ralf Sasse. **Modeling and Analyzing Security Protocols with Tamarin: A Comprehensive Guide**.

Available [online](https://tamarin-prover.com/book/index.html).

## Learning outcome

In this course, you will learn (1) about the symbolic model of cryptography, (2) how to read protocol specifications, (3) how to translate them into formal models, and (4) how to use a state-of-the-art verification tool, the [Tamarin prover](https://tamarin-prover.com/), to model and verify security properties of small to medium sized cryptographic protocols.

Topics include:
1. **The symbolic model of cryptography**: terms, term rewriting, equational theories, unification, term deduction, the Dolev-Yao model.
2. **Verification theory**: dependency graphs, constraint systems, constraint solving.
3. **The Tamarin prover**: multiset rewriting, facts, trace properties, custom threat models, predicates, restrictions, observational equivalence.

## Structure

| Lecture | Topic                                                                                                                                       | Book references |
| :-----: | :------------------------------------------------------------------------------------------------------------------------------------------ | :-------------- |
|     0   | [Organization and Motivation](./lecture_slides/slides/Lecture_00-Organization_and_Motivation.pdf)                                           | 1-2             |
|     1   | [Terms and Equational Theories](./lecture_slides/slides/Lecture_01-Terms_and_Equational_Theories.pdf)                                       | 3-3.1.4, 7      |
|     2   | [Protocols in the Symbolic Model](./lecture_slides/slides/Lecture_02-Protocols_in_the_Symbolic_Model.pdf)                                   | 3.1.5-3.2.1     |
|     3   | [Attacker Model and Trace Properties](./lecture_slides/slides/Lecture_03-Attacker_Model_and_Trace_Properties.pdf)                           | 3.2.2, 4, 5-5.8 |
|     4   | [Verification Theory (Part 1)](./lecture_slides/slides/Lecture_04-Verification_Theory_Part_1.pdf)                                           | 6-6.5           |
|     5   | [Verification Theory (Part 2)](./lecture_slides/slides/Lecture_05-Verification_Theory_Part_2.pdf)                                           | 6.6-6.8         |
|     6   | [Using Tamarin in Practice](./lecture_slides/slides/Lecture_06-Using_Tamarin_in_Practice.pdf)                                               | 11              |
|     7   | [Advanced Security Properties and Threat Models](./lecture_slides/slides/Lecture_07-Advanced_Security_Properties_and_Threat_Models.pdf)     | 5.9-5.10, 9-10  |
|     8   | [Advanced Features (Part 1)](./lecture_slides/slides/Lecture_08-Advanced_Features_Part_1.pdf)                                               | 8, 13-14        |
|     9   | [Advanced Features (Part 2)](./lecture_slides/slides/Lecture_09-Advanced_Features_Part_2.pdf)                                               | 16              |
|    10   | [Security Protocol Standards](./lecture_slides/slides/Lecture_10-Security_Protocol_Standards.pdf)                                           | 18              |
|    11   | [Relation to Cryptography, Scaling, and the Future](./lecture_slides/slides/Lecture_11-Relation_to_Cryptography_Scaling_and_the_Future.pdf) | 15              |

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License][cc-by]. All material by [Cas Cremers](https://cispa.saarland/group/cremers/) and [Aleksi Peltonen](https://peltona.github.io/).

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
