# Gemini App SQL Query Generator

## Overview

This application utilizes Google's generative AI to transform natural language queries into SQL commands, interfacing with a SQLite database to fetch and display the data via a Streamlit web interface.

## Install the required Python packages:

```sh
$ pip install -r requirements.txt
```

## Set up your environment variables: Create a .env file in your project root and add your Google API key

```sh
$ GOOGLE_API_KEY='your_google_api_key_here'
```

## Terminal usage

```sh
$ streamlit run app.py
```