# ReasoningPaperList
Reasoning tasks have aroused wide concerns in the research community. Reasoning refers to a wide range of things, which is an abstract concept in reality. In this repository, we mainly focus on the reasoning models which cover neural-symbolic, complex reasoning, logical rules or multi-hop. 

Categoried by input modalities, there are single modality like (1) Text, (2) Knowledge Graph (KG), (3) Images, and also multi-modality tasks like (4) KG-Text, (5) MKG, (6) Image-Text.

Categoried by reasoning forms, there include the followings: (1) Deductive Reasoning, (2) Inductive Reasoning, (3) Abductive Reasoning, and also some other branches like (i) analogical reasoning, (ii) causal reasoning, (iii) probabilistic reasoning. 

Categoried by downstream tasks, there are: (1) Arithmetic Reasoning, (2) Commonsense Reasoning, (3) Symbolic Reasoning, (4) Logical Reasoning, (5) Others.

Most of the current survey papers in the large area of reasoning only focus on single modality reasoning, or focus on one type of reasoning (e.g., [1] below only addresses on the `informal deductive reasoning'). Also it lacks the exploration on how the LLMs work among different reasoning forms and what are the limitations of LLMs on different reasoning forms. 

If we miss some of works or make some mistakes, please kindly point out. 

In this repository, we use tags ``De``, ``In``, ``Ab`` to represent Deductive Reasoning, Inductive Reasoning and Abductive Reasoning respectively. 

## Survey
- [arxiv] Towards Reasoning in Large Language Models: A Survey [[pdf]](https://arxiv.org/abs/2212.10403) ``De``
- [arxiv] Knowledge Graph Reasoning with Logics and Embeddings: Survey and Perspective [[pdf]](https://arxiv.org/pdf/2202.07412.pdf)


## Text Reasoning
- [NAACL 2021] DAGN: Discourse-Aware Graph Network for Logical Reasoning [[pdf]](https://arxiv.org/abs/2103.14349) ``Mix``
- [NIPS 2021] Open Rule Induction [[pdf]](https://arxiv.org/abs/2110.13577) ``In``
- [arxiv] Fact-driven Logical Reasoning [[pdf]](https://arxiv.org/abs/2105.10334) ``Mix``
- [ACL 2022 Findings] Logic-Driven Context Extension and Data Augmentation for Logical Reasoning of Text [[pdf]](https://arxiv.org/abs/2105.03659) ``Mix``
- [ACL 2022 Findings] MERIt: Meta-Path Guided Contrastive Learning for Logical Reasoning [[pdf]](https://aclanthology.org/2022.findings-acl.276.pdf) ``Mix``
- [ACL 2022 Findings] AbductionRules: Training Transformers to Explain Unexpected Inputs [[pdf]](https://aclanthology.org/2022.findings-acl.19) ``De``
- [ACL 2022] AdaLoGN: Adaptive Logic Graph Network for Reasoning-Based Machine Reading Comprehension [[pdf]](https://arxiv.org/abs/2203.08992) ``Mix``
- [SIGIR 2022] Logiformer: A Two-Branch Graph Transformer Network for Interpretable Logical Reasoning [[pdf]](https://dl.acm.org/doi/abs/10.1145/3477495.3532016) ``Mix``
- [arxiv] Mind Reasoning Manners: Enhancing Type Perception for Generalized Zero-shot Logical Reasoning over Text [[pdf]](https://arxiv.org/abs/2301.02983) ``Mix``

## KG Reasoning
- [ICDE 2023] Relational Message Passing for Fully Inductive Knowledge Graph Completion [[pdf]](https://arxiv.org/pdf/2210.03994.pdf)
- [SIGIR 2022] Incorporating Context Graph with Logical Reasoning for Inductive Relation Prediction [[pdf]](https://dl.acm.org/doi/abs/10.1145/3477495.3531996)
- [KDD 2022] Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries [[pdf]](https://arxiv.org/abs/2208.07638)
- [NIPS 2022] Neural-Symbolic Entangled Framework for Complex Query Answering [[pdf]](https://arxiv.org/pdf/2209.08779.pdf)

## Image Reasoning


## KG-Text Reasoning
- [EMNLP 2019] KagNet：Knowledge-Aware Graph Networks for Commonsense Reasoning [[pdf]](https://arxiv.org/abs/1909.02151) ``De``
- [EMNLP 2020] Scalable Multi-Hop Relational Reasoning for Knowledge-Aware Question Answering [[pdf]](https://aclanthology.org/2020.emnlp-main.99/) ``De``
- [NAACL 2021] QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering [[pdf]](https://arxiv.org/abs/2104.06378) ``De``
- [NAACL 2022] JointLK: Joint Reasoning with Language Models and Knowledge Graphs for Commonsense Question Answering [[pdf]](https://aclanthology.org/2022.naacl-main.372/) ``De``
- [ICLR 2022] GreaseLM: Graph Reasoning Enhanced Language Models For Question Answering [[pdf]](https://arxiv.org/abs/2201.08860) ``De``
- [ICLR 2022] GNN Is A Counter？Revisiting GNN For Question Answering [[pdf]](https://arxiv.org/abs/2110.03192) ``De``
- [WWW 2023] Structure Pretraining and Prompt Tuning for Knowledge Graph Transfer [[pdf]](https://arxiv.org/abs/2303.03922) ``De``


## Multimodal KG Reasoning
- [ICLR 2023] Multimodal Analogical Reasoning over Knowledge Graphs [[pdf]](https://arxiv.org/abs/2210.00312)


## Image-Text Reasoning


