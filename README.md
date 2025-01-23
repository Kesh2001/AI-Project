
# AI-Project
## Job Vacancy Prediction using Sentiment Analysis of Immigration Policies
This project predicts Ontario's job vacancies and unemployment rates using a SARIMAX-based predictive model. The model incorporates sentiment analysis of immigration policies to enhance forecasting accuracy, achieving an 8-9% improvement. Key features include:

- Data Management: Built a relational database in PostgreSQL to store and manage labor market data.
- Visualization: Designed an interactive Tableau dashboard to analyze trends and present insights.
- Sentiment Analysis: IBM Watson was used to evaluate the impact of immigration policy changes on job markets.
- Innovation: Combines traditional statistical modelling with sentiment-driven insights for actionable predictions.

This project serves as a comprehensive approach to labor market analysis by integrating data analytics, machine learning, and sentiment analysis.

## Output Screenshots:

- Prediction Dashboard with Actual Data:
![Prediction_NoSentiment](https://github.com/user-attachments/assets/a2a08faf-dd53-4847-bcce-48efd758d6ac)

This interactive dashboard explains the various demographics of the data that was downloaded from IRCC. These visualizations were achieved after extensive cleaning.

- Predictions with Sentiment Analysis:
![Prediction_Sentiment](https://github.com/user-attachments/assets/6049c8a2-afcc-4e4e-b0ca-7d40b19c14ae)

The shading of the prediction line describes the sentiment scores related to the job market and students for the policies present in those years respectively. Darker shades indicate non-supportive or less-supportive policies and lighter shades indicate the supportive years.

---

*Note: This sentiment analysis was performed with limitations of the Watson API and thus sentiment scores are subjective accordingly.*
