<div align="center">

# Ashwin Mathur

**AI Engineer · Agentic RAG & Reranking · LLM Fine-Tuning & RL · Domain-Specific AI**

[LinkedIn](https://www.linkedin.com/in/ashwin-mathur-ds/) •
[Email](mailto:ashwinmathur.business@gmail.com)
</div>

I work on LLM systems for domain-specific applications in Finance, Bio-Medical, and Legal AI, spanning retrieval, agents and model training. I've contributed to Haystack, MTEB, HuggingFace, and scikit-learn, and co-authored **[MMTEB](https://arxiv.org/abs/2502.13595)**, published at ICLR 2025. Developing open-source AI at [**AVNLP**](https://avnlp.github.io/).

### Developing Open-Source AI @ [AVNLP](https://avnlp.github.io/)

#### LLM Training & RL Alignment

| Repository | Description |
|---|---|
| [**BioThink**](https://github.com/avnlp/biothink) | Self-Reflective Bio-Medical QA training with QLoRA + GRPO to generate structured self-reflection tokens using six reward functions; evaluated across seven metrics via LLM-as-a-Judge. |
| [**RAG Model Training**](https://github.com/avnlp/rag-model-training) | Fine-tuning LLMs for Adaptive-RAG, Corrective RAG, RQ-RAG, Self-RAG, Agentic RAG, and ReZero via SFT and GRPO across finance, biomedical, and open-domain QA. |
| [**GRPO**](https://github.com/avnlp/grpo) | Four GRPO implementations comparing format/correctness rewards, DeepSpeed vs. PyTorch training, frozen/server/periodic reference models, and vLLM vs. Transformers rollout generation. |
| [**LLM Finetuning**](https://github.com/avnlp/llm-finetuning) | SFT, DPO, KTO, ORPO, PPO, and GRPO pipelines with QLoRA/LoRA/DoRA/P-Tuning/Prefix-Tuning adapter training across ARC, FactScore, TriviaQA, PopQA, Earnings Calls, and GSM8K. |

#### Retrieval Augmented Generation and Agents

| Repository | Description |
|---|---|
| [**RAG Pipelines**](https://github.com/avnlp/rag-pipelines) | Domain-specific RAG pipelines combining LangGraph orchestration, BAML structured generation, Milvus Hybrid Search, 3-layer metadata enrichment, and instruction-following rerankers for Medical and Financial QA. |
| [**DSPy Optimizers**](https://github.com/avnlp/dspy-opt) | DSPy RAG optimization with Weaviate Hybrid Search, Query Rewriting, Sub-Query Decomposition using MIPROv2/COPRO/BootstrapFewShot optimizers on FreshQA, HotpotQA, TriviaQA, and PubMedQA. |
| [**VectorDB**](https://github.com/avnlp/vectordb) | Haystack and LangChain retrieval pipelines spanning Dense/Sparse/Hybrid search, Reranking, Parent-Child Retrieval, Query Enhancement, and Multi-Tenancy across Pinecone, Weaviate, Milvus, Qdrant, and Chroma. |

#### Information Retrieval & Ranking

| Repository | Description |
|---|---|
| [**LLM Rankers**](https://github.com/avnlp/rankers) | LLM rankers using Pairwise, Setwise, and Listwise techniques with RankZephyr/RankLlama, Pydantic-validated structured generation, and efficient zero-shot sorting. |
| [**Pairwise Ranking Prompting**](https://github.com/avnlp/prp) | Zero-shot pairwise reranking with All-Pairs, Heapsort, and Sliding-K strategies, using bidirectional comparison for position-bias mitigation and Pydantic-validated outputs. |
| [**Reciprocal Rank Fusion and LLM Rankers**](https://github.com/avnlp/rrf) | Hybrid retrieval combining Reciprocal Rank Fusion with Diversity, Lost-in-the-Middle, and Similarity rankers, evaluated on BEIR (NDCG, MAP, Recall, Precision). |
| [**LLM Blender**](https://github.com/avnlp/llm-blender) | LLM ensembling framework using PairRanker for cross-attention candidate ranking and GenFuser for top-K output fusion, packaged as a Haystack component. |

### Open-Source Contributions

- **[Haystack](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc)** - Built the Haystack evaluation framework (`eval`, `EvaluationResult`, `calculate_metrics`) and four metrics (EM, F1, SAS, MRR); added HuggingFace TEI Embedders and a sentence-transformer Diversity Ranker.
- **[MTEB](https://github.com/embeddings-benchmark/mteb/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc)** - Added the complete LegalBench Benchmark (160+ legal classification and retrieval datasets) and four Japanese benchmarks (JMTEB Clustering, JSICK, JaGovFaqs, NLPJournal).
- **[Haystack Core Integrations](https://github.com/deepset-ai/haystack-core-integrations/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc)** - Implemented INSTRUCTOR Embedders, Optimum Embedders (ONNX runtime), Llama.cpp Generator, Pinecone Document Store, and Cohere V3 Embed model support.
- **[HuggingFace Transformers](https://github.com/huggingface/transformers/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Acomments-desc)**, **[Evaluate](https://github.com/huggingface/evaluate/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed)** - `BioGPTForSequenceClassification` and Trainer-free ViT pre-training scripts in Transformers; scikit-learn integration guides in Evaluate.
- **[scikit-learn](https://github.com/scikit-learn/scikit-learn/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Acomments-desc)**, **[imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn/pulls?q=is%3Apr+is%3Aclosed+author%3Aawinml)** - Three core scikit-learn features: OOB fitted scores for Gradient Boosting, sparse-matrix support for `silhouette_samples`, and multiclass `average_precision_score`.
- **[voyage-embedders-haystack](https://github.com/awinml/voyage-embedders-haystack)** - Full Haystack integration for Voyage AI: text/document embedders, reranker, multimodal embeddings, and contextualized chunk embeddings; published on PyPI.

### Publications

**[MMTEB: Massive Multilingual Text Embedding Benchmark](https://arxiv.org/abs/2502.13595)** (ICLR 2025)

Largest multilingual text embedding benchmark: 500+ tasks across 250+ languages and 10 task categories. Contributed the complete **[LegalBench](https://hazyresearch.stanford.edu/legalbench/)** suite - 160+ legal domain classification and retrieval datasets.
