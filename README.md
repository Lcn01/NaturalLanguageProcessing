# NaturalLanguageProcessing
This is my code notebook and support ticket text file for my NLP course from UT Austin's Postgraduate Certification in AI/ML: Business Applications.  In this project, I built a support ticket categorization system, using an AI model from Hugging Face, that would categorize, tag, prioritize, and respond to customer technical support requests.

The support ticket text data was first loaded into a Python notebook in Google Colab, and a suitable model was loaded into the notebook from Hugging Face (TheBloke/Mistral-7B-Instruct-v0.2-GGUF). Four different prompts were inputted into the model, for categorization, tagging, prioritization/ETA, and automatically generated response, respectively. Each generated response was then parsed from JSON format (if necessary) and compiled into a dataframe.

A system like this could greatly increase productivity, understanding of customer issues, and provide a business with a valuable customer engagement tool that allows them to immediately prioritize and respond to customer issues, as well as enhance the customer experience and increase the likelihood of long-term relationships with the customer base.
