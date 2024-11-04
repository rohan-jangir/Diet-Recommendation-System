# Diet Recommendation System

## Overview

The Diet Recommendation System is a Flask-based web application that provides personalized dietary recommendations based on user input. The application leverages the OpenAI API to suggest restaurants, breakfast options, dinner ideas, and workout routines based on various user parameters such as age, gender, weight, height, dietary preferences, and health conditions.

## Features

- User-friendly web interface
- Personalized recommendations for:
  - Restaurants
  - Breakfast items
  - Dinner items
  - Workout routines
- Utilizes OpenAI's language model for generating recommendations
- Regular expressions for parsing output

## Requirements

Before you begin, ensure you have the following installed:

- Python 3.x
- Flask
- LangChain
- OpenAI Python client

You can install the required packages using pip:

```bash
pip install Flask langchain openai
```

## Setup

To set up the Diet Recommendation System, follow these steps:

### 1. Set up your OpenAI API key:
Open the app.py file and replace 'your key is here' with your actual OpenAI API key:
```bash
os.environ['OPENAI_API_KEY'] = 'your key is here'  # your openai key
```

## Running the Application
To run the application, execute the following command:
```bash
python app.py
```
This will start the Flask server on http://127.0.0.1:5000/.

## Usage
**1. Navigate to the homepage of the application in your web browser.**

**2. Fill out the form with your details:**
* Age
* Gender
* Weight
* Height
* Dietary preference (Vegetarian/Non-Vegetarian)
* Any diseases
* Region
* Allergies
* Food type

**3. Submit the form to receive personalized dietary recommendations.**



