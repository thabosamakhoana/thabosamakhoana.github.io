---
title: "An Elementary Proof of the Near Optimality of LogSumExp Smoothing"
collection: publications
permalink: /publication/2025-08-21-the-optimal-smoothings-of-sublinear-functions-and-convex-cones
excerpt: 'The paper proves a sharp limitation on smoothing the max-of-coordinates function in $$ d $$ dimensions. Any convex surrogate with the desired smoothness must incur a worst-case error that grows like $$ \log d $$, so the standard LogSumExp smoothing is essentially optimal up to constants. This result is proved using elementary inequalities about smooth, convex functions. The paper also proves that in small dimensions ($$d = 2, 3 $$) LogSumExp fails to be optimal.'
date: 2025-08-21
paperurl: 'https://arxiv.org/abs/2512.10825v1'
venue: ArXiv Preprint
---

The paper studies how well one can approximate the max-of-coordinates function in $$ d$$ dimensions under the $$\ell_\infty$$ geometry (the setting that matches common “softmax-style” smoothings). The standard choice is the LogSumExp function $$ f(x) = \log(\sum_{i=1}^{d}e^{x_i})$$, which achieves worst-case error on the order of $$\log d $$.

The main result is an elementary, constructive lower bound showing this $$ \log d$$ dependence is unavoidable: even the best-designed convex smoothing must differ from max by at least a constant multiple of $$ \log d $$, so LogSumExp is near-optimal up to constants.


