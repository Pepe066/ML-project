# Knowledge Augmented Abstractive Summarizer

## Overview
This repository contains the implementation of a Machine Learning project for the *Machine Learning for Humanities* course. The project focuses on knowledge-augmented summarization, leveraging external data sources to enhance text generation quality and factual consistency.

## Installation & Setup
To set up and run this project, follow these steps:

 **Set Up Environment Variables**
   The project requires an API key for the *Mistral* model and an email for Wikipedia API access. Create a `.env` file in the folder containing the API integrations and add the following:
   ```env
   MISTRAL_API_KEY=your_mistral_api_key
   WIKI_ACC=your_wikipedia_email
   ```
**Dowload Packages**
  ```
  pip install spacy
  python -m spacy download en_core_web_sm
  pip install requests
  pip install SPARQLWrapper
  pip install transformers
  pip install torch
  pip install rouge-score
  pip install datasets
  pip install bert-score
  pip install fuzzywuzzy
  pip install python-dotenv
  ```
## License
This project is licensed under the MIT License.



