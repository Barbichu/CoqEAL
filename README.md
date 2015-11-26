# CoqEAL - The Coq Effective Algebra Library

This repository contains a subset of the work that was developed in
the context of the ForMath european project (2009-2013).
This archive is split in four parts:

- `theory/` (package `CoqEAL_theory`), which contains  formal developments
  in algebra.

- `refinements/` (package `CoqEAL_refinements`), which  contains optimized
  algorithms with a framework to  ease change of representation during
  a proof.

- `v0.1/`, a previous version of the framework, for archiving purpose.

- `doc/`, `tools/` for generating documentation out of local documentation.

## Installation
Using OPAM, make sure that you added the Coq repository:

    opam repo add coq-released https://coq.inria.fr/opam/released

and run:

    opam install coq-coqeal-theory
    opam install coq-coqeal-refinements

## Authors

Guillaume Cano,  Cyril Cohen,  Maxime Dénès, Anders  Mörtberg and Vincent
Siles.
