## Objective Metrics
```
Let's start with objective metrics. This includes three things, accuracy, speed, and relevancy. Digging in on accuracy a bit more, this involves two things. The first being factual correctness, meaning the responses should be verifiable facts. For instance, How long does it take to boil an egg? It typically takes 9 to 12 minutes to boil an egg. This one's pretty straightforward. And then we have semantic correctness. This can be trickier to measure and relates to whether the responses match the context and intent of a question. For example, again, How long does it take to boil an egg? And this time we get a response, An egg is a food product produced by poultry. This answer is factually correct. An egg is a food product produced by poultry, but it's not semantically correct because it doesn't answer the question that we asked. Doing evaluations of this kind can involve using a ground truth dataset, which usually involves some human verification to verify correctness. Our next objective is speed, which is simpler to measure. This can also be broken into two parts. We've got processing speed, how long it takes the AI model to generate a response. This is largely dependent on the infrastructure that supports the AI model. And then we have response speed, or how long it takes for a user to receive a response. This includes not only the processing speed, but also things like network latency and other potential delays. We can typically measure these things using time stamps and system metrics. For example, you could time stamp when a request is received, when a response is sent, and then calculate the difference. And then our third objective metric is relevancy. This relates to whether the AI's response is relevant to the question that we asked. For example, if a user asks for book recommendations and the AI provides movie recommendations, the response is not relevant even though it's coherent and fluent. This one can also be a little bit tricky to evaluate, and human evaluation usually occurs here as well. Now let's talk about subjective metrics.
```

## Notes
Absolutely, objective metrics provide a foundational evaluation of AI model responses. Here are the key points:

### Objective Metrics:
- **Accuracy:** 
  - **Factual correctness:** Responses should contain verifiable facts.
  - **Semantic correctness:** Answers should match the question's context and intent.

  *Example*: Boiling egg time question - factual correctness vs. semantic correctness.

- **Speed:** 
  - **Processing speed:** Time taken for the AI model to generate a response.
  - **Response speed:** Time from request to receiving a response, considering network latency.

- **Relevancy:** 
  - Ensures the AI response aligns with the query's subject matter.
  - It's essential for the answer to be relevant, not just coherent.

### Subjective Metrics:
- Focuses on qualitative aspects that cannot be objectively measured.
- Includes factors like user satisfaction, naturalness, and overall quality of the response.
- Involves human judgment and perception, often gathered through surveys or interviews.

Both objective and subjective metrics play pivotal roles in comprehensively evaluating AI model performance.