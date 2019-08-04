# San Francisco GoBike Data Analysis Project

In this project, the dataset I analyzed on is trips of a bike-sharing system at San Francisco Area. This data set contains information about 2,472,717 trips from May 2018 to May 2019 collected from [Lyft Bay Wheels](https://s3.amazonaws.com/baywheels-data/index.html).

<sub>This project is provided by Udacity Data Analyst Nano Degree.</sub>

## Motivation

This project will deliver an exploratory data analysis and explanatory analysis. In exploratory analysis part, I will use Python data science and visualization libraries to explore the dataset’s variables, in the process of accessing, cleaning data. The purpose is to better understand data’s structure, patterns and potential relationships. The visualization part is performing in the steps of univariate, bivariate and multivariate explorations. First break down the data explorations in pieces and then gather them to tell the story. 

In explanatory analysis I will integrate the pieces in explorations and leveraged visualizations. The objective is to perform a clear communication on the findings to the audience to tell the data story. 

## The Data

Each trip is anonymized and includes:
•	Trip Duration (seconds)
•	Start Time and Date
•	End Time and Date
•	Start Station ID
•	Start Station Name
•	Start Station Latitude
•	Start Station Longitude
•	End Station ID
•	End Station Name
•	End Station Latitude
•	End Station Longitude
•	Bike ID
•	User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
•	Member Year of Birth
•	Member Gender

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install libraries.

```bash
python3   -m pip install Package_name
```

## Usage

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sb
import os 
import glob
import math
%matplotlib inline
```

## Features
•	Defining topics and asking questions.
•	Performing Data Wrangling and Data Cleaning on data set.
•	Performing Exploratory Data Analysis with visualizations.
•	Summarizing conclusions and limitations.

## Author
This project was completed by Chloe Xue.

## License
MIT
