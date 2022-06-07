# Kaggle_ASHRAE_GreatEnergyPredictor_3

## Description

Q: How much does it cost to cool a skyscraper in the summer? A: A lot! And not just in dollars, but in environmental impact.  Thankfully, significant investments are being made to improve building efficiencies to reduce costs and emissions. The question is, are the improvements working? That’s where you come in. Under pay-for-performance financing, the building owner makes payments based on the difference between their real energy consumption and what they would have used without any retrofits. The latter values have to come from a model. Current methods of estimation are fragmented and do not scale well. Some assume a specific meter type or don’t work with different building types.  In this competition, you’ll develop accurate models of metered building energy usage in the following areas: chilled water, electric, hot water, and steam meters. The data comes from over 1,000 buildings over a three-year timeframe. With better estimates of these energy-saving investments, large scale investors and financial institutions will be more inclined to invest in this area to enable progress in building efficiencies.  About the Host   Founded in 1894, ASHRAE serves to advance the arts and sciences of heating, ventilation, air conditioning refrigeration and their allied fields. ASHRAE members represent building system design and industrial process professionals around the world. With over 54,000 members serving in 132 countries, ASHRAE supports research, standards writing, publishing and continuing education - shaping tomorrow’s built environment today.  Banner photo by Federico Beccari on Unsplash

## Evaluation 
Evaluation Metric
The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

The RMSLE is calculated as

![A1](https://github.com/ALDDSDataAnalytics/Kaggle_ASHRAE_GreatEnergyPredictor_3/blob/main/Screenshots/A1.PNG)


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
## Data 
Data Used

![Data]Screenshots/Data.PNG


