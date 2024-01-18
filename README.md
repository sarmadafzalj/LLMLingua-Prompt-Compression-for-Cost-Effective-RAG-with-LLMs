# Demonstrating LLM Lingua for Efficient Language Model Compression
### Introduction
This repository contains a Jupyter notebook that demonstrates the effective use of LLM Lingua, a tool for efficient language model compression. The project showcases how LLM Lingua can be utilized to overcome the limitations of token constraints in generative language models like GPT-3.5 and GPT-4, ensuring cost-effective and contextually rich applications. It covers a comparison of number of **Tokens** and **Cost** with and without compression while preserving the quality of **Response**

![image.png](Images/compress.png)

### Overview
LLM Lingua addresses significant challenges in language model usage:

- Token Limitations: By efficiently compressing inputs, it tackles the token limitations in models like GPT-3.
- Contextual Integrity: It ensures that essential contextual details are retained, especially in extensive interactions.

### Project Setup
To replicate and understand this demonstration, the following packages are required:

```python
# pip install llmlingua==0.1.5
# pip install streamlit==1.28.2
# pip install langchain==0.0.336
# pip install openai==1.2.0
# pip install tiktoken==0.4.0
# pip install PyPDF2==3.0.1
# pip install accelerate==0.26.1
# pip install optimum==1.16.1
# pip install auto-gptq
```
### Further Reading
For detailed insights into the methodologies and technicalities, refer to the related academic papers:

- Paper 1: https://arxiv.org/abs/2310.06839
- Paper 2: https://aclanthology.org/2023.emnlp-main.825

Notebook:
- <i>Author: <b>Sarmad Afzal</b></i>
- <i>Linkedin: https://www.linkedin.com/in/sarmadafzal/</i>
- <i>Github: https://github.com/sarmadafzalj</i>
- <i>Youtube: https://www.youtube.com/@sarmadafzalj</i>
