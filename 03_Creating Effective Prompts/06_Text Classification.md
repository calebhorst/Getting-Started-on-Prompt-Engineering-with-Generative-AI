## Text Classification
```
Moving on, next, we have text classification. Sentiment analysis is probably the most popular example of this, Classify the following comment's sentiment as positive, negative, or neutral. So we're telling it the categories that we want, and then we're guiding it saying Comment:, so this is the input. And then we say Sentiment: and then nothing else. We're saying this is where your answer should start. And this is a technique you can use for other prompts as well, basically, setting it up to answer right after that last colon. So something like this, we're getting it started on the answer here. Let's submit, see what we get. And Positive sentiment, Great course! Thank you very much. And then building on that, we can be even more efficient by asking it to classify more than one comment at a time. But once again, leading it with that Sentiment word at the end there to get it started. And this time, you'll see it gives a sentiment for each of our comments with the five different options here. And then just to give you one more use case, we could also use this to classify or route support tickets based on their contents. So the instructions here, we're looking for categories of Technical Issues, Billing, Inquiries, or Complaints. And then down below, we'll pass in the actual contents of the ticket and see what category we get, just like this. And let's see what we get for our response. It looks like this ticket is for Technical Issues. So just another example of how to use this for text classification.
```

## Notes
The text classification method is demonstrated in various scenarios:

- **Sentiment Analysis**:
  - Prompting the AI to classify comments' sentiment as positive, negative, or neutral.
  - Structuring the prompt by providing the categories and indicating where the response should start, resulting in accurate sentiment classification.

- **Batch Sentiment Analysis**:
  - Expanding the classification task to multiple comments, guiding the model to provide sentiment for each comment.
  - Using a similar format for the prompt, achieving sentiment classification for multiple inputs simultaneously.

- **Support Ticket Routing**:
  - Applying text classification for categorizing support tickets based on their content.
  - Specifying categories like Technical Issues, Billing, Inquiries, or Complaints and then feeding the ticket content to classify it accordingly.

These instances highlight the utility of text classification, ranging from sentiment analysis for comments to batch processing of sentiments and even routing support tickets based on their content categories.