<div align="center">


<img src="./figures/Prompt-EgoAlpha_white.svg" width="600px">

 <div align="center">

 [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=30&duration=2500&pause=500&color=8D589A&background=FCFCFF00&center=true&vCenter=true&width=500&lines=Hello!+Human%2C+Are+You+Ready%3F;Welcome+to+my+world!)]()
 
 </div>

**An Open-Source Engineering Guide for Prompt-in-context-learning from EgoAlpha Lab.**

<img width="200%" src="./figures/hr.gif" />

<!-- <h3 align="center">

    <p>Resources for prompt learning and engineering; Mastery of LLMs like ChatGPT, GPT3, FlanT5, etc.</p>

</h3> -->

<!-- <h4 align="center">
    <p>
        <a href="./README.md">English</a> |
        <a href="./chatgptprompt_zh.md">简体中文</a>
    <p>
</h4> -->

<p align="center">

  <a href="#📜-papers">📝 Papers</a> |
  <a href="./Playground.md">⚡️  Playground</a> |
  <a href="./PromptEngineering.md">🛠 Prompt Engineering</a> |
  <a href="./chatgptprompt.md">🌍 ChatGPT Prompt</a> ｜
  <a href="./langchain_guide/LangChainTutorial.ipynb">⛳ LLMs Usage Guide</a> 

</p>

</div>

<div align="center">

<!-- ![Build](https://img.shields.io/appveyor/build/gruntjs/grunt) -->

![version](https://img.shields.io/badge/version-v3.0.0-green)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

<!-- ![license](https://img.shields.io/bower/l/bootstrap?style=plastic) -->

</div>

> **⭐️ Shining ⭐️:** This is fresh, daily-updated resources for in-context learning and prompt engineering. As Artificial General Intelligence (AGI) is approaching, let’s take action and become a super learner so as to position ourselves at the forefront of this exciting era and strive for personal and professional greatness.

The resources include:

*🎉[Papers](#📜-papers)🎉*:  The latest papers about *In-Context Learning*, *Prompt Engineering*, *Agent*, and *Foundation Models*. 

*🎉[Playground](./Playground.md)🎉*:  Large language models（LLMs）that enable prompt experimentation. 

*🎉[Prompt Engineering](./PromptEngineering.md)🎉*: Prompt techniques for leveraging large language models. 

*🎉[ChatGPT Prompt](./chatgptprompt.md)🎉*: Prompt examples that can be applied in our work and daily lives. 

*🎉[LLMs Usage Guide](./chatgptprompt.md)🎉*: The method for quickly getting started with large language models by using LangChain.

In the future, there will likely be two types of people on Earth (perhaps even on Mars, but that's a question for Musk): 
- Those who enhance their abilities through the use of AIGC; 
- Those whose jobs are replaced by AI automation.

```

💎EgoAlpha: Hello! human👤, are you ready?

```  

<img width="200%" src="./figures/hr.gif" />

# Table of Contents
- [📢 News](#-news)
- [📜 Papers](#-papers)
  - [Survey](#survey)
  - [Prompt Engineering](#prompt-engineering)
    - [Prompt Design](#prompt-design)
    - [Chain of Thought](#chain-of-thought)
    - [In-context Learning](#in-context-learning)
    - [Retrieval Augmented Generation](#retrieval-augmented-generation)
    - [Evaluation \& Reliability](#evaluation--reliability)
  - [Agent](#agent)
  - [Multimodal Prompt](#multimodal-prompt)
  - [Prompt Application](#prompt-application)
  - [Foundation Models](#foundation-models)
- [👨‍💻 LLM Usage](#-llm-usage)
- [✉️ Contact](#️-contact)
- [🙏 Acknowledgements](#-acknowledgements)

<img width="200%" src="./figures/hr.gif" />

# 📢 News
<!-- 🔥🔥🔥 -->
☄️ **EgoAlpha releases the TrustGPT focuses on reasoning. Trust the GPT with the strongest reasoning abilities for authentic and reliable answers. You can click [here](https://trustgpt.co) or visit the [Playgrounds](./Playground.md) directly to experience it。**

- **[2024.6.28]**
  - Paper: [Dataset Size Recovery from LoRA Weights](https://arxiv.org/abs/2406.19395)

- **[2024.6.27]**
  - Paper: [OMG-LLaVA: Bridging Image-level, Object-level, Pixel-level Reasoning and Understanding](https://arxiv.org/abs/2406.19389)

- **[2024.6.26]**
  - Paper: [Fundamental Problems With Model Editing: How Should Rational Belief Revision Work in LLMs?](https://arxiv.org/abs/2406.19354)
  - Paper: [PrExMe! Large Scale Prompt Exploration of Open Source LLMs for Machine Translation and Summarization Evaluation](https://arxiv.org/list/cs/recent?skip=422&show=446)

- **[2024.6.25]**
  - Paper: [Symbolic Learning Enables Self-Evolving Agents](https://arxiv.org/abs/2406.18532)

- **[2024.6.24]**
  - Paper: [The Remarkable Robustness of LLMs: Stages of Inference?](https://arxiv.org/abs/2406.19384)

- **[2024.6.23]**
  - Paper: [Efficient World Models with Context-Aware Tokenization](https://arxiv.org/abs/2406.19320)

- **[2024.6.22]**
  - Paper: [Revisiting Referring Expression Comprehension Evaluation in the Era of Large Multimodal Models](https://arxiv.org/abs/2406.16866)

- **[2024.6.21]**
  - Paper: [Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs](https://arxiv.org/abs/2406.16860)

- **[2024.6.20]**
  - Paper: [LaMDA: Large Model Fine-Tuning via Spectrally Decomposed Low-Dimensional Adaptation](https://arxiv.org/abs/2406.12832)
  - Paper: [From RAGs to rich parameters: Probing how language models utilize external knowledge over parametric information for factual queries](https://arxiv.org/abs/2406.12824)

- **[2024.6.19]**
  - Paper: [Adversarial Attacks on Multimodal Agents](https://arxiv.org/abs/2406.12814)
  - Paper: [AITTI: Learning Adaptive Inclusive Token for Text-to-Image Generation](https://arxiv.org/abs/2406.12805)

- **[2024.6.18]**
  - Paper: [LLaNA: Large Language and NeRF Assistant](https://arxiv.org/abs/2406.11840)

- **[2024.6.17]**
  - Paper: [Unveiling Encoder-Free Vision-Language Models](https://arxiv.org/abs/2406.11832)
  - Paper: [VideoLLM-online: Online Video Large Language Model for Streaming Video](https://arxiv.org/abs/2406.11816)

- **[2024.6.16]**
  - Paper: [RepLiQA: A Question-Answering Dataset for Benchmarking LLMs on Unseen Reference Content](https://arxiv.org/abs/2406.11811)

- **[2024.6.15]**
  - Paper: [VEGA: Learning Interleaved Image-Text Comprehension in Vision-Language Large Models](https://arxiv.org/abs/2406.10228)
  - Paper: [EFM3D: A Benchmark for Measuring Progress Towards 3D Egocentric Foundation Models](https://arxiv.org/abs/2406.10224)

- **[2024.6.14]**
  - Paper: [Regularizing Hidden States Enables Learning Generalizable Reward Model for LLMs](https://arxiv.org/abs/2406.10216)

- **[2024.6.13]**
  - Paper: [Beyond LLaVA-HD: Diving into High-Resolution Large Multimodal Models](https://arxiv.org/abs/2406.08487)
  - Paper: [Enhancing End-to-End Autonomous Driving with Latent World Model](https://arxiv.org/abs/2406.08481)

- **[2024.6.12]**
  - Paper: [Magpie: Alignment Data Synthesis from Scratch by Prompting Aligned LLMs with Nothing](https://arxiv.org/abs/2406.08464)
  - Paper: [The Impact of Initialization on LoRA Finetuning Dynamics](https://arxiv.org/abs/2406.08447)

- **[2024.6.11]**
  - Paper: [Autoregressive Model Beats Diffusion: Llama for Scalable Image Generation](https://arxiv.org/abs/2406.06525)
  - Paper: [Can Language Models Serve as Text-Based World Simulators?](https://arxiv.org/abs/2406.06485)【ACL2024】

- **[2024.6.10]**
  - Survey Paper: [Towards a Personal Health Large Language Model](https://arxiv.org/abs/2406.06474)
  - Technical Report: [Husky: A Unified, Open-Source Language Agent for Multi-Step Reasoning](https://arxiv.org/abs/2406.06469)

- **[2024.6.9]**
  - Paper: [3D-GRAND: Towards Better Grounding and Less Hallucination for 3D-LLMs](https://arxiv.org/abs/2406.05132)
  - Technical Report: [Towards Semantic Equivalence of Tokenization in Multimodal LLM](https://arxiv.org/abs/2406.05127)

- **[2024.6.8]**
  - Paper: [An Empirical Study on Parameter-Efficient Fine-Tuning for MultiModal Large Language Models](https://arxiv.org/abs/2406.05130)

- **[2024.6.7]**
  - Paper: [Language models emulate certain cognitive profiles: An investigation of how predictability measures interact with individual differences](https://arxiv.org/abs/2406.04988)【ACL2024】

- **[2024.6.6]**
  - Paper: [Verbalized Machine Learning: Revisiting Machine Learning with Language Models](https://arxiv.org/abs/2406.04344)
  - Paper: [PaCE: Parsimonious Concept Engineering for Large Language Models](https://arxiv.org/abs/2406.04331)

- **[2024.6.5]**
  - Paper: [Seq1F1B: Efficient Sequence-Level Pipeline Parallelism for Large Language Model Training](https://arxiv.org/abs/2406.03488)

- **[2024.6.4]**
  - Paper: [Learning to grok: Emergence of in-context learning and skill composition in modular arithmetic tasks](https://arxiv.org/abs/2406.02550)
  - Paper: [Leveraging Visual Tokens for Extended Text Contexts in Multi-Modal Learning](https://arxiv.org/abs/2406.02547)

- **[2024.6.3]**
  - Paper: [Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis](https://arxiv.org/abs/2405.21075)
  - Paper: [Graph External Attention Enhanced Transformer](https://arxiv.org/abs/2405.21061)【ICML2024】

- **[2024.6.2]**
  - Paper: [Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality](https://arxiv.org/abs/2405.21060)【ICML2024】
  - Paper: [LACIE: Listener-Aware Finetuning for Confidence Calibration in Large Language Models](https://arxiv.org/abs/2405.21028)

- **[2024.6.1]**
  - Paper: [StrucTexTv3: An Efficient Vision-Language Model for Text-rich Image Perception, Comprehension, and Beyond](https://arxiv.org/abs/2405.21013)
  - Paper: [DeCo: Decoupling Token Compression from Semantic Abstraction in Multimodal Large Language Models](https://arxiv.org/abs/2405.20985)

- **[2024.5.31]**
  - Paper: [Enhancing Noise Robustness of Retrieval-Augmented Language Models with Adaptive Adversarial Training](https://arxiv.org/abs/2405.20978)
  - Paper: [OR-Bench: An Over-Refusal Benchmark for Large Language Models](https://arxiv.org/abs/2405.20947)

- **[2024.5.30]**
  - Paper: [Visualizing the loss landscape of Self-supervised Vision Transformer](https://arxiv.org/abs/2405.18042)【NIPS2024 workshop】
  - Paper: [TimeChara: Evaluating Point-in-Time Character Hallucination of Role-Playing Large Language Models](https://arxiv.org/list/cs/pastweek?skip=687&show=446)【ACL2024】

- **[2024.5.29]**
  - Paper: [Cross-Context Backdoor Attacks against Graph Prompt Learning](https://arxiv.org/abs/2405.17984)【KDD2024】
  - Paper: [Yuan 2.0-M32: Mixture of Experts with Attention Router](https://arxiv.org/abs/2405.17976)

- **[2024.5.28]**
  - Survey Paper: [Tool Learning with Large Language Models: A Survey](https://arxiv.org/abs/2405.17935)
  - Paper: [Long Context is Not Long at All: A Prospector of Long-Dependency Data for Large Language Models](https://arxiv.org/abs/2405.17915)

- **[2024.5.27]**
  - Paper: [Subtle Biases Need Subtler Measures: Dual Metrics for Evaluating Representative and Affinity Bias in Large Language Models](https://arxiv.org/abs/2405.14555)【ACL2024】
  - Paper: [Exploring Alignment in Shared Cross-lingual Spaces](https://arxiv.org/list/cs/pastweek?skip=687&show=446)【ACL2024】

- **[2024.5.26]**
  - Paper: [ConvLLaVA: Hierarchical Backbones as Visual Encoder for Large Multimodal Models](https://arxiv.org/list/cs/recent?skip=0&show=446)
  - Paper: [Disease-informed Adaptation of Vision-Language Models](https://arxiv.org/abs/2405.15728)【MICCAI 2024】

- **[2024.5.25]**
  - Paper: [Chain-of-Thought Prompting for Demographic Inference with Large Multimodal Models](https://arxiv.org/abs/2405.15687)【ICME2024】
  - Paper: [Prompt-Aware Adapter: Towards Learning Adaptive Visual Tokens for Multimodal Large Language Models](https://arxiv.org/abs/2405.15684)

- **[2024.5.24]**
  - Paper: [Neuromorphic dreaming: A pathway to efficient learning in artificial agents](https://arxiv.org/abs/2405.15616)
  - Paper: [DAGER: Exact Gradient Inversion for Large Language Models](https://arxiv.org/abs/2405.15586)

- **[2024.5.23]**
  - Paper: [Meteor: Mamba-based Traversal of Rationale for Large Language and Vision Models](https://arxiv.org/abs/2405.15574)
  - Paper: [When Generative AI Meets Workplace Learning: Creating A Realistic & Motivating Learning Experience With A Generative PCA](https://arxiv.org/list/cs/recent?skip=0&show=446)【ECIS2024】

- **[2024.5.22]**
  - Paper: [MAML-en-LLM: Model Agnostic Meta-Training of LLMs for Improved In-Context Learning](https://arxiv.org/abs/2405.11446)【KDD2024】
  - Paper: [Measuring Impacts of Poisoning on Model Parameters and Embeddings for Large Language Models of Code](https://arxiv.org/abs/2405.11466)【1st ACM International Conference on AI-powered Software (AIware), co-located with the ACM International Conference on the Foundations of Software Engineering (FSE) 2024, Porto de Galinhas, Brazil. 】
  - Paper: [Effective In-Context Example Selection through Data Compression](https://arxiv.org/abs/2405.11465)【ACL2024】

- **[2024.5.21]**
  - Paper: [Efficient Prompt Tuning by Multi-Space Projection and Prompt Fusion](https://arxiv.org/abs/2405.11464)
  - Paper: [CPS-LLM: Large Language Model based Safe Usage Plan Generator for Human-in-the-Loop Human-in-the-Plant Cyber-Physical System](https://arxiv.org/abs/2405.11458)【AAAI2024】
  - Paper:[DocReLM: Mastering Document Retrieval with Language Model](https://arxiv.org/abs/2405.11461)

- **[2024.5.20]**
  - Paper: [Libra: Building Decoupled Vision System on Large Language Models](https://arxiv.org/abs/2405.10140)
  - Paper: [Unsupervised Image Prior via Prompt Learning and CLIP Semantic Guidance for Low-Light Image Enhancement](https://arxiv.org/abs/2405.11478)【CVPR 2024 Workshop NTIRE: New Trends in Image Restoration and Enhancement workshop and Challenges】
  - Paper: [MarkLLM: An Open-Source Toolkit for LLM Watermarking](https://arxiv.org/abs/2405.10051)

- **[2024.5.19]**
  - Paper: [Revisiting OPRO: The Limitations of Small-Scale LLMs as Optimizers](https://arxiv.org/abs/2405.10276)
  - Survey Paper: [When LLMs step into the 3D World: A Survey and Meta-Analysis of 3D Tasks via Multi-modal Large Language Models](https://arxiv.org/abs/2405.10255)

- **[2024.5.18]**
  - Paper: [HW-GPT-Bench: Hardware-Aware Architecture Benchmark for Language Models](https://arxiv.org/abs/2405.10299)
  - Paper: [Fine-Tuning Large Vision-Language Models as Decision-Making Agents via Reinforcement Learning](https://arxiv.org/abs/2405.10292)

- **[2024.5.17]**
  - Paper: [UniRAG: Universal Retrieval Augmentation for Multi-Modal Large Language Models](https://arxiv.org/abs/2405.10311)
  - Paper: [Grounding DINO 1.5: Advance the "Edge" of Open-Set Object Detection](https://arxiv.org/abs/2405.10300)

- **[2024.5.16]**
  - Paper: [Text-to-Vector Generation with Neural Path Representation](https://arxiv.org/abs/2405.10317)
  - Paper: [Analogist: Out-of-the-box Visual In-Context Learning with Image Diffusion Model](https://arxiv.org/abs/2405.10316)

- **[2024.5.15]**
  - 🔥🔥🔥[Google strikes back: Project Astra goes head-to-head with GPT-4o, Veo fights Sora, and a new version of Gemini revolutionises search](https://blog.google/inside-google/message-ceo/google-io-2024-keynote-sundar-pichai/#creating-the-future)
  - Paper: [Improving Transformers with Dynamically Composable Multi-Head Attention](https://arxiv.org/abs/2405.08553)
  - Paper: [Learning Multi-Agent Communication from Graph Modeling Perspective](https://arxiv.org/abs/2405.08550)

- **[2024.5.14]**
  - 🔥🔥🔥[OpenAI Turns the World Upside Down: GPT-4o is Completely Free, Real-Time Voice-Video Interaction Rocks the Room](https://openai.com/index/hello-gpt-4o/)
  - Paper: [Efficient Vision-Language Pre-training by Cluster Masking](https://arxiv.org/abs/2405.08815)
  - Paper: [Promoting AI Equity in Science: Generalized Domain Prompt Learning for Accessible VLM Research](https://arxiv.org/list/cs/recent?skip=0&show=446)

- **[2024.5.13]**
  - Paper: [Linearizing Large Language Models](https://arxiv.org/abs/2405.06640)
  - Paper: [Multimodal LLMs Struggle with Basic Visual Network Analysis: a VNA Benchmark](https://arxiv.org/abs/2405.06634)

- **[2024.5.12]**
  - Paper: [UniDM: A Unified Framework for Data Manipulation with Large Language Models](https://arxiv.org/abs/2405.06510)
  - Paper: [Storypark: Leveraging Large Language Models to Enhance Children Story Learning Through Child-AI collaboration Storytelling](https://arxiv.org/abs/2405.06495)

- **[2024.5.11]**
  - Paper: [Pseudo-Prompt Generating in Pre-trained Vision-Language Models for Multi-Label Medical Image Classification](https://arxiv.org/abs/2405.06468)

- **[2024.5.10]**
  - Paper: [FlockGPT: Guiding UAV Flocking with Linguistic Orchestration](https://arxiv.org/abs/2405.05872)
  - Paper: [An Automatic Prompt Generation System for Tabular Data Tasks](https://arxiv.org/abs/2405.05618)
  - Paper: [Memory-Space Visual Prompting for Efficient Vision-Language Fine-Tuning](https://arxiv.org/abs/2405.05615)

- **[2024.5.9]**
  - Paper: [Probing Multimodal LLMs as World Models for Driving](https://arxiv.org/abs/2405.05956)
  - Paper: [Smurfs: Leveraging Multiple Proficiency Agents with Context-Efficiency for Tool Planning](https://arxiv.org/abs/2405.05955)
  - Paper: [Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers](https://arxiv.org/abs/2405.05945)

- **[2024.5.8]**
  - Paper: [ChatHuman: Language-driven 3D Human Understanding with Retrieval-Augmented Tool Reasoning](https://arxiv.org/abs/2405.04533)
  - Paper: [QServe: W4A8KV4 Quantization and System Co-design for Efficient LLM Serving](https://arxiv.org/abs/2405.04532)
  - Paper: [Unveiling Disparities in Web Task Handling Between Human and Web Agent](https://arxiv.org/abs/2405.04497)

- **[2024.5.7]**
  - Paper: [vAttention: Dynamic Memory Management for Serving LLMs without PagedAttention](https://arxiv.org/abs/2405.04437)
  - Paper: [DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://arxiv.org/abs/2405.04434)
  - Survey Paper: [Vision Mamba: A Comprehensive Survey and Taxonomy](https://arxiv.org/abs/2405.04404)

- **[2024.5.6]**
  - Paper: [Vibe-Eval: A hard evaluation suite for measuring progress of multimodal language models](https://arxiv.org/abs/2405.02287)
  - Paper: [On the test-time zero-shot generalization of vision-language models: Do we really need prompt learning?](https://arxiv.org/abs/2405.02266)
  - Paper: [Leveraging Large Language Models to Enhance Domain Expert Inclusion in Data Science Workflows](https://arxiv.org/abs/2405.02260)

- **[2024.5.5]**
  - Paper: [What matters when building vision-language models?](https://arxiv.org/abs/2405.02246)
  - Paper: [REASONS: A benchmark for REtrieval and Automated citationS Of scieNtific Sentences using Public and Proprietary LLMs](https://arxiv.org/abs/2405.02228)
  - Paper: [FairEvalLLM. A Comprehensive Framework for Benchmarking Fairness in Large Language Model Recommender Systems](https://arxiv.org/abs/2405.02219)

- **[2024.5.4]**
  - Paper: [Single and Multi-Hop Question-Answering Datasets for Reticular Chemistry with GPT-4-Turbo](https://arxiv.org/abs/2405.02128)
  - Paper: [Analyzing Narrative Processing in Large Language Models (LLMs): Using GPT4 to test BERT](https://arxiv.org/abs/2405.02024)
  - Paper: [Auto-Encoding Morph-Tokens for Multimodal LLM](https://arxiv.org/abs/2405.01926)

- **[2024.5.3]**
  - Paper: [Self-Refine Instruction-Tuning for Aligning Reasoning in Language Models](https://arxiv.org/abs/2405.00402)
  - Paper: [CofiPara: A Coarse-to-fine Paradigm for Multimodal Sarcasm Target Identification with Large Multimodal Models](https://arxiv.org/abs/2405.00390)
  - Paper: [AdaMoLE: Fine-Tuning Large Language Models with Adaptive Mixture of Low-Rank Adaptation Experts](https://arxiv.org/abs/2405.00361)

- **[2024.5.2]**
  - Paper: [When Quantization Affects Confidence of Large Language Models?](https://arxiv.org/abs/2405.00632)
  - Paper: [Causal Evaluation of Language Models](https://arxiv.org/abs/2405.00622)
  - Paper: [Investigating Automatic Scoring and Feedback using Large Language Models](https://arxiv.org/abs/2405.00602)

- **[2024.5.1]**
  - Paper: [Self-Play Preference Optimization for Language Model Alignment](https://arxiv.org/abs/2405.00675)
  - Paper: [Is Bigger Edit Batch Size Always Better? -- An Empirical Study on Model Editing with Llama-3](https://arxiv.org/abs/2405.00664)
  - Paper: [RST-LoRA: A Discourse-Aware Low-Rank Adaptation for Long Document Abstractive Summarization](https://arxiv.org/abs/2405.00657)

- **[2024.4.30]**
  - Paper: [EALD-MLLM: Emotion Analysis in Long-sequential and De-identity videos with Multi-modal Large Language Model](https://arxiv.org/abs/2405.00574)
  - Paper: [NumLLM: Numeric-Sensitive Large Language Model for Chinese Finance](https://arxiv.org/abs/2405.00566)
  - Paper: [Navigating WebAI: Training Agents to Complete Web Tasks with Large Language Models and Reinforcement Learning](https://arxiv.org/abs/2405.00516)

- **[2024.4.29]**
  - [The "Chinese NVIDIA" thousand-card cluster is now in place.](https://jxj.beijing.gov.cn/zwgk/zcjd/202404/t20240425_3637629.html)
  - [XVERSE-V: Unconditionally commercial free, outperforms Claude 3 Sonnet](https://huggingface.co/xverse/XVERSE-V-13B)

- **[2024.4.28]**
  - Paper: [Learning to Beat ByteRL: Exploitability of Collectible Card Game Agents](https://arxiv.org/abs/2404.16689)
  - Paper: [Unifying Asynchronous Logics for Hyperproperties](https://arxiv.org/abs/2404.16778)
  - Paper: [Lost in Recursion: Mining Rich Event Semantics in Knowledge Graphs](https://arxiv.org/abs/2404.16405) 

- **[2024.4.27]**
  - Paper: [AAPL: Adding Attributes to Prompt Learning for Vision-Language Models](https://arxiv.org/abs/2404.16804)
  - Paper: [SEED-Bench-2-Plus: Benchmarking Multimodal Large Language Models with Text-Rich Visual Comprehension](https://arxiv.org/abs/2404.16790)
  - Paper: [Cooperate or Collapse: Emergence of Sustainability Behaviors in a Society of LLM Agents](https://arxiv.org/abs/2404.16698)

- **[2024.4.26]**
  - Paper: [IndicGenBench: A Multilingual Benchmark to Evaluate Generation Capabilities of LLMs on Indic Languages](https://arxiv.org/abs/2404.16816)
  - Paper: [Make Your LLM Fully Utilize the Context](https://arxiv.org/abs/2404.16811)
  - Paper: [Improving Diversity of Commonsense Generation by Large Language Models via In-Context Learning](https://arxiv.org/abs/2404.16807)

- **[2024.4.25]**
  - Paper: [Cantor: Inspiring Multimodal Chain-of-Thought of MLLM](https://arxiv.org/abs/2404.16033)
  - Paper: [The PRISM Alignment Project: What Participatory, Representative and Individualised Human Feedback Reveals About the Subjective and Multicultural Alignment of Large Language Models](https://arxiv.org/abs/2404.16019)
  - Paper: [MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI](https://arxiv.org/abs/2404.16006)

- **[2024.4.24]**
  - Survey Paper: [A Survey on Visual Mamba](https://arxiv.org/abs/2404.15956)
  - Paper: [Uncertainty Estimation and Quantification for LLMs: A Simple Supervised Approach](https://arxiv.org/abs/2404.15993)
  - Paper: [Exploring LLM Prompting Strategies for Joint Essay Scoring and Feedback Generation](https://arxiv.org/abs/2404.15845)

- **[2024.4.23]**
  - Paper: [Re-Thinking Inverse Graphics With Large Language Models](https://arxiv.org/abs/2404.15228)
  - Paper: [Does Instruction Tuning Make LLMs More Consistent?](https://arxiv.org/abs/2404.15206)

- **[2024.4.22]**
  - Paper: [Unified Scene Representation and Reconstruction for 3D Large Language Models](https://arxiv.org/abs/2404.13044)
  - Paper: [Sample Design Engineering: An Empirical Study of What Makes Good Downstream Fine-Tuning Samples for LLMs](https://arxiv.org/abs/2404.13033)
  - Paper: [Stronger Random Baselines for In-Context Learning](https://arxiv.org/abs/2404.13020)

- **[2024.4.21]**
  - Paper: [When LLMs are Unfit Use FastFit: Fast and Effective Text Classification with Many Classes](https://arxiv.org/abs/2404.12365)
  - Paper: [Rethinking the Evaluation of Dialogue Systems: Effects of User Feedback on Crowdworkers and LLMs](https://arxiv.org/abs/2404.12994)
  - Paper: [Private Agent-Based Modeling](https://arxiv.org/abs/2404.12983)

- **[2024.4.20]**
  - 🔥🔥🔥[Introducing Meta Llama 3: The most capable openly available LLM to date](https://ai.meta.com/blog/meta-llama-3/)
  - Paper: [Towards Reliable Latent Knowledge Estimation in LLMs: In-Context Learning vs. Prompting Based Factual Knowledge Extraction](https://arxiv.org/abs/2404.12957)

- **[2024.4.19]**
  - Paper: [V2Xum-LLM: Cross-Modal Video Summarization with Temporal Prompt Instruction Tuning](https://arxiv.org/abs/2404.12353)
  - Paper: [Point-In-Context: Understanding Point Cloud via In-Context Learning](https://arxiv.org/abs/2404.12352)
  - Paper: [Omniview-Tuning: Boosting Viewpoint Invariance of Vision-Language Pre-training Models](https://arxiv.org/abs/2404.12139)
  
[👉 Complete history news 👈](./historynews.md)

<img width="200%" src="./figures/hr.gif" />

---

# 📜 Papers

> You can directly click on the title to jump to the corresponding PDF link location

## Survey

<div style="line-height:0.2em;">


<div style="line-height:0.2em;">



[**The Ethics of ChatGPT in Medicine and Healthcare: A Systematic Review on Large Language Models (LLMs)**](https://arxiv.org/abs/2403.14473) （**2024.03.21**）

![](https://img.shields.io/badge/Citations-0-green)

[**Parameter-Efficient Fine-Tuning for Large Models: A Comprehensive Survey**](https://arxiv.org/abs/2403.14608) （**2024.03.21**）

![](https://img.shields.io/badge/Citations-0-green)

[**ChatGPT Alternative Solutions: Large Language Models Survey**](https://doi.org/10.5121/csit.2024.140514) （**2024.03.16**）

![](https://img.shields.io/badge/Citations-0-green)

[**MM1: Methods, Analysis&Insights from Multimodal LLM Pre-training**](https://arxiv.org/abs/2403.09611) （**2024.03.14**）

![](https://img.shields.io/badge/Citations-1-green)

[**Large Language Models and Causal Inference in Collaboration: A Comprehensive Survey**](https://arxiv.org/abs/2403.09606) （**2024.03.14**）

![](https://img.shields.io/badge/Citations-0-green)

[**Model Parallelism on Distributed Infrastructure: A Literature Review from Theory to LLM Case-Studies**](https://arxiv.org/abs/2403.03699) （**2024.03.06**）

![](https://img.shields.io/badge/Citations-0-green)

[**Benchmarking the Text-to-SQL Capability of Large Language Models: A Comprehensive Evaluation**](https://arxiv.org/abs/2403.02951) （**2024.03.05**）

![](https://img.shields.io/badge/Citations-1-green)

[**A Comprehensive Survey on Process-Oriented Automatic Text Summarization with Exploration of LLM-Based Methods**](https://arxiv.org/abs/2403.02901) （**2024.03.05**）

![](https://img.shields.io/badge/Citations-0-green)

[**Large Language Models for Data Annotation: A Survey**](https://arxiv.org/abs/2402.13446) （**2024.02.21**）

![](https://img.shields.io/badge/Citations-0-green)

[**A Survey on Knowledge Distillation of Large Language Models**](https://arxiv.org/abs/2402.13116) （**2024.02.20**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "Survey"](./PaperList/survey.md)👈

## Prompt Engineering

### Prompt Design

<div style="line-height:0.2em;">



[**DLoRA: Distributed Parameter-Efficient Fine-Tuning Solution for Large Language Model**](https://arxiv.org/abs/2404.05182) （**2024.04.08**）

![](https://img.shields.io/badge/Citations-0-green)

[**3P-LLM: Probabilistic Path Planning using Large Language Model for Autonomous Robot Navigation**](https://doi.org/10.48550/arXiv.2403.18778) （**2024.03.27**）

![](https://img.shields.io/badge/Citations-0-green)

[**SAMCT: Segment Any CT Allowing Labor-Free Task-Indicator Prompts**](https://arxiv.org/abs/2403.13258) （**2024.03.20**）

![](https://img.shields.io/badge/Citations-0-green)

[**AFLoRA: Adaptive Freezing of Low Rank Adaptation in Parameter Efficient Fine-Tuning of Large Models**](https://arxiv.org/abs/2403.13269) （**2024.03.20**）

![](https://img.shields.io/badge/Citations-0-green)

[**Few-Shot Class Incremental Learning with Attention-Aware Self-Adaptive Prompt**](https://arxiv.org/abs/2403.09857) （**2024.03.14**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-1-red)

[**Unveiling the Generalization Power of Fine-Tuned Large Language Models**](https://arxiv.org/abs/2403.09162) （**2024.03.14**）

![](https://img.shields.io/badge/Citations-0-green)

[**Attention Prompt Tuning: Parameter-efficient Adaptation of Pre-trained Models for Spatiotemporal Modeling**](https://arxiv.org/abs/2403.06978) （**2024.03.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**VidProM: A Million-scale Real Prompt-Gallery Dataset for Text-to-Video Diffusion Models**](https://arxiv.org/abs/2403.06098) （**2024.03.10**）

![](https://img.shields.io/badge/Citations-0-green)

[**Localized Zeroth-Order Prompt Optimization**](https://arxiv.org/abs/2403.02993) （**2024.03.05**）

![](https://img.shields.io/badge/Citations-0-green)

[**RIFF: Learning to Rephrase Inputs for Few-shot Fine-tuning of Language Models**](https://arxiv.org/abs/2403.02271) （**2024.03.04**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "Prompt Design"](./PaperList/PromptDesignList.md)👈

### Chain of Thought

<div style="line-height:0.2em;">



[**nicolay-r at SemEval-2024 Task 3: Using Flan-T5 for Reasoning Emotion Cause in Conversations with Chain-of-Thought on Emotion States**](https://arxiv.org/abs/2404.03361) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Visualization-of-Thought Elicits Spatial Reasoning in Large Language Models**](https://arxiv.org/abs/2404.03622) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Can Small Language Models Help Large Language Models Reason Better?: LM-Guided Chain-of-Thought**](https://arxiv.org/abs/2404.03414) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Visual CoT: Unleashing Chain-of-Thought Reasoning in Multi-Modal Language Models**](https://arxiv.org/abs/2403.16999) （**2024.03.25**）

![](https://img.shields.io/badge/Citations-0-green)

[**A Chain-of-Thought Prompting Approach with LLMs for Evaluating Students' Formative Assessment Responses in Science**](https://arxiv.org/abs/2403.14565) （**2024.03.21**）

![](https://img.shields.io/badge/Citations-0-green)

[**NavCoT: Boosting LLM-Based Vision-and-Language Navigation via Learning Disentangled Reasoning**](https://arxiv.org/abs/2403.07376) （**2024.03.12**）

![](https://img.shields.io/badge/Citations-0-green)

[**ERA-CoT: Improving Chain-of-Thought through Entity Relationship Analysis**](https://arxiv.org/abs/2403.06932) （**2024.03.11**）

![](https://img.shields.io/badge/Citations-1-green)

[**Bias-Augmented Consistency Training Reduces Biased Reasoning in Chain-of-Thought**](https://arxiv.org/abs/2403.05518) （**2024.03.08**）

![](https://img.shields.io/badge/Citations-0-green)

[**Chain-of-Thought Unfaithfulness as Disguised Accuracy**](https://doi.org/10.48550/arXiv.2402.14897) （**2024.02.22**）

![](https://img.shields.io/badge/Citations-0-green)

[**Chain-of-Thought Reasoning Without Prompting**](https://doi.org/10.48550/arXiv.2402.10200) （**2024.02.15**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "Chain of Thought"](./PaperList/ChainofThoughtList.md)👈

### In-context Learning

<div style="line-height:0.2em;">



[**AFLoRA: Adaptive Freezing of Low Rank Adaptation in Parameter Efficient Fine-Tuning of Large Models**](https://arxiv.org/abs/2403.13269) （**2024.03.20**）

![](https://img.shields.io/badge/Citations-0-green)

[**ExploRLLM: Guiding Exploration in Reinforcement Learning with Large Language Models**](https://arxiv.org/abs/2403.09583) （**2024.03.14**）

![](https://img.shields.io/badge/Citations-0-green)

[**NavCoT: Boosting LLM-Based Vision-and-Language Navigation via Learning Disentangled Reasoning**](https://arxiv.org/abs/2403.07376) （**2024.03.12**）

![](https://img.shields.io/badge/Citations-0-green)

[**Attention Prompt Tuning: Parameter-efficient Adaptation of Pre-trained Models for Spatiotemporal Modeling**](https://arxiv.org/abs/2403.06978) （**2024.03.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**Bias-Augmented Consistency Training Reduces Biased Reasoning in Chain-of-Thought**](https://arxiv.org/abs/2403.05518) （**2024.03.08**）

![](https://img.shields.io/badge/Citations-0-green)

[**LoRA-SP: Streamlined Partial Parameter Adaptation for Resource-Efficient Fine-Tuning of Large Language Models**](https://arxiv.org/abs/2403.08822) （**2024.02.28**）

![](https://img.shields.io/badge/Citations-0-green)

[**Securing Reliability: A Brief Overview on Enhancing In-Context Learning for Foundation Models**](https://arxiv.org/abs/2402.17671) （**2024.02.27**）

![](https://img.shields.io/badge/Citations-0-green)

[**GISTEmbed: Guided In-sample Selection of Training Negatives for Text Embedding Fine-tuning**](https://doi.org/10.48550/arXiv.2402.16829) （**2024.02.26**）

![](https://img.shields.io/badge/Citations-1-green)  [![](https://img.shields.io/badge/Github%20Stars-15-blue)](https://github.com/avsolatorio/gistembed)

[**DiffuCOMET: Contextual Commonsense Knowledge Diffusion**](https://arxiv.org/abs/2402.17011) （**2024.02.26**）

![](https://img.shields.io/badge/Citations-0-green)

[**Long-Context Language Modeling with Parallel Context Encoding**](https://arxiv.org/abs/2402.16617) （**2024.02.26**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "In-context Learning"](./PaperList/InContextLearningList.md)👈


### Retrieval Augmented Generation

<div style="line-height:0.2em;">



[**Superposition Prompting: Improving and Accelerating Retrieval-Augmented Generation**](https://arxiv.org/abs/2404.06910) （**2024.04.10**）

![](https://img.shields.io/badge/Citations-0-green)

[**Untangle the KNOT: Interweaving Conflicting Knowledge and Reasoning Skills in Large Language Models**](https://arxiv.org/abs/2404.03577) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Unveiling LLMs: The Evolution of Latent Representations in a Temporal Knowledge Graph**](https://arxiv.org/abs/2404.03623) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Retrieval-Augmented Generation for AI-Generated Content: A Survey**](https://arxiv.org/abs/2402.19473) （**2024.02.29**）

![](https://img.shields.io/badge/Citations-0-green)

[**VerifiNER: Verification-augmented NER via Knowledge-grounded Reasoning with Large Language Models**](https://arxiv.org/abs/2402.18374) （**2024.02.28**）

![](https://img.shields.io/badge/Citations-0-green)

[**LLM Augmented LLMs: Expanding Capabilities through Composition**](https://doi.org/10.48550/arXiv.2401.02412) （**2024.01.04**）

![](https://img.shields.io/badge/Citations-1-green)  [![](https://img.shields.io/badge/Github%20Stars-120-blue)](https://github.com/lucidrains/CALM-pytorch)

[**ARES: An Automated Evaluation Framework for Retrieval-Augmented Generation Systems**](https://doi.org/10.48550/arXiv.2311.09476) （**2023.11.16**）

![](https://img.shields.io/badge/Citations-1-green)  [![](https://img.shields.io/badge/Github%20Stars-237-blue)](https://github.com/stanford-futuredata/ares)

[**Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models**](https://doi.org/10.48550/arXiv.2311.09210) （**2023.11.15**）

![](https://img.shields.io/badge/Citations-17-green)

[**From Classification to Generation: Insights into Crosslingual Retrieval Augmented ICL**](https://doi.org/10.48550/arXiv.2311.06595) （**2023.11.11**）

![](https://img.shields.io/badge/Citations-1-green)

[**Optimizing Retrieval-augmented Reader Models via Token Elimination**](https://doi.org/10.48550/arXiv.2310.13682) （**2023.10.20**）

![](https://img.shields.io/badge/Citations-3-green)  [![](https://img.shields.io/badge/Github%20Stars-4-blue)](https://github.com/mosheber/token_elimination)


</div>

👉[Complete paper list 🔗 for "Retrieval Augmented Generation"](./PaperList/KnowledgeAugmentedPromptList.md)👈


### Evaluation & Reliability

<div style="line-height:0.2em;">



[**Evaluating LLMs at Detecting Errors in LLM Responses**](https://arxiv.org/abs/2404.03602) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Do Large Language Models Rank Fairly? An Empirical Study on the Fairness of LLMs as Rankers**](https://arxiv.org/abs/2404.03192) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Unsolvable Problem Detection: Evaluating Trustworthiness of Vision Language Models**](https://doi.org/10.48550/arXiv.2403.20331) （**2024.03.29**）

![](https://img.shields.io/badge/Citations-0-green)

[**ERBench: An Entity-Relationship based Automatically Verifiable Hallucination Benchmark for Large Language Models**](https://arxiv.org/abs/2403.05266) （**2024.03.08**）

![](https://img.shields.io/badge/Citations-0-green)  [![](https://img.shields.io/badge/Github%20Stars-4-blue)](https://github.com/dilab-kaist/erbench)

[**Benchmarking the Text-to-SQL Capability of Large Language Models: A Comprehensive Evaluation**](https://arxiv.org/abs/2403.02951) （**2024.03.05**）

![](https://img.shields.io/badge/Citations-1-green)

[**Beyond Specialization: Assessing the Capabilities of MLLMs in Age and Gender Estimation**](https://arxiv.org/abs/2403.02302) （**2024.03.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**A Cognitive Evaluation Benchmark of Image Reasoning and Description for Large Vision Language Models**](https://arxiv.org/abs/2402.18409) （**2024.02.28**）

![](https://img.shields.io/badge/Citations-0-green)

[**Evaluating Very Long-Term Conversational Memory of LLM Agents**](https://doi.org/10.48550/arXiv.2402.17753) （**2024.02.27**）

![](https://img.shields.io/badge/Citations-0-green)

[**Semantic Mirror Jailbreak: Genetic Algorithm Based Jailbreak Prompts Against Open-source LLMs**](https://doi.org/10.48550/arXiv.2402.14872) （**2024.02.21**）

![](https://img.shields.io/badge/Citations-0-green)

[**TofuEval: Evaluating Hallucinations of LLMs on Topic-Focused Dialogue Summarization**](https://arxiv.org/abs/2402.13249) （**2024.02.20**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "Evaluation & Reliability"](./PaperList/EvaluationReliabilityList.md)👈

## Agent

<div style="line-height:0.2em;">



[**OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**](https://arxiv.org/abs/2404.07972) （**2024.04.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models**](https://arxiv.org/abs/2404.07738) （**2024.04.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**Laser Learning Environment: A new environment for coordination-critical multi-agent tasks**](https://arxiv.org/abs/2404.03596) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**AutoWebGLM: Bootstrap And Reinforce A Large Language Model-based Web Navigating Agent**](https://arxiv.org/abs/2404.03648) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**MIMIR: A Streamlined Platform for Personalized Agent Tuning in Domain Expertise**](https://arxiv.org/abs/2404.04285) （**2024.04.03**）

![](https://img.shields.io/badge/Citations-0-green)

[**ELITR-Bench: A Meeting Assistant Benchmark for Long-Context Language Models**](https://doi.org/10.48550/arXiv.2403.20262) （**2024.03.29**）

![](https://img.shields.io/badge/Citations-0-green)

[**Change-Agent: Towards Interactive Comprehensive Remote Sensing Change Interpretation and Analysis**](https://doi.org/10.48550/arXiv.2403.19646) （**2024.03.28**）

![](https://img.shields.io/badge/Citations-0-green)

[**Bayesian Methods for Trust in Collaborative Multi-Agent Autonomy**](https://arxiv.org/abs/2403.16956) （**2024.03.25**）

![](https://img.shields.io/badge/Citations-0-green)

[**AIOS: LLM Agent Operating System**](https://arxiv.org/abs/2403.16971) （**2024.03.25**）

![](https://img.shields.io/badge/Citations-0-green)

[**EduAgent: Generative Student Agents in Learning**](https://arxiv.org/abs/2404.07963) （**2024.03.23**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "Agent"](./PaperList/AgentList.md)👈

## Multimodal Prompt

<div style="line-height:0.2em;">



[**BRAVE: Broadening the visual encoding of vision-language models**](https://arxiv.org/abs/2404.07204) （**2024.04.10**）

![](https://img.shields.io/badge/Citations-0-green)

[**ORacle: Large Vision-Language Models for Knowledge-Guided Holistic OR Domain Modeling**](https://arxiv.org/abs/2404.07031) （**2024.04.10**）

![](https://img.shields.io/badge/Citations-0-green)

[**MoMA: Multimodal LLM Adapter for Fast Personalized Image Generation**](https://arxiv.org/abs/2404.05674) （**2024.04.08**）

![](https://img.shields.io/badge/Citations-0-green)

[**Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs**](https://arxiv.org/abs/2404.05719) （**2024.04.08**）

![](https://img.shields.io/badge/Citations-0-green)

[**MiniGPT4-Video: Advancing Multimodal LLMs for Video Understanding with Interleaved Visual-Textual Tokens**](https://arxiv.org/abs/2404.03413) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**ViTamin: Designing Scalable Vision Models in the Vision-Language Era**](https://arxiv.org/abs/2404.02132) （**2024.04.02**）

![](https://img.shields.io/badge/Citations-0-green)

[**Segment Any 3D Object with Language**](https://arxiv.org/abs/2404.02157) （**2024.04.02**）

![](https://img.shields.io/badge/Citations-0-green)

[**Iterated Learning Improves Compositionality in Large Vision-Language Models**](https://arxiv.org/abs/2404.02145) （**2024.04.02**）

![](https://img.shields.io/badge/Citations-1-green)

[**Mini-Gemini: Mining the Potential of Multi-modality Vision Language Models**](https://doi.org/10.48550/arXiv.2403.18814) （**2024.03.27**）

![](https://img.shields.io/badge/Citations-3-green)

[**Visual CoT: Unleashing Chain-of-Thought Reasoning in Multi-Modal Language Models**](https://arxiv.org/abs/2403.16999) （**2024.03.25**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "Multimodal Prompt"](./PaperList/multimodalprompt.md)👈

## Prompt Application

<div style="line-height:0.2em;">



[**Manipulating Large Language Models to Increase Product Visibility**](https://arxiv.org/abs/2404.07981) （**2024.04.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**Generating consistent PDDL domains with Large Language Models**](https://arxiv.org/abs/2404.07751) （**2024.04.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**High-Dimension Human Value Representation in Large Language Models**](https://arxiv.org/abs/2404.07900) （**2024.04.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**MetaCheckGPT -- A Multi-task Hallucination Detector Using LLM Uncertainty and Meta-models**](https://arxiv.org/abs/2404.06948) （**2024.04.10**）

![](https://img.shields.io/badge/Citations-0-green)

[**From Model-centered to Human-Centered: Revision Distance as a Metric for Text Evaluation in LLMs-based Applications**](https://arxiv.org/abs/2404.07108) （**2024.04.10**）

![](https://img.shields.io/badge/Citations-0-green)

[**LayoutLLM: Layout Instruction Tuning with Large Language Models for Document Understanding**](https://arxiv.org/abs/2404.05225) （**2024.04.08**）

![](https://img.shields.io/badge/Citations-0-green)

[**Long-horizon Locomotion and Manipulation on a Quadrupedal Robot with Large Language Models**](https://arxiv.org/abs/2404.05291) （**2024.04.08**）

![](https://img.shields.io/badge/Citations-0-green)

[**Topic-based Watermarks for LLM-Generated Text**](https://arxiv.org/abs/2404.02138) （**2024.04.02**）

![](https://img.shields.io/badge/Citations-0-green)

[**Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks**](https://arxiv.org/abs/2404.02151) （**2024.04.02**）

![](https://img.shields.io/badge/Citations-0-green)

[**Towards Greener LLMs: Bringing Energy-Efficiency to the Forefront of LLM Inference**](https://doi.org/10.48550/arXiv.2403.20306) （**2024.03.29**）

![](https://img.shields.io/badge/Citations-0-green)


</div>

👉[Complete paper list 🔗 for "Prompt Application"](./PaperList/promptapplication.md)👈

## Foundation Models

<div style="line-height:0.2em;">



[**RecurrentGemma: Moving Past Transformers for Efficient Open Language Models**](https://arxiv.org/abs/2404.07839) （**2024.04.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**OpenBias: Open-set Bias Detection in Text-to-Image Generative Models**](https://arxiv.org/abs/2404.07990) （**2024.04.11**）

![](https://img.shields.io/badge/Citations-0-green)

[**Scaling Up Video Summarization Pretraining with Large Language Models**](https://arxiv.org/abs/2404.03398) （**2024.04.04**）

![](https://img.shields.io/badge/Citations-0-green)

[**Pre-trained Vision and Language Transformers Are Few-Shot Incremental Learners**](https://arxiv.org/abs/2404.02117) （**2024.04.02**）

![](https://img.shields.io/badge/Citations-0-green)

[**MTLoRA: A Low-Rank Adaptation Approach for Efficient Multi-Task Learning**](https://doi.org/10.48550/arXiv.2403.20320) （**2024.03.29**）

![](https://img.shields.io/badge/Citations-0-green)

[**ReALM: Reference Resolution As Language Modeling**](https://doi.org/10.48550/arXiv.2403.20329) （**2024.03.29**）

![](https://img.shields.io/badge/Citations-0-green)

[**RSMamba: Remote Sensing Image Classification with State Space Model**](https://doi.org/10.48550/arXiv.2403.19654) （**2024.03.28**）

![](https://img.shields.io/badge/Citations-3-green)

[**DreamLIP: Language-Image Pre-training with Long Captions**](https://arxiv.org/abs/2403.17007) （**2024.03.25**）

![](https://img.shields.io/badge/Citations-0-green)

[**Instruction Multi-Constraint Molecular Generation Using a Teacher-Student Large Language Model**](https://arxiv.org/abs/2403.13244) （**2024.03.20**）

![](https://img.shields.io/badge/Citations-0-green)

[**VideoMamba: State Space Model for Efficient Video Understanding**](https://arxiv.org/abs/2403.06977) （**2024.03.11**）

![](https://img.shields.io/badge/Citations-1-green)


</div>

👉[Complete paper list 🔗 for "Foundation Models"](./PaperList/foundationmodels.md)👈

<!-- ### 📌 Hard Prompt/ Discrete Prompt

<div style="line-height:0.2em;">



[**Winner-Take-All Column Row Sampling for Memory Efficient Adaptation of Language Model**](https://arxiv.org/abs/2305.15265) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  [![](https://img.shields.io/badge/Github%20Stars-1-blue)](https://github.com/zirui-ray-liu/wtacrs)

[**How to Distill your BERT: An Empirical Study on the Impact of Weight Initialisation and Distillation Objectives**](https://arxiv.org/abs/2305.15032) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-12-red)  [![](https://img.shields.io/badge/Github%20Stars-8-blue)](https://github.com/mainlp/how-to-distill-your-bert)

[**ChatAgri: Exploring Potentials of ChatGPT on Cross-linguistic Agricultural Text Classification**](https://arxiv.org/abs/2305.15024) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-53-red)  [![](https://img.shields.io/badge/Github%20Stars-32-blue)](https://github.com/albert-jin/agricultural_textual_classification_chatgpt)

[**Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large Language Models**](https://arxiv.org/abs/2305.15023) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-49-red)

[**LLMDet: A Large Language Models Detection Tool**](https://arxiv.org/abs/2305.15004) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-7-red)

[**OverPrompt: Enhancing ChatGPT Capabilities through an Efficient In-Context Learning Approach**](https://arxiv.org/abs/2305.14973) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-8-red)

[**Interpretable by Design Visual Question Answering**](https://arxiv.org/abs/2305.14882) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-3-red)

[**In-Context Demonstration Selection with Cross Entropy Difference**](https://arxiv.org/abs/2305.14726) （**2023.05.24**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-5-red)  [![](https://img.shields.io/badge/Github%20Stars-2.8k-blue)](https://github.com/microsoft/lmops)

[**LogicLLM: Exploring Self-supervised Logic-enhanced Training for Large Language Models**](https://arxiv.org/abs/2305.13718) （**2023.05.23**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-13-red)  [![](https://img.shields.io/badge/Github%20Stars-1-blue)](https://github.com/sparkjiao/logicllm)

[**Contrastive Learning with Logic-driven Data Augmentation for Logical Reasoning over Text**](https://arxiv.org/abs/2305.12599) （**2023.05.21**）

![](https://img.shields.io/badge/Citations-0-green)  ![](https://img.shields.io/badge/Mendeley%20Readers-3-red)


</div>

👉[Complete paper list 🔗 for "Hard Prompt"](./PaperList/HardPromptList.md)👈

### 📌 Soft Prompt/ Continuous Prompt

<div style="line-height:0.2em;">




</div>

👉[Complete paper list 🔗 for "Soft Prompt"](./PaperList/SoftPromptList.md)👈 -->

<!-- ## Prompt for Knowledge Graph

// __PAPER_LIST__:{field:'Prompt Design',size:10,state:'corrected',type:'lite'}

👉[Complete paper list 🔗 for "Prompt for Knowledge Graph"](./PaperList/PromptKnowledgeGraphList.md)👈 --> 

<img width="200%" src="./figures/hr.gif" />

<!-- # 🎓 Citation

If you find our work helps, please star our project and cite our paper. Thanks a lot!

```

综述论文可以放在这个位置

``` -->

<!-- <img width="200%" src="./figures/hr.gif" /> -->

# 👨‍💻 LLM Usage
Large language models (LLMs) are becoming a revolutionary technology that is shaping the development of our era. Developers can create applications that were previously only possible in our imaginations by building LLMs. However, using these LLMs often comes with certain technical barriers, and even at the introductory stage, people may be intimidated by cutting-edge technology: Do you have any questions like the following?

- ❓ *How can LLM be built using programming?* 
- ❓ *How can it be used and deployed in your own programs?* 

💡 If there was a tutorial that could be accessible to all audiences, not just computer science professionals, it would provide detailed and comprehensive guidance to quickly get started and operate in a short amount of time, ultimately achieving the goal of being able to use LLMs flexibly and creatively to build the programs they envision. And now, just for you: the most detailed and comprehensive Langchain beginner's guide, sourced from the official langchain website but with further adjustments to the content, accompanied by the most detailed and annotated code examples, teaching code lines by line and sentence by sentence to all audiences.

**Click 👉[here](./langchain_guide/LangChainTutorial.ipynb)👈 to take a quick tour of getting started with LLM.**

<img width="200%" src="./figures/hr.gif" />

# ✉️ Contact

This repo is maintained by [EgoAlpha Lab](https://github.com/EgoAlpha). Questions and discussions are welcome via `helloegoalpha@gmail.com`.

We are willing to engage in discussions with friends from the academic and industrial communities, and explore the latest developments in prompt engineering and in-context learning together.

<img width="200%" src="./figures/hr.gif" />

# 🙏 Acknowledgements

Thanks to the PhD students from [EgoAlpha Lab](https://github.com/EgoAlpha) and other workers who participated in this repo. We will improve the project in the follow-up period and maintain this community well. We also would like to express our sincere gratitude to the authors of the relevant resources. Your efforts have broadened our horizons and enabled us to perceive a more wonderful world.


<!-- <img width="200%" src="./figures/hr.gif" /> -->

<!-- # 👨‍👩‍👧‍👦 Contributors

## Main Contributors
* [Yu Liu]()
* [Yifei Cao](https://github.com/cyfedu1024)
* [Jizhe Yu]()
* [Yuan Yao]()
* [He Qi]() -->


<!-- ## Guest Contributors
* [No] -->

<!-- <img width="200%" src="./figures/hr.gif" />

# 📔 License

This project is open source and available under the MIT

<div align="center">
<img src="./figures/rocket.png"/>
</div> -->