# Clinical AI Defer

Reliability-aware prediction under information degradation and cross-center shift.

## Overview

Clinical AI systems can become unreliable when patient information is incomplete, corrupted, or collected at a different medical center. This project investigates when a predictive model should make a decision and when it should defer the case to a clinician.

The accompanying notebook contains the complete experimental workflow, including data preparation, model evaluation, reliability analysis, and result generation.

## Research Goals

- Measure predictive performance under increasing information degradation.
- Evaluate generalization across clinical centers.
- Identify uncertain or high-risk predictions that should be deferred.
- Study the trade-off between coverage and reliability.
- Support safer human–AI collaboration in clinical decision-making.

## Methodology

The analysis compares model predictions across different degradation levels and center shifts. A reliability-aware deferral strategy retains sufficiently reliable predictions while referring uncertain cases for expert review.

Key evaluation concepts include:

- Predictive discrimination and classification performance
- Calibration and uncertainty
- Selective prediction and coverage
- Risk after deferral
- Cross-center robustness

## Repository Contents

- Jupyter notebook containing the analysis and results
- Generated figures, tables, or other experiment outputs
- This README with project documentation

## Running the Notebook

1. Clone this repository:

   ```bash
   git clone https://github.com/USERNAME/clinical-ai-defer.git
   cd clinical-ai-defer
   ```

2. Create a Python environment and install the packages imported by the notebook.

3. Start Jupyter:

   ```bash
   jupyter notebook
   ```

4. Open the project notebook and run its cells in order.

Update `USERNAME` in the clone URL with the GitHub account that owns the repository.

## Results

The notebook provides the authoritative experimental results. It reports how performance changes under degraded inputs and cross-center evaluation, along with the effect of deferring less reliable predictions.

## Intended Use

This repository is intended for research and educational purposes. It is not a certified medical device and must not be used as a substitute for professional clinical judgment.

## License

Add an appropriate open-source license before redistributing or reusing the project.
