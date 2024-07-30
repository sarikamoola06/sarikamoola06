
# AskInsureAI

**AskInsureAI** is an interactive Streamlit application designed to help users query insurance-related data, extract information from PDFs and URLs, and get insights using advanced natural language processing. This app leverages OpenAI's language models and a SQLite database to provide meaningful responses to user queries.

## Features

- **URL Scraping**: Extract and ask questions about the content from a URL.
- **PDF Upload**: Upload a PDF file and ask questions about its content.
- **SQL Queries**: Ask questions about insurance policies, including details about active/inactive policies, vehicles, coverage, claims, and more.

## Technologies Used

- **Streamlit**: For building the interactive web application.
- **OpenAI API**: For natural language processing and generating responses.
- **SpaCy**: For processing natural language queries.
- **SQLite**: For storing and querying insurance data.
- **BeautifulSoup**: For scraping text from web pages.
- **PyPDF2**: For extracting text from PDF files.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Required Python libraries (see `requirements.txt`)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/<USERNAME>/<REPOSITORY>.git
   cd <REPOSITORY>
   ```

2. **Create a Virtual Environment**

   ```bash
   python -m venv .venv
   ```

3. **Activate the Virtual Environment**

   - On Windows:

     ```bash
     .venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source .venv/bin/activate
     ```

4. **Install Required Packages**

   ```bash
   pip install -r requirements.txt
   ```

5. **Set Your OpenAI API Key**

   Replace `YOUR_OPENAI_API_KEY` with your actual OpenAI API key in the code.

6. **Run the Application**

   ```bash
   streamlit run app.py
   ```

   This command will start the Streamlit server and open the app in your web browser.

## Usage

- **URL Tab**: Enter a URL to scrape and ask questions about the content.
- **PDF Tab**: Upload a PDF file and ask questions about its content.
- **SQL Tab**: Ask questions about the insurance database (e.g., active policies, vehicles for a policy).

