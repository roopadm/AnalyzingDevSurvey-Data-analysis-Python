<h1 align="center">
  <a href="https://stackoverflow.com/" target="_blank">
    <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/stackoverflow_logo.png" alt="StackOverflow" width="50" height="50" style="vertical-align: middle;"/>
  </a>
  <strong>An Analysis of Developer Communities: Insights from the 2022 Stack Overflow global Survey</strong>
  <a href="https://docs.python.org/3/" target="_blank">
    <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/768px-Python.svg.png" alt="Python" width="50" height="50" style="vertical-align: middle;"/>
  </a>
</h1>

This repository contains an in-depth exploratory data analysis (EDA) and data visualization project using Python of the annual survey data collected by Stack Overflow from its globally dispersed developer community. The project aims to gain insights and explore trends in the data, providing a better understanding of the developer community and their preferences.

The project uses various Python libraries, including Pandas, Matplotlib, Seaborn, and Plotly,this repository provides a comprehensive analysis of the survey data, including descriptive statistics, data cleaning, data preprocessing, and data visualization.

<b>For full narative version of this analysis: <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook">check out my Jupyter notebook.</a></b>

<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/The%20StackOver.png" alt="Projectimage" width="80%" height="10%"/> </a> </p>

This repository serves as a valuable resource for anyone interested in learning about data analysis using Python and gaining insights into the trends and behaviors of developers worldwide.

## Dataset 

The <a href="https://insights.stackoverflow.com/survey/?_ga=2.155663928.223806346.1681222549-2053459658.1677942845">data</a> is the survey responses of 73,268 software developers from 180 countries around the world.The survey was fielded from May 11, 2022 to June 1, 2022.
According to source: <a href="https://survey.stackoverflow.co/2022/#methodology-general">Stack Overflow</a>.


**Prerequisite:** <code>[Python](https://www.python.org/about/gettingstarted/)</code> :hourglass: , <code>[Data analysis with Python](https://jovian.com/learn/data-analysis-with-python-zero-to-pandas)</code> 📑 & <code>[Statistics and probability](https://www.khanacademy.org/math/statistics-probability)</code> 🗂️


## Technologies used ⚙️

* <a href="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/768px-Python.svg.png">Python</a> <a href="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/768px-Python.svg.png" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="25" height="20"/> </a>

* <a href="https://jupyter.org/">Jupyter Notebook</a><a href="https://jupyter.org/" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/jupyternotebook.png" alt="JupyterNotebook" width="25" height="25"/> </a>


##### Python Libraries : 
* <a href="https://pandas.pydata.org/">Pandas</a><a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="25" height="20"/> </a> |  <a href="https://numpy.org/">NumPy</a><a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/2a582d085b324cff4917325112229027309ecae3/Numpy-logo.svg" alt="numpy" width="25" height="20"/> </a> |  <a href="https://matplotlib.org/">Matplotlib</a><a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/1331979c3208a15be2c2a6177ffc38ced3d6b434/Matplotlib_icon.svg" alt="matplotlib" width="25" height="20"/> </a> |  <a href="https://seaborn.pydata.org">Seaborn</a><a href="https://seaborn.pydata.org" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" width="25" height="20"/> </a> |  <a href="https://realpython.com/python-folium-web-maps-from-data/#:~:text=Python's%20Folium%20library%20gives%20you,can%20share%20as%20a%20website.">Folium</a><a href="https://realpython.com/python-folium-web-maps-from-data/#:~:text=Python's%20Folium%20library%20gives%20you,can%20share%20as%20a%20website." target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/folium%20logo.png" alt="Folium" width="20" height="20"/> </a>

### Project Outline
* Install and Import the required libraries.
* Data preparation and cleaning with pandas.
* Performing exploratory analysis and visualization.
* Asking and answering interesting questions.
* Summarizing inferences and drawing conclusions.

### Objective 
<small> 
  
* Examine respondent demographics by gender, age, and education level across countries.
* Explore the distribution of respondents across employment statuses and professional roles.
* Investigate popular programming languages of 2022, preferred languages by company types, and respondents' favorite languages.
* Examine how respondents learn to code and the importance of starting young in programming careers.
* Investigate miscellaneous topics, including respondents' mental health, problem-solving time at work, female respondents' professions, and attitudes towards Blockchain. Additionally, explore the percentage of respondents by gender who have coding as a hobby and the top 15 countries where respondents have coding as a hobby.
</small>

## Exploratory analysis and visualization
Before, we start asking right questions the best is to start with knowing respondents better such as their demographics like country, gender, employment type, education etc.

<h3 style="font-size:30px;color:green;"><a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook">For more on this section check out my notebook</a></h3>

- Respondent Count by Country
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/country.png" alt="Agevsyearsofcoding" width="50%" height="10%"/> </a> </p>

- Distribution of respondent's years of coding
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/yearsofcoding.png" width="50%" height="10%"/> </a> </p>

- Categorical Feature → DevType
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/wordcloud.png" width="50%" height="10%"/> </a> </p>

<h3 style="font-size:30px;color:green;"><a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook">In this project, I have asked 11 questions to explore the trends and understand developer community better.</a></h3>
I have added quick snapshots of what the project brings to you.

## Visualizing few interesting questions asked :

1. Is it important to start young to build a career in programming ?
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/ageVsYearsofcoding.png" alt="Agevsyearsofcoding" width="50%" height="10%"/> </a> </p>

2. Countries with female respondents
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/countrieswithfemalerepond.png" alt="Countries" width="50%" height="80%"/> </a> </p>

3. Which languages are the most liked among survey respondents ? 
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/likedlanguages.png" alt="Languages" width="50%" height="50%"/> </a> </p>

4. Top 15 countries where respondents have coding as a Hobby?
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/codingashobby.png" alt="Hobby" width="50%" height="80%"/> </a> </p>

5.  Which languages are the most  liked among respondents ?
<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook" target="_blank"> <img src="https://github.com/roopadm/AnalyzingDevSurvey-Data-analysis-using-Python/blob/main/Images/likedlanguages.png" alt="Languages" width="50%" height="50%"/> </a> </p>

<h3 style="font-size:30px;color:green;"><a href="https://www.kaggle.com/code/roopamoorthy/an-analysis-of-developer-communities-so-2022/notebook">and much more on my jupyter notebook</a></h3>


## Check out my other projects too : :mag: 👨‍💻 🛰️

<code>[Data-Driven Marketing Strategies for Rider Conversion : Rider Usage Analysis with R and Tableau](https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/edit/main/README.md)</code> 📊

<code>[A Deep Dive into Indian Hardware Company's Sales Performance: Profit and Revenue Analysis with SQL and Tableau ](https://github.com/roopadm/Sales-Performance-Analysis-using-SQL-and-Tableau-AtiQ/edit/main/README.md) </code> 📊

