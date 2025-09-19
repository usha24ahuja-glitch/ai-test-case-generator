# ai-test-case-generator
an AI powered test case generator that is built on tools of google cloud.
# AI-Powered Healthcare Test Case Generator

## About the Project
This prototype for the Gen AI Exchange Hackathon solves a critical challenge in the development of healthcare software: the slow, manual, and error-prone process of creating compliant test cases.

Our solution is a GenAI-powered tool that automates the generation of detailed and traceable test cases directly from natural language requirements.

## Key Features

* **Natural Language to Test Cases:** The core of our prototype is its ability to transform a simple English requirement into a comprehensive and structured test suite, drastically reducing manual effort.
* **Continuous Improvement Loop:** We've designed a feedback mechanism that allows users to provide input on the generated tests. This data is used to continuously train and improve the AI model, ensuring it becomes more accurate over time.
* **Built-in Traceability & Compliance:** The AI's output is automatically stored in a Firestore database, providing an immutable audit trail. This is a crucial feature that ensures all test cases are traceable and compliant with industry regulations like ISO 13485 and HIPAA.

## Technology Stack

Our project is built entirely on the Google Cloud Platform, leveraging the following services:

* **Google Cloud Vertex AI (Gemini):** The core of our solution, providing the Generative AI capabilities for test case creation.
* **Google Cloud Firestore:** A secure, scalable NoSQL database used to store the structured test case data, providing traceability and a foundation for future integrations.
* **Google Colab:** Used as a simple, shareable environment to demonstrate the end-to-end functionality of our prototype.

## How to Run the Prototype

To see our prototype in action, you can follow these simple steps:

1.  Click on this link to our Google Colab notebook:
    https://colab.research.google.com/drive/1FIAfRj8wr52z5VocL0SwFtNcrUKwJ7jb?usp=sharing

2.  Sign in with a Google account to authenticate with Google Cloud.

3.  Click `Runtime` -> `Run all` to execute the notebook from start to finish.

The notebook will then:
* Generate new test cases for a predefined scenario.
* Display the AI's output in the notebook.
* Automatically save the test cases to our Firestore database.

## Our Team

* Dr Urja S Ahuja
