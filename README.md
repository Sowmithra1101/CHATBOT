Randomized Responses:

For queries with multiple potential responses, a random response is selected to make the interaction feel more dynamic.
Simple Matching:

The chatbot matches user input by checking if any key in the chat dictionary is a substring of the input text.
Case-Insensitive Matching:

By converting the input to lowercase, the chatbot ensures that it responds correctly regardless of how the user capitalizes their query.
Graceful Exit:

The chatbot recognizes "bye" and terminates the conversation politely.
Limitations:
Limited Understanding:

The chatbot uses simple substring matching, which might lead to incorrect responses if the user's input is complex or phrased differently.
Static Responses:

The chatbot cannot generate context-specific or personalized responses beyond what's predefined in the chat dictionary.
No Memory or Context:

The chatbot doesn't remember previous messages, so it can't provide context-aware replies.
