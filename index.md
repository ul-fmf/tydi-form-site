---
layout: page
title: TyDiForm
---

# About the project

TydiForm focuses on designing and implementing new techniques for formal verification of mathematics with the aim of improving the capabilities of proof assistants. In the project, we will build on the natural synergy between formalized mathematics and databases of mathematical structures, develop domain-specific type theories and type systems for programming languages.

Project information:

* Title: _Type Theory for Data-Intensive Formalization_ (TydiForm)
* Funding: Air Force Office of Scientific Research (AFOSR)
* Project number: FA9550-21-1-0024
* Project duration: 5 years (november 2020 -- october 2025)
* Host: [Faculty of mathematics and physics](https://www.fmf.uni-lj.si/si/), University of Ljubljana

## Formalized mathematics and databases of mathematical structures

Formalized mathematics is mathematical knowledge presented in a form that can be processed and verified by proof assistants, which check correctness of all the reasoning steps. Libraries of formalized mathematics collect and curate definitions, theorems, and proofs from various branches of mathematics.

Apart from proving theorems, mathematicians also curate large collections of mathematical structures, which are used for mathematical exploration, hypothesis testing, and discovery of new mathematical laws. These collections are generated with computers, but rarely formally verified by computers.

In this project, we will apply mathematical formalization methods to these collections, thereby granting an assurance of their correctness, as well as enable further exploration and analysis. We will also facilitate incorporation of such databases into proof assistants, enabling heuristic checking of statements, automatic generation of hypotheses, and guidance of proof search.

## Domain-specific type theories

Most formalized mathematics is written in one of many flavors of type theory. Ordinarily, a type theory is designed to be general and very expressive, so that it can incorporate most, if not all mathematics. However, databases of mathematical structures are almost always narrowly specialized, e.g., they contain just graphs, or just finite groups. To make formal processing of such databases efficient, we will design domain-specific type theories that aim to be small and tailored for representation and verification of large databases of mathematical structures.  We will also design and implement transformations between type theories that will allow the databases to be interfaced with proof assistants and other tools for formal reasoning.

The domain-specific type theories will have other uses in formalized mathematics as well. They can be used to express auxiliary notions of type theory, such as universe levels and induction schemata, and to give modular and reusable implementations of automated reasoning algorithms.

## Type systems for programming languages

A second goal of the project is the development of novel type systems for programming languages with low-level real-world computational effects that exhibit asynchronous, stochastic, or even quantum-mechanical behavior. We shall adapt and extend algebraic effect systems, which have so far been used successfully to describe computational effects as a programming technique for implementation of effects within a language. The results will improve our ability to design and verify the interaction of programs with their external environments.
