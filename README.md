This is a page that lists many useful links related to the [Lean Theorem Prover](http://leanprover.github.io/)

<!-- update table of contents using: https://imthenachoman.github.io/nGitHubTOC/ -->
  <!-- - [Main links](#main-links)
  - [Try Lean](#try-lean)
  - [Learn Lean](#learn-lean)
  - [Installation](#installation)
  - [Reference](#reference)
  - [Community](#community)
  - [FAQs](#faqs)
  - [Lean Repositories / Papers using Lean](#lean-repositories--papers-using-lean)
  - [Papers about Lean](#papers-about-lean)
  - [Lean 4](#lean-4)
  - [Misc](#misc)
  - [HoTT in Lean](#hott-in-lean) -->

## Main links

* [Zulip](https://leanprover.zulipchat.com/): the Lean chatroom. Requires you to create an account. Ask any and all questions in the [new members stream](https://leanprover.zulipchat.com/#narrow/stream/113489-new-members).
* [Mathlib](https://github.com/leanprover-community/mathlib): the main library of Lean. Probably required for any nontrivial Lean project.
* [Lean 3 on Github](https://github.com/leanprover/lean): the official current (frozen) version of Lean.
* [Lean 3 Community Edition](https://github.com/leanprover-community/lean/): a fork of the frozen Lean 3 repository maintained by the mathlib team.
* [Lean 4 on Github](https://github.com/leanprover/lean4): the next version of Lean under development.
* [Leanprover official website](http://leanprover.github.io/).

## Try Lean

* [Try Lean in your browser](https://leanprover.github.io/live/3.4.1/).
* [Try Lean + mathlib in your browser](https://leanprover-community.github.io/lean-web-editor/).

## Learn Lean

* [Kevin Buzzard's natural number game](http://wwwf.imperial.ac.uk/~buzzard/xena/natural_number_game/) is a online interactive tutorial to Lean.
* [Theorem Proving in Lean](https://leanprover.github.io/theorem_proving_in_lean/): a textbook to learn Lean with interactive code snippets.
* [Logic and Proof](https://leanprover.github.io/logic_and_proof/): a textbook that is a first rigorous proving course that teaches Lean at the same time.
* [Logical Verification in Lean (pdf)](https://github.com/blanchette/logical_verification_2019/raw/master/logical_verification_in_lean.pdf): course notes for a [course](https://lean-forward.github.io/logical-verification/2019/index.html) at VU Amsterdam.
* [Video tutorial](https://av-media.vu.nl/VUMedia/Play/27894c3a8a4d4768a0421f62e5345a6c1d) of type theory and Lean.
* [Lean tutorial](https://github.com/leanprover-community/tutorials/blob/master/src/first_proofs.lean): a file with many descriptive comments.
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

## Reference material
* [Lean Reference Manual](https://leanprover.github.io/reference/).
* [Mathlib documentation](https://leanprover-community.github.io/mathlib_docs/)
* [Lean tactics for Coq users](https://github.com/jldodds/coq-lean-cheatsheet).
* [Tactics in mathlib](https://github.com/leanprover-community/mathlib/blob/master/docs/tactics.md).

## Community
* [Zulip](https://leanprover.zulipchat.com/) is a chat room where most of the action happens.
* [leanprover-community website](https://leanprover-community.github.io/). This includes:
  - [Zulip archive](https://leanprover-community.github.io/archive/)
  - [Mathlib documentation](https://leanprover-community.github.io/mathlib_docs/)
* There are also discussions on the mathlib [issue tracker](https://github.com/leanprover-community/mathlib/issues) and [pull requests](https://github.com/leanprover-community/mathlib/pulls).
* [IMO Grand Challenge](https://imo-grand-challenge.github.io/): a grand challenge to write an AI that can write formal proofs of IMO problems.

## FAQs

* [FAQ of the Lean 3 repository](https://github.com/leanprover/lean/blob/master/doc/faq.md)
* [FAQ in this repository](FAQ.md) (currently empty)

## How to Write Lean Tactics
* [Tactics writing tutorial](https://github.com/leanprover-community/mathlib/blob/master/docs/extras/tactic_writing.md)
* [Programming in Lean](https://leanprover.github.io/programming_in_lean): chapters 8 and 9 might be useful if you want to learn to write tactics.

## Papers about Lean
* [Official list of publications](https://leanprover.github.io/publications/)
* [The Type Theory of Lean](https://github.com/digama0/lean-type-theory/releases): Meta-theoretic properties, including soundness, of Lean 3.
* [Counting Immutable Beans: Reference Counting Optimized for Purely Functional Programming](https://arxiv.org/abs/1908.05647): reference counting in Lean 4.
* [A metaprogramming framework for formal verification](https://dl.acm.org/citation.cfm?id=3110278): metaprogramming in Lean 3.
* [Congruence Closure in Intensional Type Theory](https://leanprover.github.io/papers/congr.pdf): congruence closure in Lean 3.
* [The Lean Theorem Prover (System Description)](https://link.springer.com/chapter/10.1007/978-3-319-21401-6_26): system description of Lean 2 ([pdf](https://kilthub.cmu.edu/articles/The_Lean_Theorem_Prover_system_description_/6492815/files/11937416.pdf))
* [Elaboration in Dependent Type Theory](https://arxiv.org/abs/1505.04324): elaboration in Lean 2.

## Lean Repositories
* The [core library](https://github.com/leanprover/lean/tree/master/library): ships with Lean.
* [mathlib](https://github.com/leanprover-community/mathlib): the main library of Lean ([paper](https://arxiv.org/abs/1910.09336)).
* [mathlib archive](https://github.com/leanprover-community/mathlib/tree/master/archive): some formalization projects maintained by mathlib maintainers.
* [Perfectoid Project](https://github.com/leanprover-community/lean-perfectoid-spaces): formalization of the definition of perfectoid spaces ([paper](https://arxiv.org/abs/1910.12320)).
* [Flypitch](https://github.com/flypitch/flypitch): Formalization of the independence of the continuum hypothesis ([website](https://flypitch.github.io/), [paper 1](https://arxiv.org/pdf/1904.10570.pdf), [paper 2](https://github.com/flypitch/flypitch-cpp-2020/releases/tag/1.0)).
* Formalization of the [Cap set problem](https://github.com/lean-forward/cap_set_problem) ([paper](https://arxiv.org/abs/1907.01449)).
* [ModalTab](https://github.com/minchaowu/ModalTab): Verified decision procedures for modal logics ([paper](http://drops.dagstuhl.de/opus/volltexte/2019/11086/pdf/LIPIcs-ITP-2019-31.pdf)).
* [Developing Bug-Free Machine Learning Systems With Formal Mathematics](https://github.com/dselsam/certigrad) ([paper](https://arxiv.org/abs/1706.08605)).
* [Alive in Lean](https://github.com/microsoft/aliveinlean): A Verified LLVM Peephole Optimization Verifier ([website](https://sf.snu.ac.kr/aliveinlean/), [paper](https://sf.snu.ac.kr/publications/aliveinlean.pdf)).
* [Iterated chromatic localisation](https://github.com/NeilStrickland/itloc) ([paper](https://arxiv.org/abs/1907.07801)).
* [Data types as quotients of polynomial functors](https://github.com/avigad/qpf) ([paper](https://www.andrew.cmu.edu/user/avigad/Papers/qpf.pdf)).
* [Verified Decision Procedures for Modal Logics](https://github.com/minchaowu/ModalTab) ([paper](http://drops.dagstuhl.de/opus/volltexte/2019/11086/pdf/LIPIcs-ITP-2019-31.pdf)).
* [A bi-directional extensible ad hoc interface between Lean and Mathematica](https://github.com/robertylewis/mathematica) ([website](https://robertylewis.com/leanmm/), [paper](https://robertylewis.com/leanmm/lean_mm.pdf)).
* [Schemes in Lean](https://github.com/ramonfmir/lean-scheme) ([project report](https://www.imperial.ac.uk/media/imperial-college/faculty-of-engineering/computing/public/1819-ug-projects/Fernandez-I-MirR-Schemes-in-Lean.pdf)).
* This list is likely incomplete!

### Papers using Lean without dedicated repository
* [Formalizing computability theory via partial recursive functions](https://arxiv.org/abs/1810.08380). The formalization is in [mathlib/computability](https://github.com/leanprover-community/mathlib/tree/master/src/computability).
* [A formal proof of Hensel's lemma over the p-adic integers](https://robertylewis.com/padics/padics.pdf) ([website](https://robertylewis.com/padics/), the [formalization](https://github.com/leanprover-community/mathlib/tree/master/src/data/padics) is part of mathlib).
* [Arithmetic and Casting in Lean](https://lean-forward.github.io/internships/arithmetic_and_casting_in_lean.pdf): A description of the [`norm_cast` tactic](https://github.com/leanprover-community/mathlib/blob/master/src/tactic/norm_cast.lean) in mathlib.
* More reports/theses are listed on the [Lean Forward project page](https://lean-forward.github.io/#papers).

## Conferences
* [Lean Together 2019](https://lean-forward.github.io/lean-together/2019/) ([recorded videos](https://lean-forward.github.io/lean-together/2019/#videos))
* [Lean Together 2020](http://www.andrew.cmu.edu/user/avigad/meetings/fomm2020/)

## Lean 4
Lean 4 is the next version of Lean. It was made public early 2019, but is still missing certain core features as of October 2019 (such as a tactic framework)
* [Lean 4 on Github](https://github.com/leanprover/lean4): the source code.
* [Lean 4: a guided preview](http://leanprover.github.io/talks/vu2019.pdf): a presentation about Lean 4 at Lean Together 2019.
* [Counting Immutable Beans: Reference Counting Optimized for Purely Functional Programming](https://arxiv.org/abs/1908.05647): reference counting in Lean 4.

<!-- ## Misc -->
<!-- * [ProvingGround](http://siddhartha-gadgil.github.io/ProvingGround/) -->

## HoTT in Lean
[Homotopy type theory](https://homotopytypetheory.org/book/) is not actively maintained in Lean. Here are some pointers to past projects:
* The [Lean 2 HoTT library](https://github.com/leanprover/lean2/blob/master/hott/hott.md).
* The [Spectral repository](https://github.com/cmu-phil/Spectral) in Lean 2, doing more synthetic homotopy theory and formalizing the Serre spectral sequence.
* The [Lean 3 HoTT library](https://github.com/gebner/hott3) (much smaller, not officially supported by Lean).

### Papers using Lean 2
* [Constructing the Propositional Truncation using Non-recursive HITs](https://arxiv.org/abs/1512.02274) ([code](https://github.com/fpvandoorn/leansnippets/blob/master/cpp.hlean)).
* [The Cayley-Dickson Construction in Homotopy Type Theory](https://arxiv.org/abs/1610.01134) ([code](https://github.com/leanprover/lean2/blob/master/hott/homotopy/imaginaroid.hlean)).
* [The real projective spaces in homotopy type theory](https://arxiv.org/abs/1704.05770) ([code](https://github.com/cmu-phil/Spectral/blob/master/homotopy/realprojective.hlean)).
* [Higher Groups in Homotopy Type Theory](https://arxiv.org/abs/1802.04315) ([code](https://github.com/cmu-phil/Spectral/blob/master/higher_groups.hlean)).
