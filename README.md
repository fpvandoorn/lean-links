This is a page that lists many useful links related to the [Lean Theorem Prover](http://leanprover.github.io/)

## Important

* [Leanprover official website](http://leanprover.github.io/)
* [Mathlib](https://github.com/leanprover-community/mathlib): the main library of Lean. Probably required for any nontrivial Lean project.
* [Zulip](https://leanprover.zulipchat.com/): the Lean chatroom. Requires you to create an account. Ask any and all questions in the [new members stream](https://leanprover.zulipchat.com/#narrow/stream/113489-new-members)
* [Lean 3 on Github](https://github.com/leanprover/lean)
* [Lean 4 on Github](https://github.com/leanprover/lean4): the next version of Lean.

## Installation

You are strongly recommended to follow only the [installation instructions](https://github.com/leanprover-community/mathlib/blob/master/README.md) provided in the mathlib repository. (The installation instructions on the [downloads page](https://leanprover.github.io/download/) are not recommended). Here are the links to the OSs:
* On [Debian-derived Linux](https://github.com/leanprover-community/mathlib/blob/master/docs/install/debian.md) (Debian, Ubuntu, LMDE...)
* On [other Linux](https://github.com/leanprover-community/mathlib/blob/master/docs/install/linux.md)
* On [MacOS](https://github.com/leanprover-community/mathlib/blob/master/docs/install/macos.md)
* On [Windows](https://github.com/leanprover-community/mathlib/blob/master/docs/install/windows.md)

Don't forget to also follow the instructions on [Lean Projects](https://github.com/leanprover-community/mathlib/blob/master/docs/install/project.md).

* If you want to compile mathlib yourself (not recommended), you can skip the steps under *Installing mathlib supporting tools*. Compiling mathlib will take about an hour.
* If you want to contribute to mathlib, [here](https://github.com/leanprover-community/mathlib/blob/master/docs/contribute/index.md) are some useful pointers.

## Tutorials


## Lean Repositories
* The [core library](https://github.com/leanprover/lean/tree/master/library): ships with Lean.
* [mathlib](https://github.com/leanprover-community/mathlib): the main library of Lean.
* [mathlib archive](https://github.com/leanprover-community/mathlib/tree/master/archive): some formalization projects maintained by mathlib maintainers.
* [Perfectoid Project](https://github.com/leanprover-community/lean-perfectoid-spaces): formalization of the definition of perfectoid spaces.
* [Flypitch](https://github.com/flypitch/flypitch): Formalization of the independence of the continuum hypothesis.
* Formalization of the [Cap set problem](https://github.com/lean-forward/cap_set_problem).
* [ModalTab](https://github.com/minchaowu/ModalTab): Verified decision procedures for modal logics.
<!-- Sensitivity project intentionally left out as it is PR'd to archive. -->
* Feel free to add your repository if you've done something substantial in Lean.

## Information on Lean 4

## Known Bugs
* variable `a` bug.
* type-class inference has exponential slowdown.
* Lean sometimes crashes on unexpected input.

## HoTT in Lean

Homotopy type theory is not actively maintained in Lean. Here are some pointers to projects:
* The [Lean 2 HoTT library](https://github.com/leanprover/lean2/blob/master/hott/hott.md).
* The [Spectral repository](https://github.com/cmu-phil/Spectral) in Lean 2, doing more synthetic homotopy theory and formalizing the Serre spectral sequence.
* The [Lean 3 HoTT library](https://github.com/gebner/hott3) (much smaller, not officially supported by Lean).

## To sort
* [leanprover-community website](https://leanprover-community.github.io/) and [Zulip archive](https://leanprover-community.github.io/archive/)