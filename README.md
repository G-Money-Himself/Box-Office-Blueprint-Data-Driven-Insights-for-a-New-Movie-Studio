![Box Office](Box_Office_Image.jpeg)
# Box Office Blueprint: Data-Driven Insights for a New Movie Studio
## Overview
This project aims to use a Linear Regression Model to target numeric variables such as **domestic_gross** and **foreign_gross** to determine therir impact on how well box office movies are performing.  Linear regression is a fundamental predictive modeling technique suitable for estimating continuous outcomes based on one or more independent variables (e.g., **year**, **studio**)
## Business Problem 
My company now sees all the big companies creating original video content and they want to get in on the fun. And have decided to create a new movie studio, but they don’t know anything about creating movies. So I will be exploring what types of films are currently doing the best at the box office and translate those findings into actionable insights that the head of the company's new movie studio can use to help decide what type of films to create.
## Data Analysis Approach
The goal was to examine the below factors;
- **1. Predict Domestic Box Office Revenue Based on Year and Studio**
- **2. Estimate Foreign Gross Earnings Using Domestic Performance**
- **3. Predict Total Gross Revenue (Domestic + Foreign) Using Available Features**
- **4. Analyze the Trend of Domestic Revenue Over Time**
- **5. Compare Studio Impact on Revenue While Controlling for Year**
## Key Findings
- **Predict Domestic Gross Using Studio and Year** Domestic box office earnings are partially predictable based on studio reputation and timing, with 28% of revenue variation explained by these features.
- **Predict Foreign Gross from Domestic Gross** Based on past data, a movie’s domestic box office performance is a strong predictor of its international success, explaining roughly 70% of the variation in foreign gross revenue.
- **Predict Total Gross Using All Numeric Features** Before a movie is released, knowing the studio and year gives us a moderate ability to predict its total gross revenue. These two factors alone explain about 27% of box office performance, suggesting brand power and release timing matter — but more factors are needed for strong predictions.
- **Analyze Domestic Revenue Trend Over Time** There is no meaningful upward or downward trend in domestic box office revenue across the years 2010–2018. Other factors (like genre, cast, marketing, or competition) are likely much more influential than release year alone.
- **Predict Total Gross While Controlling for Studio and Year** With only the studio and year available before launch, we can forecast a movie’s global revenue with moderate confidence. This insight is valuable for initial budgeting, marketing expectations, and risk planning.
# Conclusion
This analysis explored key factors influencing box office performance using linear regression models. Our findings show that **studio reputation** and **release year** moderately predict **domestic and total gross revenues**, explaining around 27–28% of their variation. Notably, **domestic box office performance** is a strong predictor of foreign revenue, with a model explaining nearly 70% of international earnings, a valuable insight for global forecasting. Conversely, **release year** alone shows little predictive power, indicating that time trends have minimal influence without additional context. These results highlight that while pre-release factors like studio and timing provide useful signals, more detailed data such as genre, cast, and budget is essential for stronger predictive accuracy and strategic planning.
# Repository Structure
├── .ipynb checkpoints
├── Box-Office-Blueprint-Data-Driven-Insights-for-a-New-Movie-Studio
├── Visualizations
├── Box Office Blueprint Data Driven Insights for a New Movie Studio.ipynb
├── Box Office Blueprint Data Driven Insights for a New Movie Studio.pdf
├── Box_Office_Image.jpeg
├── Box office blueprint.pptx
├── notebook.pdf
├── presentation.pdf
└── bom.movie_gross.csv
