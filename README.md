# testing-gpt-4o

Testing out GPT-4o (omni) api access and capabilities and comparing against GPT-4

## Files in the repo currently

[gpt4otest.ipynb](./src/gpt4otest.ipynb) : a basic test of the GPT-4o model asking it to "Write a persuasive essay about why Dr. Dog is the greatest band ever. Use markdown format. The essay should start with an outline and aim to be close to 2,000 words."

[gpt4turbocomparisontest.ipynb](./src/gpt4turbocomparisontest.ipynb) : same as above to compare against GPT-4-Turbo v2024-04-09

[autogenwithgpt4otest.ipynb](./src/autogenwithgpt4otest.ipynb) : a basic agent set-up with groupchat to write a persuasive essay on the topic of "Why Dr. Dog is the greatest band ever."

[promptflowandautogen.ipynb](./src/promptflowandautogen.ipynb) : same multi-agent set-up as above but with [promptflow trace](https://microsoft.github.io/promptflow/tutorials/trace-autogen-groupchat.html) enabled for better viewing and tracking of the internal process