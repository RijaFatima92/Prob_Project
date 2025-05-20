# COVID-19 City-wise Data Analysis in Pakistan using R & Shiny

This project presents an interactive dashboard built with **R** and **Shiny** to analyze COVID-19 data from **February to April 2020** across various cities in **Pakistan**. It helps users understand the regional impact of the pandemic through statistics, visualizations, and predictive modeling.

## 🔍 Features

- 📊 **Statistical Summaries**: City-wise breakdown of confirmed, recovered, and death cases.
- 📈 **Interactive Graphs**: Visualizations for trends and comparisons across cities and time.
- 📉 **Probability Estimations**: Likelihood of recovery or death from the virus based on available data.
- 🔮 **Predictive Modeling**: Linear regression to forecast future case counts.
- 🧭 **User-Friendly Dashboard**: Built using Shiny for real-time exploration and insights.

## 🗃️ Dataset

The dataset includes reported COVID-19 cases in Pakistan from **February to April 2020**, organized city-wise. It includes:

- Date of report  
- City  
- Number of confirmed, recovered, and death cases  

> *Note: This is historical data and may not reflect current conditions.*

## 🛠️ Technologies Used

- **R** – Data analysis, modeling, and visualization  
- **Shiny** – Web-based interactive dashboard  
- **ggplot2** – Custom visualizations  
- **dplyr** & **tidyr** – Data manipulation  

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/covid19-pakistan-analysis.git
````

2. Open the project in RStudio.
3. Install required packages if not already installed:

   ```R
   install.packages(c("shiny", "ggplot2", "dplyr", "tidyr"))
   ```
4. Run the app:

   ```R
   shiny::runApp()
   ```

## 📌 Project Structure

```
├── app.R               # Main Shiny app file
├── data/               # COVID-19 dataset files
├── plots/              # Graphs and visualizations (optional)
└── README.md           # Project description
```

## 📚 Acknowledgments

* Data sources: [National Institute of Health Pakistan](https://www.nih.org.pk/)
* Visualization inspiration from TidyTuesday and R Graph Gallery

