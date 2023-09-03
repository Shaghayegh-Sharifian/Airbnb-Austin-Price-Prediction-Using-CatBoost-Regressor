# Airbnb-Austin-Price-Prediction-Using-CatBoost-Regressor
# **Introduction and project aim**<br>
Airbnb is a home-sharing platform that allows homeowners and renters ('hosts') to put their properties ('listings') online so that guests can pay to stay in them. Hosts are expected to set their prices for their listings. Although Airbnb and other sites provide some general guidance, there are currently no free services that help hosts price their properties. Paid third-party pricing software is available, but generally, you are required to put in your expected average price ('base price’), and the algorithm will vary the daily price around that base price on each day depending on the day of the week, seasonality, how far away the date is, and other factors.
<br>
<br>
Airbnb pricing is important to get right, particularly in big cities where there is lots of competition and even small differences in prices can make the difference between optimum occupancy and high earnings, or being priced out of the market. It is also a difficult thing to do correctly, to balance the price with occupancy (which varies inversely with price) to maximize revenue.<br>
<br>
This project aims to use machine learning to predict the base price for properties in Austin and also to explore Airbnb listing data, to help Airbnb hosts maximize their earnings.<br>
<br>
The data is quite messy and has some limitations. The major one is that it only includes the advertised price (sometimes called the 'sticker' price). The sticker price is the overall nightly price that is advertised to potential guests, rather than the actual average amount paid per night by previous guests. The advertised prices can be set to any arbitrary amount by the host, and hosts that are less experienced with Airbnb will often set these to very low (e.g., $0) or very high (e.g., $10,000) amounts.<br>
<br>
## **Instalation**<br>
All necesary libraries are indicated at the beggining of the notebook. The code should run with no issues using Python versions 3.*.<br>
You may need to install **Catboost Regressor and Shap**, before importing the necesary libraries.<br>
<br>
## **Project Motivation**<br>
As part of my Data Scientist Course, I get to have my very own Data Science Capstone, where I get a taste of what is like to solve problems and answer questions like a data scientist. For my assignment, I had to do a project that looked into the relationship between Airbnb prices and its determinants to predict nightly renting prices in Austin.<br>
<br>
## **Conclusion**<br>
Eventually, I had to use machine learning models for this project and not neural networks, hence, I chose the Catboost Regressor for predicting the nightly prices, which was **able to explain 74% of the price variation**. The remaining 26% is probably made up of features that were not present in the data. A significant proportion of this unexplained variance is likely due to variations in the listing photos. The photos of properties on Airbnb are very important in encouraging guests to book, and so can also be expected to have a significant impact on price - better photos (primarily better-quality properties and furnishings, but also better-quality photography) equal higher prices.
