# Gillespie Algorithm for Stochastic Gene Expression

## Introduction

This project implements the Gillespie algorithm to model the stochastic process of gene transcription into mRNA. The inherent randomness of mRNA production and degradation is captured through computational simulations using Python. By analyzing the temporal behavior of mRNA molecules, this study provides valuable insights into gene expression dynamics.
![_- visual selection](https://github.com/user-attachments/assets/5b032ddc-0052-4e92-96a9-6913c15a8785)
## Why is This Analysis Important?

**1. Capturing Stochasticity in Biology:** Traditional deterministic models often overlook the random fluctuations in biological systems. Stochastic modeling bridges this gap.
**2. Understanding Gene Regulation:** Helps researchers explore how genes are expressed under different cellular conditions.
**3. Application in Synthetic Biology:** Provides a framework for designing genetic circuits and understanding noise in gene expression.

## Methodology
### Step 1: Stochastic Simulation Algorithm (SSA)
1. The Gillespie algorithm simulates the stochastic nature of mRNA transcription and degradation.
2. **Reactions:**
   
   i. mRNA Production: Gene → Gene + mRNA (transcription)
   
   ii. mRNA Degradation: mRNA → ∅ (degradation)
4. Reaction propensities determine the probability of each reaction occurring at a given time.

### Step 2: Running the Simulation
1. The algorithm iterates through randomly selected reaction events based on probability distributions.
2. Tracks changes in mRNA count over time.

### Step 3: Data Analysis and Visualization
1. The time evolution of mRNA levels is plotted.
2. Fluctuations are analyzed to understand variability in gene expression.

## Key Insights
**1. **Gene Expression is Highly Variable:**** Stochastic effects cause significant fluctuations in mRNA levels, even under identical conditions.

**2. **Burst-Like Transcription Patterns:**** Observed periods of rapid mRNA production followed by degradation events.

**3. **Impact of Reaction Rates:**** Small changes in transcription/degradation rates dramatically affect overall expression levels.

**4. **Real-World Implications:**** Supports the need for probabilistic models in synthetic biology and disease research.

## Results and Discussion
**1. Time-Series Plots:** Visualizations confirm the stochastic fluctuations in mRNA count.

**2. Comparison to Deterministic Models**: Shows that ignoring stochastic effects can lead to oversimplified interpretations of gene regulation.

**3. Practical Relevance:** The findings emphasize the importance of modeling biological noise, particularly in single-cell gene expression studies.



