# Smart-ATS
Smart ATS is a tool designed to help individuals improve their resumes using an AI-powered Application Tracking System (ATS). This tool evaluates resumes based on a provided job description, assigning a percentage match and identifying missing keywords to assist users in optimizing their resumes for specific job opportunities.

# How to Use
- **Input Job Description**: Paste the job description into the text area provided.
- **Upload Your Resume**: Upload your resume in PDF format using the file uploader.
- **Submit**: Click the "Submit" button to process the job description and resume.
- **View Results**: The tool will provide a summary of the evaluation, including the percentage match, missing keywords, and profile summary.

# Requirements
- Python 3.6+
- Streamlit
- google.generativeai
- PyPDF2
- dotenv

# Installation
Clone the repository: 
-      git clone <repository-url>
Install dependencies:
-      pip install -r requirements.txt

# Configuration
Ensure you have set up your environment variables, including the API key required for the generative AI model. You can use a .env file to store your environment variables.
-        AI_API_KEY=<your-api-key>
# Running the Application
Run the Streamlit application:

-        streamlit run app.py
# About
This application utilizes the Google Generative AI model to evaluate resumes and provide personalized feedback based on the provided job description. It aims to assist individuals in tailoring their resumes for specific job opportunities in competitive job markets.



    
