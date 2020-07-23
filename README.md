# Bay Wheels Data Exploration
## by Shilpa Madini


## Contents

1. data-exploration.ipynb
    * Jupyter notebook file to run the data analysis and visualization on cleaned data set.
2. data-analysis-report.ipynb
    * Jupyter notebook file to capturing the entire data wrangling process.
3. data-exploration.html
       * data exploration report in HTML format
4. explanatory_analysis-slides.html
       * Final analysis report slides in HTML format
5. data
    * 2017-fordgobike-tripdata.zip
        ** Because of GITHUB size limit , I did not add the original file.
    * bikedata_clean.zip
6. output_toggle.tpl
    * toggle file used in slide generation.
7. README.md
8. environment.yaml
    * environment file for this project

## Installation
please follow below instruction to create this project environment on your local desktop.
- download the project folder from the github url
     ```
    git clone https://github.com/shilpamadini/baywheels.git
    ```
- install the conda environment using the environment file. this will create a conda environment with the same name listed in the environment file. this will also install all the required packages for this project
    ```
    conda env create -f environment.yaml
    ```
- list the conda environments
     ```
     conda env list
     ```
- activate the enviroment for bikeshare
     ```
     source activate dand_py3
     ```

## Dataset

> This data consists of 519700 bike rides data recorded for the year 2017.
This dataset can be found at [Bay Wheels  System Data](https://www.lyft.com/bikes/bay-wheels/system-data)


## Summary of Findings

> In this exploration I found that weekdays have more number of rides on weekends.
subscribers have more number of rides than customers. I also found the Top 10
stations where most of the rides originated.I also found that average trip duration varies by user type and day of the week.


## Key Insights for Presentation

> For the presentation I focused mainly on how ridership is affected by user type and the day of the week ride occurs.Subscribers take more
number of rides but their ride duration tends to be shorter and they ride mostly
on weekdays. Customers on the other hand have less over ridership but have longer
average ride duration and they mostly use the bikes on weekends.
