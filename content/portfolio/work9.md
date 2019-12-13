+++
date = "2019-12-12"
title = "Model"
draft = false
image = "img/method/random_forest.png"
categories = [ "Methods"]
weight = 9
+++

<!--more-->

For this analysis, we chose to employ a random forest that inputs the predictors described above to predict one of the five batted ball outcomes. In the random forest model, we only considered batted balls that contained values for all the predictors above. 

![](/img/method/dag.png)

One reason for choosing a random forest is that many of the predictors are highly interactive in their propensity to produce certain outcomes. Another reason is that the random forest allows us to include an extensive set of features, so that we can identify which features are most important in predicting outcomes of batted balls. We expect that the features that are direct measurements of a batted ball, such as launch speed, launch angle, and spray angle, will be the most predictive of its outcome. However, we are also interested in identifying if other factors, such as attributes of the pitch, defense, or stadium, are important in predicting outcomes. Additionally, by including an expansive set of features, we can assess how well the most modern, cutting-edge measurements of baseball plays can predict their outcomes.
