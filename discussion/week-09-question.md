---
id: w09-hswhhe-uiuc-kernel-trick-validity
title: "Why can't any similarity function be a kernel?"
author: "Haoran Sun (hswhhe-uiuc)"
---

A kernel SVM replaces feature-space inner products with a kernel function.
Why can't we use any similarity function as a kernel? How does requiring
the kernel matrix to be positive semidefinite connect to the existence of
a feature map, and what can go wrong with the SVM optimization problem if
that requirement fails?
