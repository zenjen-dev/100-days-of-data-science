# 100-days-of-data-science

### Problem Statement: Classification of Accident Severity Using Historical NYC Crash Data

Based on the historical data available with respect to NYC crash data, I developed a model to classify whether an accident is deemed severe, or not severe. The model is a **binary classifier** in which the target variable named *serious_accident* is either True/False dependent on whether at least 1 (>1) injury was reported. 

The dataset contains approximately 1.2 million records, each representing a motor vehicle accident that occurred within the 5 boroughs of NYC between April 2012 and August 2022. This is the entirety of the crash data available as of August 2022, accessed directly from NYC OpenData and downloaded to a CSV dataset.

Analysis of the model performance revealed that the type of vehicle(s) and contributing factor(s) invovled in the crash are the most important features with regard to predicting severity classification. This is consistent with studies(*) that conclude that point of impact and/or vehicle size are highly relevant factors in accident severities.

