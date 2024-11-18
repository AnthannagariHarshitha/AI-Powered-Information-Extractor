# AI-Powered Information Extractor

## Project Description

The **AI-Powered Information Extractor** is a web-based tool that allows users to upload a CSV file, define a query template, and use AI to extract specific information from web pages. The tool uses **Google's Gemini AI** to generate insights based on the data scraped from search engine results. It is designed to save time on data extraction tasks, particularly when gathering information on companies, products, or any other list of entities.

### Key Features:
- Upload a CSV file with a list of entities (e.g., company names).
- Define a custom query template (e.g., "What is the founding year of {}?").
- Perform a web search for each entity and scrape relevant data.
- Generate insights using Google’s Gemini AI to answer the query.
- Download the results as a CSV file for further analysis.

## Setup Instructions

### Prerequisites:
1. **Python 3.x**: The project is developed in Python 3.x.
2. **Streamlit**: This tool is powered by Streamlit for the front-end.
3. **Google Gemini API**: You'll need a valid API key to interact with Gemini AI.

### Installing Dependencies:
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/AI-Powered-Information-Extractor.git
   cd AI-Powered-Information-Extractor
