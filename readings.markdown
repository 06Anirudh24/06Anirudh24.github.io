---
layout: page
title: Reading List
---

This is my NLP paper reading list! Here, I maintain a list of papers (and posts) that I consider important for understanding the fundamentals of NLP. I also add papers I enjoyed reading the most in different sub-domains and try to update the list frequently.

# Fundamentals - Neural Language Models, Transformers, BERT, etc. 
- [On the difficulty of training recurrent neural networks](https://proceedings.mlr.press/v28/pascanu13.pdf) - This paper introduces the vanishing gradient problem in RNNs. (2013)
- A super easy-to-read [blog post](https://medium.com/analytics-vidhya/introduction-to-long-short-term-memory-lstm-a8052cd0d4cd) for understanding LSTMs (2023)
- [Neural machine translation by jointly learning to align and translate](https://arxiv.org/pdf/1409.0473) - Introduces attention mechanism. (2015)
- [Attention Is All You Need](https://arxiv.org/pdf/1706.03762) - The super famous transformers paper! (2017)
- Understanding attention and transformer - [Blog post 1](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/), [Blog post 2](https://jalammar.github.io/illustrated-gpt2/) (2021)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805) (2019)
- [Roformer: Enhanced transformer with rotary position embedding](https://arxiv.org/pdf/2104.09864) - An excellent paper on positional embedding. (2021)
- [Deep contextualized word representations](https://arxiv.org/pdf/1802.05365) - ELMo word embeddings (2018)
- [Finetuned language models are zero-shot learners](https://example-link.com) - Jason Wei's paper on Instruction Tuning (FLAN) (2022)

***
# Parameter-efficient Adoption of LLMs
- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) (2021)
- [The Power of Scale for Parameter-Efficient Prompt Tuning](https://arxiv.org/pdf/2104.08691) (2023)

***
# LLM Alignment
- [Training language models to follow instructions with human feedback](https://cdn.openai.com/papers/Training_language_models_to_follow_instructions_with_human_feedback.pdf) - RLHF Paper (2022)
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/pdf/2212.08073) (2022)
- An excellent, easy-to-read [blog](https://gist.github.com/yoavg/6bff0fecd65950898eba1bb321cfbd81) explaining the the need for RLHF. (2023)
- [RLAIF vs. RLHF: Scaling Reinforcement Learning from Human Feedback with AI Feedback](https://arxiv.org/pdf/2309.00267) (2023)
- [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290) (2023)
- [Fine-tuning Language Models for Factuality](https://arxiv.org/pdf/2311.08401) (2023)
- [Alignment for Honesty](https://arxiv.org/abs/2312.07000) (2023)
- [Understanding the effects of rlhf on llm generalisation and diversity](https://arxiv.org/abs/2310.06452)(2024)
- Huggingface's [blog post](https://huggingface.co/blog/pref-tuning) on DPO v/s IPO v/s KTO. (2024)

***
# Evaluation and Factuality
- [BLEURT: robust metrics for text generation](https://arxiv.org/pdf/2004.04696) (2020)
- [Judging LLM as a Judge with MT-Bench and Chatbot Arena](https://arxiv.org/pdf/2306.05685) (2023)
- [FactScore: Fine-grained atomic evaluation of factual precision](https://arxiv.org/pdf/2305.14251) (2023)
- [AVeriTeC: A Dataset for Real-world Claim Verification with Evidence from the Web](https://arxiv.org/abs/2305.13117) (2023)
- [Long-form factuality in large language models](https://arxiv.org/pdf/2403.18802) - SAFE Score (2024)
- [BooookScore: A systematic exploration of book-length summarization in the era of LLMs](https://arxiv.org/abs/2310.00785) (2024)
- [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference] (2024)
- [Automatic Metrics in Natural Language Generation: A Survey of Current Evaluation Practices](https://www.arxiv.org/pdf/2408.09169) (2024)
- [Enabling Language Models to Implicitly Learn Self-Improvement](https://arxiv.org/abs/2310.00898) (2024)
- [VERISCORE: Evaluating the factuality of verifiable claims in long-form text generation](https://arxiv.org/abs/2406.19276) (2024)
- [Suri: Multi-constraint Instruction Following for Long-form Text Generation](https://arxiv.org/abs/2406.19371) (2024)

*** 
# Creativity and Narrative Writing
- [AI as Humanity's Salieri: Quantifying Linguistic Creativity of Language Models via Systematic Attribution of Machine Text against Web Text](https://arxiv.org/pdf/2410.04265v1) (2024)
- [Are Large Language Models Capable of Generating Human-Level Narratives?](https://arxiv.org/abs/2407.13248) (2024)

*** 
# RAG and Personalization
- [REALM: Retrieval-Augmented Language Model Pre-Training](https://arxiv.org/pdf/2002.08909) (2020)
- [LaMP: When Large Language Models Meet Personalization](https://arxiv.org/abs/2304.11406) (2023)
- [FreshLLMs: Refreshing Large Language Models with Search Engine Augmentation](https://arxiv.org/abs/2310.03214) (2023)
- [Evaluating Retrieval Quality in Retrieval-Augmented Generation](https://dl.acm.org/doi/abs/10.1145/3626772.3657957) (2024)
- [LongLaMP: A Benchmark for Personalized Long-form Text Generation](https://arxiv.org/pdf/2407.11016) (2024)

***
# Prompt Engineering and In-context Learning
- [Rethinking the role of demonstrations: What Makes In-Context Learning Work?](https://arxiv.org/pdf/2202.12837) (2022)
- [Blog](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/) on different prompting strategies (2023)
- [What learning algorithm is in-context learning? Investigations with linear models](https://openreview.net/pdf?id=0g0X4H8yN4I) (2023)
- [To CoT or not to CoT? Chain-of-thought helps mainly on math and symbolic reasoning](https://arxiv.org/abs/2409.12183) (2024)
- [LLMs Are In-Context Reinforcement Learners](https://arxiv.org/abs/2410.05362) (2024)

***
# Detecting LLM-generated Text
- [A Watermark for Large Language Models](https://arxiv.org/pdf/2301.10226) (2023)
- [Paraphrasing evades detectors of AI-generated text, but retrieval is an effective defense](https://arxiv.org/pdf/2303.13408) (2023)
- [PostMark: A Robust Blackbox Watermark for Large Language Models](https://arxiv.org/pdf/2406.14517) (2024)
