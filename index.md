---
layout: default
title: DSC 180A Methodology Assignment 4
---

# Fiona Zou

**UCSD email:** `fzou@ucsd.edu`  
**Section:** D30 — LLM Steering  
**Mentor:** Tianhao Wang

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic to me is activation steering: changing a language model's internal activations to shift a behavior in a measurable direction. I’m especially interested in how affective dimensions such as valence, arousal, and dominance can be represented and steered, and whether a measured shift in those dimensions also changes a model’s reasoning or task performance.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

One possible direction is to test whether activation steering can make a language model less likely to simply endorse a user's preferred choice when giving decision advice. I would compare ordinary prompting with steering across a set of fictional scenarios, then evaluate both preference mirroring and advice quality using held-out cases and blinded ratings. This is a candidate for discussion, not a commitment to continue the exact Quarter 1 replication.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

I would make the evaluation more robust by comparing no-steering, random-direction, and steering conditions across more than one task or prompt set. I would also report both the intended activation or VAD shift and task outcomes such as answer validity and accuracy, so a behavioral change is not mistaken for an improvement if performance declines. The current replication is constrained by the available model and compute, so I would treat results as preliminary.

**4. What other techniques would you be interested in using in your project?**

I would be interested in combining sparse autoencoder feature analysis with causal interventions such as feature ablation or activation patching, then testing effects with controlled comparisons and confidence intervals. For advice-quality outcomes, blinded human ratings could complement automatic measures and show whether a numerical steering effect is meaningful to people.
