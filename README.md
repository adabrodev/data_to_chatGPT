# Introduction 
This code implements the functionality of Data to LLM (Large Language Models) using ChatGPT, which is being explored as part of a data analytics platform for a vocal school. The purpose of Data to ChatGPT is to accelerate the initial level of data interpretation through analysis using a large language model (LLM) like ChatGPT.

You can find the dashboard, which is fed with the results of this code, here : https://lookerstudio.google.com/s/r3zE0r4iICg

You can access the article related to this code at the following link: https://medium.com/@aleksander.dabrowski/harnessing-chatgpt-for-data-analysis-my-first-tests-9356850660dc

# The code performs the following tasks:

1. Technical settings: It imports libraries and creates the main table in BigQuery to store ChatGPT responses.
2. Business settings: It defines roles and main business guidelines for the ChatGPT prompt.
3. Organization settings: It defines roles and main business guidelines for the ChatGPT prompt.
4. Extracting data for analysis from the BigQuery database.
5. Three analyses to be conducted by ChatGPT, including prompt creation, interaction with the ChatGPT API, and storing the response in BigQuery.  

# Some definitions Used in the Code
- PI_description: Performance indicator description, which refers to a very short description of columns.
- PI metrics: Refers to the data extracted to add to the prompt.
- business_issue: Represents a business question asked by the business owner with reference to the metrics. This question is to be answered by ChatGPT.
- ChatGPT_role: Refers to the role assigned to ChatGPT in the prompt.
- prompt_for_chatGPT: Denotes the text sent to ChatGPT to generate the response.
- response_from_chatGPT: Represents the text generated by ChatGPT as a response to the prompt.

I welcome any suggestions or ideas via email: aleksander.dabrowski@gmail.com