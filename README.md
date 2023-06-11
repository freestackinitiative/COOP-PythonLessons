# Introduction to Python for Data Analysis

Welcome to Introduction to Python for Data Analysis!  Over the course of these five lessons, we will guide you through the basics of Python and how to use it for data analysis. We start out by teaching you just enough Python fundamentals to get you familiar with syntax, basic data structures, and control flow. Then we take you through using two of the most popular data analytics libraries, `pandas` and `matplotlib`, to learn the basics of data cleaning, processing, and visualization using Python. In our final lesson, we combine everything you have learned so far into a mini-project where we guide you through performing Exploratory Data Analysis (EDA) using Python, `pandas`, `matplotlib`, and SQL.   

## Lessons

Click on any lesson to learn more about it and access those resources:

- [Lesson 1 - Python Fundamentals](#lesson-1---python-fundamentals)
- [Lesson 2 - Basic Control Flow & Algorithms](#lesson-2---basic-control-flow--algorithms)
- [Lesson 3 - Elementary Exploratory Data Analysis with  `pandas`](#lesson-3---elementary-exploratory-data-analysis-with-pandas)
- [Lesson 4 - Data Visualization with Python & `matplotlib`](#lesson-4---data-visualization-with-python--matplotlib)
- [Lesson 5 - A Guided Exploratory Data Analysis using Python and SQL](#lesson-5---a-guided-exploratory-data-analysis-using-python-and-sql)

## Prerequisites

There are no prerequisites for this course. We structured this course with the beginner in mind, so if you have never written code then this is for you! Of course, if you already have a coding background, then this material may be more of a refresher.

## How do I access the materials and what do I need in order to use them?

All you need to use the materials in this course is a valid Google account and an internet connection. *That's it.* There are links to all the course material you'll need down in the [Course Outline](#course-outline) below. You do not need to set anything else up.

### What if I already have Anaconda/VSCode/some other coding environment already set up?

If you already have your own coding environment set up, you can simply download the course files from this repository and run them in your environment. However, since each environment can look different across machines and operating systems, we will not be providing direct support for issues related to your environment (e.g. Why can't Anaconda find this library?)

### What if I want to set up my own coding environment to use for the course?

You may set up your own coding environment for this course if you wish. However, if you have not had prior experience with this or with coding, we recommend completing the course using the cloud resources we set up *first* before setting up your own environment. There is quite a bit of management going on behind the scenes with setting up environments for these course materials to be executed smoothly, which you will have to manage on your own in a local environment. 

As far as coding environments, we recommend using either [`Anaconda`](https://www.anaconda.com/download) or [`Miniconda`](https://docs.conda.io/en/latest/miniconda.html). They are essentially the same, but `Miniconda` comes with less preinstalled software out-of-the-box, so it is "lighter" to use than `Anaconda`, which has more pre-installed software and will take up more space on your system. 

[This presentation shows you how to install Anaconda on your local machine](https://docs.google.com/presentation/d/1zr-q-rARXpMhe_f8ukyZeFz34lsma5jg55RNO96FiXU/edit?usp=drive_link)

## What you can expect after completing this course

This course is meant to give you a hands-on introduction to Python and how it can be used in the data analytics process. After completing it, you will have a rudimentary understanding of Python syntax and basic programming concepts, as well as how to apply those concepts to exploratory data analysis using popular libraries. Our goal is simply to introduce you to these concepts - not to provide a rigorous study that would prepare you for technical interviews (at least not with this material alone.) 

What this course does prepare you for:
- Further study with Python or other programming languages

What this course does *not* prepare you for: 
- Python technical interviews
- Technical roles such as data scientist, data engineer, or software developer

After completing this course, we strongly encourage you to pursue further studies in programming with Python (or any other programming language you like) - especially if you would like to get into a more technical role. Again, this course can be considered foundational, but it is not enough by itself to prepare you for more technical roles.

## Course Outline

Each lesson is outlined below. For each one, we use Jupyter Notebooks to run our Python code. To access the Jupyter Notebook for a given lesson, simply click on the <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/> button for that lesson. We also include a link to the accompanying presentation for each lesson.

---
### **Lesson 1 - Python Fundamentals**
**Notebook**: <a href="https://colab.research.google.com/github/freestackinitiative/COOP-PythonLessons/blob/main/lessons/lesson1/Lesson%201.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Slide Deck**: [Click here](https://docs.google.com/presentation/d/1rMA7wX07vFyc6XBrd8iTl6BEFfTsdm1Mo-8Lod4Easg/edit?usp=drive_link) to view the presentation for this lesson

To start things off, we introduce you to fundamental syntax and data structures in Python. After completing this lesson, you will know:
- What objects are in Python and their three fundamental properties
- How variables work and how to use them in our code
- How to perform basic arithmetic and logical operations
- How the basic container data structures (strings, lists, tuples, and dictionaries) work
- The basics of slicing and indexing

[Back to top](#lessons)

---
### **Lesson 2 - Basic Control Flow & Algorithms**
**Notebook**: <a href="https://colab.research.google.com/github/freestackinitiative/COOP-PythonLessons/blob/main/lessons/lesson2/Lesson%202.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Slide Deck**: [Click here](https://docs.google.com/presentation/d/1lbbsTjzqm5Uzm7rsSSf_kXdUht13e2wg9QeVLLIwgIs/edit?usp=drive_link) to view the presentation for this lesson

Following up on our previous lesson, we introduce you to basic control flow concepts (if/else statements & loops) and functions. After completing this lesson, you will know:
- How we can control the flow of our program's execution using basic control flow concepts
- How to execute different code based on conditions that we specify using if/else statements
- How to use both `for` and `while` loops to repeatedly execute code in an efficient manner
- How functions work in Python and how to create your own custom functions
- How to use basic control flow and functions to create algorithms that solve problems

[Back to top](#lessons)

---
### **Lesson 3 - Elementary Exploratory Data Analysis with Pandas**
**Notebook**: <a href="https://colab.research.google.com/github/freestackinitiative/COOP-PythonLessons/blob/main/lessons/lesson3/Lesson%203.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Slide Deck**: [Click here](https://docs.google.com/presentation/d/1UvhIfG0yuYpEKvOvQzH1DULn5N2_IZP_E-Bh3IRnzZ8/edit?usp=drive_link) to view the presentation for this lesson

After learning just enough basic Python, we introduce you to `pandas` - one of the most popular (and ubiquitous) Python libraries for working with data. We'll show you the basic methods you should know in order to explore and understand your data. Since a lot of the operations we perform here have parallels in SQL, we will show the connections between the two concepts where applicable. After completing this lesson, you will know:
- What `DataFrames` are and how to use them to work with your data
- How to read data stored in CSV files and manipulate it using `DataFrames`
- Basic data manipulation using `pandas`, including how to select rows and columns, filtering, joining your data with other data sets, renaming columns, and dealing with null values
- How to use built-in `pandas` features to view metadata and gain a better understanding of your data

[Back to top](#lessons)

---
### **Lesson 4 - Data Visualization with Python & matplotlib**
**Notebook**: <a href="https://colab.research.google.com/github/freestackinitiative/COOP-PythonLessons/blob/main/lessons/lesson4/Lesson%204.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Slide Deck**: [Click here](https://docs.google.com/presentation/d/1co_Af34Xyc0WmAYfXWAD478lNGpNzoiahPYuc-dT0iU/edit?usp=drive_link) to view the presentation for this lesson

Part of working with data is creating visualizations to help us better understand it and communicate our findings. In this lesson, we introduce you to `matplotlib` - a popular library for creating visualizations with Python. After completing this lesson, you will know:
- How to create basic graphs with `matplotlib`, such as histograms, line charts, bar charts, and pie charts
- How to customize your charts using parameters offered by `matplotlib`

[Back to top](#lessons)

---
### **Lesson 5 - A Guided Exploratory Data Analysis using Python and SQL**
**Notebook**: <a href="https://colab.research.google.com/github/freestackinitiative/COOP-PythonLessons/blob/main/lessons/lesson5/Python%20105%20-%20Exploratory%20Data%20Analysis" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Slide Deck**: [Click here](https://docs.google.com/presentation/d/11EOfWXflQD0w10yBW_sNrzOtTfigPPReWk5IhcbnEdM/edit?usp=drive_link) to view the presentation for this lesson

In this final lesson, we combine all of the concepts you have learned in the previous four lessons and guide you through an Exploratory Data Analysis using the Data Science Salaries data set. 

Here is the scenario: 

*You are a data analyst working for a company that just received this data set and your management team wants you to explore it. They have some some questions about the data they would like you to answer. Additionally, they want you to give any insights you may find after exploring the data.*

This is a comprehensive mini-project that will test your understanding of basic data analysis, Python, `pandas`, `matplotlib`, and SQL (optional) concepts. After completing this lesson, you will know:
- How to perform a basic Exploratory Data Analysis using Python and SQL
- How to structure and communicate your findings in a professional manner

[Back to top](#lessons)

---