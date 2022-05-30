# Kaggle_ASHRAE_GreatEnergyPredictor_3

## Description

Q: How much does it cost to cool a skyscraper in the summer? A: A lot! And not just in dollars, but in environmental impact.  Thankfully, significant investments are being made to improve building efficiencies to reduce costs and emissions. The question is, are the improvements working? That’s where you come in. Under pay-for-performance financing, the building owner makes payments based on the difference between their real energy consumption and what they would have used without any retrofits. The latter values have to come from a model. Current methods of estimation are fragmented and do not scale well. Some assume a specific meter type or don’t work with different building types.  In this competition, you’ll develop accurate models of metered building energy usage in the following areas: chilled water, electric, hot water, and steam meters. The data comes from over 1,000 buildings over a three-year timeframe. With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies.  About the Host   Founded in 1894, ASHRAE serves to advance the arts and sciences of heating, ventilation, air conditioning refrigeration and their allied fields. ASHRAE members represent building system design and industrial process professionals around the world. With over 54,000 members serving in 132 countries, ASHRAE supports research, standards writing, publishing and continuing education - shaping tomorrow’s built environment today.  Banner photo by Federico Beccari on Unsplash

## Evaluation 
Evaluation Metric
The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

The RMSLE is calculated as

![A1]


Where:

 is the RMSLE value (score)
 is the total number of observations in the (public/private) data set,
 is your prediction of target, and
 is the actual target for .
 is the natural logarithm of 
Note that not all rows will necessarily be scored.

Notebook Submissions
You can make submissions directly from Kaggle Notebooks. By adding your teammates as collaborators on a notebook, you can share and edit code privately with them.

Submission File
For each id in the test set, you must predict the target variable. The file should contain a header and have the following format:

 id,meter_reading
 0,0
 1,0
 2,0
 etc.

## Prizes

1st place - $10,000
2nd place - $7,000
3rd place - $5,000
4th place - $2,000
5th place - $1,000

Because this competition is being hosted in coordination with the ASHRAE Organization and its Winter or Annual meetings in 2020, winners will be invited and strongly encouraged to attend the conference, contingent on review of solution and fulfillment of winners' obligations.

Note that in addition to the standard Kaggle Winners' Obligations (open-source licensing requirements, solution packaging/delivery, presentation to host), the host team also asks that you create a short video (under 5 minutes) summarizing your solution.
## Timeline 
December 12, 2019 - Team Merger deadline. This is the last day participants may join or merge teams.
December 12, 2019 - Entry deadline. You must accept the competition rules before this date in order to compete.
December 19, 2019 - Final submission deadline.

All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.
## Prior Competitions
History of Great Building Energy Predictor Shootout I and II Competitions

ASHRAE has previously hosted two data competitions, called the "Great Building Energy Predictor Shootout I" (1993) and "Great Building Energy Predictor Shootout II" (1994). If you are interested in seeing how the field has changed over the years, we have rehosted a copy of the first competition here with a leaderboard. It's entirely for fun and does not award points, medals, etc.

For both of these competitions, participants were asked to develop empirical models for predicting building energy data from data sets and compare how those models could be used to forecast energy usage (Shootout I) and calculate energy conservation retrofit savings (Shootout II).

The 1994 competition asked participants to retrieve the competition training data set via an FTP server. Teams were required to submit their empirical models along with predictions via floppy disks. The submitted package included predictions of energy savings and a sufficient explanation of how the specific method (calculation method, data removal, etc.) was applied. Submissions using black-box, or proprietary methods, were disqualified. A combination accuracy metric of CV-RMSE (Coefficient of Root Mean Square Error) and MBE (Mean Bias Error) was used to evaluate prediction accuracy.

While the 1994 competition awarded no monetary prizes, over 150 teams competed. Six winning teams were formally recognized, all participants were asked to write an ASHRAE paper to document their efforts and to present at ASHRAE conferences. As a part of these efforts, over a dozen peer-reviewed papers were published and several software vendors incorporated the algorithms described in these papers.

Haberl, J. (1994, July 1). Instructions - "The Great Building Energy Predictor Shootout II: Measuring Retrofit Energy Savings".

## Acknowledgments

In addition to the Data Driven Modeling (DDM) Subcommittee of ASHRAE Technical Committee 4.7: Energy Calculations, the following organizations have generously contributed to data collection, travel and resources to host this competition:



Singapore Berkeley Building Efficiency and Sustainability in the Tropics



BUDS Lab



Engineering Experiment Station Texas A&M University