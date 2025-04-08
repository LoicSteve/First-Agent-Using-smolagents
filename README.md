# First-Agent-Using-smolagents
create your very first Agent capable of performing actions such as image generation, web search, time zone checking and much more!
To make this Agent, we’re going to use smolagents, a library that provides a framework for developing your agents with ease.

This lightweight library is designed for simplicity, but it abstracts away much of the complexity of building an Agent, allowing you to focus on designing your agent’s behavior.

In short, smolagents is a library that focuses on codeAgent, a kind of agent that performs “Actions” through code blocks, and then “Observes” results by executing the code.

Here is an example of what we’ll build!

We provided our agent with an Image generation tool and asked it to generate an image of a cat.

The agent inside smolagents is going to have the same behaviors as the custom one we built previously: it’s going to think, act and observe in cycle until it reaches a final answer