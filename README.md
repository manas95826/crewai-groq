# CrewAI Machine Learning Assistant with Streamlit

The **CrewAI Machine Learning Assistant** is a Streamlit-based application designed to guide users through the process of defining, assessing, and solving machine learning problems. It leverages AI agents from CrewAI to assist in problem clarification, data assessment, and model recommendation.

## Overview

This application provides a user-friendly interface for:
- Defining machine learning problems
- Uploading and assessing data quality
- Recommending suitable machine learning models

Whether you're new to machine learning or a seasoned data scientist, this tool aims to jumpstart your projects by providing expert guidance and recommendations.

## Features

- **Customization Options**: Users can choose from different AI models (e.g., llama3-8b-8192, mixtral-8x7b-32768, gemma-7b-it) to power the AI agents.
- **Problem Definition Agent**: Clarifies the user's machine learning problem, identifying its type and any specific requirements.
- **Data Assessment Agent**: Evaluates uploaded data for quality and suitability, suggesting preprocessing steps if needed.
- **Model Recommendation Agent**: Recommends the most suitable machine learning models based on the defined problem and assessed data.

## Usage

1. **Choose a Model**: Select an AI model from the sidebar.
2. **Describe Your ML Problem**: Enter a description of the machine learning problem you want to solve.
3. **Upload Data (Optional)**: Upload a CSV file containing sample data for assessment.
4. **Results**: Receive outputs from each AI agent summarizing the problem definition, data assessment, and model recommendations.

## Installation

To run the application locally, follow these steps:

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

Make sure you have Python installed on your machine.

## Dependencies

- Streamlit
- pandas
- crewai (for AI agents)
- langchain_groq (for ChatGroq model)

## Contributors

- [Your Name](https://github.com/manas95826)


