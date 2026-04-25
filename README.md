<div align="center">

# Ashwin Mathur

**AI Engineer · Agentic RAG & Reranking · LLM Fine-Tuning & RL · Domain-Specific AI**

[LinkedIn](https://www.linkedin.com/in/ashwin-mathur-ds/) •
[Email](mailto:ashwinmathur.business@gmail.com)
</div>

I work on LLM systems for domain-specific applications in Finance, Bio-Medical, and Legal AI, spanning retrieval, agents and model training. I’ve contributed to Haystack, MTEB, HuggingFace, and scikit-learn, and co-authored **[MMTEB](https://arxiv.org/abs/2502.13595)**, published at ICLR 2025. Developing open-source AI at [**AVNLP**](https://avnlp.github.io/).

### Developing Open-Source AI @ [AVNLP](https://avnlp.github.io/)

#### LLM Training & Alignment

| Repository | Description |
|---|---|
| [**BioThink**](https://github.com/avnlp/biothink) | Self-Reflective Bio-Medical Question Answering system - trains Qwen3-1.7B with QLoRA + GRPO using 5 custom reward functions (Relevance, Grounding, Utility token enforcement + XML structure + GEval correctness); evaluated across 7 metrics including faithfulness and answer correctness via LLM-as-a-Judge. |
| [**LLM-Finetuning**](https://github.com/avnlp/llm-finetuning) | Fine-tuning pipelines covering SFT, DPO, ORPO, KTO, and PPO; comparative benchmarking of QLoRA, LoRA, DoRA, P-Tuning, and Prefix-Tuning across ARC, FactScore, TriviaQA, and PopQA. |
| [**GRPO**](https://github.com/avnlp/grpo) | GRPO implementations comparing reward functions (format/correctness), training frameworks (DeepSpeed and PyTorch), and reference-model handling strategies. |
| [**RAG-Model-Training**](https://github.com/avnlp/rag-model-training) | Fine-tuning LLMs for 6 RAG paradigms - Adaptive-RAG, Corrective RAG, RQ-RAG, Self-RAG, Agentic RAG, ReZero - via SFT and GRPO; uses Llama-3.2, and Llama-3-8B across finance, biomedical, and open-domain QA datasets. |

#### Retrieval-Augmented Generation

| Repository | Description |
|---|---|
| [**RAG-Pipelines**](https://github.com/avnlp/rag-pipelines) | Agentic RAG pipelines with metadata enrichment, contextual reranking and structured generation. |
| [**DSPy-Optimizers**](https://github.com/avnlp/dspy-opt) | DSPy-based RAG optimization framework using MIPRO, COPRO, and BootstrapFewShot on FreshQA, HotpotQA, TriviaQA, PubMedQA. |
| [**VectorDB**](https://github.com/avnlp/vectordb) | Production Haystack and LangChain pipelines for Hybrid Search, Parent-Child Retrieval, MMR, Metadata Filtering, Multi-Tenancy, and Re-ranking across Pinecone, Weaviate, Milvus, Qdrant, and Chroma - with benchmarks on TriviaQA, ARC, PopQA, FactScore, and Earnings Calls. |

#### Information Retrieval & Ranking

| Repository | Description |
|---|---|
| [**LLM Rankers**](https://github.com/avnlp/rankers) | LLM re-ranking library for IR and RAG. Implements Pairwise, Setwise, and Listwise ranking with RankZephyr and RankLlama; supports sliding windows, efficient sorting, and zero-shot inference. |
| [**Pairwise Ranking Prompting**](https://github.com/avnlp/prp) | Zero-shot pairwise reranking library (Heapsort, Sliding Window, All-Pairs strategies) with bidirectional comparison for position-bias mitigation; Pydantic-validated. |
| [**Reciprocal Rank Fusion and LLM Rankers**](https://github.com/avnlp/rrf) | Hybrid retrieval with Reciprocal Rank Fusion (RRF); evaluates Diversity, Lost-in-the-Middle, and Similarity rankers against the BEIR suite (NDCG, MAP, Recall, Precision). |
| [**LLM-Blender**](https://github.com/avnlp/llm-blender) | Ensembling framework combining PairRanker (pairwise ranking) and GenFuser (output merging) to synthesize superior responses from multiple open-source models. |

### Open-Source Contributions

| Project | Contributions |
|---|---|
| **[Haystack](https://github.com/deepset-ai/haystack/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc)** | **Evaluation Framework**: Designed and built Haystack's pipeline evaluation from scratch - `StatisticalEvaluator`, `EvaluationResult`, and six metrics: Exact Match, F1, Semantic Answer Similarity, Recall, MRR, and MAP<br>**HuggingFace TEI Embedders**: Components supporting self-hosted Docker, free Inference API, and paid HF Inference Endpoints<br>**Diversity Ranker**: Document reranker optimizing for maximum semantic diversity via sentence-transformer embeddings |
| **[Haystack Core Integrations](https://github.com/deepset-ai/haystack-core-integrations/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc)** | **INSTRUCTOR Embedders**: Task- and domain-specific embedding components with instructable prompt prefixes<br>**HF Optimum**: Embedding inference with ONNX and TensorRT runtimes<br>**Llama.cpp Generator**: Text generation with quantized models<br>**Pinecone**: Vector DB integration with advanced metadata filtering |
| **[voyage-embedders-haystack](https://github.com/awinml/voyage-embedders-haystack)** | Haystack integration for Voyage AI embedding and reranking models |
| **[MTEB](https://github.com/embeddings-benchmark/mteb/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Aupdated-desc)** | **LegalBench**: Added the complete LegalBench benchmark suite - 160+ legal domain classification and retrieval datasets; Integrated Japanese embedding benchmarks JMTEB and JSICK.  |
| **[HuggingFace Transformers](https://github.com/huggingface/transformers/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Acomments-desc)** | `BioGPTForSequenceClassification` implementation; ViT pre-training scripts without the Trainer class; HuggingFace Evaluate + scikit-learn integration docs. |
| **[scikit-learn](https://github.com/scikit-learn/scikit-learn/pulls?q=is%3Apr+author%3Aawinml+is%3Aclosed+sort%3Acomments-desc)**, **[imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn/pulls?q=is%3Apr+is%3Aclosed+author%3Aawinml)** | Out-of-bag scores for Gradient Boosting; sparse matrix support for Silhouette Score; multi-class Average Precision (One-vs-Rest). |

### Publications

**[MMTEB: Massive Multilingual Text Embedding Benchmark](https://arxiv.org/abs/2502.13595)** (ICLR 2025)

Largest multilingual text embedding benchmark: 500+ tasks across 250+ languages and 10 task categories. Contributed the complete **[LegalBench](https://hazyresearch.stanford.edu/legalbench/)** suite - 160+ legal domain classification and retrieval datasets.
