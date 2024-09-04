# Econometric-Analysis-of-Pitch-Dynamics-and-Batter-Stance-in-Baseball

### Project Overview
This project investigates the relationship between pitch dynamics (lateral and vertical movement) and batter stance (left or right) on swing likelihood using Bayesian econometric models. The analysis aims to uncover the causal relationships between these variables and guide baseball strategy, providing insights for coaches and players on optimizing batting performance and pitching strategy.

The code for this project is currently housed in a private repository. If you would like access, please contact the project maintainer.

### Purpose of the Study
The purpose of this study is to:

Analyze how batter stance and pitch dynamics interact to affect swing decisions.
Understand how confounding variables like pitch type and the pitcher’s throwing hand influence these dynamics.
Provide actionable insights for baseball coaches and players to improve game strategy.

### Key Features
Bayesian econometric analysis of pitch dynamics and batter stance.
Utilization of posterior distributions to estimate the impact of predictors on swing likelihood.
Analysis of confounding variables, including pitch type and the pitcher’s hand.

### Libraries and Packages Used
Python: Core programming language for the project.
PyMC4: Used for Bayesian statistical modeling and MCMC sampling.
ArviZ: For exploratory analysis of Bayesian models and visualization of posterior distributions.
Pandas: Data manipulation and cleaning.
NumPy: Handling of numerical operations and random data generation.
Matplotlib: Visualization of results and graphical presentation of posterior distributions.

### Data
The dataset comprises pitch data from the Miami Marlins over three seasons.

### Key variables in the dataset:

stand: Represents the batter's stance (L for left, R for right).
pfx_x: Lateral movement of the pitch.
pfx_z: Vertical movement of the pitch.
pitch_type: Type of pitch thrown.
p_throws: The hand used by the pitcher (left or right).

### Methodology
Generative Model: Logistic regression to model the probability of a swing based on batter stance and pitch dynamics.
Sampling from Posterior Distribution: The Markov Chain Monte Carlo (MCMC) method was used to sample from the posterior distribution, offering insight into how each predictor affects the swing decision.
Posterior Interpretation: Posterior distributions provide the updated beliefs about model parameters after observing the data.

### Results
The study revealed key findings:

Right-handed batters generally exhibit a higher swing probability than left-handed batters.
Lateral pitch movement significantly affects swing decisions, with more movement reducing swing likelihood.
Vertical movement showed no consistent effect on swing probability.
For further details, refer to the project report or contact me olubayodeeben@gmail.com.

# How to Run the Code

Contact
For access to the repository or any questions regarding the project, feel free to reach out to me.

