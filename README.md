# Affective Dynamics Under Contradictory Stimulation: A Stochastic Model


Reproduction code for the paper **"Affective Dynamics Under Contradictory Stimulation: A Stochastic Model"** (submitted to the *Journal of Artificial Societies and Social Simulation*, JASSS).

## Overview

This repository contains the Python implementation of the stochastic simulations presented in the paper. The model formalises how exposure to contradictory information—a hallmark of modern media ecosystems—shapes an individual's core affective state. Contradictory stimulation is operationalised as stochastic noise in the influence function of a continuous affective variable $x$, where $x>0$ represents positive affect, $x<0$ negative affect, and $x=0$ emotional neutrality.

## Figures generated

The script produces two figures from the paper:

| Figure | Description | File |
|--------|-------------|------|
| Fig. 8 | Trimodal distribution emerging from multiple stochastic parameters | `3picos.pdf` |
| Fig. 44 | Bimodal distribution with noise in both inertia and baseline | `noises_b_m.pdf` |

## Dependencies

- Python 3.7 or later
- `numpy`
- `scipy`
- `matplotlib`

Install with:

```bash
pip install numpy scipy matplotlib
