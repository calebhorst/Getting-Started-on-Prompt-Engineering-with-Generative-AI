## Text Summarization
```
Now let's move on to the next type of prompt, and that's text summarization. Here we're saying go summarize some piece of text and then we provide the text. Building on that, you can say the kind of format that you want for output like using three bullet points or a short paragraph or a formal report, something like that. And this brings us to a best practice or a pro tip. When you're entering instructions, it's helpful for the model if you can delimit them from the rest of the input. Open AI recommends using three hashes or three double quotes. You'll also see three hyphens used as well, just something to offset the instructions so that the model can distinguish instructions from the text that it's supposed to summarize. Seeing that here in the playground, I'm just using the three hashtags to separate the instructions from the text that it's supposed to summarize. And then we'll get that summary in three bullet points like we asked. Another use case is to summarize code, and the instructions are similar, so Summarize this code using two short paragraphs. We've got the delimiter, and then we would put the code in. So just like this, I've got some React code here, the tic‑tac‑toe game, and then we get a summary of what it is. So just another example of how we can do summarization and how it's helpful to separate your code from the instructions.
```

## Notes
Absolutely, here's a breakdown of the text summarization techniques covered:

- **Text Summarization Basics**:
  - **Providing Input**:
    - Instructing the AI to summarize text, specifying the desired format like bullet points or paragraphs for the output.
    - Best Practice: Delimiting instructions from the text using three hashes, three double quotes, or three hyphens, aiding the model in distinguishing instructions from the content to be summarized.

- **Summarization Examples**:
  - **Summarizing Text**:
    - Demonstrating the use of delimiters (###) to separate instructions from the text to be summarized.
    - Outputting the summary in the specified format, like three bullet points.

  - **Code Summarization**:
    - Employing a similar approach for summarizing code.
    - Using the delimiter to set apart the instructions and the code snippet (React code for tic-tac-toe game).
    - Receiving a summary of the code based on the given instructions.

These examples illustrate the technique of instructing AI models to summarize text and code, emphasizing the importance of clearly separating instructions from the content to be summarized using specific delimiters.