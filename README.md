# Private Repository for ML Instruction

### DS/MLE Interview Cheatsheet

*The term 'Data Scientist' is too broad. You NEED to know what your expertise is and what kind of DS aligns better with your career goals. That is, before applying for the positions, read carefully about the job descriptions. In general, here are what the job description would indicate*
- Data Scientist (Analytics): product driven, very analytical, visualization, sql intensive, ab testing, work intensively with product manager + products + propose/validate ideas around products
- Data Scientist (Engineering): statistical + ML modeling, ab testing, optimization
- Machine Learning Engineer:  deep learning related, CV or NLP, real time serving, recommendation system
- Research Scientist/ Applied Scientist/ Data Scientist (Research/ Core): research driven, methodology development; robotics + reinforcement learning; typically requires doctorate in CS, EE, Stats

#### CORE Technical Knowledge: (Know them cold, A.K.A, whiteboard them from scratch; no other way around)
1. Probability: Distributions, Brainteaser Problems, Bayesian/Conditional Probability, Maximum Likelihood
2. Basic Statistics: CLT, Hypothesis Testing, Statistical Moments (Mean, Median, Mode, Quantiles, Variance, Covariance, Correlation, Skewness)
3. Advanced Statistics: Ordered Statistics, Sampling Methods, Importance Sampling, MCMC, Bayesian Statistics, Nonparametric Testing, PSM
4. Regression: OLS, Logit, GLS, WLS, Possion regression, ordered regression; model interpretation 
5. ML Supervised: KNN, Naive Bayes, logistic regression, decision tree and CART, DNN, CNN, RNN, SVM
6. ML Unsupervised: Kmeans, Gaussian Mixture, PCA
7. Numerical methods: GD, SGD, Batch GD, dropout, Batch normalization, under-sampling, over-sampling
8. ML key concepts: Loss function, Backprop, Bias-variance tradeoff, overfitting/underfitting, hyperparameters and tuning, cross-validation, classification (precision, recall, f1, accuracy, class weight, ROC/AUC, false positive vs false negative tradeoff)
9. Basic A/B Testing: A/A Testing, bias and variance, variance reduction, experiment debugging (traffic splitting and sample ratio mismatch, network effect and debias), type I vs type II error tradeoff
10. Advanced A/B Testing: Multiple testing, Sequential testing, Doubly-Robust estimator, Double ML, causal tree/forest

#### CORE Coding Skills: (Know them cold, A.K.A, efficient syntax + bug free; no other way around)
1. SQL/Scala/Spark-SQL: join, group by, window functions, self-join, date functions
2. Pandas/R: basic <-> advanced data manipulation (anything written in SQL, rewrite them in Pandas/R)
3. Optional for some DS; Required for all MLEs, Leetcode (Algorithms: BFS, DFS, Heap/Merge-sort, DP; Data Structures: ListNode, BST, Hashtables; Complexity Analysis: Time-Space, NP-Hard)
4. Optional for DS; Required for most MLEs: System design, Kafka and real-time serving
5. Nice to have: vim, git, bash

#### CORE Analytical Skills: (On par with techinical competency; You need to know how to communicate)
1. Understand the product and business questions
- What is the objective?
- What are key metrics you want to evaluate? What are guard-rail metrics you need to monitor?
- What data do you need? How do you want to set up the ETL?
- Before launching a new product, what tests do you want to do?

2. What would you do when a metric drop?
- How do you develop your hypotheses?
- How do you test your hypotheses, and what are the caveats when you set up your tests?

#### Soft Skills and Behavioral Prep:
1. How do you demonstrate that you are a team player?
2. How do you communicate technical knowledge to non-technical audience?
3. How can you convince people using evidence from data, and handle challenges from different parties?
4. How can you move quick in taking measured risks and fix mistakes?
