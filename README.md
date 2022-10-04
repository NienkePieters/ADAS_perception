# ADAS_perception [WIP]

A discrete choice research into the perception of the impact of ADAS (Advanced Driver Assistance Systems) on comfort and safety of lease cars. The final report for this research can be found here: https://repository.tudelft.nl/islandora/object/uuid%3Aed189e28-7dd7-4bce-8ceb-d6fa8686d222

In this project 2 subjects are researched:
1. The effect of an ADAS configuration on Perceived Internal Safety (PIS), Perceived External Safety (PES) and Perceived Comfort (PC) of the lease car. This is estimated with a Ordinal Logistic Regression. The respondents had to rate each package on those three metrics.
2. After rating three different packages, the respondent had to choose between these three packages. 

- I created a survey. 
- A Ordinal Logistic regression was estimated, to see how people arrive at each perception rating for ADAS pacakges. To be specific in the type of regression: Cumulative odds ordinal logistic regression with proportional odds. This type of ordinal regression uses cumulative categories representing the perception ratings.
- From the observed choices, discrete choice models are estimated that indicates whether Perceived Internal Safety (PIS), Perceived External Safety (PES), Perceived Comfort (PC), Luxurious features (LUX) or Price (PR) have a stronger effect on utility, and as such on choices

In Attributes.ipyb a Notebook can be found which is used for the pilot (34 respondents that made 8 choices each), to estimate the impact of each attribute (each ADAS) on perceived utility of a package. These numbers are used as primers.
