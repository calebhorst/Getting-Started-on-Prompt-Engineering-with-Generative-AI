## Factual Responses
```
Starting with factual responses or basically asking questions and getting answers, for a straightforward question and answer, we can say, What is the value of Pi? And there we get the response as we would expect. But for these types of prompts where there is a factual response, you might know that sometimes it doesn't quite get it right. It can hallucinate or make things up, and it can sound very confident when it does that. To limit the likelihood of it doing that for fact‑based answers, you can tell it what to do if it doesn't know the answer. So here we're playing a game of trivial pursuit, and I'll say, If you don't know the answer, respond with a question mark. This is an example of something I can put in the SYSTEM message, just giving it a persona and a little bit more information about what it's supposed to do. And then over here, we can add our USER message. What is the name given to a right‑angled triangle where all sides are integers, named after a Greek mathematician? And we'll hit Submit, the Pythagorean theorem. So that's correct. That's a fact. What if we try something like adding a message, What planet was discovered by Chuck McChuckles, who is a totally made‑up character. Let's see what it says. There is no planet called Chuck McChuckles. Well, that is true as well, but you'll see that it didn't respond with a question mark. At the moment, this Chat mode is in beta and the SYSTEM input over there on the left is currently given very little weight, but I wanted to at least show it to you. So if you're using this model and you come up against something like that, what you can do is just put this context, the SYSTEM message, into the actual USER message here. So if we were to put that here and then ask our question again, let me copy this one, and now it's saying it doesn't know, and it should respond with a question mark. Sometimes it will respond just a question mark. So your mileage may vary a little bit, but that's what the SYSTEM section is for. For the rest of our demos, I'm actually going to switch over to Completion mode where we'll put all of our background and context and instructions and so on just right here in this single window, but I want you to see the other one as well. The other way you can help the model be more confident in its responses is to lower the temperature. A lower temperature closer to 0 will lead to more factual, confident answers versus a higher temperature leads to more creative and, thus, less confident responses. Another use case for the question and answer here is to have it explain things. So it's not just giving a simple answer, but it's also giving an explanation for it. Explain the theory of relativity, for example. Even better, it can explain things at a certain level like for a teenager or you can say explain in simple terms or explain for an expert, that type of thing.
```

## Notes
Of course, here's a summary:

- **Factual Responses and Adjustments**:
  - **Question and Answer**:
    - Examples: *Asking for the value of Pi* yields the expected response.
    - Note: Sometimes AI may provide incorrect information confidently, termed as hallucinations.

  - **Managing Uncertainty**:
    - **System Input**: Introduced to guide the AI when it doesn't know the answer.
    - Example: Specifying, "If you don't know the answer, respond with a question mark."
    - Observation: In the beta Chat mode, the SYSTEM input has minimal influence, but it's a tool to manage AI's uncertainty.

  - **Using Different Modes**:
    - Transition to Completion Mode: Future demos will utilize the Completion mode, consolidating all information into one prompt.
    - Explanation: This mode permits setting context, instructions, and prompts in a single window for more straightforward input.

- **Confidence and Temperature Adjustments**:
  - **Temperature Control**: Lowering temperature reduces AI's creativity and increases confidence in factual responses.
  - **Temperature and Confidence**: Lower temperature near 0 produces more factual and confident answers, while higher temperatures lean towards creativity and less confidence.

- **Explaining Concepts**:
  - **Expanded Queries**: AI isn't confined to providing straightforward answers; it can also explain complex concepts.
  - Example: *Requesting an explanation of the theory of relativity*, with options like explaining in simple terms or for specific audiences, such as teenagers or experts.

This segment emphasizes handling factual queries, managing AI's uncertainty through adjustments in temperature and system inputs, and utilizing different modes while exploring the AI's capacity to explain concepts at various complexity levels.