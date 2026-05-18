# Cosmic Anisotropy AIP

This repository accompanies the manuscript:

**Is Cosmic Anisotropy Physically Interpretable?  
A Non-Identifiability Framework via Selection Geometry and Geometry-Preserving Nulls**

## Official Manuscript and Record

The full manuscript is available on Zenodo:

https://zenodo.org/records/20190296

## Overview

This repository presents the **Anisotropy Identifiability Protocol (AIP)**, a null-hierarchy framework for testing whether an apparent cosmic anisotropy signal remains physically interpretable after the survey selection geometry is preserved.

The central issue is not simply whether anisotropy is detected.  
The key question is whether the physical origin of the signal is identifiable.

## Key Result

In the analyzed void-based anisotropy statistic:

- The observed anisotropy statistic is approximately **A_obs ≈ 0.646**.
- Under the naive L1 null, the signal appears strongly anomalous.
- In the independent VoidFinder validation, the signal shows **L1 z ≈ 6.51**.
- Under the geometry-preserving L2 null, the same signal becomes statistically consistent, with **L2 z ≈ 0.05**.

This indicates that an apparent high-significance anisotropy signal can lose physical interpretability once the data-generating survey geometry is preserved.

## Core Concept

A direction-dependent statistic can appear physically meaningful under an insufficient null model.

However, when the null model preserves the survey footprint, radial selection, and observational geometry, the same statistic may become statistically consistent with the null expectation.

This creates a case of **generative ambiguity**:

> The same observed anisotropy statistic may be produced either by intrinsic cosmic structure or by the geometry of the catalog construction itself.

The AIP framework is designed to test this distinction before assigning physical meaning to a directional cosmological signal.

## Anisotropy Identifiability Protocol

The AIP framework uses a null hierarchy:

- **L1 null**: naive random baseline
- **L2 null**: geometry-preserving null that retains survey footprint and radial selection
- **L3 null**: structure-preserving or higher-order diagnostic null

A signal should not be interpreted as physically meaningful unless it remains distinguishable under geometry-preserving validation.

## Applications

The manuscript includes:

- cosmic void anisotropy analysis
- geometry-preserving null tests
- independent VoidFinder validation
- angular-radial decomposition
- mask-sensitivity checks
- isotropic mock comparisons
- Pantheon+ H0-proxy extension

## Keywords

Cosmic anisotropy, non-identifiability, selection geometry, geometry-preserving nulls, survey systematics, cosmic voids, large-scale structure, VoidFinder, Pantheon+, Hubble tension, null hierarchy, Anisotropy Identifiability Protocol, AIP.

## Citation

If you refer to this work, please cite the Zenodo record:

https://zenodo.org/records/20190296

## License

This repository is released under the MIT License.
