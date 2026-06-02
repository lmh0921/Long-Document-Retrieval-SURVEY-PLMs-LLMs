# LongDocumentRetrieval-PLM-LLM-Survey

This repository collects papers related to **Long-Document Retrieval (LDR)** for **Information Retrieval (IR)**, with emphasis on **PLM/LLM-era LDR**.

- Most are in our survey paper: **A Survey of Long-Document Retrieval in the PLM and LLM Era**

## Citation

```bibtex
@article{li2025survey,
  title={A Survey of Long-Document Retrieval in the PLM and LLM Era},
  author={Li, Minghan and Luo, Miyang and Lv, Tianrui and Zhang, Yishuai and Zhao, Siqi and Nie, Ercong and Zhou, Guodong},
  journal={arXiv preprint arXiv:2509.07759},
  year={2025}
}
```

## Table of Contents

- [PLM and LLM Era Models for Long-Document Retrieval](#plm-and-llm-era-models-for-long-document-retrieval)
- [LLM-era Emerging Directions for Long-Document Retrieval](#llm-era-emerging-directions-for-long-document-retrieval)
- [Datasets, Benchmarks, and Evaluation](#datasets-benchmarks-and-evaluation)
- [Applications and Use Cases](#applications-and-use-cases)
- [Current Challenges and Future Directions](#current-challenges-and-future-directions)

## Paper List

Papers are grouped by the survey chapter/subsection where they are discussed, starting from Chapter 4. Entries are sorted by year in descending order. Code links are included when a public repository can be identified.

### PLM and LLM Era Models for Long-Document Retrieval

#### The Holistic Paradigm in the PLM & LLM Era

##### Naive Truncation Baselines

- **Dense Passage Retrieval for Open-Domain Question Answering** - Karpukhin, 2020 | Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP) [Paper](https://doi.org/10.18653/v1/2020.emnlp-main.550) [Code](https://github.com/facebookresearch/DPR)
- **Approximate nearest neighbor negative contrastive learning for dense text retrieval** - Xiong, 2021 | International Conference on Learning Representations [Paper](https://openreview.net/forum?id=zeFrfgyZln) [Code](https://github.com/microsoft/ANCE)

##### Long-Sequence Transformer Architectures

- **LongEmbed: Extending Embedding Models for Long Context Retrieval** - Zhu, 2024 | Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2024.emnlp-main.47) [Code](https://github.com/dwzhu-pku/LongEmbed)
- **BGE M3-Embedding: Multi-Lingual, Multi-Functionality, Multi-Granularity Text Embeddings Through Self-Knowledge Distillation** - Chen, 2024 | Findings of the Association for Computational Linguistics ACL 2024 [Paper](https://doi.org/10.18653/v1/2024.findings-acl.137) [Code](https://github.com/FlagOpen/FlagEmbedding)
- **Longnet: Scaling transformers to 1,000,000,000 tokens** - Ding, 2023 | arXiv preprint arXiv:2307.02486 [Paper](https://arxiv.org/abs/2307.02486)
- **Socialformer: Social network inspired long document modeling for document ranking** - Zhou, 2022 | Proceedings of the ACM Web Conference 2022 [Paper](https://doi.org/10.1145/3485447.3511962)
- **Flashattention: Fast and memory-efficient exact attention with io-awareness** - Dao, 2022 | Advances in neural information processing systems [Paper](https://doi.org/10.52202/068431-1189) [Code](https://github.com/Dao-AILab/flash-attention)
- **Longformer: The Long-Document Transformer** - Beltagy, 2020 | arXiv preprint arXiv:2004.05150 [Paper](https://arxiv.org/abs/2004.05150) [Code](https://github.com/allenai/longformer)
- **Long document ranking with query-directed sparse transformer** - Jiang, 2020 | Findings of the Association for Computational Linguistics: EMNLP 2020 [Paper](https://doi.org/10.18653/v1/2020.findings-emnlp.412)
- **Big Bird: Transformers for Longer Sequences** - Zaheer, 2020 | Advances in Neural Information Processing Systems 33 [Paper](https://proceedings.neurips.cc/paper/2020/hash/c8512d142a2d849725f31a9a7a361ab9-Abstract.html) [Code](https://github.com/google-research/bigbird)
- **Reformer: The Efficient Transformer** - Kitaev, 2020 | International Conference on Learning Representations [Paper](https://openreview.net/forum?id=rkgNKkHtvB)

##### LLMs as Holistic Rerankers

- **Language Model Re-rankers are Fooled by Lexical Similarities** - Hagstrom, 2025 | Proceedings of the Eighth Fact Extraction and VERification Workshop (FEVER) [Paper](https://doi.org/10.18653/v1/2025.fever-1.2)
- **Lost in the middle: How language models use long contexts** - Liu, 2024 | Transactions of the association for computational linguistics [Paper](https://doi.org/10.1162/tacl_a_00638)
- **Fine-tuning llama for multi-stage text retrieval** - Ma, 2024 | Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3626772.3657951)
- **Lost in the Middle: How Language Models Use Long Contexts** - Liu, 2024 | Transactions of the Association for Computational Linguistics [Paper](https://doi.org/10.1162/tacl_a_00638)
- **Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agents** - Sun, 2023 | Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2023.emnlp-main.923) [Code](https://github.com/sunnweiwei/RankGPT)

##### Limitations and Open Problems

- **An efficient long-text semantic retrieval approach via utilizing presentation learning on short-text** - Wang, 2024 | Complex & Intelligent Systems [Paper](https://doi.org/10.1007/s40747-023-01192-3)
- **The power of selecting key blocks with local pre-ranking for long document information retrieval** - Li, 2023 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3568394)
- **Parade: Passage representation aggregation for document reranking** - Li, 2024 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3600088) [Code](https://github.com/canjiali/PARADE)
- **Longtriever: a pre-trained long text encoder for dense document retrieval** - Yang, 2023 | Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2023.emnlp-main.223)
- **A novel dense retrieval framework for long document retrieval** - Wang, 2023 | Frontiers of Computer Science [Paper](https://doi.org/10.1007/s11704-022-2041-5)
- **Long document re-ranking with modular re-ranker** - Gao, 2022 | Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3477495.3531860)
- **Intra-document cascading: Learning to select passages for neural document ranking** - Hofstatter, 2021 | Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3404835.3462889)
- **Deeper text understanding for IR with contextual neural language modeling** - Dai, 2019 | Proceedings of the 42nd international ACM SIGIR conference on research and development in information retrieval [Paper](https://doi.org/10.1145/3331184.3331303)

#### Divide-and-Conquer Paradigm for Long Documents (PLM & LLM Era)

##### Pooling-based Heuristics: BERT-MaxP and SumP

- **Deeper text understanding for IR with contextual neural language modeling** - Dai, 2019 | Proceedings of the 42nd international ACM SIGIR conference on research and development in information retrieval [Paper](https://doi.org/10.1145/3331184.3331303)

##### Hierarchical Aggregation: PARADE, DRSCM, LTR-BERT, and MORES+

- **An efficient long-text semantic retrieval approach via utilizing presentation learning on short-text** - Wang, 2024 | Complex & Intelligent Systems [Paper](https://doi.org/10.1007/s40747-023-01192-3)
- **Parade: Passage representation aggregation for document reranking** - Li, 2024 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3600088) [Code](https://github.com/canjiali/PARADE)
- **A novel dense retrieval framework for long document retrieval** - Wang, 2023 | Frontiers of Computer Science [Paper](https://doi.org/10.1007/s11704-022-2041-5)
- **Long document re-ranking with modular re-ranker** - Gao, 2022 | Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3477495.3531860)

##### Key Passage/Block Selection: IDCM, KeyB, KeyB2, and DCS

- **Efficient Long-Document Reranking via Block-Level Embeddings and Top-k Interaction Refinement** - Li, 2025 | arXiv preprint arXiv:2501.17039 [Paper](https://arxiv.org/abs/2501.17039)
- **Dynamic Chunking and Selection for Reading Comprehension of Ultra-Long Context in Large Language Models** - Sheng, 2025 | Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) [Paper](https://doi.org/10.18653/v1/2025.acl-long.1538)
- **EviRerank: Adaptive Evidence Construction for Long-Document LLM Reranking** - Li, 2024 | arXiv preprint arXiv:2411.06254 [Paper](https://arxiv.org/abs/2411.06254)
- **The power of selecting key blocks with local pre-ranking for long document information retrieval** - Li, 2023 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3568394)
- **Intra-document cascading: Learning to select passages for neural document ranking** - Hofstatter, 2021 | Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3404835.3462889)

##### Hybrid Cascades and Late Interaction: ICLI, Match-Ignition, and Longtriever

- **Longtriever: a pre-trained long text encoder for dense document retrieval** - Yang, 2023 | Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2023.emnlp-main.223)
- **Bert-based dense intra-ranking and contextualized late interaction via multi-task learning for long document retrieval** - Li, 2022 | Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3477495.3531856)
- **Match-ignition: Plugging pagerank into transformer for long-form text matching** - Pang, 2021 | Proceedings of the 30th ACM international conference on information & knowledge management [Paper](https://doi.org/10.1145/3459637.3482450)
- **ColBERT: Efficient and Effective Passage Search via Contextualized Late Interaction over BERT** - Khattab, 2020 | Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3397271.3401075) [Code](https://github.com/stanford-futuredata/ColBERT)

#### Indexing-Structure-Oriented Paradigm

- **Raptor: Recursive abstractive processing for tree-organized retrieval** - Sarthi, 2024 | International Conference on Learning Representations [Paper](https://openreview.net/forum?id=GN921JHCRw) [Code](https://github.com/parthsarthi03/raptor)
- **MC-indexing: Effective Long Document Retrieval via Multi-view Content-aware Indexing** - Dong, 2024 | Findings of the Association for Computational Linguistics: EMNLP 2024 [Paper](https://doi.org/10.18653/v1/2024.findings-emnlp.150)
- **Extracting variable-depth logical document hierarchy from long documents: method, evaluation, and application** - Cao, 2022 | Journal of Computer Science and Technology [Paper](https://doi.org/10.1007/s11390-021-1076-7)
- **QuALITY: Question answering with long input texts, yes!** - Pang, 2022 | Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies [Paper](https://doi.org/10.18653/v1/2022.naacl-main.391)

#### Context and Query Scaling: Query Complexity and Coverage-Oriented Retrieval

##### Long-Query and Query-by-Document Retrieval

- **Retrieval for extremely long queries and documents with RPRS: a highly efficient and effective transformer-based re-ranker** - Askari, 2024 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3631938)
- **A legal case retrieval dataset for Chinese law system** - Ma, 2021 | Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval, Online [Paper](https://doi.org/10.1145/3404835.3463250)
- **BERT-PLI: Modeling paragraph-level interactions for legal case retrieval** - Shao, 2020 | IJCAI [Paper](https://doi.org/10.24963/ijcai.2020/484)

##### Aspect / Facet Decomposition

- **Scientific Paper Retrieval with LLM-Guided Semantic-Based Ranking** - Zhang, 2025 | Findings of the Association for Computational Linguistics: EMNLP 2025 [Paper](https://doi.org/10.18653/v1/2025.findings-emnlp.108)
- **Chain of Retrieval: Multi-Aspect Iterative Search Expansion and Post-Order Search Aggregation for Full Paper Retrieval** - Park, 2025 [Paper](https://arxiv.org/abs/2507.10057) [Code](https://github.com/psw0021/Chain-of-Retrieval-Official)
- **Sailer: structure-aware pre-trained language model for legal case retrieval** - Li, 2023 | Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3539618.3591761)

##### Comparison and Design Trade-offs

- **Scientific Paper Retrieval with LLM-Guided Semantic-Based Ranking** - Zhang, 2025 | Findings of the Association for Computational Linguistics: EMNLP 2025 [Paper](https://doi.org/10.18653/v1/2025.findings-emnlp.108)
- **Chain of Retrieval: Multi-Aspect Iterative Search Expansion and Post-Order Search Aggregation for Full Paper Retrieval** - Park, 2025 [Paper](https://arxiv.org/abs/2507.10057) [Code](https://github.com/psw0021/Chain-of-Retrieval-Official)
- **Retrieval for extremely long queries and documents with RPRS: a highly efficient and effective transformer-based re-ranker** - Askari, 2024 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3631938)
- **Sailer: structure-aware pre-trained language model for legal case retrieval** - Li, 2023 | Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3539618.3591761)
- **BERT-PLI: Modeling paragraph-level interactions for legal case retrieval** - Shao, 2020 | IJCAI [Paper](https://doi.org/10.24963/ijcai.2020/484)

#### Cross-Cutting Efficiency Strategies for LDR

##### Efficiency Challenges and Mitigation

- **Efficient re-ranking with cross-encoders via early exit** - Busolin, 2025 | Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3726302.3729962)
- **Ranked list truncation for large language model-based re-ranking** - Meng, 2024 | Proceedings of the 47th international ACM SIGIR conference on research and development in information retrieval [Paper](https://doi.org/10.1145/3626772.3657864)
- **Longlora: Efficient fine-tuning of long-context large language models** - Chen, 2024 | International Conference on Learning Representations [Paper](https://openreview.net/forum?id=6PmJoRfdaK) [Code](https://github.com/dvlab-research/LongLoRA)
- **DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads** - Xiao, 2025 | International Conference on Learning Representations [Paper](https://openreview.net/forum?id=cFu7ze7xUm) [Code](https://github.com/mit-han-lab/duo-attention)

#### A Practical Decision Matrix Across Paradigms

- **Retrieval for extremely long queries and documents with RPRS: a highly efficient and effective transformer-based re-ranker** - Askari, 2024 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3631938)
- **Raptor: Recursive abstractive processing for tree-organized retrieval** - Sarthi, 2024 | International Conference on Learning Representations [Paper](https://openreview.net/forum?id=GN921JHCRw) [Code](https://github.com/parthsarthi03/raptor)
- **MC-indexing: Effective Long Document Retrieval via Multi-view Content-aware Indexing** - Dong, 2024 | Findings of the Association for Computational Linguistics: EMNLP 2024 [Paper](https://doi.org/10.18653/v1/2024.findings-emnlp.150)
- **EviRerank: Adaptive Evidence Construction for Long-Document LLM Reranking** - Li, 2024 | arXiv preprint arXiv:2411.06254 [Paper](https://arxiv.org/abs/2411.06254)
- **Fine-tuning llama for multi-stage text retrieval** - Ma, 2024 | Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3626772.3657951)
- **Extracting variable-depth logical document hierarchy from long documents: method, evaluation, and application** - Cao, 2022 | Journal of Computer Science and Technology [Paper](https://doi.org/10.1007/s11390-021-1076-7)
- **Clinical-longformer and clinical-bigbird: Transformers for long clinical sequences** - Li, 2022 | arXiv preprint arXiv:2201.11838 [Paper](https://arxiv.org/abs/2201.11838)
- **Lawformer: A pre-trained language model for chinese legal long documents** - Xiao, 2021 | AI Open [Paper](https://doi.org/10.1016/j.aiopen.2021.06.003)
- **Intra-document cascading: Learning to select passages for neural document ranking** - Hofstatter, 2021 | Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval [Paper](https://doi.org/10.1145/3404835.3462889)

### LLM-era Emerging Directions for Long-Document Retrieval

#### Generative Retrieval for Long Documents

- **Generative retrieval with few-shot indexing** - Askari, 2026 | European Conference on Information Retrieval [Paper](https://doi.org/10.1007/978-3-032-21300-6_52)
- **Learning to tokenize for generative retrieval** - Sun, 2023 | Advances in Neural Information Processing Systems [Paper](https://doi.org/10.52202/075280-2010)

#### Agentic and Deep-Research Long-Document Retrieval

- **SPAR: Scholar Paper Retrieval with LLM-based Agents for Enhanced Academic Search** - Shi, 2025 [Paper](https://arxiv.org/abs/2507.15245) [Code](https://github.com/xiaofengShi/SPAR)
- **PaSa: An LLM Agent for Comprehensive Academic Paper Search** - He, 2025 | Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) [Paper](https://doi.org/10.18653/v1/2025.acl-long.572) [Code](https://github.com/bytedance/pasa)
- **Browsecomp-plus: A more fair and transparent evaluation benchmark of deep-research agent** - Chen, 2025 | arXiv preprint arXiv:2508.06600 [Paper](https://arxiv.org/abs/2508.06600)

### Datasets, Benchmarks, and Evaluation

#### Datasets

- **Multi-CPR: A Multi Domain Chinese Dataset for Passage Retrieval** - Long, 2022 | arXiv preprint arXiv:2203.03367 [Paper](https://arxiv.org/abs/2203.03367) [Code](https://github.com/Alibaba-NLP/Multi-CPR)
- **BGE M3-Embedding: Multi-Lingual, Multi-Functionality, Multi-Granularity Text Embeddings Through Self-Knowledge Distillation** - Chen, 2024 | Findings of the Association for Computational Linguistics ACL 2024 [Paper](https://doi.org/10.18653/v1/2024.findings-acl.137) [Code](https://github.com/FlagOpen/FlagEmbedding)
- **MIMIC-IV** - Johnson, 2020 | PhysioNet [Paper](https://doi.org/10.13026/s6n6-xd98)

#### Evaluation protocols and metrics

##### Long-Context-Specific Evaluation Paradigms

- **RULER: What's the real context size of your long-context language models?** - Hsieh, 2024 | Conference on Language Modeling [Paper](https://openreview.net/forum?id=kIoBbc76Sy) [Code](https://github.com/NVIDIA/RULER)
- **Ragas: Automated evaluation of retrieval augmented generation** - Es, 2024 | Proceedings of the 18th conference of the european chapter of the association for computational linguistics: system demonstrations [Paper](https://doi.org/10.18653/v1/2024.eacl-demo.16) [Code](https://github.com/explodinggradients/ragas)
- **MMLongBench-Doc: Benchmarking Long-context Document Understanding with Visualizations** - Ma, 2024 | Advances in Neural Information Processing Systems 37 [Paper](https://doi.org/10.52202/079017-3041)
- **LongEmbed: Extending Embedding Models for Long Context Retrieval** - Zhu, 2024 | Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2024.emnlp-main.47) [Code](https://github.com/dwzhu-pku/LongEmbed)
- **Lost in the Middle: How Language Models Use Long Contexts** - Liu, 2024 | Transactions of the Association for Computational Linguistics [Paper](https://doi.org/10.1162/tacl_a_00638)
- **Longbench: A bilingual, multitask benchmark for long context understanding** - Bai, 2024 | Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) [Paper](https://doi.org/10.18653/v1/2024.acl-long.172)
- **L-Eval: Instituting Standardized Evaluation for Long Context Language Models** - An, 2024 | Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) [Paper](https://doi.org/10.18653/v1/2024.acl-long.776)
- **Enabling large language models to generate text with citations** - Gao, 2023 | Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2023.emnlp-main.398) [Code](https://github.com/princeton-nlp/ALCE)

##### LLM-as-a-Judge, Reflection, and Long-Context Diagnostics

- **Query performance prediction using relevance judgments generated by large language models** - Meng, 2025 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3736402)
- **Principles and Guidelines for the Use of LLM Judges** - Dietz, 2025 | Proceedings of the 2025 International ACM SIGIR Conference on Theory of Information Retrieval (ICTIR '25) [Paper](https://doi.org/10.1145/3731120.3744588)
- **Browsecomp-plus: A more fair and transparent evaluation benchmark of deep-research agent** - Chen, 2025 | arXiv preprint arXiv:2508.06600 [Paper](https://arxiv.org/abs/2508.06600)
- **Perspectives on large language models for relevance judgment** - Faggioli, 2023 | Proceedings of the 2023 ACM SIGIR international conference on theory of information retrieval [Paper](https://doi.org/10.1145/3578337.3605136)

### Applications and Use Cases

#### Legal Retrieval

- **Lawgpt: A chinese legal knowledge-enhanced large language model** - Zhou, 2024 | arXiv preprint arXiv:2406.04614 [Paper](https://arxiv.org/abs/2406.04614)
- **Disc-lawllm: Fine-tuning large language models for intelligent legal services** - Yue, 2023 | arXiv preprint arXiv:2309.11325 [Paper](https://arxiv.org/abs/2309.11325)
- **Chatlaw: Open-source legal large language model with integrated external knowledge bases** - Cui, 2023 | CoRR [Paper](https://arxiv.org/abs/2306.16092)
- **Legal-bigbird: An adapted long-range transformer for legal documents** - Dassi, 2021 | NeurIPS 2021 Black in AI Workshop [Paper](https://neurips.cc/virtual/2021/48411)
- **Lawformer: A pre-trained language model for chinese legal long documents** - Xiao, 2021 | AI Open [Paper](https://doi.org/10.1016/j.aiopen.2021.06.003)
- **Longformer: The Long-Document Transformer** - Beltagy, 2020 | arXiv preprint arXiv:2004.05150 [Paper](https://arxiv.org/abs/2004.05150) [Code](https://github.com/allenai/longformer)
- **LEGAL-BERT: The muppets straight out of law school** - Chalkidis, 2020 | Findings of the Association for Computational Linguistics: EMNLP 2020 [Paper](https://doi.org/10.18653/v1/2020.findings-emnlp.261)

#### Scholarly Long-Document Retrieval

- **SPAR: Scholar Paper Retrieval with LLM-based Agents for Enhanced Academic Search** - Shi, 2025 [Paper](https://arxiv.org/abs/2507.15245) [Code](https://github.com/xiaofengShi/SPAR)
- **Scientific Paper Retrieval with LLM-Guided Semantic-Based Ranking** - Zhang, 2025 | Findings of the Association for Computational Linguistics: EMNLP 2025 [Paper](https://doi.org/10.18653/v1/2025.findings-emnlp.108)
- **Chain of Retrieval: Multi-Aspect Iterative Search Expansion and Post-Order Search Aggregation for Full Paper Retrieval** - Park, 2025 [Paper](https://arxiv.org/abs/2507.10057) [Code](https://github.com/psw0021/Chain-of-Retrieval-Official)
- **PaSa: An LLM Agent for Comprehensive Academic Paper Search** - He, 2025 | Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) [Paper](https://doi.org/10.18653/v1/2025.acl-long.572) [Code](https://github.com/bytedance/pasa)
- **LLM-Based Compact Reranking with Document Features for Scientific Retrieval** - Tian, 2025 [Paper](https://arxiv.org/abs/2505.13757)
- **DocReLM: Mastering Document Retrieval with Language Model** - Wei, 2024 [Paper](https://arxiv.org/abs/2405.11461)
- **Advancing Academic Knowledge Retrieval via LLM-enhanced Representation Similarity Fusion** - Dai, 2024 [Paper](https://arxiv.org/abs/2410.10455)
- **PaperQA: Retrieval-Augmented Generative Agent for Scientific Research** - Lála, 2023 [Paper](https://arxiv.org/abs/2312.07559) [Code](https://github.com/Future-House/paper-qa)
- **Neighborhood Contrastive Learning for Scientific Document Representations with Citation Embeddings** - Ostendorff, 2022 | Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2022.emnlp-main.802) [Code](https://github.com/malteos/scincl)
- **SPECTER: Document-level Representation Learning using Citation-informed Transformers** - Cohan, 2020 | Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics [Paper](https://doi.org/10.18653/v1/2020.acl-main.207) [Code](https://github.com/allenai/specter)
- **SciBERT: A Pretrained Language Model for Scientific Text** - Beltagy, 2019 | Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP) [Paper](https://doi.org/10.18653/v1/d19-1371)

#### Biomedical Literature Search

- **BioClinical ModernBERT: A State-of-the-Art Long-Context Encoder for Biomedical and Clinical NLP** - Sounack, 2025 | arXiv preprint arXiv:2506.10896 [Paper](https://arxiv.org/abs/2506.10896)
- **Clinical-longformer and clinical-bigbird: Transformers for long clinical sequences** - Li, 2022 | arXiv preprint arXiv:2201.11838 [Paper](https://arxiv.org/abs/2201.11838)
- **Domain-specific language model pretraining for biomedical natural language processing** - Gu, 2021 | ACM Transactions on Computing for Healthcare (HEALTH) [Paper](https://doi.org/10.1145/3458754)

#### Cross-Lingual Long-Text Retrieval

- **CROSS: Analyzing the Trade-offs in Long-Context Cross-lingual Retrieval** - Nezhad, 2025 | ICLR 2025 Workshop on Foundation Models in the Wild [Paper](https://openreview.net/forum?id=sOXznQZgnM)
- **mGTE: Generalized Long-Context Text Representation and Reranking Models for Multilingual Text Retrieval** - Zhang, 2024 | Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing: Industry Track [Paper](https://doi.org/10.18653/v1/2024.emnlp-industry.103)
- **McCrolin: Multi-consistency Cross-lingual Training for Retrieval Question Answering** - Limkonchotiwat, 2024 | Findings of the Association for Computational Linguistics: EMNLP 2024 [Paper](https://doi.org/10.18653/v1/2024.findings-emnlp.157)
- **XOR QA: Cross-lingual Open-Retrieval Question Answering** - Asai, 2021 | Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies [Paper](https://doi.org/10.18653/v1/2021.naacl-main.46)
- **Language-agnostic BERT Sentence Embedding** - Feng, 2022 | Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) [Paper](https://doi.org/10.18653/v1/2022.acl-long.62)
- **BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding** - Devlin, 2019 | Proceedings of NAACL-HLT 2019 [Paper](https://doi.org/10.18653/v1/N19-1423)

#### Other Applications

##### Web and News Retrieval

- **A Novel Multi-Document Retrieval Benchmark: Journalist Source-Selection in Newswriting** - Spangher, 2025 | Proceedings of the 4th International Workshop on Knowledge-Augmented Methods for Natural Language Processing [Paper](https://doi.org/10.18653/v1/2025.knowledgenlp-1.18)

##### Multimedia and Interactive Document Processing

- **Mmdocir: Benchmarking multi-modal retrieval for long documents** - Dong, 2025 | Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2025.emnlp-main.1576)
- **M3docrag: Multi-modal retrieval is what you need for multi-page multi-document understanding** - Cho, 2024 | arXiv preprint arXiv:2411.04952 [Paper](https://arxiv.org/abs/2411.04952) [Code](https://github.com/bloomberg/m3docrag)

##### Enterprise Knowledge Management

- **eSapiens: A Real-World NLP Framework for Multimodal Document Understanding and Enterprise Knowledge Processing** - Shi, 2025 | arXiv preprint arXiv:2506.16768 [Paper](https://arxiv.org/abs/2506.16768)

### Current Challenges and Future Directions

#### Future Directions

- **Query performance prediction using relevance judgments generated by large language models** - Meng, 2025 | ACM Transactions on Information Systems [Paper](https://doi.org/10.1145/3736402)
- **Principles and Guidelines for the Use of LLM Judges** - Dietz, 2025 | Proceedings of the 2025 International ACM SIGIR Conference on Theory of Information Retrieval (ICTIR '25) [Paper](https://doi.org/10.1145/3731120.3744588)
- **Roformer: Enhanced transformer with rotary position embedding** - Su, 2024 | Neurocomputing [Paper](https://doi.org/10.1016/j.neucom.2023.127063)
- **LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression** - Jiang, 2024 | Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) [Paper](https://doi.org/10.18653/v1/2024.acl-long.91) [Code](https://github.com/microsoft/LLMLingua)
- **Perspectives on large language models for relevance judgment** - Faggioli, 2023 | Proceedings of the 2023 ACM SIGIR international conference on theory of information retrieval [Paper](https://doi.org/10.1145/3578337.3605136)
- **Enhancing retrieval-augmented large language models with iterative retrieval-generation synergy** - Shao, 2023 | Findings of the Association for Computational Linguistics: EMNLP 2023 [Paper](https://doi.org/10.18653/v1/2023.findings-emnlp.620)
- **VideoWebArena: Evaluating Long Context Multimodal Agents with Video Understanding Web Tasks** - Jang | NeurIPS 2024 Workshop on Open-World Agents [Paper](https://arxiv.org/abs/2410.19100)
- **Memorizing Transformers** - Wu | International Conference on Learning Representations [Paper](https://openreview.net/forum?id=TrjbxzRcnf-)
- **Compressing Context to Enhance Inference Efficiency of Large Language Models** - LI | The 2023 Conference on Empirical Methods in Natural Language Processing [Paper](https://doi.org/10.18653/v1/2023.emnlp-main.391)

## Contributing

- Add missing long-document retrieval papers, paper links, or code links by PR.
- Keep entries grouped by survey section and sorted by year.
