# ADAS_perception [WIP]

This code is based on my Msc thesis. It contains a discrete choice research into the impact of ADAS (Advanced Driver Assistance Systems) on consumers' perceived comfort and safety (for the driver as well other road users) of lease cars. The final report for this research can be found here: https://repository.tudelft.nl/islandora/object/uuid%3Aed189e28-7dd7-4bce-8ceb-d6fa8686d222. I am still updating this project such that it is readable and presentable.

In this project 2 topics are researched:
1. The effect of an ADAS configuration on Perceived Internal Safety (PIS), Perceived External Safety (PES) and Perceived Comfort (PC) of the lease car.
2. The effect of Perceived Internal Safety (PIS), Perceived External Safety (PES) and Perceived Comfort (PC) on the final choice for a package.

What was done during this research:
- I created a survey and conducted a pilot & final version with an online respondents group.
- For topic 1, the respondents had to rate each package on each of the 3 metrics. Based on this data, an Ordinal Logistic regression was estimated, to see how people arrive at each perception rating for ADAS packages.
- For topic 2, the respondent had to choose between three packages (A, B, C) after rating them. From the observed choices, discrete choice models are estimated that indicates whether Perceived Internal Safety (PIS), Perceived External Safety (PES), Perceived Comfort (PC), Luxurious features (LUX) or Price (PR) have a stronger effect on utility, and as such on choices

In the file Attributes.ipyb a Notebook can be found which is used for the pilot (34 respondents that made 8 choices each), to estimate the impact of each attribute (each ADAS) on perceived utility of a package. These numbers are used as primers.
