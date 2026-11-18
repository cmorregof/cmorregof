<div align="center">

# Carlos Manuel Orrego-Franco

Lecturer in Mathematics · M.Sc. candidate in Applied Mathematics<br>
Universidad Nacional de Colombia, Manizales<br>
Undergraduate degrees in Mathematics (with honors) and Computer Science

[Email](mailto:corregof@unal.edu.co) · [LinkedIn](https://www.linkedin.com/in/cmorregof) · [ORCID](https://orcid.org/0009-0001-9163-5137) · [OSF](https://osf.io/vr6wd)

</div>

---

I study one question about AI systems that do mathematics. How do we know that what a system formalizes or proves is what it meant, and what we meant?

In a proof assistant, a small trusted program called the kernel certifies the proof, but nobody certifies the statement. I call the missing property *adequacy*, in a sense close to Tarski's, and the field calls it *faithfulness*. It matters for oversight because a machine-checked proof tells us something about an AI system only when the statement is the one we asked for.

## Beyond the Lean Code Alone · [faithfulness](https://github.com/cmorregof/faithfulness)

Preprint with J. C. Riaño-Rojas and F. F. Serrano-Suárez. *Do frozen language models linearly separate faithful from unfaithful Lean 4 formalizations?* Code, decision rules and result files are in the repository.

We fit linear probes on the activations of frozen models. One probe reads the statement together with the Lean code, and the other reads the Lean code alone.

- On 450 formalizations from CriticLeanBench, a preregistered replication did not pass. A post hoc bootstrap puts the mean gap at +0.045 AUROC (95% CI [0.021, 0.069]) at a fixed layer, and at the last token the interval includes zero.
- On 377 minimal pairs certified by Lean, exploratory runs gave a positive gap in three of four models. Against the stronger of two surface controls, only one keeps a margin whose interval excludes zero.
- Shifting activations along the axis that separates the classes changes the model's answer more than 20 random directions do in two of four models, one of them post hoc.

These numbers come from a reference implementation written with AI coding assistants under rules I set, and the comparison with my implementation by hand is pending.

## Formal proof judges as reward · [prometeo](https://github.com/cmorregof/prometeo)

*Prometheus Unbound*, M.Sc. thesis.

On a university Isabelle benchmark, 6 of 220 validated (model, exercise) pairs depended on the model declaring the theorem as an axiom. A defect in my own harness rejected 218 lemma submissions in the memory condition only, and 184 passed after the fix. The main learning hypothesis came out null twice, and I reported it that way.

A confirmatory study is [preregistered on OSF](https://osf.io/w4eru). The article, *The Kernel Is Not the Judge*, is in preparation.

## Hefestus · [propose-decide-certify](https://github.com/cmorregof/propose-decide-certify)

*Language Models Propose Finite-Difference Schemes and Lean Certifies Their Stability*, with J. C. Riaño-Rojas. Code, approved Lean statements and benchmarks are in the repository.

## How I work

I write the decision rule before I see the results. When a hypothesis comes out null, I report it as null. I set the questions and the specifications, and I approve every formal statement before any proof is attempted. AI assistants write a good part of the code.

## Also

- I build MemorIA, a set of AI assistants for the administration of my faculty. The model reads and drafts, fixed rules verify, and people decide.
- I teach Numerical Analysis, Numerical Methods, Calculus and Introduction to Computer Science, with labs where students work alongside AI tools.
- I was accepted to the workshop *Bridging the LMFDB and Lean* at MIT in January 2027.

## Earlier work

Before this, I studied the latent representations of biological foundation models ([latent_geometry](https://github.com/cmorregof/latent_geometry), [FluGenome3D](https://github.com/cmorregof/FluGenome3D)) and language dynamics ([language_dynamics](https://github.com/cmorregof/language_dynamics)). One article is published in [*Life* 16(10):1724, 2026](https://doi.org/10.3390/life16101724). Papers on the Goldbach variance are submitted ([goldbach-variance](https://github.com/cmorregof/goldbach-variance)).
