# awesome-compbio-chatgpt

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome repository of community-curated applications of ChatGPT and other LLMs in computational biology!

Any material is welcome, as long as it is: 
* Free to read without accounts
* High quality (subjective, but we know it when we see it)
* Relevant to bioinformaticians



To contribute, just add the link to this document and open a Pull Request!

Have fun!

## Prompt collections

* Data science prompts: https://github.com/travistangvh/ChatGPT-Data-Science-Prompts
* ChatGPT cheatsheet for Data Science: https://www.datacamp.com/cheat-sheet/chatgpt-cheat-sheet-data-science
* Fun and useful prompts: https://github.com/f/awesome-chatgpt-prompts
* List of awesome ChatGPT lists: https://github.com/OpenMindClub/awesome-chatgpt  
* Collection of prompts for developers (YouTube): https://www.youtube.com/watch?v=sTeoEFzVNSc&t=901s

## Applications that use the GPT API

* GPT for Google Sheets: https://gptforwork.com/ 
* GPT for R Studio: https://github.com/MichelNivard/gptstudio 
* GPT for R Developers: https://jameshwade.github.io/gpttools/
* GPT for PDFs (in a web interface, freemium service): https://chatpdf.com
* GPT directly from the command line: https://github.com/npiv/chatblade


## Prompt Engineering

* Quick guide of best practices for Prompt Engineering:  https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api
* More advanced guidance on Prompt Engineering: https://www.promptingguide.ai/
* Good 20 min blogpost covering core aspects of Prompt Engineering: https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/

## Understanding the tool 

* A very good post by Stephen Wolfram on the details on _how_ it works: https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/
* List of papers published by OpenAI: https://openai.com/research 
* Basic YouTube Crash Course on ChatGPT (12/December/2022, so a bit old): https://www.youtube.com/watch?v=JTxsNm9IdYU
* Technnical overview of details on how LLMs work and what can be their future (Eight Things to Know about Large Language Models): https://cims.nyu.edu/~sbowman/eightthings.pdf

### Ethics and Accountability Discussions

* "Pause Giant AI Experiments: An Open Letter" https://futureoflife.org/open-letter/pause-giant-ai-experiments/

## Bioinformatics-specific resources

* Ten Quick Tips for Harnessing the Power of ChatGPT/GPT-4 in Computational Biology (our preprint on tips, conflict disclosed): https://arxiv.org/abs/2303.16429 

* Single-cell RNA-seq analysis in Python guided by ChatGPT (nice video, from Cell Ranger output to final plots): https://www.youtube.com/watch?v=fkuLFlC2ZWk 

* Using ChatGPT in bioinformatics and biomedical research (good blog post): https://omicstutorials.com/using-chatgpt-in-bioinformatics-and-biomedical-research/

* ChatGPT for bioinformatics (on the perspective of a bioinformatician): https://medium.com/@91mattmoore/chatgpt-for-bioinformatics-404c6d0817a1

* ChatGPT and bioinformatics careers (Reddit forum discussion): https://www.reddit.com/r/bioinformatics/comments/11wwnqj/chatgpt_and_bioinformatics_careers/

* ChatG-PPi-T: Finding Interactions with OpenAI (far from production-ready, but creative idea): https://www.linkedin.com/pulse/chatg-ppi-t-finding-interactions-openai-jon-hill/

* BioGPT: generative pre-trained transformer for biomedical text generation and mining: https://github.com/microsoft/BioGPT

## API and advanced applications

* LangChain combines LLM/GPT API requests with (1) access to external documents and (2) abilities to talk to the wider web, creating semi-autonomous agents: https://python.langchain.com/en/latest/
* Llama Index is an interface for combining LLMs with external data (such as documents): https://gpt-index.readthedocs.io/en/latest/index.html 
* guardrails is an application to improve and refine LLM outputs in Python: https://github.com/ShreyaR/guardrails 

## Quick Prompts

The following prompts may not be the most efficient in terms of prompt engineering, but they are quick, useful and exemplify usage of ChatGPT for computational biologists. 

###  Improve Code Readability and Documentation

* “Add explanatory comments to this code: {code here}”
* “Rename the variables for clarity: {code here}” 
* "Render roxygen2 documentation for the function: {R code here}”.

### Write Code Efficiently

* "Extract functions to increase modularity: {code here}"
* "Write a unit test for the following function and help me implement it: {code here}"
* "Re-write and optimize this for loop: {code here}"

### Clean up data

* "Write me regex for R/python/Excel with a pattern that will extract {} from {}"
* "Act as a table. Add a new column with consistent labels to this dataset:"


### Improve data visualization

* "Create a ggplot2 violin plot with a log10 Y axis"
* "Change my code to make the plot color-blind friendly"
* "Translate this plot from ggplot2 to matplotlib syntax"

## Tutorials

* "A Guide to Using ChatGPT For Data Science Projects" : https://www.datacamp.com/tutorial/chatgpt-data-science-projects
