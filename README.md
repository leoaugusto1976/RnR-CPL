# Research and Reflect

## Dataset files:

- [CPL_2019.xls](https://github.com/leoaugusto1976/RnR-CPL/blob/main/data/CPL_2019.xls)
- [CPL_2020.xls](https://github.com/leoaugusto1976/RnR-CPL/blob/main/data/CPL_2020.xls)
- [CPL_2021.xls](https://github.com/leoaugusto1976/RnR-CPL/blob/main/data/CPL_2021.xls)
- [CPL_2022.xls](https://github.com/leoaugusto1976/RnR-CPL/blob/main/data/CPL_2022.xls)

**On the first tab of each Excel file, you can find the meaning for each column on the sheets.**

## Project

As a student of the Data Science Program at LightHouse Labs, this project is the culmination of the Research and Reflect discipline. I chose the Canadian Premier League for two reasons: my passion for soccer and its emergence as a fresh league in Canada. The CPL began in 2019, and I live in Victoria, BC, where I proudly support [Pacific FC](https://pacificfc.canpl.ca/). Joining us ([TOP](https://www.facebook.com/TORCIDA.ORGANIZADA.PACIFIC/)) at the tailgate before the games is a fantastic experience.

The goal of this project is to create a prediction for the 2023 season based on historical data. We will then compare the machine learning predictions with the actual results, shedding light on the accuracy of our model. You can find the published results [CPL: Machine Learning vs Real Result](https://medium.com/@leo.fonseca.canada/cpl-machine-learning-vs-real-result-8738a6f67115).

## Process

To create the datasets, I employed data scraping techniques to retrieve statistical data from the [Canadian Premier League website](https://canpl.ca/statistics/leaders). This process allowed me to collect data from 2019 to 2022. The most challenging part of data scraping was translating team logos into a usable string format. You can delve into the details of how this was achieved in the [data scraping notebook](https://github.com/leoaugusto1976/RnR-CPL/blob/main/data-scraping.ipynb).

This approach enabled the creation of four datasets spanning the years 2019 to 2022.

Subsequently, I leveraged the power of scikit-learn packages to make predictions. I opted for the Linear Regression model. The 2019 to 2021 dataset served as the training data, while the 2022 dataset was reserved for testing. You can explore the algorithm and detailed comments in the [predictions notebook](https://github.com/leoaugusto1976/RnR-CPL/blob/main/predictions.ipynb).

## Overall

This project has been an exciting journey, combining my passion for soccer with the power of data science. By analyzing the Canadian Premier League's historical statistics from 2019 to 2022, I aimed to predict the team standings for the 2023 season. While the results from my machine learning model may not always align perfectly with reality, this project has provided invaluable insights into the intricate world of soccer statistics and the capabilities of data-driven predictions.

I've learned that the beautiful game of soccer is a complex interplay of various factors, and predicting outcomes is a challenging task. Yet, my model has provided a solid foundation for future improvements and enhancements.

As we look ahead, I am committed to refining my approach and exploring new avenues. Soccer analytics is a dynamic field, and there is always room for improvement and innovation. I believe that classification algorithms hold great potential in the context of the Canadian Premier League. By shifting my focus to predicting specific match outcomes, player performance, or even fan engagement levels, I aim to unlock new layers of insight and provide valuable tools for soccer enthusiasts and analysts.

## Future Goals

**Classification Algorithms for Match Predictions**: In the future, I plan to explore the use of classification algorithms to predict individual match outcomes within the Canadian Premier League. By analyzing historical player and team statistics, I aim to develop a model that can forecast whether a match will end in a win, loss, or draw. This approach will not only provide valuable insights for soccer enthusiasts but also open doors to sports betting and fan engagement applications. Additionally, I intend to investigate player performance prediction, enabling soccer fans to anticipate standout moments on the field. With classification algorithms at my disposal, the possibilities are endless, and I'm excited to embark on this new phase of my project.
