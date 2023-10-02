# Symptom Checker

This Python script allows you to search for home remedies based on symptoms and then summarizes the content of the search results using the Metaphor AI and OpenAI GPT-3.5 APIs.

## Installation

You'll need to install the required Python libraries to use this script. You can do this using pip3:

pip3 install metaphor-python
pip3 install beautifulsoup4
pip3 install requests
pip3 install openai

## Configuration

Before running the script, make sure to set up your API keys for both Metaphor AI and OpenAI, as well as enter the virtual environment. Replace the API keys in the following lines of code with your own keys:

# Initialize the Metaphor AI client with your API key

metaphor = Metaphor("YOUR_METAPHOR_API_KEY")

# Set your OpenAI API key

openai.api_key = "YOUR_OPENAI_API_KEY"

# You can activate the virtual environment by using the bash script:

source venv/bin/activate

# And deactivate the virtual environment by using the following line:

deactivate


## Usage

1. Run the script.

2. Enter your symptoms when prompted.

3. Enter the number of results you want to retrieve.

4. The script will search for home remedies based on your symptoms using Metaphor AI.

5. It will then extract and summarize the content of the search results using OpenAI GPT-3.5.

6. The summary will be printed to the console.

## Example

# Here's how you can run the script:

python symptom.py


## Dependencies

- `metaphor-python`: For interacting with the Metaphor AI API.
- `beautifulsoup4`: For parsing HTML content.
- `requests`: For making HTTP requests.
- `openai`: For using the OpenAI GPT-3 API.

## Bugs

I am not 100% sure about the functionality as I have run into a message stating "You exceeded your current quota, please check your plan and billing details. - OpenAI". However, I am confident that it works, due to the fact that I was able to get the prototypical version running when I had enough credits.

## Disclaimer

Please be aware of the API usage limits and any associated costs for using the Metaphor AI and OpenAI services. Ensure that you have an appropriate plan and billing details in place.

---

