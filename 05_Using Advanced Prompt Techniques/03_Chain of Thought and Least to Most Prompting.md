## Chain of Thought and Least to Most Prompting
```
Next up, we have chain of thought prompting. And I'm actually going to throw at least to most prompting in here as well as it's very similar. You can use these types of prompts to solve complex problems by breaking them into smaller steps. We kind of incrementally walk the model through the thought process with different questions and answers to get to the final results, so chaining our thoughts together to help ensure we get the final correct answer. For example, I have a rectangular garden that's 20 ft long and 10 ft wide. How many square feet is that? The model responds, that's 200 square feet. And then we can build on that. I want to cover the garden in mulch. One bag of mulch covers 25 square feet. How many bags do I need? The model can then say we need eight bags of mulch. Then getting into cost calculation, each bag costs $5. How much will it cost me to cover the garden? It'll cost $40. Now you'll find that in a lot of cases, GPT is capable of doing this chain of thought by itself. So rather than you breaking it into individual questions, you can just effectively give it a word problem like this and then say, think step by step. Let's go see how this does in the playground. Okay, heres the word problem. We're saying think step by step. And then it should go through step by step all of the different calculations that it's coming up with. And in the end, we get the $40 to cover the garden in mulch, which is correct. And then least to most is a similar technique where you break things into smaller problems, least, to get to the final answer, most. Here we have a word problem about Elbra playing miniature golf. It takes her 10 minutes to play the first half, 7 minutes to play the second half, and we need to figure out how many more rounds she can play before the course closes. Lets go see how this does in the playground. And this time, I'll just give the word problem, we're not going to say think step by step, and we'll see if we get the correct answer. I find that sometimes we do and sometimes we don't for this particular question. So let's give it a shot. So in this example, the model actually got it wrong. It's telling us there's five more rounds of golf that she could play before the course closes. It should actually be 10. So, let me get rid of the response here. This time, we'll tell it to think step by step, and we'll see if we get a different answer. So it's going to take us through the different steps, the different reasoning, the calculations. And now we're coming up with 16 more rounds of golf. In the first step, you can see that it's assuming that Elbra has already played one round of golf, even though we didn't specifically say that, which could be throwing off the other calculations. So if you're still not getting the correct answer, then you'll need to do some prompting yourself to break the problem into smaller steps so that it can ultimately arrive at the correct answer, something like this. We first need to figure out how long it takes to play one total game, and you should get an answer of 17 minutes. Then we'll ask how many minutes are in 3 hours? 180 minutes. What is 180 divided by 17? That gives us 10.58. And then round down to the nearest hold number, which should give us 10. And Elbra can play 10 more rounds of golf before the course closes. So that's an example of breaking things into smaller steps to help the model ultimately arrive at the correct final answer.
```

## Notes
Absolutely, summarizing those concepts:

- **Chain of thought prompting:** Involves breaking down complex problems into smaller, sequential steps by asking the AI a series of questions and building on previous answers to reach a final solution. This technique walks the AI model through a process step by step, solving multiple stages of a problem or inquiry.

- **Least to most prompting:** Similar to chain of thought, it's a method to break down complex problems into smaller segments but usually focuses on solving from the simplest step (least) to the more complex (most). This strategy gradually leads the AI model through a progression of questions or tasks, starting from the easiest aspect towards the final solution.

The examples showcased how these techniques can be used to guide the AI through a sequence of problem-solving steps, allowing it to gradually arrive at the correct answer. The chain of thought involves a sequential progression of questions and answers, while least to most breaks the problem into segments from the least complicated to the most challenging. Both aim to help the AI reach the desired conclusion by walking it through a structured thought process.