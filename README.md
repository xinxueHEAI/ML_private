# Private Repository for ML Instruction

### DS/MLE Interview Cheatsheet

*The term 'Data Scientist' is too broad. You NEED to know what your expertise is and what kind of DS aligns better with your career goals. That is, before applying for the positions, read carefully about the job descriptions. In general, here are what the job description would indicate*
- Data Scientist (Analytics): product driven, very analytical, visualization, sql intensive, ab testing, work intensively with product manager + products + propose/ validate ideas around products
- Data Scientist (Engineering): statistical + ML modeling, ab testing, optimization; work along with engineers; write production code
- Machine Learning Engineer:  DL, CV and/or NLP, real time serving, recommendation system; full-stack of ML serving pipelines
- Research Scientist/ Applied Scientist/ Data Scientist (Research/ Core): research driven, frontier methodology development; robotics + reinforcement learning; typically requires a PhD in CS, EE, Stats, Physics or Applied Math

#### CORE Technical Knowledge: (Know them cold, A.K.A, whiteboard them from scratch; no other way around)
1. Basic Probability: Distributions, Brainteaser Problems, Bayesian/Conditional Probability, Maximum Likelihood
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
2. Pandas/R: basic <--> advanced data manipulation (anything written in SQL, rewrite them in Pandas/R)
3. Optional for some DS; Required for all MLEs, Leetcode (Algorithms: BFS, DFS, Heap/Merge-sort, DP; Data Structures: ListNode, BST, Hashtables; Complexity Analysis: Time-Space, NP-Hard)
4. Optional for DS; Required for most MLEs: System design, Kafka and real-time serving
5. Nice to know: vim, git, bash

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

#### During the interviews
1. If you know you do not know the answer, say that you don't know! Don't guess or dance with the experts. You will surely make a joke of yourself.
2. To avoid 1., do not write something you just heard of on your resume. 
3. Communication is the key. You need to explain your thought process. 
4. Always ask for clarification! Re-interate and make sure they know that you understand. 
5. Make propositions and look for signals. Typically an interviewer wants to hear certain answers. Your interview score largely depends on these key points.
6. Sense the signals from the interviews
- Some interviewers prefer a focused solutions; deepdive in this case. 
- Some interviewers prefer a wide-range of solutions; you need to activated your neurons and brainstorm.
7. The last thing you want to be is a jerk. Don't be cocky or easily irritated. You are expected to be coachable. 
8. Don't intend to show off. You want to impress people by being yourself and leading a healthy and constructive discussion. 
9. Regardless how tough the questions are, most interviewers will appear to be nice and warm; some are cold with a poker face; and some are straighly mean and unprofessional. You should be able to keep your composure and stay focused. 
10. Your interviewers are likely to treat you as if you are a colleague. You are not a robot, share a laugh and be a human being. 

The interviewing process is costly to both interviewers and interviewees. Be stressed out and well-prepared before the interview, and enjoy the conversation!
