Sarvar Khamidov's data science related projects

# [Project 1: Capstone Project - Sports Prediction](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/tree/main/Capstone)
Detailed sports data is freely available on the internet, but historical odds data is surprisingly difficult to find, with no APIs offering historical betting odds and game statistics in a usable format. In this project we aim to collect data for a variety of sources containing both historical odds and team statistics. Then we aim to perturb copies of our dataset such that its quality deteriorates in the few key metrics selected. With these datasets—the baseline and the perturbed—we aim to compare the quality of model prediction we are able to achieve. In other words, in the domain of sports betting, we hope to discover which key data quality metrics are most important. These results provide clarity on what data quality metrics are most useful in looking for systematic mispricing in the sports betting market. To accomplish this we are going to look to predict the odds of NBA games on a series of perturbed datasets to assess which data quality metric is most influential in our predictions.

Me and my team was able to calculate different data perturbations for the sports betting dataset. Row uniformity performed identical to the model. Adding noise significantly degraded the model performance but boots-strao sampled features increased it. After dropping features or adding dummy features to our data we observed that performance drastically declined.

# [Project 2: Profitable App Profiles for the App Store and Google Play Markets](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/blob/main/JupyterProjects/Profitable_App.ipynb)
Aim in this project is to find mobile app profiles that are profitable for the App Store and Google Play markets. Working as data analysts for a company that builds Android and iOS mobile apps, and job is to enable the team of developers to make data-driven decisions with respect to the kind of apps they build.

At the company that only build apps that are free to download and install, and  main source of revenue consists of in-app ads. This means that  revenue for any given app is mostly influenced by the number of users that use  app. Goal for this project is to analyze data to help our developers understand what kinds of apps are likely to attract more users.

# [Project 3: Stock Prediction](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/blob/main/JupyterProjects/StockProject.ipynb)
Let's say we want to make money by buying stocks. Since we want to make money, we only want to buy stock on days when the price will go up (we're against shorting the stock). I created a machine learning algorithm to predict if the stock price will increase tomorrow. If the algorithm says that the price will increase, we'll buy stock. If the algorithm says that the price will go down, we won't do anything.

I maximized our true positives - days when the algorithm predicts that the price will go up, and it actually goes go up. Therefore, we'll be using precision as our error metric for our algorithm, which is true positives / (false positives + true positives). This will ensure that we minimize how much money we lose with false positives (days when we buy the stock, but the price actually goes down).

This means that we will have to accept a lot of false negatives - days when we predict that the price will go down, but it actually goes up. This is okay, since we'd rather minimize our potential losses than maximize our potential gains.

# [Project 4: Correlation between GDP of a country and Internet Prices using R](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/tree/main/r-projects)
* Used two data csv files from Kaggle
* Data Wrangling / Cleaning: General data wrangling, join operations, regular expressions and etc
* Data Visualization: dot plot with correlation line, leaflet map of the world

![](/pictures/GDPvsIP2018.png)

# [Project 5: VastChallenge](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/tree/main/Tableau)
Mini-Challenge 2 uses a collection of spreadsheets and geospatial files to detail the activities of GASTech employees, including staff that are members of the Protectors of Kronos (POK) as they prepare for their daring kidnapping of GASTech employees. Hidden among the daily routines of regular employees are activities such as practicing the kidnapping route and monitoring   the targets’ homes to gather information. This dataset identifies the potential members of POK and their intended targets.
![](/pictures/VastChallenge.png)
