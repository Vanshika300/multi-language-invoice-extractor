🧾 Multi-Language Invoice Extractor

A Streamlit web application that leverages Google Gemini's multimodal capabilities to analyze invoice images and extract information based on natural language queries. This tool simplifies data extraction from various invoice formats and languages.

✨ Features
Image-to-Text Extraction: Processes uploaded invoice images (JPG/PNG) to extract relevant text and data.

Natural Language Querying: Allows users to ask specific questions about the invoice content (e.g., "What is the total amount?", "Who is the vendor?", "What is the date?").

AI-Powered Interpretation: Uses Google Gemini 2.5 Flash to understand the invoice context and provide accurate answers to user queries.

Multi-Language Support: Capable of interpreting invoices in various languages, leveraging Gemini's understanding.

Interactive UI: User-friendly interface built with Streamlit for easy image upload and query input.

🚀 Technologies Used
Python

Streamlit: For building the interactive web application.

Google Generative AI (Gemini 2.5 Flash): The core LLM for image understanding and natural language processing.

PIL (Pillow): For image handling and processing.

python-dotenv: For secure management of API keys.

📸 Screenshots
(Note: Replace these placeholders with actual screenshots of your running application, showing an invoice upload and a query result.)

Invoice Upload Interface:
A screenshot showing the application's interface for uploading an invoice image.

Query Result Example:
A screenshot demonstrating a user query and the AI's extracted response from the invoice.

⚙️ How to Run Locally
Follow these steps to set up and run the Multi-Language Invoice Extractor on your local machine.

1. Prerequisites
   Python 3.8+: Ensure you have Python installed.

Google Gemini API Key: Obtain an API key from Google AI Studio.

2. Clone the Repository
   git clone https://github.com/your-username/multi-language-invoice-extractor.git
   cd multi-language-invoice-extractor

(Replace your-username with your actual GitHub username.)

3. Configure API Key
   Create a file named .env in the root directory of your project (the same directory as multi_ai.py). Add your Google Gemini API key to it:

GOOGLE_API_KEY="YOUR_ACTUAL_GOOGLE_GEMINI_API_KEY"

Important: Replace "YOUR_ACTUAL_GOOGLE_GEMINI_API_KEY" with your real key. This file is ignored by Git and will not be uploaded to GitHub, keeping your key secure.

4. Install Dependencies
   It's highly recommended to use a virtual environment:

# Create a virtual environment

python -m venv venv

# Activate the virtual environment

# On Windows:

.\venv\Scripts\activate

# On macOS/Linux:

source venv/bin/activate

# Install required Python packages

pip install -r requirements.txt

5. Run the Application
   Once all dependencies are installed and your .env file is configured, run the Streamlit application from your terminal:

streamlit run multi_ai.py

This command will open the application in your web browser, usually at http://localhost:8501.

📧 Contact
Feel free to reach out if you have any questions or feedback!

Email: vanshikashukla065@gmail.com

LinkedIn: linkedin.com/in/vanshika-shukla30
