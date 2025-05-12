# PTcausal: Measuring the PT instructor influence on student grades

This is the repo with the paper's code. The paper investigates the causal effect of part-time instruction on students’ final grades. 
The research usesthirteen years of data (2012-2024) drawn from a private four-year institution located in upstate New York.
The study focuses first on first-semester freshmen and then extends its analysis to the entire undergraduate
student body. We implement Judea Pearl’s causal graph framework for identification, using the backdoor
criterion to determine valid adjustment sets. The average treatment effect (ATE) is estimated using multiple
analytical methods, including linear regression and double machine learning (DML), (Chernozhukov et al.,
2024). The DoWhy library’s refutation methods, (Sharma and Kiciman, 2020), are used to assess the robust-
ness of causal claims by testing model assumption violations. Variability across courses is estimated using
Bayesian hierarchical linear regression models. We use conditional average treatment effects (CATEs) via
DML and quantile regression (25th, 50th, and 75th percentiles) to estimate heterogeneity effects. The re-
search findings indicate that part-time instruction leads to moderate positive effects on student final grades,
particularly among students who achieve lower grades. The study provides a guideline on how causal in-
ference methods, combining statistical and machine learning tools, can be used to analyze large educational
datasets and generate results that can aid instructional staffing decisions.

Keywords: causal inference, causal machine learning, part-time faculty, student success, higher educa-
tion analytics.

