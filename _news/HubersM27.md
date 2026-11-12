---
title: *Normalization By Evaluation of Higher-Order Rows* accepted to CPP'27
date: 2026-11-11
author: Alex Hubers
layout: post
related_publications:
    HubersM27
---

My paper *Normalization by Evalution of Higher-Order Rows* has been accepted to [Certified Programs and Proofs (CPP) 2027](https://popl27.sigplan.org/home/CPP-2027), a conference colocated with POPL formal verification and certification. Preprint coming soon. The work gives a sound and complete equational theory for row types. We prove the theory is sound and complete by way of a *Normalization by Evaluation* (NbE) procedure that maps types to normal forms. We prove consistency (that every type is equivalent to its normal form) and soundness (that equivalent types have equal normal forms), which entails completeness. Combined with a syntactic equality check, type equivalence is constructively decidable: given types τ and υ, there is either (i) a derivation that Δ ⊢ τ ≡ υ : κ or (ii) a proof that no such derivation is possible. Along the way, we discover some neat hidden type equivalence rules necessary for normalization. For example, the type Π {l : {r : τ}} must reduce to {l : Π {r : τ}}.