# GPT-API-Access-Tutorial
A quick tutorial that will allow anyone with API access to prompt OpenAI models if the web version limits them in some capacity. 

The tutorial is all contained within the Jupyter Notebook, which outlines the steps needed to prompt OpenAI models. The other files are simply examples of how to store an API key and an outline for a text prompt. 

The story of this tutorial goes back to a night when I was trying to understand the concepts in a difficult paper. The GPT4 web version context window was not large enough for it to analyze the paper, as many mathematical concepts built upon each other over the course of multiple pages. As the "turbo" version had recently been released, I realized that I could take advantage of the much larger context window to read the entire paper. Thus, I wrote this quick notebook. 

Although it could be made much more modular with multiple files and could be more powerful via the use of a pdf reader etc, the process described in the notebook worked just fine for me. I typically download arxiv source files, convert them to markdown using pandoc, and copy and paste the relevant sections of the paper to avoid confusing the model with extra formatting characters or unnecessary footnote text. This is all described within the notebook. Hopefully this is useful to someone who is also limited by the web version in some capacity! 
