---
title: "Applying statistical methods to teaching problems"
excerpt: "Using research methods to give quantitative guidance in undergraduate laboratories"
collection: research
---

Using Bayesian inference and model selection (a form of A\/B testing), it is possible to identify when commonly-made approximations made in undergraduate labs fail.

To begin with, I consider the simple pendulum. In introductory laboratories, the small-angle approximation is commonly used and textbooks such as Giancoli's Physics recommend
that the initial displacement of the pendulum not exceed 15 degrees so that the small-angle approximation is applicable. This is derived from the deviation of the small angle approximation sin\(theta in radians\) is approximately theta when theta is small. At 15 degrees displacement, the difference between the approximation and the exact result deviates by 1 percent.

If students with realistic measurement uncertainty can't hope to measure this 1 percent deviation, then this guidance is not data-driven. I used Bayesian inference to determine the biasing effect of the small angle approximation and when the deviation from the approximation becomes sufficiently strongly measurable as to necessitate a different calculation. The goal of the inverse problem posed here was to accurately infer the true value of the gravitational acceleration for a frictionless simple pendulum of known length.

Natural extensions for this work include adding friction to the pendulum and deformation in the string, which are beyond the scope of an introductory physics course, but represent opportunities for teaching sophisticated data analysis techniques in upper-year courses with a familiar example. In service of this goal, the existing 1-parameter study with the simple pendulum was designed as a tutorial in rigorously-defined statistical modeling that may easily be extended to other problems.

[View the pre-print on the arXiv](https://arxiv.org/abs/2104.08621)
