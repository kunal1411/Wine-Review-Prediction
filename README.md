# Wine-Review-Prediction

Objective

We analyzed Wine Review dataset from Kaggles.com to extract meaningful marketing insights from it to help online wine platform startup to navigate in the complicated market. We utilized ggplot library to create intuitive and informative visualizations to help identifying pattern and relationship between wine variables and reviewed scores. We further utilized linear regression analysis to further investigate the relationship we identified, and kept optimizing the model with feature engineering and natural language processing techniques. With the accurate model we trained, our client can not only determine popularity or quality of each product, but also predict scores when it is not available to provide customers with helpful information.

Data Description
The dataset contains 13 variables and 150,000 observations. Below is the list of all variables:
Country: The country that the wine is from.
Description: A few sentences from a sommelier describing the wine's taste, smell, look, feel, etc.
Designation: The vineyard within the winery where the grapes that made the wine are from.
Points: The number of points WineEnthusiast rated the wine on a scale of 1-100 (though they say they only post reviews for wines that score >=80).
Price: The cost for a bottle of the wine.
Province: The province or state that the wine is from.
Region 1: The wine growing area in a province or state (ie Napa).
Region 2: Sometimes there are more specific regions specified within a wine growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank.
Taster Name: Name of the person who tasted and reviewed the wine.
Taster twitter handle: Twitter handle for the person who tasted and reviewed the wine.
Title: The title of the wine review, which often contains the vintage if you're interested in extracting that feature.
Variety: The type of grapes used to make the wine.
Winery: The winery that made the wine
