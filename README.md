## PROJECT WEB SCRAPING

### Table of Contents

1. [Installations](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [How to Interact with my project / Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## 1. Installations <a name="installation"></a>
There some libraries that you should install to run this python code shared in jupyter notebook. They are:

	1. pandas
	2. urllib
	3. bs4
		
<p align="justify">You can install all of them using pip install <librarie_name> or you can add one more cell in jupyer notebook e write !pip install <librarie_name>
All module used in this project can be see below. They were extracted from the libraries mentioned above.</p>

	import bs4
	import urllib.request as urllib_request
	import pandas
	
Beisdes, only to complement, I developed the project using python version 3.8.5. You check the python version with this command:

	!python --version	

## 2. Project Motivation<a name="motivation"></a>

<p align="justify">The motivation for this project was to create a knowledge base to provide structured data in CSV format of vehicle advertisements on the OLX website. In this way, this knowledge base can be used in a data pipeline to apply a machine learning model to estimate vehicle value, categorize vehicle types as well as identify possible groupings in the data.</p>

## 3. File Descriptions<a name="files"></a>

This project consists of the files below:

<ul>		
	<li><p align="justify">Web_Scraping_OLX_Carros: In this file you will find all code developed in python such as the organization and use of the phases to create the web scraping.</p>
	<li><p align="justify">Exploratory Data Analysis (EDA) files: Here, you will find the files generated using two approaches of exploratory data analysis. They are: EDA - Dados de Anúncio dos carros da OLX.html and EDA - Sweetviz - Dados de Anúncio dos carros da OLX.html</p>
	<li><p align="justify">Folder Output: This folder contains the result of the web scraping where the data is saved in the file dataset.csv. In the img folder, the images of each car extracted from the captured ads can be found.</p>
	<li>Report of Web_Scraping_OLX_Carros: In this file, you can check the code developed as well as a report.
</ul>

## 4. How to Interact with my project / Results<a name="results"></a>

<p align="justify">To interact with this project, just open the jupyter notebook called Web_Scraping_OLX_Carros.ipynb and run the cell with the codes created. A table will be generated with the columns: Value, Title, Mileage, Exchange, Fuel and Location.</p>

## 5. Licensing, Authors, Acknowledgements, etc.<a name="licensing"></a>

<ul>
	<li><p align="justify">https://www.alura.com.br/conteudo/web-scraping-data-science-python</p>
</ul>
