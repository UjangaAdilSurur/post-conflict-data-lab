## Post-Conflict Data Lab

A simulation and empirical research project exploring economic recovery dynamics in post-conflict economies.

This lab moves from real-world data analysis to structural macroeconomic modeling, focusing on how war affects capital accumulation, productivity, and long-run equilibrium outcomes.

## Research Motivation

Post-conflict economies often experience:

Sudden capital destruction

Institutional breakdown

Human capital loss

Volatility in growth

Diverging long-run outcomes

## This project investigates:

How quickly economies recover after conflict

Whether recovery restores previous equilibrium levels

How structural productivity damage affects long-run output

## Project Structure
post-conflict-data-lab/
│

├── data/

│
├── rwanda_gdp_growth.csv

│
└── bosnia_gdp_growth.csv
│

├──
notebooks/
│
├── rwanda_recovery_analysis.ipynb
│
├── rwanda_vs_bosnia.ipynb
│  
├── recovery_speed_analysis.ipynb
│ 
├── reconstruction_simulator.ipynb
│
├── solow_war_simulation.ipynb
│
└── solow_productivity_shock.ipynb
│

├── images/

└── README.md

## 1. Empirical Recovery Analysis

Using World Bank GDP growth data, we:

Visualized post-conflict growth trajectories for Rwanda and Bosnia

Identified contraction troughs

Compared rebound patterns

This stage provided empirical grounding before simulation.

## 2. Recovery Speed Metrics

We developed quantitative metrics to measure:

Years to return to positive growth

Years to sustained recovery

Comparison to pre-conflict baseline averages

This moved the analysis beyond visualization into measurable recovery dynamics.

## 3. Reconstruction Simulation

A deterministic growth simulation model was built to test:

Different reconstruction intensities

Temporary growth boosts

Fading instability

## Key insight:
Small differences in post-conflict growth rates compound into large long-run output gaps.

4. Calibrated Solow War-Shock Model

We implemented a structural Solow growth model:

𝑌
𝑡
=
𝐾
𝑡
𝛼
Y
t
	​

=K
t
α
	​

𝐾
𝑡
+
1
=
𝑠
𝑌
𝑡
+
(
1
−
𝛿
)
𝐾
𝑡
K
t+1
	​

=sY
t
	​

+(1−δ)K
t
	​


## Key features:

Steady-state calibration

40% capital destruction shock

Transitional recovery paths

Savings-rate sensitivity

This introduced equilibrium-based recovery dynamics.

5. Productivity Shock & Hysteresis

We extended the Solow framework to include productivity 
𝐴
A:

𝑌
𝑡
=
𝐴
𝑡
𝐾
𝑡
𝛼
Y
t
	​

=A
t
	​

K
t
α
	​


We compared:

Temporary productivity loss

Permanent productivity loss

## Key insight:

Temporary capital shocks allow full recovery

Permanent productivity damage lowers steady-state capital and output

Institutional scarring creates long-run output gaps

Core Economic Insights

Capital destruction alone does not guarantee permanent output loss.

Permanent productivity damage shifts equilibrium downward.

Higher savings accelerates convergence but cannot fully offset structural scarring.

Institutional recovery is as important as physical reconstruction.

## Tools Used

Python

NumPy

Pandas

Matplotlib

Jupyter Notebook

## Future Extensions

Endogenous savings behavior

Government reconstruction financing

Debt-growth tradeoffs

Population growth integration

Multi-country calibration using real GDP levels
