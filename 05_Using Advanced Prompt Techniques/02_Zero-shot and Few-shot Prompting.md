## Zero-shot and Few-shot Prompting
```
Starting with zero‑shot and few‑shot prompting. Now this first one, zero‑shot prompting, is one that we've actually already covered, but maybe you just didn't know that it had a name. This is a simple prompt that includes zero examples, meaning you're not giving it explicit information to train on. Rather, it's just using general knowledge it had already acquired through training. Like this, classify the sentiment of the following text. The model has already been trained a lot on sentiment. You don't have to provide additional examples or further instructions on what to do. Pretty simple. Then we have a few‑shot prompting, which, as the name implies, is a prompt with a few contextual examples to enhance the model's performance. You're effectively training it with a little bit more data to give it context and background for what you're asking it to do. For example, if we don't want the regular sentiment analysis of positive, neutral, or negative, we want superb, meh, or neutral, then we need to give it some examples of statements that would fall into those categories. So a few examples, which is few‑shot prompting.
```

## Notes
- **Zero-shot prompting:** Utilizes the model's pre-existing knowledge without providing specific examples. 
    - The model draws on its general training to perform a task without additional context or training data, like sentiment analysis without explicitly offering examples.

- **Few-shot prompting:** Involves offering a limited set of contextual examples to enhance the model's performance for a specific task. 
    - This method provides a bit of additional data or context to guide the AI's understanding, aiding in tasks where specific nuances or categorizations are desired, such as custom sentiment categories beyond typical positive, neutral, or negative.