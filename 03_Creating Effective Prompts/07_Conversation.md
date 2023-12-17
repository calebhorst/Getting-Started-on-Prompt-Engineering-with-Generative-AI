## Conversation
```
Next up, we can use GPT models for conversation. So here we're giving some context that the following is a conversation with an AI robot and a human, more information about the robot, and then we give it the actual conversation. We're asking the AI to take on the role of one of the quote, unquote people in the conversation. And at the end, we say Robot:, and that's the clue that we want the model to play the robot in this conversation and keep it going. So let's see if we get a very intelligent, sarcastic, and funny continuation of this conversation and see what the robot gives us. The human saying, I'm bored. What should I do? Well, if you're looking for something to do, why not try something new? Take a cooking class, learn a language, and so on. So a fairly basic response. What if we want something more creative? Well, remembering back to earlier in the module, we talked about the parameters that we have. One of those is for Temperature, and it can range from 0 to 2. The higher the number, the more variable or creative the model is going to be with its responses. So let's go adjust this and see what it does. And incidentally, if you hover over any of these, you get a nice popup telling you what it does. So right now, my Temperature is at 0. Let's bump this up to maybe 1, and then we'll try this prompt again. I'll get rid of the response that we had earlier, and we'll hit Submit. We'll see if we get anything a little bit more creative. Depends on what kinds of things you're into. What are your hobbies? Okay, so maybe a little bit more interesting. Let's adjust it to Temperature of 2 and see if we get anything different. So again, starting with our original prompt. All right, here we go. Oh my goodness, going swimming with droid comrades, clone diving, and my goodness, words I don't even recognize here, so obviously more creative and more variety in this response. Let's play along and we'll say, Human: What do you do when you're bored? We're looking for something super creative, and here we're not even using English anymore, so it's gone a little bit off the rails. I'll just cancel this, but that's what the temperature control does. So if you're using it for conversation, figure out the general tone that makes sense for your use case, and then you can dial it up or down.
```

## Notes
In conversation prompts, the AI takes on specific roles within a dialogue based on the provided context. Here's how it's set up:

- **Dialogue Context**:
  - Context setting includes instructions about the nature of the conversation, the involved entities (human and AI), and the role the AI should assume in continuing the conversation.

- **Initial Conversation**:
  - The prompt initiates a conversation between a human and an AI in this case. The human starts with a question or statement ("I'm bored. What should I do?"), and the AI responds accordingly.

- **Adjusting Temperature**:
  - The Temperature parameter in GPT models regulates the response's variability and creativity. Higher values (from 0 to 2) yield more imaginative and diverse responses.
  - A lower temperature (e.g., 0) generates more straightforward or factual responses, while higher temperatures (e.g., 1 or 2) lead to more creative, diverse, and sometimes offbeat or surreal outputs.

- **Impact of Temperature on Responses**:
  - By adjusting the Temperature, you can influence the tone and creativity level of the AI-generated conversation.
  - Lower temperatures produce more grounded, direct responses, while higher temperatures result in a broader, more imaginative range of answers, sometimes diverging from the original language or context.

Understanding and managing the Temperature parameter allows users to tailor AI responses to fit specific conversation tones or requirements, from factual and straightforward to highly creative and imaginative.