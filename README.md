## Introduction
This is continution project from the first project (titled as "AML_Project.ipynb"). Taking in feedback for the first project (please see "Project1_Feedback.md"), I will be cleaning this project by taking a unsupervised classification approach. I made this decision because there the data from APIs like ACLED are too sparse for certain countries (i.e. US and Ukraine)

In this fictitious scenario, I am a US military data analyst working with data mining, data analytics, and machine learning to understand human tendencies for violence. My job is to train a machine learning algorithim to "categorize" countries based on their geopolitical volatility  using economic, weather, and geographical features through unsupervised learning. The motive behind this is the fact that US stakeholders and decision makers only have limited resources (i.e. vehicles, personnel, etc.) to spare in dynamic situations, so it is very difficult to respond "appropriately" to certain area. My training dataset will come from "traditional" conflict zones in the Middle East, North Africa, and Ukraine. I will be using a combined dataset taken from hetergenous sources (i.e. ACLED, World Bank, NASA). In addition, my employers have asked me to keep an eye on potential violent outbreak and intensity in the United States, a country that does not experience high levels of violence in comparison to "hot" countries and possibly find "hidden" trends. This is a the true test of the value of my models. 

Data Usage: Our actual Y values will be taken from the Armed Conflict Location and Event Database (ACLED) by totaling up the number of violent incidents in each country per year from 2000 to 2023. Our feature X values will be taken from the Worldbank and NASA Power. 

Machine Learning Pipeline: I will first start with preprocessing the data by create a merged "mega" dataframe from the different APIs and making sure that there is limited data loss during the merging phase. The next step will be using PCA and ICA for reducing our feature dimenstions and find our k-values for clustering through the elbow and shadow silleoutte methods. Next I will use K-means, DBSCAN, and GMM clustering with PCA.  Finally, I will see how our algorithms classifies different countries throughout a span of 23 years. Please see "Final_Project.ipynb" for the full code and results. 

## Analysis 




## Conclusion
