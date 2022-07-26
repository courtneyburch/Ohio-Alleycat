# Ohio Alleycat Resource
Project for Code Kentucky Data Analysis 2 class, using data from Ohio Alleycat Resource.

# About
[Ohio Alleycat Resource and Spay/Neuter Clinic (OAR)](http://www.ohioalleycat.org/) is a 501(c)(3) organization located in Cincinnati Ohio. OAR has been operating since 1998 with the mission of providing low-cost spay/neuter services, education and outreach, and TNR (trap-neuter-return) programs. OAR also runs no-kill adoption center that accepts cats from other rescue organizations and adopts them to new homes in the Cincinnati tri-state area.

# Project Goals
To conduct extract, analyze, and visualizYou e data related to adopted animals from Ohio Alleycat Resource. 
Questions to be answered include:
- How do factors such as age, sex, or coloring, interact with adoption rates?
- How do geographic factors such as zip code interact with adoption rates?

# The Data
OAR uses a shelter management software program called Animal Shelter Manager 3 (ASM). While the software has extensive built-in data reporting capability, for this this project I aim to extract data from the shelter database and create my own reports.

As a regular volunteer at OAR, I previously had a basic user account that allowed me to access the Ohio Alleycat account on the ASM web application in order to view and update animal information and conduct adoptions. To allow me to pursue this project, the OAR director gractiously upgraded my account to developer status, allowing me to view and create queries on the database.

# Data Extraction
To learn about the Animal Shelter Manager software, I used the excellent documentation found 	[here](https://sheltermanager.com/repo/asm3_help/index.html). To query the database and extract the data I needed into csv files, I used the dictionary of [Database Tables/Columns](https://sheltermanager.com/repo/asm3_help/databasetables.html#) and the [Entity Relationship Diagrams](https://sheltermanager.com/repo/asm3_help/relationships.html).

Queries I wrote to extract data can be found in sql.md.

# Data Analysis

Can be found in oar_data.ipynb

# Visualization

Can be found on [Tableau public](https://public.tableau.com/app/profile/courtney.burch/viz/OhioAlleycat/Dashboard1) 

# Code Kentucky Requirements

1. Loading Data
- Read TWO data files (JSON, CSV, Excel, etc.). 

2. Clean and operate on the data while combining them
- Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.  

3. Visualize / Present your data
- Make at least 1 Pandas pivot table and 1 matplotlib/seaborn plot. 
- Make a Tableau dashboard to display your data.

4. Best practices
- Utilize a virtual environment and include instructions in your README on how the user should set one up

# Running the project

1. Set up a virtual environment and activate it:
`python -m venv venv`
Windows:
` venv/Scripts/activate`
Mac/Linux:
`source venv/bin/activate`
2. Install requirements.txt
`python3 -m pip install requirements.txt`
3. run oar_data.ipynb in Jupyter Notebook









