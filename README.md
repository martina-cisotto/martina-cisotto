# Martina Cisotto

Data Science Master's student with a background in Statistics. I like turning math, probability, and algorithmic theory into clean, scalable code that solves actual problems. 

Right now, I'm working with machine learning, large-scale data processing in PySpark, and mathematical optimization. I am currently looking for a curricular internship where I can write my Master's thesis with an analytics or data science team, learn from real-world datasets, and ideally continue into a full-time role after graduating.

---

### Areas of Expertise

* **Programming & Tools:** Python (Pandas, NumPy, Scikit-learn), PySpark, R, SQL
* **Machine Learning & AI:** Machine Learning, Deep Learning, Natural Language Processing (NLP), Numerical Optimization
* **Quantitative & Big Data:** Statistics, Probability, Distributed Computing, Game Theory

---

### Key Projects

* **[Distributed Fair k-Center Clustering](/martina-cisotto/Distributed_Fair_k-Center_Clustering)**
  * Built **MRFairFFT**, a two-round MapReduce framework in Apache Spark to solve the k-center clustering problem under demographic group fairness constraints (`kA, kB`).
  * Handled large-scale data across Spark partitions using a coreset approach via `mapPartitions` for local candidate extraction, followed by driver consolidation to guarantee bounded radii while avoiding demographic under-representation.
  * *Tech Stack:* PySpark, Apache Spark, Python.

* **[Streaming Frequent Items Estimation](/martina-cisotto/Streaming_Frequent_Items_Estimation) (PySpark)**
  * Developed a streaming analytics pipeline with Spark Streaming to process live network data ingested over a TCP socket.
  * Implemented and benchmarked **Sticky Sampling** and **Count-Min Sketch** from scratch to find heavy hitters in sub-linear space, comparing their empirical error and memory usage against ground-truth counts.
  * *Tech Stack:* PySpark Streaming, Socket Programming, Python.

* **[Multiclass Logistic Regression](/martina-cisotto/Multiclass_Logistic_Regression)**
  * Implemented first-order optimization algorithms from scratch using NumPy to minimize negative log-likelihood on high-dimensional data.
  * Built standard **Gradient Descent (GD)** and **Block Coordinate Gradient Descent (BCGD)** with the Gauss-Southwell greedy rule.
  * Ran Lipschitz constant grid search and benchmarked convergence versus CPU runtime on synthetic data and the real-world **ISOLET5** speech dataset.
  * *Tech Stack:* Python, NumPy, Matplotlib, SciPy, Scikit-learn.
