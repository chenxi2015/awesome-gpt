# awesome-gpt
利用gpt4 生成的好玩的代码集合、文档、工具汇总等

## 注意：本仓库内容全部由GPT3.5、GPT4 生成，请理性阅读。

## 简介

本项目是一个基于ChatGPT GPT3.5 GPT4模型的代码和工具的汇总，包含了一些常用的交流模型、数据预处理、模型训练与评估、调参工具、文本生成工具等，旨在帮助开发人员更好地使用ChatGPT GPT3.5 GPT4模型进行自然语言处理（NLP）应用的开发。

[英文文档](README.md)

## 内容

### 代码合集【code目录】
- `inpainting.html` 利用canvas在图片背景绘画线条 可改变笔触宽度和颜色

### 文档汇总
1. GPT-3：深度学习与人工智能大爆发的时刻

https://cloud.tencent.com/developer/article/1889246

这篇文章介绍了GPT-3（Generative Pre-trained Transformer 3），它是一个由OpenAI开发的自然语言处理模型，被称为“神经网络大脑”的代表作之一。

2. Chatbots: Overview, Types, And Platforms To Build One

https://www.cleveroad.com/blog/chatbots-overview-types-and-platforms-to-build-one

这篇文章总结了聊天机器人的基础知识，包括各种类型、它们的应用领域和平台，以及如何构建一个聊天机器人。

3. Chatbot Development: From Intent to Integration

https://dzone.com/articles/chatbot-development-from-intent-to-integration

这篇文章介绍了聊天机器人开发的概述。作者从意图( Intent )，实体(Entity) 和对话管理框架(Dialogue management framework)三个方面入手，讨论如何构建聊天机器人。

4. ChatBots Magazine

https://chatbotsmagazine.com/

这是一个以聊天机器人为主题的在线杂志。

5. What is GPT-3? How does it work, and is it being overhyped?

https://www.zdnet.com/article/what-is-gpt-3-how-does-it-work-and-is-it-being-overhyped/

这篇文章介绍了GPT-3的基本原理和应用情况，并讨论了在人工智能领域中这种技术的各种争议。

6. GPT-3 Documentation

https://beta.openai.com/docs/

这是OpenAI官方网站上的GPT-3文档，提供了有关API、Python库、可用模型和示例的使用说明。

7. Building a Conversational AI Chatbot with Dialogflow

https://chatbotslife.com/building-a-conversational-ai-chatbot-with-dialogflow-7c138d170e8

这篇文章介绍了Dialogflow平台的基础知识，如何创建一个简单的聊天机器人，并涵盖了一些高级用途。

8. How to Build and Deploy a Chatbot Using Rasa

https://blog.rasa.com/how-to-build-and-deploy-a-chatbot-using-rasa/

这篇文章演示了用Rasa创建和部署一个聊天机器人的过程。包括数据预处理、教程、模型训练和测试等。

9. Python ChatBot Tutorial - Chatbot with Python

https://www.edureka.co/blog/python-chatbot-tutorial/

这篇文章是一个Python聊天机器人教程，教你如何使用Python和早期版本的GPT来构建自己的聊天机器人。

10. Building chat bots with Python and NLTK

https://becominghuman.ai/building-chat-bots-with-python-and-nltk-2a7ebe639373

这篇文章介绍了使用Python和NLTK创建聊天机器人的过程。作者讨论了如何从自然语言文本中提取特征，并展示了如何将这些特征与对话管理算法结合起来，以产生自然的对话。

### 工具汇总
1. [huggingface/transformers](https://github.com/huggingface/transformers) - 由 Hugging Face 维护的 Transformers 项目是一组自然语言处理 Python 库，其中包括了多个预训练语言模型的实现，其中包括最近相对较新的 GPT-3。该项目对 ChatGPT 进行了实现，可供用户直接使用。
2. [YaleGuitar/ChatGPT](https://github.com/YaleGuitar/ChatGPT) - 该作者针对 Microsoft 的 DialoGPT 模型进行了一些改进，使其可以训练更加适合聊天机器人场景的模型。
3. [VMware-AI/Conversational-AI-Agent](https://github.com/VMware-AI/Conversational-AI-Agent) - 该项目旨在使用 ChatGPT 模型从 VMware 社区贡献中构建聊天机器人，使用户可以与该机器人进行对话以得到答案和支持。使用了 DialoGPT 训练，将模型训练在 VMWare 社区提供的对话语料库上。
4. [liao991022/gpt_chatbot](https://github.com/liao991022/gpt_chatbot) - 作者这个项目使用的是泛华科技发布的 GPT-2 预训练模型，结合了微调和机器学习方法使得 ChatGPT 模型的聊天效果更好一些。
5. [tommy0103/sdumc_chatbot](https://github.com/tommy0103/sdumc_chatbot) - 作者这个项目研究聊天机器人应用在医疗领域，使用 transfer-learning 技术从 DialoGPT 模型进行微调，加入领域相关语料库后再进行训练，达到了更好的对话质量。
6. [turing-nlg/gpt-chatbot](https://github.com/turing-nlg/gpt-chatbot) - 作者使用了 GPT-3 和 DialoGPT，构建了一个聊天机器人，可以和人类进行交互，并提供对话日志以对论点进行评估。

## 使用

使用本项目中的工具和代码需要基本的NLP和Python编程知识，以下是一些快速入门资料和教程：

- Hugging Face官方文档：<https://huggingface.co/docs>
- Python基础教程：<https://docs.python.org/3/tutorial/>
- NLP基础知识：<https://web.stanford.edu/~jurafsky/slp3/>
- Transformer模型介绍：<https://arxiv.org/abs/1706.03762>

## 贡献

本项目欢迎各种形式的贡献，包括但不限于：

- 提交代码
- 优化代码
- 报告bugs
- 修复bugs
- 提供文档意见
- 提供工具建议

为了保证代码和文档的质量和可读性，请在提交前阅读贡献指南（[CONTRIBUTING.md](CONTRIBUTING.md)）。

## 许可证

本项目的代码和文档遵循MIT许可证，具体条款请见LICENSE文件。