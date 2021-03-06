# Sarcasm-Reddit

# Sarcasm-Research-Project
Title: Automatic Sarcasm Detection Across Two Social Media Platforms




Introduction: This repository explores a computational approach, specially using NLP features, to automatic sarcasm detection across two social media platforms; Twitter and Reddit. The linguistic features that are investigated are a combination of count, stylistic, and psychological features. The features are first run on a corpus of tweets from Twitter and separately on a corpus of Reddit threads, with and without context. The two results of each social media platform are compared. 


Hypotheses: Sarcasm tweets and threads tend to be associated with a negative emotion. The presence of hash tags is crucial for sarcasm detection. Sarcastic responses are typically incongruent in terms of senitment and emotion with their contextual counterpart. Context is absolutely critical information for sarcasm detection. A lower lexical diversity in a coporus produces higher accuracy rates in sarcasm detection. 

Will need:

Download pre-trained word vectors...https://fasttext.cc/docs/en/english-vectors.html

Hugging face pretrained model...https://huggingface.co/mrm8488/t5-base-finetuned-emotion

Data collected from: https://github.com/EducationalTestingService/sarcasm

Code language: Python 3.6

Python libraries used: LIWC, Vader, NLTK, textblob, SHAPLEY

*Both test sets are made available on this page, including the label as well as only contxt /0 - context /1. Training data can be found as well as the full testing data on the github of the shared task. https://github.com/EducationalTestingService/sarcasm

Critical findings: This research proves the hypothesis that contextual information is absolutely necessary for sarcasm detection. When response was only considered, the classifer performed much lower. The more hashtags in the data set, the higher the results of the classifier. Hash tags appear to be an indicator of sarcasm. Lastly, sarcastic tweets and threads are associated with a negative emotion; anger, as well as their contextual counterpart. Non-sarcastic contexts typically reply with a positive emotion;joy. 


Description of all experiments run


Notebooks: 

Response on select Ling. Features= response_select.ipynb


Response on All ling. Features= response_ALL_features.ipynb


Response and context on select ling. Features = response_context_select.ipynb


Response and context on All ling. Features= response_context_ALL.ipynb



*Paper on the current work is located under the file "Research_for_Comp__Ling (1).pdf" 
