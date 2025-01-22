# Recommendation-Engine
Building a recommendation engine for articles on the IBM Watson Studio

### Table of Contents
 
1. [Project Motivation](#motivation)
2. [Data](#data)
3. [Files](#files)
4. [Libraries](#libraries)

## Project Motivation <a name="motivation"></a>

The goal is building a user based recommendation engine for articles on [IBM Watson Studio](https://dataplatform.cloud.ibm.com/login)

## Data <a name="data"></a>
The data provided consist of two .csv Files:
<ul>
  <li>user-item-interactions.csv - contains 45993 destinct interactions between users and articles
  <li>articles_community.csv - contains 1051 articles (id, name, description, body, status) 
</ul>

## Files <a name="files"></a>

<p>The following files are provided within this project:</p>

<ul>
  <li><b>Recommendations_with_IBM.ipynb:</b> Jupyter notebook containing the recommendation engine</li>
</ul>

<ul>
  <li><b>README.md:</b> this file</li>
</ul>

## Libraries <a name="libraries"></a>

I used a Jupyter notebook (Python) for the analysis. The ipynb file should run on any Python 3 version (3.0.* or higher) without any problems.</br>

Here are the additional Python libraries used within this project:

<ul>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>pickle</li>
  <li>matplotlib.pyplot</li>
</ul>
