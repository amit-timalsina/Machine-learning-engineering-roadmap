# End to End machine learning

![Machine learning project lifecycle](https://github.com/amit-timalsina/Machine-learning-engineering-roadmap/blob/master/assets/ML%20project%20lifecycle-2%20Large.jpeg)

Machine learning is not just about building a model using some publicly available clean data. There are multiple steps that are required to build an ML product. The above figure shows the end to end steps required to build a machine learning product that could potentially make an impact. I have a dedicated [article series](https://amit-timalsina.medium.com/list/machine-learning-project-lifecycle-4ba518381213) that goes into details of each step shown in above diagram.

I will divide the resources into different levels of learning and will also provide the best resources to learn each topic. The levels of learning are:

1. Getting ready to learn data science 📊
2. Core Data Science Fundamentals 📈
3. Machine Learning Engineering 🤖

## 1. Getting ready to learn data science 📊

### Applied Mathematics 🔢

Applied Mathematics is a combination of Linear Algebra, Statistics, Probability, and Calculus. There is a lot of buzz that you need to be really great at mathematics for getting into Data Science🤔. Unless you want to be Machine Learning Researcher than fundamentals of the above topics is sufficient. Even better would be having good some grasp of high school Mathematics. You can always go to grad school to be a Machine Learning researcher or start learning complicated mathematics after you land a job.

Nonetheless, below i mention some great resources on coursera by Imperial college of London for Linear Algebra and Calculus. Their videos are publicly available on YouTube 🎥. For statistics & Probability, I have some great recommendations of courses by MIT OpenCourseWare 🎓.

- **Linear Algebra**: Mathematics for Machine Learning: Linear Algebra ([Coursera](https://www.coursera.org/learn/linear-algebra-machine-learning?specialization=mathematics-machine-learning)), ([YouTube](https://www.youtube.com/playlist?list=PLiiljHvN6z1_o1ztXTKWPrShrMrBLo5P3))
- **Statistics**: MIT 18.650 Statistics for Applications ([YouTube](https://www.youtube.com/playlist?list=PLUl4u3cNGP60uVBMaoNERc6knT_MgPKS0))
- **Probability**: MIT 6.041SC Probabilistic Systems Analysis and Applied Probability ([YouTube](https://www.youtube.com/playlistlist=PLUl4u3cNGP60A3XMwZ5sep719_nh95qOe))
- **Calculus**: Mathematics for Machine Learning: Multivariate Calculus ([Coursera](https://www.coursera.org/learn/multivariate-calculus-machine-learning)), ([YouTube](https://www.youtube.com/playlist?list=PLiiljHvN6z193BBzS0Ln8NnqQmzimTW23))

### Programming Language 💻

#### **Deciding a Language**:

Programming languages are essential tools for machine learning (ML) engineers, data scientists, and researchers to develop and deploy ML models 🚀. Machine learning requires programming languages that are capable of handling large datasets, performing complex computations, and integrating with powerful libraries and frameworks. The choice of programming language is critical for machine learning projects because it can affect development time, model performance, and scalability.

When it comes to choosing a programming language for machine learning, there are several criteria to consider:

- Learning curve: Ease with which a language can be learned.
- Community: A language with a large and active community means that there are more resources, tools, and support available online.
- Libraries and Frameworks: Existing libraries for every step of the machine learning pipeline as show in cover image of this article.
- Industry demand: You should consider the industry demand for different languages.
- Performance: Performance is a critical factor to consider when working with large datasets.

Python and R are most popular languages for machine learning. Other programming languages are Julia, Java, and C++. Let's see their comparison based on the criteria we discussed above:

Comparison of languages based on different criteria:

![Fig 2: Machine learning project lifecycle](https://github.com/amit-timalsina/Machine-learning-engineering-roadmap/blob/master/assets/Screenshot%202023-03-11%20at%2011.50.26%20AM.png)

If you want to be a software engineer with skills in machine learning, go with Python - you don't even need to think twice. On the other hand, if you want to be a data scientist, you could choose either Python or R. But remember python will give you flexibility in your career if you ever want to pivot. On a personal note, I recommend python 🐍.

Congrats, you completed the first step on your journey 🎉.

#### **🐍 Python for Beginners**:

[Programiz](https://www.programiz.com) creates great resources for python developers of all levels. Their basic courses are a combination of video and text resources which have been praised by many.

- 🎥 Introduction to Python (Basic): https://www.youtube.com/playlist?list=PL98qAXLA6afuh50qD2MdAj3ofYjZR_Phn/

Object oriented programming is really important for machine learning especially when you start working on pytorch and transformer based architecture. But no worries this 🎥 (Object oriented programming (OOP))[https://www.youtube.com/playlist?list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc] course on YouTube has got you covered.

🔗 Below are additional resources just in case above are not up to your taste:

- https://developers.google.com/edu/python
- https://python.swaroopch.com/

<mark style="background-color: grey;">Note: **Interviewers love to ask questions on Data Structures and Algorithms (mainly for roles other than interns).** I have not mentioned resources for them here. But you can revisit them once after you complete all the steps mentioned here. Don't stress it a lot at beginning.</mark>

## 2. Core Data Science Fundamentals 📈

### Data Collection & Exploration 🔍

Data collection and Data exploration are the core Data Science Fundamentals as show in ML Lifecycle figure. Python libraries Numpy, Pandas, and Matplotlib will be you aid for core data science.

📗 Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter by Wes Mckiney will be more than sufficient. A Beginner shall start with this book as it covers basic Python, ipython, NumPy, Pandas, and Matplotlib followed by few documented data anlaysis projects with code implementation.

I have seen a lot of people skip learning the core data science fundamentals for flashy Deep learning, which creates a lot of problem later when we start working on End-to-end machine learning to solve a business problem. So better learn them.

**Additional resources:**
- 🔗 [Data Analysis with Python: Zero to Pandas](https://jovian.com/learn/data-analysis-with-python-zero-to-pandas)
- 📗 [Python Data Science Handbook (Chapter 1–4)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/02.01-Understanding-Data-Types.ipynb)

Tip: All the libraries mentioned above, have elegant documentation. Feel free to explore them as well.

## SQL

Data Science is the all-around study of data. To work with data, we need to extract it from the database. This is where SQL comes into the picture. SQL is the most widely used programming language while working with databases and supported by various relational database systems, like MySQL, SQL Server, and Oracle. A Data Scientist can control, define, manipulate, create, and query the database using SQL commands.

Many modern industries have equipped their products data management with NoSQL technology but, SQL remains the ideal choice for many business intelligence tools and in-office operations.

Many of the Database platforms are modeled after SQL. This is why it has become a standard for many database systems. Modern big data systems like Hadoop, Spark also make use of SQL only for maintaining the relational database systems and processing structured data.

I have heard good things about 🔗[SQL Tutorial - Full Database Course for Beginners](https://www.youtube.com/watch?v=HXV3zeQKqGY) course available on YouTube.

### Additional resources:
- 📗[SQL for Data Analysis Cathy Tanimura](https://www.oreilly.com/library/view/sql-for-data/9781492088776/)
- 📗[Learning SQL](https://www.oreilly.com/library/view/learning-sql-3rd/9781492057604/)


Notes: 
1. Interviewers love to ask SQL questions for data science roles.
2. People usually have question around learning Big data tools in initial phases of data science, I personally think, it's not necessary to learn big data tools in initial phases of data science, but if you're interested in learning it, you can learn it later on. There are different perspectives on this, i would like you to check out the answers from this [quora answer](https://www.quora.com/Do-you-need-to-know-big-data-tools-like-Hadoop-and-Spark-to-be-a-data-scientist/answer/Sean-Owczarek).

## 3. Machine Learning Engineering 🤖

### Data Preparation/Feature Engineering

Most of the times, the raw data can't be directly fed into a model. These raw data need to be prepared according to the model and task at hand. Data preparation is important regardless of the model being machine learning or deep learning. Feature engineering is needed for Machine learning while Deep learning is about learning those features through neurons.

Data preparation varies a lot based on project and data. So, having good knowledge of python helps a lot. You will have to learn different libraries based on your requirement (your data preparation skills improve as you work on more projects). My suggestions for learning Data preparation and feature engineering are provided below:

- 🎥 [Feature Engineering Krish Naik Playlist](https://www.youtube.com/playlist?list=PLZoTAELRMXVPwYGE2PXD3x0bfKnR0cJjN) (YouTube)
- 📗 [Approaching almost any Machine Learning problem](https://github.com/abhishekkrthakur/approachingalmost/raw/master/AAAMLP.pdf) (Chapter 6,7, 8)](Book available for free)
- 🔗 [Data Preparation and Feature Engineering in ML](https://towardsdatascience.com/data-preparation-and-feature-engineering-in-machine-learning-95a1581673c) (Article)
- 🔗 [Advanced Feature Engineering Tutorial](https://www.kaggle.com/ryanholbrook/advanced-feature-engineering-tutorial) (Kaggle Course)

### Machine Learning

For Machine Learning, I just have two suggestions for you.

- 🎥 [Machine Learning Specialization 2022 - Andrew Ng, Stanford University](https://www.coursera.org/specializations/machine-learning) -> This is the updated course and is perfect for 2023.
- 📗 [Hands-On Machine Learning with Scikit-Learn and TensorFlow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow-ebook/dp/B07XGF2G87) by Geron Aurelien (Part 1)

### Deep Learning

MIT 6.S191: Introduction to Deep Learning is an ongoing course you can find details on the [website](http://introtodeeplearning.com/). This course has video lectures, code assignments, and great projects all of which will help you to have a good portfolio. None of my other suggestions are going to beat this if you sincerely complete the whole course.

- 📗[Hands-On Machine Learning with Scikit-Learn and TensorFlow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow-ebook/dp/B07XGF2G87) by Geron Aurelien (Part 2)
- [DeepLearning.AI TensorFlow Developer Professional Certificate](https://www.coursera.org/professional-certificates/tensorflow-in-practice) - Coursera

Deep Learning has different domains like reinforcement learning (RL), Natural Language Processing (NLP), and Computer Vision(CV). The above MIT course has good resources for RL and CV but it misses to talk about NLP. Below are resources for it.

- 🎥 [Natural Language Processing with Deep Learning (Stanford University)](https://web.stanford.edu/class/cs224n/) [NLP]
- 📗 [Practical NLP from O'REILLY](https://www.oreilly.com/library/view/practical-natural-language/9781492054056/)

Note: A lot of university courses for Machine Learning Engineering are public. You just need to search them on youtube and go through their playlist.

### MLOPs

MLOPs is a combination of Model Deployment, Model Serving, Model Monitoring, and Model Maintenance. I struggled a lot to learn about MLOPs because i couldn't find good resource for it. I recently came across a MLOPs course that has everything required. I learned about all those topics separately but this course has everything in same place.

- 🔗 [MLOPs by MadewithML](https://madewithml.com/courses/mlops/)

I will also recommend 📗 [Practical MLOPs by Alfredo Deza and Noah Gift](https://www.oreilly.com/library/view/practical-mlops/9781098103002/).

## Upcoming Topics 📚

This repository is a work in progress, we will be adding more topics in the future, you can check out the following topics which we will be adding in the future:-

- Data science projects, 
- Detailed Guide to Data Science Portfolio, 
- Detailed Guide to Data Science Resume, 
- Preparing for Job interviews, and many more.

### Contributions 🤝

I am open to contributions. If you want to contribute to this repository, just submit a pull request. I will review and merge it. The only criteria is that it should help fellow learners.
