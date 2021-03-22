
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You will need the standard data science libraries found in the [Anaconda](https://docs.anaconda.com/anaconda/install/) distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing COVID-19 situation in Brazil. Understanding the shape, speed, and location of outbreaks. Specifically, I looked at the following questions:

1. What was the total cases on 2021-03-19?
2. What was the total new cases on 2021-03-19 (for last 24 hours)?
3. What was the total recovered cases on 2021-03-19?
4. What was the total followup cases on 2021-03-19?
5. What was the cumulative COVID-19 deaths on 2021-03-19?
6. What was the total new deaths on 2021-03-19 (for last 24 hours)?
7. What was the Incidence Coefficient of Covid-19?
8. What was the Mortality Coefficient for Covid-19?
9. What was the Covid-19 Lethality Rate?
10. Which region(zone) has the highest cumulative COVID-19 cases on 2021-03-19?
11. Which states have the highest cumulative COVID-19 cases on 2021-03-19?
12. Which cities have the highest cumulative COVID-19 cases on 2021-03-19?
13. Which region(zone) has the highest cumulative Covid-19 deaths on 2021-03-19?
14. Which states have the highest cumulative Covid-19 deaths on 2021-03-19?
15. Which cities have the highest cumulative Covid-19 deaths on 2021-03-19?


## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `BrazilCovid19_DatAnalysis.ipynb` - a JUPYTER notebook containing all performed analisys. It follows the CRISP-DM process.

* `COVIDBR.zip` - contains the  data analysed by the  `.ipynb` file. To use it properly, unzip `COVIDBR.csv` and put it in the same directory as the `.ipynb` file.

The State Health Secretariats and Government is releasing a series of data files with cumulative counts of coronavirus cases in Brazil, at the state and county level, over time. They are compiling this data from state and local governments and health departments in an attempt to provide a complete record of the ongoing outbreak. You can find the original CSV files available on OpenDataSUS and Brazilian Open Data Portal.

## Results<a name="results"></a>

The main findings of the code can be found at the [blog post available here](https://romulloferreira.medium.com/brazil-covid-19-data-analysis-646c78d22d61). And other conclusions at the end of the `BrazilCovid19_DatAnalysis.ipynb` file.

 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

We have no complete official account of COVID-19 cases data in the Brazil, so we have to get this data from the public health authority in each Brazil state and territory (and the Federal District). This data we collect on some open data government sites, like OpenDataSUS.

Must give credit to OpenDataSUS and Brazilian Open Data Portal for the data.  You can find the Licensing for the data and other descriptive information for the COVID-19 data on [OpenDataSUS](https://opendatasus.saude.gov.br/) and [Brazilian Open Data Portal](https://dados.gov.br/dataset).  
