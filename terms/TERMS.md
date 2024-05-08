# Machine Learning Terminology 

1. **Inference**: The process of predicting the target variable for a given input. Inference is the final step in the machine learning pipeline, where the model is used to make predictions on new, unseen data.
2. **Point Estimate**: A single value that serves as the best prediction of a target variable. Point estimates are used in regression models to predict the value of the target variable for a given input.
3. **Univariate**: A type of analysis that involves only one variable. Univariate analysis is used to describe the distribution of a single variable and identify patterns or trends in the data.
   1. **Univariate Regression**: Is a form of regression analysis that involves only one independent variable and one dependent variable. It is used to model the relationship between the independent variable and the dependent variable by measuring the least squares fit of the data.
   2. **Univariate Normal**: A distribution of data that has only one variable and follows a normal distribution. Univariate normal distributions are used to model the distribution of data in statistical analysis.
4. **Heteroscedastic**: A term used to describe data that has non-constant variance. Heteroscedastic data has a variance that changes over the range of the data, which can affect the performance of regression models. Said another way; the underlying data has a different spread of values at different points in the data, meaning the data doesn't follow a consistent pattern.
5. **Homoscedastic**: A term used to describe data that has constant variance. Homoscedastic data has a variance that remains the same over the range of the data, which is a desirable property for regression models. Said another way; the underlying data has a consistent spread of values across the data, meaning the data follows a consistent pattern.
6. **Discrete Distributions**: A type of probability distribution that represents the probability of occurrence of discrete values. Discrete distributions are used to model data that can only take on specific values, such as counts or categories. Some of these variants are;
   - **Bernoulli Distribution**: A discrete probability distribution that represents the probability of success or failure of a single experiment. The Bernoulli distribution is used to model binary data, where the outcome can be either success or failure.
   - **Binomial Distribution**: A discrete probability distribution that represents the number of successes in a fixed number of independent Bernoulli trials. The binomial distribution is used to model the number of successes in a sequence of independent experiments, where each experiment has only two possible outcomes.
   - **Poisson Distribution**: A discrete probability distribution that represents the number of events occurring in a fixed interval of time or space. The Poisson distribution is used to model the number of occurrences of an event in a fixed interval, such as the number of customers arriving at a store in an hour.
   - **Categorical Distribution**: A discrete probability distribution that represents the probability of occurrence of different categories. The categorical distribution is used to model data that can take on one of several discrete values, such as the outcome of a dice roll or the color of a car.
   - **Geometric Distribution**: A discrete probability distribution that represents the number of Bernoulli trials needed to get the first success. The geometric distribution is used to model the number of trials needed to achieve the first success in a sequence of independent experiments.
7. **Continuous Distributions**: A type of probability distribution that represents the probability of occurrence of continuous values. Continuous distributions are used to model data that can take on any value within a range, such as measurements or observations. Some of these variants are;
   - **Normal Distribution**: A continuous probability distribution that represents the distribution of data around a central mean value. The normal distribution is used to model data that is symmetrically distributed around the mean, such as height or weight measurements.
   - **Uniform Distribution**: A continuous probability distribution that represents the equal probability of occurrence of values within a range. The uniform distribution is used to model data where all values within a range are equally likely to occur, such as the outcome of a fair dice roll.
   - **Exponential Distribution**: A continuous probability distribution that represents the time between events in a Poisson process. The exponential distribution is used to model the time between occurrences of events that happen at a constant rate, such as the time between customer arrivals at a store.
   - **Gamma Distribution**: A continuous probability distribution that generalizes the exponential distribution to model the time between events in a Poisson process. The gamma distribution is used to model the time between occurrences of events that happen at a constant rate, such as the time between customer arrivals at a store.
   - **Beta Distribution**: A continuous probability distribution that represents the distribution of probabilities. The beta distribution is used to model the uncertainty in the probability of an event occurring, such as the probability of success in a Bernoulli trial.