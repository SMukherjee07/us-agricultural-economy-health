An analysis of agricultural exports, commodity composition, and regional variation in health outcomes across U.S. states

Status: Research project / exploratory statistical analysis
Data: 2019 U.S. state-level agricultural and health data
Methods: Exploratory Data Analysis · OLS Regression · Model Diagnostics · ANOVA · ANCOVA · GAM · GLM · LASSO · Ridge

Overview

This project investigates whether differences in agricultural economic structure are associated with differences in state-level health outcomes across the United States.

Rather than examining agricultural activity only through total export volume, the analysis separates economic scale from economic composition, examining measures such as livestock, produce, grain, dairy, and cotton export shares. Regional variation is also incorporated to examine whether observed agricultural-health associations persist after accounting for broader geographic differences.

The analysis uses state-level data from 2019 and focuses on obesity, hypertension, diabetes, physical inactivity, and depression-related outcomes.

Research Questions
Does the scale of agricultural exports associate with state-level health outcomes?
Does agricultural commodity composition provide information beyond overall export scale?
Are relationships between agricultural economic structure and health approximately linear?
Do regional differences persist after adjustment for agricultural and economic predictors?
Data

The analysis combines state-level agricultural export measures with health prevalence estimates.

Agricultural variables
Total agricultural exports
Log-transformed export value
Livestock export share
Dairy export share
Produce export share
Grain export share
Cotton export share
Agricultural economic diversity

Economic diversity is represented using Shannon entropy, allowing the analysis to distinguish the size of an agricultural economy from the composition of that economy.

Health outcomes
Obesity prevalence
Hypertension prevalence
Diabetes prevalence
Physical inactivity
Depression prevalence

The analysis is conducted at the state level (n = 50).

Statistical Methods

The project progressively evaluates the relationship between agricultural structure and health using:

Exploratory data analysis
Correlation analysis
Nested multiple linear regression
OLS assumption diagnostics
Breusch–Pagan testing
Variance inflation factors
Cook's distance
ANOVA
Tukey HSD
ANCOVA
Estimated marginal means
LOESS
Regression splines
Generalized additive models
Logistic regression
Poisson GLM
LASSO regression
Ridge regression
Cross-validation

The analysis deliberately compares simpler and more flexible models rather than assuming that a single modeling framework is appropriate from the outset.

Key Findings

The analysis suggests that agricultural export scale alone provides limited explanatory power for state-level obesity variation. Adding commodity composition and regional structure substantially improves model fit.

The full linear model explains approximately 68% of the observed variation in state-level obesity prevalence (R^2=0.682, adjusted R^2=0.620).

Regional differences remain substantial after adjustment for agricultural economic predictors. In the ANCOVA analysis, region remains statistically significant, with adjusted obesity prevalence highest in the South and Midwest and lower in the Northeast and West.

Exploratory analyses also show positive associations between livestock export share and several health outcomes, while produce export share tends to show negative associations. These relationships should be interpreted as state-level associations rather than causal effects.

Important Limitations

This is an observational, cross-sectional analysis of only 50 states.

Therefore:

Associations should not be interpreted as causal relationships.
State-level patterns cannot be assumed to describe individuals within those states.
Unmeasured factors such as healthcare access, poverty, food environments, and historical inequality may contribute to observed regional differences.
The relatively small sample limits statistical power and makes complex models susceptible to overfitting.
The data represent 2019 and should not automatically be extrapolated to later periods.

A central methodological consideration is the ecological fallacy: relationships observed between states do not necessarily hold at the individual level.

Research Direction

Future extensions could include:

County-level analysis
Multi-year panel data
Fixed-effects models
Mediation analysis
Instrumental-variable approaches
Individual-level health data
More rigorous out-of-sample model comparison
