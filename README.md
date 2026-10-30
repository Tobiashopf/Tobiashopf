# Hi, I'm Tobias 👋

I work on imitation learning and evaluation of sequential decision problems, mostly in
Python, PyTorch and NumPy. I care less about training bigger models and more about
measuring honestly whether a problem is hard: analytic floors instead of measured
baselines, the expected value of the chosen action instead of the realized reward, and a
power analysis before believing any difference.

Most of my professional work lives in private repositories, so this profile shows
public, rebuilt-from-scratch versions of the kinds of problems I work on.

## Featured project

**[decision-benchmark-screening](https://github.com/Tobiashopf/decision-benchmark-screening)**:
a harness that checks whether an evaluation task for decision-making agents is actually
hard *before* you spend weeks building it. Build the strongest cheap attacker first, and
kill the design if the attacker ties your intended method.
Paired tests on shared seeds, minimum detectable effect, and a verdict that refuses to
call a result the run could not have seen.

## What I work with

- **ML:** behavior cloning with DAgger, permutation-invariant (DeepSets-style) policies,
  distribution shift, why REINFORCE fails where long cloning works
- **Numerical engineering:** PyTorch → NumPy ports with numerical parity tests,
  profiling hot paths, the small details that flip actions (`torch.std` applies Bessel's
  correction and `numpy.std` does not)
- **Measurement:** benchmark design, statistical power, paired comparisons, Bayesian
  inference and approximate planning (lookahead, particle filters)

## Contact

- LinkedIn: https://www.linkedin.com/in/tobias-hopf-profissional/
- Email: tobiashopf0@gmail.com
