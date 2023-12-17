## Evaluation Techniques
```
Now that we've seen the metrics and several examples, let's talk about some ways that you can collect and evaluate them. The first is surveys and interviews of your users, the humans. Because we do want human‑like responses, we need humans to give input on how good or not those responses are. Here are some questions that you can ask. Did the AI understand your prompt correctly? Was the response AI gave relevant to your prompt? Was the AI's response easy to understand? Did the AI provide a complete answer to your prompt or did it miss anything? Continuing on, did you find the AI's response helpful? Was the response delivered in an appropriate tone? How satisfied are you with the speed of the AI's response? And did you feel the conversation with the AI flowed naturally? You can also do A/B testing where you basically split your users into two groups, A and B. Each group is going to get a different prompt, and here we're using an example of a customer service chatbot that's interacting with customers. So Group A would get the prompt. I'm sorry to hear you're not satisfied with your purchase. Could you please tell me the order number and the reason for the return? And then Group B would get, I understand you want to return an item. Can I have the order number and the specific issue with the product? And then the conversation would flow from there. Once the groups are done interacting with the bot, you could ask things like, Which prompt led to more successful return transactions? Which prompt resulted in shorter conversation lengths? That might indicate a smoother interaction. And Which prompt received higher customer satisfaction scores in post‑interaction surveys? Now there might not always be super obvious differences between the two prompts, but if there are, then you'll know to use the one that gave you better results. Finally, for those of you who are interested in digging more into the code and the API side of things, you'll want to check out this fine tuning guide from openai.com. This will give you some additional information on objective metrics that you can get from the API. If we go down to the Advanced usage section here, the section about Analyzing the model, you've got metrics like training loss, sequence accuracy, token accuracy. And then here under Classification, there's also some additional metrics down here, accuracy, precision, recall, and so on. These are a little outside of the scope of a getting started course, but I wanted to at least point you here if you're looking for more advanced topics on these metrics.
```

## Notes
Absolutely, evaluating metrics can be done through various methods. Here's how:

### User Surveys and Interviews:
- **Understanding:** Inquire if the AI comprehended the user's prompt accurately.
- **Relevancy:** Assess if the AI's response aligned well with the given prompt.
- **Clarity:** Determine if the response was easy to comprehend and complete.
- **Helpfulness:** Check if the response offered helpful information or guidance.
- **Tone and Flow:** Gauge satisfaction with the response's emotional tone and conversation flow.

### A/B Testing:
- **Prompt Variations:** Offer different prompts to user groups A and B.
- **Measure Outcomes:** Compare transaction success, conversation length, and user satisfaction between the groups.
- **Selecting the Better Prompt:** Decide based on which prompt yields superior results.

### Advanced Metrics (API):
- **Training Metrics:** Consider metrics like training loss, sequence accuracy, and token accuracy from the API.
- **Classification Metrics:** Explore additional metrics like accuracy, precision, and recall.

These methods offer diverse perspectives for evaluation, from user feedback to quantitative API-driven metrics. It's essential to blend human judgment with statistical metrics for a comprehensive assessment. For further exploration, the fine-tuning guide on openai.com provides insights into advanced metric analysis through the API.