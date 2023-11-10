<h3 align="center">
HI THERE, WE'RE <b>TEAM SINTRA</b> 👋
</h3>  

<h2 align="center">
ECONOMIC INEQUALITY ML PREDICTION
</h2>


![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white%29)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

# Machine Learning API using FastAPI

## Introduction

Economic Inequality  is a disparity in distribution of income between individuals, groups, populations, social class or countries. Income is the major determinant of quality of life and varies by social factors such as age, sex, race etc. On global level, the richest 1 percent of people in the world receiving as much as the bottom 56 percent in the early 21st century.

Further Information : [britannica](https://britannica.com/money/topic/income-inequality)

This project uses Docker container to create a containerized application that serves a model prediction with FastAPI. Docker is a tool that allows you to package and run applications in isolated environments, making them portable, secure, and easy to deploy. the docker file is on Hugging Face.

Hugging Face is a platform that provides state-of-the-art natural language processing models and datasets. FastAPI is a modern web framework that simplifies the development of RESTful APIs with Python. By combining these tools, you can build a scalable and robust machine learning app that can handle various natural language tasks.

## Setup

For manual installation, you need to have [`Python3`](https://www.python.org/) on your system. Then you can clone this repo and follow the steps below:

- Windows:

        python -m venv venv; venv\Scripts\activate;
        python -m pip install -q --upgrade pip;
        python -m pip install -qr requirement.txt

- Linux & MacOs:

        python3 -m venv venv; source venv/bin/activate;
        python -m pip install -q --upgrade pip;
        python -m pip install -qr requirement.txt

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

## How to Run

The project consists two application. The first one accepts inputs from the user and return result with its confidentiality score. The second on accepts csv file which has input of various rows that going to be predicted. So the app read the file and retrieve records and predict for each rows and append the result with confidentiality score.

## 1. App For Filling Form

- Adjust the path

       cd "Economic Inequality\Applications\App_For_Accepting_Forms"

- Then run the python file

      py main.py

- Then browse to

      http://127.0.0.1:8000/docs

## 2. App for Uploading file

- Adjust the path

       cd "Economic Inequality\Applications\App_for_Uploading_File"

- Then run the python file

      py main.py

- Then browse to

      http://127.0.0.1:8000/docs

## 3. Docker in Hugging Face

- You can also run the app from Hugging Face docker image by clicking the following links

   https://henok21-economic-inequality.hf.space/docs

   https://henok21-economic-inequality-loader.hf.space/docs

## Screenshots
<h3>API for Accepting File</h3>

![image](screenshots/file%20upload%20screenshot.png)

<h3>API for Filling A Form </h3>

![image](screenshots/form%20screenshot.png)


### 🤝 Connect with US :
<ul>
<b>
<li><a href="mailto:henok.dirirsa@azubiafrica.org">Henok Solomon Dirirsa</a></li>
<li><a href="https://www.linkedin.com/in/petereduah/">Peter Kobena Eduah </a></li>
<li><a href="https://www.linkedin.com/in/calistus-saratuki/">Calistus Saratuki Wanyama</a></li>
<li><a href="https://www.linkedin.com/in/lawrencelarweh/">Lawrence Larweh</a></li>
<li><a href="https://www.linkedin.com/in/pascal-wambua/">Pascal Wambua </a></li>
</b>
</ul>
