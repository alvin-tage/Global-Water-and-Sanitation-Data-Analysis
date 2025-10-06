🌍 Global Water and Sanitation Data Analysis

This project analyzes and visualizes global access to safe drinking water and sanitation using R.
It focuses on exploring coverage trends, regional differences, and the correlation between clean water and sanitation facilities from 2007–2022.

📊 Overview

The analysis covers:

Distribution and trends of drinking water and sanitation access by region and year

Comparison between countries with the highest and lowest clean water coverage

Geographic visualization using choropleth maps

Correlation analysis between safe sanitation and clean drinking water

All visualizations are created in R Markdown with interactive plots using Plotly and ggplot2.

🧠 Key Insights

Global access to safely managed drinking water and sanitation has steadily increased from 2007–2022

There’s a very strong positive correlation (r = 0.986, p < 0.001) between improved sanitation and access to clean water

Regions such as Europe and Oceania maintain the highest coverage, while Africa shows significant improvement rates

🧩 Tools & Libraries

Language: R

Libraries: tidyverse, plotly, ggplot2, rnaturalearth, countrycode, psych, viridis, RColorBrewer

Methods: Exploratory Data Analysis (EDA), Correlation Test, Data Visualization

📂 Dataset

The dataset was obtained from the official WHO/UNICEF Joint Monitoring Programme (JMP):
🔗 https://washdata.org/data/household#!/table?geo0=region&geo1=sdg

The data contains country-level records on:

Drinking water coverage (drinking_water_dataset.csv)

Sanitation coverage (sanitation_dataset.csv)

👩‍💻 Project Contributors

This project was developed as part of a data analysis course.

Ferdinand David Anggono

Yosia

Rainer Alexander Irawan

Alvin Febrian (R coding and visualization)

📈 Example Visualizations

Global trend of safe drinking water coverage (2007–2022)

Geographic map of 2022 clean water access

Top 10 countries with highest and lowest access

Correlation between clean water and sanitation

📜 License

This project is for educational purposes only. Dataset © WHO/UNICEF JMP — used under fair academic use.
