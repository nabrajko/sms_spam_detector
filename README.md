# SMS Spam Detector
hw 21

A machine learning application using Support Vector Classification (SVC) and Gradio to classify SMS text messages as spam or legitimate (ham) with an interactive web interface.

## Project Overview

This project refactors SMS text classification code into a production-ready application with a user-friendly interface. Users can input text messages through a Gradio web app and receive instant feedback on whether the message is classified as spam or legitimate.

## Business Problem

SMS spam detection is critical for:
- Protecting users from fraudulent messages
- Filtering unwanted marketing communications
- Improving user experience in messaging applications
- Reducing security risks from phishing attempts

## Technologies Used

- **Python**: Primary programming language
- **Scikit-learn**: Machine learning library for SVC model
- **Gradio**: Web interface framework for ML applications
- **Pandas**: Data manipulation and analysis
- **Natural Language Processing (NLP)**: Text feature extraction and processing
- **Jupyter Notebook**: Interactive development environment

## Dataset

**File**: `SMSSpamCollection.csv`

**Structure**:
- **label**: Classification label ("ham" for legitimate, "spam" for spam messages)
- **text**: SMS message content

## Project Structure

### Part 1: Create the SMS Classification Function

#### Function Purpose
Build a reusable function that constructs and trains a Linear Support Vector Classification model for SMS spam detection.

#### Implementation Steps

**1. Feature and Target Definition**
```python
