---
id: w05-hswhhe-uiuc-knn-redundant-predictors
title: "Can redundant predictors change KNN?"
author: "Haoran Sun (hswhhe-uiuc)"
---

If we duplicate one predictor in a KNN model, we add no new information,
but that predictor contributes twice to squared Euclidean distance.
Could this change the nearest neighbors and predictions even after
standardizing all predictors? How should we handle redundant predictors
when choosing a distance measure?
