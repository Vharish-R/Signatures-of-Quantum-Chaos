# Signatures of Quantum Chaos in Random Optical Networks
## Overview
This project investigates the probability densities of possible outputs from Gaussian Boson Sampling (GBS), one of the main models used to demonstrate quantum computational advantage. We investigate the distributions produced by injecting squeezed states into randomly selected optical networks, and analyse the effects on this distribution when key variables such as the squeezing amplitude and the transmission coefficient are altered.

Given that GBS has recently proven highly useful as an analogue quantum device for solving problems in graph theory, drug discovery, and artificial intelligence, understanding its chaotic signatures and its robustness to noise is important.

## Key Elements
- Gaussian Boson Sampling: Consists of injecting squeezed vacuum states into an optical network, as opposed to standard Boson Sampling which relies on single-photon Fock states that are experimentally difficult to generate.

- Quantum Chaos: By measuring the output probabilities of multiple Haar-random optical networks and plotting their probability density, we observe the emergence of the Porter-Thomas distribution, a definitive signature of quantum chaos.

- Environmental Decoherence: To accurately reflect realistic experimental conditions, we must model uniform photon loss, which inevitably degrades quantum correlations.

- Robustness Analysis: Calculated the Total Variation Distance (TVD) to measure how far the lossy system deviates from the ideal chaotic regime.

<img width="1788" height="1405" alt="Porter-Thomas_Distr" src="https://github.com/user-attachments/assets/ec727fbd-6ff6-423c-93c4-1f35c87476e5" />

## Conclusion
Through this simulation of Gaussian Boson Sampling across Haar-random linear optical networks, it is verified that multiphoton interference yields a Porter-Thomas output distribution, a key hallmark of quantum chaos. This balance between input non-classicality and environmental loss is critical for the engineering and scaling of practical GBS devices.
