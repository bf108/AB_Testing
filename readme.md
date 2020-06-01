# E-Commerce Website AB Testing

This analysis was conducted on a hypothetical e-commerce website as part of
the Udacity Data Analyst NanoDegree

## Dataset

The data consists of information regarding **290,584 unique users** of the
e-commerce site. The observation period was over **22 days**. The business
metric on which to evaluate the New and Old page is conversion rate.

## Summary of Findings

The A/B Testing conducted on the new and old page of the e-commerce website to
evaluate conversion rate provided insufficient evidence to reject our
Null Hypothesis.

The evidence suggests that the old page performed better or at least as good as
the new page. There is no justification in terms of customer conversion rate
from changing the web design. Conversion rate in this example was deemed the
most important business metric by which to measure value back to the business.

Conversion rate alone may not always be the best metric to evaluate a change on.
If a business wants to evaluate the performance of a new feature in relation to
an existing one, there should be some real careful consideration into what
metric is best to conduct the evaluation on. This should link back to what the
central business model and strategy is.

In some further analysis, we looked at regression model for predicting
conversion rate. This had limited success, partly because we don't have many
features on which to base the conversion rate on and the impact of the web page
appeared to be close to null.

It is evident that inclusion of country has little impact on accuracy of the
model in predicting conversion. This remains the case when we determine the
interaction between country and page.

In order to better predict the conversion rate, additional research would be
required to obtain new features.
