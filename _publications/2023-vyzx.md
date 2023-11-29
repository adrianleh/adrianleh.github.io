---
title: "VyZX: Formal Verification of a Graphical Quantum Language"
collection: publications
permalink: /publication/2023-vyzx
excerpt: 'Formalizing the ZX Calculus -- a graphical representation of quantum circuits -- in Coq'
date: 2019-09-30
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2311.11571'
citation: 'Adrian Lehmann, Ben Caldwell, Robert Rand (2023). "VyZX: Formal Verification of a Graphical Quantum Language". Preprint'
---
Mathematical representations of graphs often resemble adjacency matrices or lists, representations that facilitate whiteboard reasoning and algorithm design. In the realm of proof assistants, inductive representations effectively define semantics for formal reasoning. This highlights a gap where algorithm design and proof assistants require a fundamentally different structure of graphs, particularly for process theories which represent programs using graphs. To address this gap, we present VyZX, a verified library for reasoning about inductively defined graphical languages. These inductive constructs arise naturally from category theory definitions. A key goal for VyZX is to Verify the ZX-calculus, a graphical language for reasoning about quantum computation. The ZX-calculus comes with a collection of diagrammatic rewrite rules that preserve the graph's semantic interpretation. We show how inductive graphs in VyZX are used to prove the correctness of the ZX-calculus rewrite rules and apply them in practice using standard proof assistant techniques. VyZX integrates easily with the proof engineer's workflow through visualization and automation. 