---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# Add section to Activities

## Papers & talks

layout: page
---

## Project information

* Title: _Type Theory for Data-Intensive Formalization_ (TydiForm)
* Funding: Air Force Office of Scientific Research (AFOSR)
* Project number: FA9550-21-1-0024
* Project duration: 5 years (november 2020 -- october 2025)
* Host: [Faculty of mathematics and physics](https://www.fmf.uni-lj.si/si/), University of Ljubljana


## Resources

* [Eff programming language](https://www.eff-lang.org)
* [Andromeda proof assistant](https://www.andromeda-prover.org)
* [HoTT library](https://github.com/HoTT/HoTT)


## About the project

TydiForm focuses on designing and implementing new techniques for formal verification of mathematics with the aim of improving the capabilities of proof assistants. In the project, we will build on the natural synergy between formalized mathematics and databases of mathematical structures, develop domain-specific type theories and type systems for programming languages.

#### What is formalized mathematics?

Formalized mathematics is mathematical knowledge presented in a form that can be processed and verified by proof assistants, which check correctness of all the reasoning steps.

### The synergy between formalized mathematics and databases of mathematical structures

Apart from proving theorems, mathematicians also curate large collections of mathematical structures, which are used for mathematical exploration, hypothesis testing, and discovery of new mathematical laws. These collections are generated with computers, but rarely verified by computers. Applying mathematical formalization methods to these collections will grant an assurance of their correctness and enable further exploration and analysis. At the same time, this will allow us to incorporate the databases into proof assistants, enabling heuristic checking of statements, automatic generation of hypotheses, and guidance of proof search.

### Domain-specific type theories

The most successful collections of formalized mathematics are written in type theory, making  domain-specific type theories (i.e. for graph theory, finite groups, or combinatorics) a suitable language for presenting the specific content and structure of mathematical data. In TydiForm, we will design and implement transformations between type theories that will allow the databases to be interfaced with proof assistants and other tools for formal reasoning.

The domain-specific type theories will have other uses in formalized mathematics as well. They can be used to express auxiliary notions of type theory, such as universe levels and induction schemata, and to give modular and reusable implementations of automated reasoning algorithms.

### Type systems for programming languages

A second goal of the project is the development of novel type systems for programming languages with low-level real-world computational effects that exhibit asynchronous, stochastic, or even quantum-mechanical behavior. We shall adapt and extend algebraic effect systems, which have so far been used successfully to describe computational effects as a programming technique for implementation of effects within a language. The results will improve our ability to design and verify the interaction of programs with their external environments.
