# BnB or not to BnB - Statistical Learning

This paper will present a complete statistical analysis of Airbnb data from six major european cities. We start by presenting an exploratory analysis of our dataset, in which we try to identify both the most relevant components that drive prices and possible differences between the collected cities. We then evaluate different statistical learning models that predict the prices given different instrumental variables. At the end we generate different clusters both from the whole dataset and from subset related to single cities, to better understand the composition of the dataset.

We find that the most important drivers for prices are (apart from the actual city in which is located the property) the type of the room, weather is shared or private, and the number of guests that can stay at the property, the higher the number, the lower the price. These main variables are followed by others like the rating of the property, the number of bathrooms and the presence of air conditioning.

We estimated a simple pruned tree, a Random Forest and a Boosted tree model which achieve a Root Mean Squared Error from 80 to 73.

We finally try and cluster our data but we find that the clusters have no actual grographical interpretation.
