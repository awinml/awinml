<h2 align="center"> Hi there, I'm Ashwin Mathur!</h2>

NLP Developer with expertise in the development of applications using Large Language Models (LLMs). Active contributor to open-source projects.

Some interesting projects I have worked on:

**Open-Ended Question-Answering Pipeline on Earnings Call Transcripts using Generative LLMs:**

- Built a Retrieval Augmented Generation (RAG) pipeline that reduced time for investors and analysts to extract actionable insights from earnings calls, enabling better investment decisions through easy information attribution and minimal hallucination. Key components include Embedding Model, Context Retriever, Prompt Generator, and Generative LLM.
- Extracted text snippets from each section of the earnings call, chunked them dynamically based on similarity, and created embeddings which were stored in a Pinecone vector database.
- Experimented with and selected the best SOTA embedding models (SBERT, MPNET, SGPT and INSTRUCTOR) and context retrieval strategies for the pipeline, resulting in significant improvements in accuracy and performance. The INSTRUCTOR Embedding model gave the best context retrieval. A combination of dense and hybrid retrieval strategies gave the best results. 
- Leveraged weak supervision techniques to dynamically generate few-shot examples for prompts for entity extraction and question-answering. Carried out extensive prompt tuning by iteratively refining prompt formatting, instructions and incorporating few-shot examples.
- Experimented with the SOTA instruction-tuned LLMs for generating answers: Llama-2, Vicuna, Alpaca, Dolly, FLAN-T5 and GPT-3. The Llama-2 and GPT-3 LLMs generated the most accurate and concise answers.
- Evaluated the generated answers on Coverage, Redundancy, and Hallucination, quantitatively comparing text generation performance while ensuring accuracy.

**Effect of Few-Shot Prompting on LLM Performance and Evaluation using the EleutherAI LLM Harness:**

- Evaluated the generative performance of three language models - OPT, GPTNeo, and Dolly - across benchmark datasets (AI2’s Reasoning Challenge, Adversarial Natural Language Inference, and Winograd Schema Challenge) using various prompt settings: Zero-Shot, One-Shot, Three-Shot, and Five-Shot prompts.
- Observed that model performance on all the benchmarks linearly scales with an increase in model size and there is a significant increase in performance as the number of few-shot (in-context) examples increases in the prompt.

**Effect of Optimizer Selection and Hyperparameter Tuning on Training Efficiency and LLM Performance:**

- Investigated the impact of optimizer selection and associated hyperparameters on model performance during training across diverse tasks.
- Evaluated the performance of five different optimizers (AdamW, RMSProp, NAG, SGD with Momentum, and SGD) on various natural language processing tasks such as Sentiment Analysis, Question Answering, and Text Summarization. Analyzed the convergence of the best-performing models on each dataset.
- Fine-tuned DistilBERT, BERT, and FinBERT models for Sentiment Analysis on the StockTwits dataset, while DistilBERT, BERT, RoBERTa were fine-tuned for Question Answering on the CoQA dataset. For Text Summarization, BART, DistillBART, and T5 models were fine-tuned on the BillSum dataset.
- Empirical observations highlighted that more general optimizers like RMSProp and AdamW consistently performed as well as, if not better than, specialized optimizers like SGD, Nesterov, or Momentum, given appropriately selected hyperparameters.


**Open Source Contributions**:
  - **[Haystack](https://github.com/deepset-ai/haystack)**: [deepset-ai/haystack](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc), [deepset-ai/haystack-core-integrations](https://github.com/deepset-ai/haystack-core-integrations/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc)
  - **[HuggingFace](https://github.com/huggingface)**: [huggingface/transformers](https://github.com/huggingface/transformers/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Acomments-desc), [huggingface/evaluate](https://github.com/huggingface/evaluate/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Acomments-desc)
  - **[scikit-learn](https://github.com/scikit-learn)**: [scikit-learn](https://github.com/scikit-learn/scikit-learn/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Acomments-desc), [imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn/pulls?q=is%3Apr+is%3Aclosed+author%3Aawinml)

I'm best reached via Email or LinkedIn. Open to interesting conversations and collaboration. 

Feel free to reach out to me:  &nbsp;

<a href="mailto:ashwinmathur.business@gmail.com"><img src="https://img.shields.io/badge/Email-grey?style=for-the-badge&logo=Gmail" alt="Email" href="mailto:ashwinmathur.business@gmail.com"></a>
<a href="https://www.linkedin.com/in/ashwin-mathur-ds/"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=LinkedIn" alt="LinkedIn" href="https://www.linkedin.com/in/ashwin-mathur-ds/"></a>


<!--
  Title: Ashwin Mathur Github
  Description: Data Science - Ashwin Mathur Github
  Author: awinml

**awinml/awinml** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:



- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

[![My GitHub Stats](https://github-readme-stats.vercel.app/api/?username=awinml&count_private=true&show_icons=true&hide_rank=true&hide=contribs&include_all_commits=true)]()

![](https://komarev.com/ghpvc/?username=awinml&color=green&style=for-the-badge&label=Profile+Views)

-->

