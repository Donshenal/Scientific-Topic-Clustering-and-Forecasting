# Scientific-topic-clustering-and-forecasting

67,000 Nature publications from 2005 to 2023 were obtained using the Springer-Nature API. 

After data cleaning the title and abstracts of the publications were used for text topic clustering with BERTopic 
and the developments of the topics over time was visualised with animations using plotly. 

The data was grouped by the obtained clusters (topics) and time periods.and XGBoost was employed for time series forecasting based on topic frequencies.

