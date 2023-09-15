# Cloud-Native Analytics Application: Predicting Bitcoin Cash on GCP

### About the project
This is the Final Project for MSDS434 Analytics System. In this project, I constructed a continuous Cloud-based ML pipeline with Cloud Run and Cloud Build, implemented as a interactive Flask application for Bitcoin Cash price prediction on given date.
                       
The cloud-native architecture ensures the pipeline is both scalable and flexible to changes, accommodating increases in user traffic or computational needs without requiring manual intervention. This implementation serves as a foundation for more complex ML projects, where computational demand and data volume escalate rapidly.

- Constructed dynamic Flask ML interface from ML model built on  Bigquery and trained in Vertex AI.
- Continuously deployed with Docker on Cloud Build with triggers in different environments.
- Implemented recurrent neural network algorithm of gated recurrent unit to predict bitcoin order price based on daily price flow.
- Fine-tuned model with a MAPE of 0.5%.

### Built With
- Flask
- Git
- Docker
- GCP - Cloud Run
- GCP - Cloud Build
- GCP - BigQuery
- GCP - Vertex AI
(- GCP - Stackdriver)

### ML Model
1. BigQuery approach : Moving-Average time-series model with 'ML.FORECAST'.
2. Vertex AI approach : Implementation of the GRU approach from the "A Novel Cryptocurrency Price Prediction Model Using GRU, LSTM and bi-LSTM Machine Learning Algorithms."

### Reference 
https://www.researchgate.net/publication/355202227_A_Novel_Cryptocurrency_Price_Prediction_Model_Using_GRU_LSTM_and_bi-LSTM_Machine_Learning_Algorithms



