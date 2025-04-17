This folder contains the datafiles, R-Scripts, and Mplus files accompanying the manuscript
"Who Loses Motivation and Who Keeps it up? Investigating Factors for Changes in Motivational Profiles Across Multiple Domains".

The files can be opened with any text reader.

Analytic datafile including item-level data for factor analyses etc.:
Schuler Welle 1-3 Peter_items_neu2.sav
...including full gender information:
Schüler Welle 1-3 Peter-korr_fullgender.sav


Analytic datafile for models:
mot_mplus_fullgender_sp_noschaffhausen.txt

Analytic files for main analyses reported in manuscript:

2020-10_Measurement models.Rmd
R markdown script for confirmatory factor analyses across subjects and time points

Data preps.Rmd
R markdown script for data preparations, descriptive statistics, and outputfile import from Mplus into R

Figures.Rmd
R markdown script for violin plot


1_LTA_Intrinsic.out
Output from multilevel latent transition analysis for intrinsic value in all four subjects with gender as covariate

2_LTA_Extrinsic.out
Output from multilevel latent transition analysis for extrinsic value in all four subjects with gender as covariate

3_Predictors_LogisticRegressionSEM.out
Output for logistic regression model to predict decline in intrinsic and extrinsic value, including all predictor variables

4_Predictors_LogisticRegressionSEM_selected.out
Output for logistic regression model to predict decline in intrinsic and extrinsic value, including significant predictor variables from last step

5_Achievement.out
Output for path model predicting within-person achievement variation across school years from intrinsic and extrinsic decline dummy variables

Additional scripts:

LTA_2020-06
Folder including all inputs for Mplus latent transition analyses

LTA.Rmd
R-Markdown script for defining the LTA Mplus models, creating the input scripts, and running them via the R package MplusAutomation

GMM_2025-04
Folder including all inputs for outputs the estimated alternative models:
Growth mixture models with residual variance and covariance specifications suggested by McNeish & Harring (2020) for improved convergence.
Reference:
https://doi.org/10.3758/s13428-019-01292-4

GMM.Rmd
R-Markdown script for defining the GMM Mplus models, creating the input script, and running them via the R package MplusAutomation

