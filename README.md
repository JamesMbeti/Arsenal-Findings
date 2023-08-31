# Premier League Probability Predictor - Arsenal's League Win Probability Estimation 22/23

<img src="image.jpg" />

## Overview

This project focuses on utilizing a binomial maximum likelihood estimator to predict the probability of Arsenal, a prominent football club in the Premier League, winning the league title 22/23 as it is 8 points clear off the table. The prediction is based on historical match data scraped from online sources for the last 20 Premier League seasons since 2000. By applying statistical analysis, this project aims to provide insights into the potential success of Arsenal in the league.

## Features

- **Data Collection:** Scraped match data of Arsenal from [this site](https://fbref.com/en/squads/18bb7c10/2002-2003/Arsenal-Stats), compiling a comprehensive dataset for analysis.

- **Statistical Analysis:** Applied binomial maximum likelihood estimator to calculate the probability of Arsenal winning the Premier League.

- **Visualization:** Presented the probability estimation using visually informative charts and graphs.

- **Modular Structure:** Codebase is organized into separate modules for data collection, analysis, and visualization for easy understanding and maintenance.

## Maximum Likelihood Estimator (MLE)
``Maximum likelihood estimation`` is a method that determines values for the parameters of a model. The parameter values are found such that they maximise the likelihood that the process described by the model produced the data that were actually observed. In this case I used the MLE of binomial distribution as I assumed that the data followed closely a binomial distribution in terms of wins and loses. in the last 20 years. Really not perfect as there are many things to put into consideration but good for a start right?

The MLE of a binomial distribution is given by:

\[
\hat{p} = \frac{x}{n}
\]

where:
- \(\hat{p}\) represents the estimated probability of the event (in this case Arsenal winning the league).
- \(x\) is the number of favorable outcomes (Arsenal winning matches).
- \(n\) is the total number of trials (total number of matches played in the league).

The proof of the above Binomial MLE can be found [here.](https://statproofbook.github.io/P/bin-mle.html)


## Results

The analysis of the data using the binomial maximum likelihood estimator yielded a predicted probability of 56% that Arsenal will win the Premier League title for the previous season.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to reach out.

## Contact

For any inquiries or questions, please contact jamesmbeti@gmail.com and visit my [LinkedIn Profile](https://www.linkedin.com/in/james-mbeti-128519175/)

