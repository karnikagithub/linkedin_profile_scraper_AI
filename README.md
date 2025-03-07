A repository for learning LangChain🦜🔗 by building a generative ai application.

This is a web application crawling Linkedin & Twitter data about a person and customizes an ice breaker with them.

Logo udemy

Environment Variables
To run this project, you will need to add the following environment variables to your .env file

OPENAI_API_KEY

SCRAPIN_API_KEY

TAVILY_API_KEY

TWITTER_API_KEY

TWITTER_API_SECRET

TWITTER_ACCESS_TOKEN

TWITTER_ACCESS_SECRET

LANGCHAIN_TRACING_V2

LANGCHAIN_API_KEY

LANGCHAIN_PROJECT # Optional

To run this project, you will need to add the following environment variables to your .env file:

Note: This project uses paid API services:

Scrapin.io for LinkedIn data scraping (20% discount available through this link, includes 20 free credits to start)
Twitter API (paid) for accessing Twitter data
Important Note: If you enable tracing by setting LANGCHAIN_TRACING_V2=true, you must have a valid LangSmith API key set in LANGCHAIN_API_KEY. Without a valid API key, the application will throw an error. If you don't need tracing, simply remove or comment out these environment variables.

Run Locally
Clone the project

  git clone https://github.com/emarco177/ice_breaker.git
Go to the project directory

  cd ice_breaker
Install dependencies

  pipenv install
Start the flask server

  pipenv run app.py
Running Tests
To run tests, run the following command

  pipenv run pytest .
