---
id: w10-hswhhe-uiuc-oob-tuning-optimism
title: "Can tuning make OOB error too optimistic?"
author: "Haoran Sun (hswhhe-uiuc)"
---

Each training observation's OOB prediction uses only trees that left it out.
If we try many combinations of mtry and node size and select the lowest OOB
misclassification rate, can that selected error become too optimistic?
Why might we still need an independent test set, even though each OOB
prediction excludes the observation being predicted?
