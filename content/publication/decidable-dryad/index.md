+++
title = "A Decidable Logic for Tree Data-Structures with Measurements"
date = 2019-01-01
authors = ["Xiaokang Qiu", "**Yanjun Wang**"]
publication_types = ["1"]
abstract = "We present Dryad_dec, a decidable logic that allows reasoning about tree data-structures with measurements. This logic supports user-defined recursive measure functions based on Max or Sum, and recursive predicates based on these measure functions, such as AVL trees or red-black trees. We prove that the logic's satisfiability is decidable. The crux of the decidability proof is a small model property which allows us to reduce the satisfiability of Dryad_dec to quantifier-free linear arithmetic theory which can be solved efficiently using SMT solvers. We also show that Dryad_dec can encode a variety of verification and synthesis problems, including natural proof verification conditions for functional correctness of recursive tree-manipulating programs, legality conditions for fusing tree traversals, synthesis conditions for conditional linear-integer arithmetic functions. We developed the decision procedure and successfully solved 220+ Dryad_dec formulae raised from these application scenarios, including verifying functional correctness of programs manipulating AVL trees, red-black trees and treaps, checking the fusibility of height-based mutually recursive tree traversals, and counterexample-guided synthesis from linear integer arithmetic specifications. To our knowledge, Dryad_dec is the first decidable logic that can solve such a wide variety of problems requiring flexible combination of measure-related, data-related and shape-related properties for trees."
featured = false
publication = "*20th International Conference on Verification, Model Checking, and Abstract Interpretation*"
publication_short = "VMCAI 2019"
url_preprint = "decidable_dryad.pdf"
url_slides = "vmcai.ppsx"
url_poster = "poster.pdf"
DOI = "/10.1007%2F978-3-030-11245-5_15"
+++

