This is a page that lists many useful links related to the [Lean Theorem Prover](http://leanprover.github.io/)

## Main links

* [Zulip](https://leanprover.zulipchat.com/): the Lean chatroom. Requires you to create an account. Ask any and all questions in the [new members stream](https://leanprover.zulipchat.com/#narrow/stream/113489-new-members)
* [Mathlib](https://github.com/leanprover-community/mathlib): the main library of Lean. Probably required for any nontrivial Lean project.
* [Lean 3 on Github](https://github.com/leanprover/lean): the current version of Lean.
* [Lean 4 on Github](https://github.com/leanprover/lean4): the next version of Lean.
* [Leanprover official website](http://leanprover.github.io/)

## Try Lean

* [Try Lean in your browser](https://leanprover.github.io/live/3.4.1/)
* [Try Lean + mathlib in your browser](https://leanprover-community.github.io/lean-web-editor/)

## Learning Lean

* [Kevin Buzzard's natural number game](http://wwwf.imperial.ac.uk/~buzzard/xena/natural_number_game/) is a online interactive tutorial to Lean.
* [Theorem Proving in Lean](https://leanprover.github.io/theorem_proving_in_lean/): a textbook to learn Lean with interactive code snippets.
* [Logic and Proof](https://leanprover.github.io/logic_and_proof/): a textbook that is a first rigorous proving course that teaches Lean at the same time.
* [Lean tutorial](https://github.com/leanprover-community/tutorials/blob/master/src/first_proofs.lean): a file with many descriptive comments.
* [Programming in Lean](https://leanprover.github.io/programming_in_lean): chapters 8 and 9 might be useful if you want to learn to write tactics.
* Ask questions in the [new members stream](https://leanprover.zulipchat.com/#narrow/stream/113489-new-members) on Zulip.

## Installation

You are strongly recommended to follow only the [installation instructions](https://github.com/leanprover-community/mathlib/blob/master/README.md) provided in the mathlib repository. (The installation instructions on the [downloads page](https://leanprover.github.io/download/) are not recommended). Here are the links to the OSs:
* On [Debian-derived Linux](https://github.com/leanprover-community/mathlib/blob/master/docs/install/debian.md) (Debian, Ubuntu, LMDE...)
* On [other Linux](https://github.com/leanprover-community/mathlib/blob/master/docs/install/linux.md)
* On [MacOS](https://github.com/leanprover-community/mathlib/blob/master/docs/install/macos.md)
* On [Windows](https://github.com/leanprover-community/mathlib/blob/master/docs/install/windows.md)

Don't forget to also follow the instructions on [Lean Projects](https://github.com/leanprover-community/mathlib/blob/master/docs/install/project.md).

* If you want to compile mathlib yourself (not recommended unless you only want to use very low-level files), you can skip the steps under *Installing mathlib supporting tools*. Compiling all of mathlib will probably take more than an hour.
* If you want to contribute to mathlib, [here](https://github.com/leanprover-community/mathlib/blob/master/docs/contribute/index.md) are some useful pointers.

## Reference
* [Lean Reference Manual](https://leanprover.github.io/reference/)
* [Lean tactics for Coq users](https://github.com/jldodds/coq-lean-cheatsheet)
* [tactics in mathlib](https://github.com/leanprover-community/mathlib/blob/master/docs/tactics.md)

## Community
* [Zulip](https://leanprover.zulipchat.com/) is where the main action happens.
* [leanprover-community website](https://leanprover-community.github.io/). This includes:
  - [Zulip archive](https://leanprover-community.github.io/archive/)
  - [Mathlib documentation](https://leanprover-community.github.io/mathlib_docs/)
* There are also discussions on the mathlib [issue tracker](https://github.com/leanprover-community/mathlib/issues) and [pull requests](https://github.com/leanprover-community/mathlib/pulls).
* [IMO Grand Challenge](https://imo-grand-challenge.github.io/): a grand challenge to write an AI that can write formal proofs of IMO problems.
<!-- [ProvingGround](http://siddhartha-gadgil.github.io/ProvingGround/) -->

## Lean Repositories / Papers using Lean
* The [core library](https://github.com/leanprover/lean/tree/master/library): ships with Lean.
* [mathlib](https://github.com/leanprover-community/mathlib): the main library of Lean ([paper](https://leanprover-community.github.io/papers/mathlib-paper.pdf)).
* [mathlib archive](https://github.com/leanprover-community/mathlib/tree/master/archive): some formalization projects maintained by mathlib maintainers.
* [Perfectoid Project](https://github.com/leanprover-community/lean-perfectoid-spaces): formalization of the definition of perfectoid spaces ([paper](https://arxiv.org/abs/1910.12320)).
* [Flypitch](https://github.com/flypitch/flypitch): Formalization of the independence of the continuum hypothesis ([paper 1](https://arxiv.org/pdf/1904.10570.pdf), [paper 2](https://github.com/flypitch/flypitch-cpp-2020/releases/tag/1.0)).
* Formalization of the [Cap set problem](https://github.com/lean-forward/cap_set_problem) ([paper](https://arxiv.org/abs/1907.01449)).
* [ModalTab](https://github.com/minchaowu/ModalTab): Verified decision procedures for modal logics ([paper](http://drops.dagstuhl.de/opus/volltexte/2019/11086/pdf/LIPIcs-ITP-2019-31.pdf)).
* [Alive in Lean](https://sf.snu.ac.kr/aliveinlean/): A Verified LLVM Peephole Optimization Verifier (repository + paper linked on that page)
* [Iterated chromatic localisation](https://github.com/NeilStrickland/itloc) with [corresponding paper](https://arxiv.org/abs/1907.07801).
* Feel free to add your repository if you've done something substantial in Lean.

## Papers about Lean
* [Counting Immutable Beans: Reference Counting Optimized for Purely Functional Programming](https://arxiv.org/abs/1908.05647): reference counting in Lean 4.
* [A metaprogramming framework for formal verification](https://dl.acm.org/citation.cfm?id=3110278): metaprogramming in Lean 3.
* [The Lean Theorem Prover (System Description)](https://link.springer.com/chapter/10.1007/978-3-319-21401-6_26): system description of Lean 2 ([pdf](https://kilthub.cmu.edu/articles/The_Lean_Theorem_Prover_system_description_/6492815/files/11937416.pdf))
* [Elaboration in Dependent Type Theory](https://arxiv.org/abs/1505.04324): elaboration in Lean 2.

## Lean 4
Lean 4 is the next version of Lean. It was made public early 2019, but is still missing certain core features as of October 2019 (such as a tactic framework)
* [Lean 4 on Github](https://github.com/leanprover/lean4): the next version of Lean.

## Misc
<!-- * link to various talks/papers on Lean 4 -->

## HoTT in Lean
Homotopy type theory is not actively maintained in Lean. Here are some pointers to projects:
* The [Lean 2 HoTT library](https://github.com/leanprover/lean2/blob/master/hott/hott.md).
* The [Spectral repository](https://github.com/cmu-phil/Spectral) in Lean 2, doing more synthetic homotopy theory and formalizing the Serre spectral sequence.
* The [Lean 3 HoTT library](https://github.com/gebner/hott3) (much smaller, not officially supported by Lean).
