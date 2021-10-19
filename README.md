# Estimation-of-Neonatal-Mortality-Rate-NMR-
The aim of this paper is to estimate the average neonatal mortality rate (NMR) by a linear regression analysis. This is of interest for we want to analyse the claim that the composition of child mortality has changed, where the under  5 mortality rate (U5MR) has declined globally over the decades (since 1950, when  our data starts) leading to a higher classification of child mortality as NMR.
Hence, our regression model(s) will look at the effect of NMR on U5MR, as well 
as other predictors such as by year and by region, if applicable.
A rudimentary check of the applicability of such a model including `year`, 
`region`, `u5mr`, requires us to start by analysing the simple linear model of 
`scaled_nmr` on `year` and adding more covariates if it improves the fit of our model, as 
determined by the adjusted $R^{2}$. That is, does adding more covariates
describe more of our child mortality data?
