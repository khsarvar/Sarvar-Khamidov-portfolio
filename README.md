Sarvar Khamidov's data science related projects

# [Project 1: Correlation between GPD of a country and Internet Prices(RStudio)](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/tree/main/r-projects)
* Used two data csv files from Kaggle
* Data Wrangling / Cleaning: General data wrangling, join operations, regular expressions and etc
* Data Visualization: dot plot with correlation line, leaflet map of the world
![](/pictures/GDPvsIP2018.png)

# [Project 2: Stock Prediction(JupyterNotebook)](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/blob/main/JupyterProjects/StockPrediction.ipynb)
Let's say we want to make money by buying stocks. Since we want to make money, we only want to buy stock on days when the price will go up (we're against shorting the stock). We'll create a machine learning algorithm to predict if the stock price will increase tomorrow. If the algorithm says that the price will increase, we'll buy stock. If the algorithm says that the price will go down, we won't do anything.

We want to maximize our true positives - days when the algorithm predicts that the price will go up, and it actually goes go up. Therefore, we'll be using precision as our error metric for our algorithm, which is true positives / (false positives + true positives). This will ensure that we minimize how much money we lose with false positives (days when we buy the stock, but the price actually goes down).

This means that we will have to accept a lot of false negatives - days when we predict that the price will go down, but it actually goes up. This is okay, since we'd rather minimize our potential losses than maximize our potential gains.

# [Project 3: VastChallenge(Tableau)](https://github.com/khsarvar/Sarvar-Khamidov-portfolio/tree/main/Tableau)

![](/pictures/VastChallenge.png)
