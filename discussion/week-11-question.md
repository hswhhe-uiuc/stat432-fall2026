---
id: w11-hswhhe-uiuc-kmeans-curved-clusters
title: "Can K-means miss obvious clusters?"
author: "Haoran Sun (hswhhe-uiuc)"
---

Suppose a scatterplot shows two curved, crescent-shaped groups that do not
overlap. Even if we know $K=2$ and run K-means from many random initializations,
could it still produce clusters that do not match these groups? How does
assigning points to their nearest mean create this limitation, and would
standardizing the variables solve it?
