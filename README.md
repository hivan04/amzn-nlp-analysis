# NLP Analysis using VADER and RoBERTa
Using Sentiment Analysis and NLP Techniques to analyse an Amazon Reviews dataset <br>

→ Explored a traditional NLP technique (VADER) to identify whether a comment was to be judged as negative, neutral or positive by the model. <br><br> 
→ Learnt about its strengths and weaknesses - finding that it generally made a good inference; with its downfall coming to linking words together. This is a weakness as when we form sentences, we don't think of each word mutually exclusively, but instead as a whole. Therefore, with the model pulling words out of context, it found it challenging to determine the difference between a genuine expression and false expressions (such as sarcasm or irony) at times. <br><br> 
→ The tutorial followed on to showcase the model, RoBERTa, using an industry-standard library (Hugging Face) - going through the API connection, all the way to developing a for loop to run judgements of review comments of a dataset (although, only the first 500 observations, out of the 500,000 observations, were used for analysis to reduce computational expense) <br><br> 
→ We also learnt to deal with errors when using the RoBERTa classification, through using a try/except method, which simply `ignored' comments which had too many tokens for the model to process. <br><br> 
→ Finally, a pipeline of the entire method was shown in order to make the extraction and analysis process more efficient and generalised. <br><br> 

*It was also great to have a review on some ML projects such as the softmax function* <br>

The tutorial I followed: https://www.youtube.com/watch?v=QpzMWQvxXWk

---

### Final Comparison between VADER and RoBERTa Models
![image](https://github.com/hivan04/amzn-nlp-analysis/blob/main/vaderxroberta_results.png)
