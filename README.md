# sns-assignment

**Problem Statement 1**: Natural Language Processing (NLP)
Problem: Implement a function to preprocess and tokenize text data. 

**Requirements:**
Implement in Python using libraries like NLTK or spaCy.
Handle edge cases such as punctuation, stop words, and different cases.

**Solution**

**Features**
**Text preprocessing:** Converts text to lowercase, removes punctuation, and filters stop words.
**Tokenization:** Uses spaCy to split text into tokens.
**Lemmatization:** Reduces tokens to their base forms (lemmas).
**Stop words removal:** Uses NLTK's stop word corpus to exclude common stop words.
**Punctuation removal:** Removes all punctuation marks from the text.

**Requirements**
Python 3.x
Required libraries:
nltk
spacy

**Problem Statement 2:** Text Generation
Problem: Create a basic text generation model using a pre-trained transformer (e.g., GPT-3).

**Requirements:**
Use the Hugging Face Transformers library.
Generate coherent text based on a given prompt.

**Solution**

**Features**
**Text generation:** Uses a pre-trained DistilGPT-2 model to generate coherent text sequences.
**Pipeline simplicity:** The Hugging Face pipeline function abstracts the model loading and text generation, making the script easy to use.
**Configurable output:** You can specify the length and number of generated text sequences.

**Requirements**
Python 3.x
Required libraries:
transformers

**Problem Statement 3:** Prompt Engineering
Problem: Design and evaluate prompts to improve the performance of a given AI model on a specific task (e.g., summarization, question answering).

**Requirements:**
Experiment with different prompt designs.
Evaluate the effectiveness of each prompt using appropriate metrics

**Solution**

**Features**
**Question-Answering (QA):** Uses the DistilBERT model fine-tuned on the SQuAD dataset to answer questions based on a given context.
**Multiple prompt designs:** Generates answers using different prompt formats for each question.
**Answer evaluation:** Evaluates the model-generated answers against reference answers using the ROUGE metric.
**Scoring:** Computes ROUGE-1, ROUGE-2, and ROUGE-L scores to assess the quality of the generated answers.

**Requirements**
Python 3.x
Required libraries:
transformers
datasets

**Problem Statement 4:** Data Analysis
Problem: Analyze a dataset and generate insights using a combination of descriptive statistics and visualizations.

**Requirements:**
Use Python libraries like Pandas, NumPy, and Matplotlib/Seaborn.
Provide a Jupyter notebook with the analysis and visualizations.



**Problem Statement 5:** Live Coding Session - API Integration
Problem: Develop a Python script to integrate with an external API and fetch data based on user input.

**Requirements:**
Use the Requests library to make API calls.
Handle API responses and errors gracefully.
Parse and display the fetched data in a user-friendly format.

**Solution**

**Features**
**YouTube Data API connection:** Connects to YouTube using an API key to access channel data.
**Channel data extraction:** Retrieves key metrics and details about a specific YouTube channel, such as subscribers, total views, and description.
**DataFrame output:** The data is returned as a Pandas DataFrame for further processing or analysis.

**Requirements**
Python 3.x
Required libraries:
pandas
google-api-python-client




