"# GenerativQuizAI" 
# Quiz Generator using GPT-3.5 and Streamlit

Welcome to the Quiz Generator, a powerful tool that leverages the GPT-3.5 language model to create quizzes on any topic of your choice. This application is built using Python and Streamlit, making it easy to create, customize, and share quizzes with others.

![Screenshot (32)](https://github.com/ayahalsaad/GenerativQuizAI/assets/147486757/ccce3bfb-bb66-422d-9552-562a4c765c77)


## Table of Contents

- [Requirements](#requirements)
- [Obtaining OpenAI API Keys](#obtaining-openai-api-keys)
- [Setting Secrets](#setting-secrets)
- [Executing the App](#executing-the-app)
- [Contributing](#contributing)
- [License](#license)

## Requirements

To use the Quiz Generator, you need the following:

- Python 3.8 or higher
- An OpenAI API key to access GPT-3.5

## Obtaining OpenAI API Keys

To obtain the necessary API key and organization from OpenAI, follow these steps:

1. Go to the [OpenAI website](https://www.openai.com/).
2. If you don't have an account, click "Sign up" and create one.
3. Once logged in, navigate to the [API key management page](https://platform.openai.com/account/api-keys).
4. Click "Create new secret key" and note down the generated API key (you would not see the key again).
5. On the same page, find your organization ID under the "Settings" section.

You now have the API key required for the Exam Generator.

## Setting Secrets

Create new directory `.streamlit` in the root directory of the project and create a new file `secrets.toml` inside it.


mkdir .streamlit
echo .streamlit/secrets.toml


Open the `secrets.toml` file and add the following lines:


[secrets]
[OPENAI_TOKEN]
key = "your OPENAI_TOKEN_KEY"


## Executing the App

After installing dependencies and setting secrets, execute the Exam Generator app by running:


streamlit run main.py


The Exam Generator app should now be accessible in your web browser at `http://localhost:8501`.
