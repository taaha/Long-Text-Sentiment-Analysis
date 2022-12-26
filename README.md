# Long-text-sentiment-analysis-using-BERT

This natural language processing exercise is to practice long text sentiment classification.

Text used for classification is a reddit financial post. finbert pretrained NLP model was used.

Windows method was used to split text into tensors of 512 tokens each. 
Sentiment analysis was done for each tensor and probabilities for each tensor were calculated using softmax. 
probabilities for all tensors were averaged and class(sentiment) having the maximum average probability was selected
