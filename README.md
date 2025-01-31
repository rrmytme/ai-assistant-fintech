# AI Assistant for Market Sentiment Analysis

This project uses AI agents to analyze market sentiment and financial data for specific companies. The agents utilize OpenAI's GPT-4 model and various tools to search for news articles, retrieve financial data, and synthesize the information into a comprehensive analysis.

## Project Structure

- `ai-assistant-market-sentiment-anlysis.py`: Main script that defines and runs the AI agents.
- `.env`: Environment file containing the OpenAI API key.
- `venv/`: Virtual environment directory.

## Requirements

- Python 3.8+
- OpenAI API key

## Setup

1. Clone the repository:

   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Create and activate a virtual environment:

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```sh
   pip install -r requirements.txt
   ```

4. Set up the [.env](http://_vscodecontentref_/1) file with your OpenAI API key:
   ```sh
   echo "openai.api_key = 'your-api-key-here'" > .env
   ```

## Usage

Run the main script to execute the agents:

```sh
python ai-assistant-market-sentiment-anlysis.py
```
