# Sentiment Analysis Web Application
# Overview
This web application provides users with a platform to perform sentiment analysis on text data. It offers functionalities to input text directly or upload CSV/TXT files for analysis. The sentiment analysis is performed using the TextBlob library, and results are visualized using Matplotlib. Users can download sentiment analysis results for further analysis or sharing.

# Installation
To run the application locally, follow these steps:

1. Clone the repository to your local machine:

        https://github.com/Harshu1121/sentimenttextfile.git

2. Navigate to the project directory:

         cd sentiment-analysis-web-app

3. Install the required dependencies:

        pip install -r requirements.txt

4. Run the Streamlit application:

         streamlit run app.py
   Access the application in your web browser at the provided URL (typically http://localhost:8501).

# Usage
Once the application is running, you can:

* Input text directly in the "Analyze Text" section to perform sentiment analysis.
* Upload CSV/TXT files in the "Analyze CSV/TXT" section for batch sentiment analysis.
* Visualize sentiment analysis results using the provided charts.
* Download sentiment analysis results as CSV files for further analysis.

# File Structure
The project directory contains the following files:

* app.py: The main Streamlit application script.
* requirements.txt: A text file listing all the required Python dependencies.
* README.md: The project's README file providing information and instructions.
* LICENSE: A license file specifying the project's usage rights and permissions.
* data/: A directory containing sample data files for testing the application.

# Contributors
Harshvardhan Pasalkar