# Generative AI Applications
With Generative Artificial Intelligence (GenAI), especially Large Language Models (LLMs), garnering so much attention it begs the question -- how can they *really* be used?

Here are some of my ideas to answer that question.

## Meeting Transcription Analysis
Ever walked away from a meeting or, more accurately these days, hung up a Zoom call and wondered what you should take away from it? 

Well I sure have! In this notebook I ask various LLMs to analyze the meeting transcription to produce the following: 
- Main topics discussed
- Jargon that was used
- Potential action items

I do this by using the [OpenAI REST API](https://platform.openai.com/docs/api-reference/introduction) to call models on a self-hosted [FastChat](https://github.com/lm-sys/FastChat) deployment. I can then easily load a supported LLM from HuggingFace which then makes it available via the API, making comparing and contrasting responses from various LLMs rather smooth.
