# Mobile Price Classification

## Problem Framing
We want to know the general specifications of mobile phones in a certain price range. We will be using supervised classification because we already have the label (price range), but we will not be using overly complex models because the end goal is the interpretability of the model, and complex models generally have low interpretability.

We will be prioritizing accuracy score because we want the model to make as close a prediction as possible to the true value, so that we can interpret the model accurately.

## Conclusion
<img src=Images/Coef.png>

From the chart, we can see that features that have the most impact are:

* ram
* battery_power
* px_height, and
* px_width

By seeing the 4th chart (visualizing whether a phone will be classified into the most expensive category or not), we can see that with 1 unit increase of ram, the chances of the phone being classified as the most expensive increased by  𝑒10.9  times. We can also see that features such as fc (front camera megapixels) and blue (bluetooth availability) have little to no effect on the price

Average RAM of phones in the cheapest price is 785, while the most expensive is 3449.

Source: https://quantifyinghealth.com/interpret-logistic-regression-coefficients/
