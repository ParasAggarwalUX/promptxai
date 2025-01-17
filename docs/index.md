---
title: Generative AI Playbook by PromptxAI
hide:
    - navigation
---
# Generative AI Playbook by PromptxAI

Generative AI is disrupting many industries and significantly reshaping future of work for many creative and knowledge-driven functions. PromptxAI is on a mission to help businesses and individuals leverage the power of Generative AI to accelerate their growth and innovation. We are building a Generative AI Playbook to help you get started with Generative AI. You can access the Generative AI Playbook on this website in various ways including learning creative prompt engineering [techniques](chatgpt/generating-diagrams-from-world-knowledge) to make the most of Generative AI applications like [ChatGPT](chatgpt/historical-fact-question-answer), Midjourney, DALL-E, [Stable Diffusion](stability-ai/interview-with-stability-ai-ceo), D-ID, and more. You can also learn about the [trends](chatgpt/openai-ceo-sam-altman-on-ai-for-the-next-era) impacting future of work and how to leverage these as ideas for your own business or career. We are also sharing accelerator [notebooks](api/low-code-blog-authoring-automation) and code [libraries](api/promptxai-api) to help you get started with Generative AI.

## Playbook with popular examples

Here is a version of the playbook with most popular examples.

![PromptxAI Generative AI Playbook](assets/images/promptxai-generative-ai-playbook.jpg)

## Extended playbook with a generic framework

Here is a generic version of the playbook which extends the Generative AI landscape with Agents, Tools, and Content. This playbook extends and uses [LangChain](https://langchain.readthedocs.io/en/latest/index.html) as a generic framework for working with LLMs.

1. **Prompts:** This includes prompt management, prompt optimization, and prompt serialization.
2. **Models:** This includes LLMs and pre-trained deep learning transformer models.
3. **Content:** This includes content which can be used to enhance a prompt with few-shot learning, content which can fine-tune an LLM, or content which can be enhanced or generated by LLM completions.
4. **Tools:** Language models are often more powerful when interacting with other sources of knowledge or computation. This can include Python REPLs, embeddings, search engines, and more.
5. **Chains:** Chains go beyond just a single LLM call, and are sequences of calls (whether to an LLM or a different utility).
6. **Agents:** Agents involve an LLM making decisions about which Actions to take, taking that Action, seeing an Observation, and repeating that until done.
7. **Memory:** Memory is the concept of persisting state between calls of a chain/agent.
8. **Infrastructure:** This includes hubs like Hugging Face, GitHub, and Kaggle. It also includes cloud providers like AWS, GCP, and Azure. First movers like OpenAI and Stability AI are hosted providers of LLMs. Another emerging category is specialized multi-cloud orchestrators for LLM training, optimization, and inference.

![PromptxAI Generative AI Playbook Generic](assets/images/promptxai-generative-ai-playbook-generic.jpg)

### Content generation

You can explore the generic playbook on this website. Let's start with far right part of the playbook, Content. An example of prompt-model-completion sequence generating content in the format of a diagram is demonstrated in [Generating Diagrams from World Knowledge](chatgpt/generating-diagrams-from-world-knowledge) section. You can also explore [Low Code Blog Authoring Automation](api/low-code-blog-authoring-automation) section to learn about how to use PromptxAI API to automate blog authoring. The post on [Natural Language Analytics and Visualization](chatgpt/natural-language-analytics-and-visualization) demonstrates charts and graphs. The [OpenAI CEO Sam Altman on AI for Next Era](chatgpt/openai-ceo-sam-altman-on-ai-for-the-next-era) interview demonstrates creating topic maps and summaries as content. You can generate datasets like [Historical Fact Question Answer](chatgpt/historical-fact-question-answer) does for ancient civilizations.

### Content ingestion

While LLMs are trained on large corpuse of data, the training process is expensive and time consuming and requires a lot of compute. This means LLMs are not aware of the latest developments in a domain. So, you cannot use them to answer questions based on this unseen content. This is where content ingestion comes in. You can apply the capabilities of LLMs to understand and analyze content in a domain even if they have not seen it before. The limit though is the number of tokens an LLM can take as a prompt completion sequence. An example of content ingestion is demonstrated by [Model Card Generator](api/model-card-generator) notebook. The PromptxAI API can be used to generate model cards for any model where a public website explains relevant details about the model. We have create model cards under the menu [Models](models/large-language-models/) to demonstrate this capability.


## Trends impacting future of work

There are several trends impacting future of work. We are concerned about impact on the knowledge worker and startup community. Here are some trends we believe are at the heart of the workplace disruption as explained by ChatGPT Transformer model (leading example of trend 1) generated completions or responses based on prompts or inputs we have provided (example of trend 2). We have coined a shared name for GitHub, Kaggle, and Huggingface as trend 3, calling them Creator Hubs.

## Trend 1: Generative AI

ChatGPT, DALL-E, Midjourney, Stable Diffusion, D-ID are popular applications of Generative AI. While ChatGPT generates human-like responses as a chatbot, DALL-E, Midjourney, and Stable Diffusion can generate images from text prompts. D-ID generates videos. Behind the scenes these applications use Transformer models such as GPT-3, also known as Large Language Models.

```yaml title="ChatGPT Prompt"
Explain Generative AI with well known examples. Cite sources.
```

!!! note "ChatGPT Completion"
    Generative AI is a type of artificial intelligence that focuses on creating new data from existing data. It is used to generate new data that is similar to existing data, but not identical. Generative AI can be used to create new images, music, text, and videos.

    One of the most well-known examples of generative AI is Google’s DeepDream. DeepDream is a computer vision program that uses a deep neural network to generate new images based on existing images. It can be used to create surreal and abstract images from existing photographs.

    Another example of generative AI is OpenAI’s GPT-3. GPT-3 is a natural language processing system that can generate text based on existing text. It can be used to generate new stories, articles, and other written content.

    Finally, generative AI can also be used to create new music. Google’s Magenta project uses generative AI to create new music based on existing music. It can be used to create new compositions or remix existing songs.

    Sources:

    - https://www.analyticsinsight.net/what-is-generative-ai/
    - https://www.forbes.com/sites/cognitiveworld/2020/07/14/what-is-generative-ai-and-how-it-works/#3f9f9f9f3f2f
    - https://www.towardsdatascience.com/generative-ai-what-it-is-and-how-it-works-f9f9f9f3f2f


## Trend 2: Prompt Engineering

Prompt Engineering is right now the buzz on social media. It is interesting how Sam Altman addresses future of Prompt Engineering in the interview (25:09) where he thinks it will evolve to people just interacting with AGI in a natural way. However, Reid Hoffman makes a counterpoint how an artist can articulate much better prompts and get more out of Transformer Models than a casual user.

```yaml title="ChatGPT Prompt"
Explain Prompt Engineering as it applies to models like ChatGPT and Midjourney
```

!!! note "ChatGPT Completion"
    Prompt engineering is a technique used to improve the performance of natural language processing (NLP) models such as ChatGPT and Midjourney. It involves carefully crafting the input to the model to ensure that it produces the desired output. This can involve changing the wording of the input, adding additional context, or providing additional information. By doing this, the model can better understand the user’s intent and provide more accurate and relevant responses. Prompt engineering can also be used to improve the model’s ability to generate natural-sounding responses.


## Trends 3: Creator Hubs

To understand the gap between successful entrepreneurs or startup teams and the typical knowledge worker at an established enterprise, one can compare their tooling, work habits, and skills. Alternatively, one can look at the rapid clip of advances made by open source and citizen data science communities versus those of market leaders in the same space. The acquisitions of Kaggle by Google in 2017 (financial terms undisclosed), GitHub by Microsoft in 2018 (for $7.5 billion), Streamlit by Snowflake in 2021 (for $800 million), the $2 billion valuation of Huggingface, and the projected $20 billion valuation of OpenAI at the end of 2022 demonstrate the impact of these new market makers on the future of work and the growth of a community of knowledge workers learning new skills. Hugging Face offers Streamlit Spaces for hosting apps built on Streamlit. OpenAI GPT-2 model is available on Hugging Face Models reponsitory (as on Feb'23 hosting more than 133K pre-trained models).

```yaml title="ChatGPT Prompt"
Briefly explain what is GitHub, Kaggle, and Huggingface. 
What does success of GitHub, Huggingface, and Kaggle have in common? 
Explain as an expert in the subject using a few paragraphs in narrative style. 
```

!!! note "ChatGPT Completion"
    GitHub is a platform for version control and collaboration on software projects. It allows developers to share and work on code together, and offers a variety of tools and features to make it easier for developers to collaborate and manage their projects.

    Kaggle is a platform for data science competitions and collaboration on data science projects. It offers a variety of datasets, as well as tools for data exploration, visualization, and machine learning model development. Kaggle is popular among data scientists and analysts who want to learn from and work with others in the field.

    Huggingface is a platform for working with natural language processing (NLP) models. It provides access to a large collection of pre-trained models and tools for working with them, and is popular among researchers and developers working on NLP projects.

    The success of GitHub, Huggingface, and Kaggle can be attributed to a few key factors.

    First, all three platforms offer valuable resources and tools that are useful to developers and data scientists. GitHub is a popular platform for version control and collaboration on software projects, and it offers a variety of tools and features that make it easier for developers to work together on code. Huggingface is a platform for working with natural language processing (NLP) models, and it provides access to a large collection of pre-trained models and tools for working with them. Kaggle is a platform for data science competitions and collaboration on data science projects, and it offers a variety of datasets, as well as tools for data exploration, visualization, and machine learning model development.

    Another factor contributing to the success of these platforms is their focus on community and collaboration. All three platforms provide a way for users to share their work with others and collaborate on projects, which can be a valuable resource for developers and data scientists. This helps to create a sense of community and encourages users to contribute their knowledge and skills.

    Finally, the success of these platforms can also be attributed to their user-friendly interfaces and ease of use. GitHub, Huggingface, and Kaggle all have well-designed websites that are easy to navigate and use, which helps to make them accessible to a wide range of users.

    Overall, the success of GitHub, Huggingface, and Kaggle can be attributed to the valuable resources and tools they offer, their focus on community and collaboration, and their user-friendly interfaces. These factors have helped to make these platforms popular among developers and data scientists, and have contributed to their success in the tech industry.

