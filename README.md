# Location Pricing

This assignment asks you to do some feature engineering to fit into the `Carbitrage` project. As part of the `Carbitrage` offering, we have built models to estimate the value of a given car. Our current approach is to build a separate model for every combination of location and make/model with sufficient data. This approach is great in large locations for popular cars, but we are limiting the efficacy of our model by dividing our data in such a fine way. We would like to aggegate locations to enhance the predictive power of our models. 

The product manager believes that we can classify location into a "reasonable number" of groups. The head of data science suspects that something between 3 and 20 groups will be optimal. The data scientist has created a static set of about 14 months of data for you. You can find that data here:   `umt-msba.carbitrage.processed_listing_pages_20240913`. 

Your job is to analyze the processed listing pages and make a recommendation on the location grouping. Your recommendation should take the form of a notebook that the data scientist can read. They have provided you with a notebook to get you started. 

### Recommended steps: 

1. Build on the notebook the data scientist gave you and explore the data.
2. Do analyses to determine the location grouping.
3. Create a new notebook that reads in the data, does the analyses that support your recommendation, and would allow the data science team to reproduce your work.
4. Finish with the final recommendation of location groups.
