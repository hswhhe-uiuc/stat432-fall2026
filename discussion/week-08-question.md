---
id: w08-hswhhe-uiuc-svm-margin-normalization
title: "When does SVM margin normalization fail?"
author: "Haoran Sun (hswhhe-uiuc)"
---

In Homework 8, we rescaled a linear score so that its smallest functional
margin became 1 without changing the decision boundary. What happens if
one observation is misclassified or lies exactly on the boundary? Can
positive rescaling still make every functional margin at least 1, and
how does a soft-margin SVM handle observations that violate this condition?
