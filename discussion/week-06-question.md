---
id: w06-hswhhe-uiuc-knn-probability-ties
title: "How do tied KNN probabilities affect AUC?"
author: "Haoran Sun (hswhhe-uiuc)"
---

In Homework 6, KNN with equal neighbor weights estimates a probability
as the fraction of neighbors in class 1. When k is small, there are only
a few possible probabilities, so many observations receive the same
score. How are ties between positive and negative observations handled
when calculating AUC? Could increasing k improve AUC even if the
predicted classes at a 0.5 threshold stay the same?
