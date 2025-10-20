# About the Repository

The repository I found uses LLM to analyze European Parliament speeches. It works by first scraping all speaches in a given time frame and the pre-sorting the data (e.g. removing speeches below 400 characters). It then asks the LLM (in this case GPT-3.5-turbo) to classify every speech into categories. These were also limited to 100 in the end which cover 99% of the speeches, to make everything more managable. 
In a second step the code also analyzes