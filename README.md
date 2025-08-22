# 🚀 AI Researcher Ecosystem: Empowering Scientific Discovery with AI

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/[YOUR_USERNAME]/[YOUR_REPO_NAME]/pulls) <!-- Replace placeholders -->
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/github/last-commit/[YOUR_USERNAME]/[YOUR_REPO_NAME]?label=Updated&logo=github)](https://github.com/[YOUR_USERNAME]/[YOUR_REPO_NAME]/commits/main) <!-- Replace placeholders -->
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](CONTRIBUTING.md) <!-- Link removed or points to CONTRIBUTING.md -->
[![Contribution Welcome](https://img.shields.io/badge/Contributions-welcome-blue)](CONTRIBUTING.md)

**Dive into the rapidly evolving world of AI-powered research automation!** 💡 This curated repository is your compass to navigate the cutting-edge tools, frameworks, and methodologies that are revolutionizing scientific discovery. We track the latest advancements, focusing on resources that empower researchers and accelerate breakthroughs.

<!-- omit in toc -->
# 👀 Introduction

AI is transforming the scientific landscape, offering powerful tools to assist researchers throughout the entire research lifecycle. This repository provides a structured overview of the AI researcher ecosystem, focusing on key components and advancements.

<p align="center">
  <img src="https://github.com/zhu-minjun/Researcher/blob/main/img/ai-research.png" alt="AI Research Automation Landscape" width="800">
  <!-- Consider replacing placeholder image -->
</p>

We categorize resources 📚 based on the core stages of research automation impacted by AI, drawing heavily from the surveyed literature. For the papers compiled, we provide links to the paper itself 📄, associated code 💻, and available reviews 📝. Crucially, for some publications lacking open reviews, we've utilized our [**DeepReviewer**](https://ai-researcher.net/DeepReviewer) to generate AI-powered review analyses 🤖, also including links to these results. We welcome everyone to use our [**AI-Researcher.net**](https://ai-researcher.net), including **DeepReviewer**, **CycleResearcher**, **AutoSurvey**, and others! ✨

<!-- omit in toc -->
# 📌 Table of Contents

- [⚙️ Core Components](#️-core-components)
    - [Research Automation Stack](#research-automation-stack)
    - [Emerging Capabilities](#emerging-capabilities)
- [📰 Latest Buzz / News](#-latest-buzz--news)
- [🔥 Featured Projects](#-featured-projects)
    - [Open Source Tools](#open-source-tools)
    - [Commercial Platforms](#commercial-platforms)
-   [📚 Knowledge Acquisition](#-1-knowledge-acquisition)
    -   [Pre-LLM Era Methods](#11-pre-llm-era-methods)
    -   [LLM Era Methods](#12-llm-era-methods)
        -   [Literature Search and Curation](#121-literature-search-and-curation)
        -   [Knowledge Retrieval and Summarization](#122-knowledge-retrieval-and-summarization)
    -   [Evaluation](#13-evaluation)
-   [💡 Idea Generation](#-2-idea-generation)
    -   [Methods](#21-methods)
    -   [Evaluation](#22-evaluation)
-   [🔬 Verification and Falsification](#-3-verification-and-falsification)
    -   [Methods](#31-methods)
    -   [Evaluation](#32-evaluation)
-   [⚖️ Review System](#-4-review-system)
    -   [Methods](#41-methods)
    -   [Evaluation Benchmarks](#42-evaluation-benchmarks)
-   [📈 Evolution](#-5-evolution)
    -   [Methods](#51-methods)
        -   [Dynamic Planning](#511-dynamic-planning)
        -   [Autonomous Learning](#512-autonomous-learning)
- [📜 Survey](#-Survey)
- [🏆 Benchmarks](#-benchmarks)
- [🌐 Community](#-community)
    - [📅 Upcoming Events](#upcoming-events)
    - [💬 Discussion Forums](#discussion-forums)
- [👋 Contributing](#-contributing)
- [📜 License](#-license)

# ⚙️ Core Components

<!-- omit in toc -->
## Research Automation Stack

The fundamental layers where AI is impacting the research lifecycle:

| Layer                 | Key Papers Category Alignment | Example Technologies / Concepts                                                                      | Description                                                                                                                                  |
| :-------------------- | :---------------------------- | :--------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------- |
| **Knowledge Building** | Knowledge Building            | [Elicit](https://elicit.org), [Consensus](https://consensus.app), SciSpace, Semantic Scholar, KG Tools | AI tools for literature discovery, summarization, knowledge graph construction, understanding figures/tables, and synthesizing existing work. |
| **Idea Generation**   | Idea Generation               | Hypothesis generators (e.g., based on KGs, LLMs), Agent-based exploration (e.g., [ResearchAgent](https://github.com/JinheonBaek/ResearchAgent)) | AI assisting in formulating novel research questions, hypotheses, identifying gaps, and exploring new research directions.                 |
| **Experimentation**   | Experiment Execution          | Autonomous Labs (e.g., [CoScientist](https://github.com/gomesgroup/coscientist)), [AlphaFold](https://alphafold.ebi.ac.uk), AutoML, Agent-driven simulation | AI aiding in experimental design, automating experiment execution (physical or simulated), data collection, analysis, and interpretation. |
| **Paper Writing**     | Paper Writing                 | [Overleaf AI](https://www.overleaf.com), [PaperRobot](https://github.com/EagleW/PaperRobot), [CycleResearcher](https://github.com/zhu-minjun/Researcher),Citation/Figure generators | AI assistance in drafting sections (abstract, related work), generating figures/tables, citation management, editing, and formatting.     |
| **Paper Review**       | Paper Review                   | Reviewer assignment tools, Argument mining, Review generation aids (e.g., [ReviewRobot](https://github.com/EagleW/ReviewRobot), [CycleResearcher](https://github.com/zhu-minjun/Researcher))            | AI tools supporting reviewer assignment, review quality assessment, argument extraction, and potentially review generation/summarization.      |

<!-- omit in toc -->
## Emerging Capabilities

Exciting frontiers pushing the boundaries of AI in research:

-   **End-to-End Research Agents:** AI systems attempting to automate multiple stages of the research cycle autonomously (e.g., The AI Scientist, AutoSurvey).
-   **Human-AI Collaboration Patterns:** Novel workflows and interfaces integrating AI assistance seamlessly into researcher tasks for enhanced productivity and creativity.
-   **AI for Reproducibility & Validation:** Tools focused on verifying scientific claims, attempting automated replication of results, and ensuring overall scientific rigor.



# 📰 Latest Buzz / News

Recent news, announcements, and noteworthy updates circulating in the AI researcher ecosystem.

* **Launch | Airaxiv. Your Gateway to AI-Generated Research!**
    *   *Source:* Airaxiv Website
    *   *Link:* [Website](https://airaxiv.com/)

* **Paper | Using generative AI, researchers design compounds that can kill drug-resistant bacteria**
    *   *Source:* MIT News (Aug 2025)
    *   *Link:* [Article](https://news.mit.edu/2025/using-generative-ai-researchers-design-compounds-kill-drug-resistant-bacteria-0814)

* **Survey | How Far Are AI Scientists from Changing the World?**
    * *Source:* arXiv Publication (Jul 2025)
    * *Link:* [Paper](https://arxiv.org/pdf/2507.23276)

* **Paper | Autonomous Scientific Discovery Through Hierarchical AI Scientist Systems**
    *   *Source:* Preprints.org Publication (Jul 2025)
    *   *Link:* [Paper](https://www.preprints.org/manuscript/202507.1951/v1)

* **Position Paper | AI Scientists Fail Without Strong Implementation Capability**
    * *Source:* arXiv Publication (Jun 2025)
    * *Link:* [Paper](https://arxiv.org/pdf/2506.01372)

* **Sakana AI Labs Update on AI Scientist**
    * *Source:* X (Twitter) Post (Mar 2025)
    * *Link:* [Tweet](https://x.com/SakanaAILabs/status/1899646987781501181)

* **Meet CARL: The First AI System To Produce Academically Peer-Reviewed Research**
    * *Source:* AutoScience AI Blog Post (Mar 2025)
    * *Link:* [Blog Post](https://www.autoscience.ai/blog/meet-carl-the-first-ai-system-to-produce-academically-peer-reviewed-research)



# 🔥 Featured Projects

<!-- omit in toc -->
## Open Source Tools

| Project | Description | Stars | Link |
|---------|-------------|-------|------|
| [CycleResearcher&DeepReviewr](https://github.com/zhu-minjun/Researcher) | Improving Automated Research via Automated Review. | ![](https://img.shields.io/github/stars/zhu-minjun/Researcher?style=social) | [GitHub](https://github.com/zhu-minjun/Researcher) |
| [AutoSurvey](https://github.com/AutoSurveys/AutoSurvey) | Large language models automatically writing surveys. | ![](https://img.shields.io/github/stars/AutoSurveys/AutoSurvey?style=social) | [GitHub](https://github.com/AutoSurveys/AutoSurvey) |
| [AI-Scientis](https://github.com/SakanaAI/AI-Scientist) | Towards Fully Automated Open-Ended Scientific Discovery. | ![](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=social) | [GitHub](https://github.com/SakanaAI/AI-Scientist) |
| [Galactica](https://github.com/paperswithcode/galai) | Meta's scientific language model for research tasks. | ![](https://img.shields.io/github/stars/paperswithcode/galai?style=social) | [GitHub](https://github.com/paperswithcode/galai) |
| [SciKit-LLM](https://github.com/iryna-kondr/scikit-llm) | Integration of LLMs into scientific workflows. | ![](https://img.shields.io/github/stars/iryna-kondr/scikit-llm?style=social) | [GitHub](https://github.com/iryna-kondr/scikit-llm) |
| [CoScientist](https://github.com/gomesgroup/coscientist) | Autonomous chemical research with LLMs. | ![](https://img.shields.io/github/stars/gomesgroup/coscientist?style=social) | [GitHub](https://github.com/gomesgroup/coscientist) |
| [PaperRobot](https://github.com/EagleW/PaperRobot) | Incremental Draft Generation of Scientific Ideas. | ![](https://img.shields.io/github/stars/EagleW/PaperRobot?style=social) | [GitHub](https://github.com/EagleW/PaperRobot) |


<!-- omit in toc -->
## Commercial Platforms

*   [AI Researcher](https://ai-researcher.net/)
*   [AiraXiv](https://airaxiv.com/)
*   [Elicit](https://elicit.org/)
*   [Consensus](https://consensus.app/)
*   [SciSpace](https://scispace.com/)
*   [Wolfram Research Assistant](https://www.wolfram.com/research-assistant/)
*   [IBM Watson Discovery](https://www.ibm.com/cloud/watson-discovery)
*   [Overleaf AI](https://www.overleaf.com)


# 📚 1. Knowledge Acquisition

### 1.1. Pre-LLM Era Methods

-   A dataset of peer reviews (peerread): Collection, insights and nlp applications [[Paper]](https://arxiv.org/abs/1804.09635) ![](https://img.shields.io/badge/arXiv-2018.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1804.09635)
-   Biobert: a pre-trained biomedical language representation model for biomedical text mining [[Paper]](https://arxiv.org/abs/1901.08746) ![](https://img.shields.io/badge/arXiv-2019.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1901.08746)
-   Scibert: Pretrained language model for scientific text [[Paper]](https://arxiv.org/abs/1903.10676) ![](https://img.shields.io/badge/arXiv-2019.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1903.10676)
-   Probing biomedical embeddings from language models [[Paper]](https://arxiv.org/abs/1904.02181) ![](https://img.shields.io/badge/arXiv-2019.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1904.02181)
-   Clinicalbert: Modeling clinical notes and predicting hospital readmission [[Paper]](https://arxiv.org/abs/1904.05342) ![](https://img.shields.io/badge/arXiv-2019.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1904.05342)
-   Identification of tasks, datasets, evaluation metrics, and numeric scores for scientific leaderboards construction [[Paper]](https://arxiv.org/abs/1906.09317) ![](https://img.shields.io/badge/arXiv-2019.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1906.09317)
-   AxCell: Automatic extraction of results from machine learning papers [[Paper]](https://arxiv.org/abs/2004.14356) ![](https://img.shields.io/badge/arXiv-2020.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2004.14356)
-   TLDR: Extreme summarization of scientific documents [[Paper]](https://arxiv.org/abs/2004.15011) ![](https://img.shields.io/badge/arXiv-2020.04-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=V28j2iGfig)
-   Domain-specific language model pretraining for biomedical natural language processing [[Paper]](https://arxiv.org/abs/2007.15779) ![](https://img.shields.io/badge/arXiv-2020.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2007.15779)
-   BioMegatron: Larger biomedical domain language model [[Paper]](https://arxiv.org/abs/2010.06060) ![](https://img.shields.io/badge/arXiv-2020.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2010.06060)
-   BioM-transformers: Building large biomedical language models with BERT, ALBERT and ELECTRA [[Paper]](https://aclanthology.org/2021.bionlp-1.24/) [No Review]
-   Towards table-to-text generation with numerical reasoning [[Paper]](https://aclanthology.org/2021.acl-long.115/) [No Review]
-   Scigen: a dataset for reasoning-aware text generation from scientific tables [[Paper]](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/149e9677a5989fd342ae44213df68868-Paper-round2.pdf) [No Review]
-   MatSciBERT: A materials domain language model for text mining and information extraction [[Paper]](https://arxiv.org/abs/2109.15290) ![](https://img.shields.io/badge/arXiv-2021.09-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=j5oGf-2H2k)
-   The diminishing returns of masked language models to science [[Paper]](https://arxiv.org/abs/2205.11342) ![](https://img.shields.io/badge/arXiv-2022.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2205.11342)
-   TELIN: Table entity LINker for extracting leaderboards from machine learning publications [[Paper]](https://aclanthology.org/2022.wiesp-1.3/) [No Review]
-   Comlittee: Literature discovery with personal elected author committees [[Paper]](https://arxiv.org/abs/2302.06780) ![](https://img.shields.io/badge/arXiv-2023.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2302.06780)
-   Orkg-leaderboards: a systematic workflow for mining leaderboards as a knowledge graph [[Paper]](https://arxiv.org/abs/2305.11068) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2305.11068)
-   All data on the table: Novel dataset and benchmark for cross-modality scientific information extraction [[Paper]](https://arxiv.org/abs/2311.08189) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2311.08189)

### 1.2. LLM Era Methods

#### 1.2.1. Literature Search and Curation

-   Paperqa: Retrieval-augmented generative agent for scientific research [[Paper]](https://arxiv.org/abs/2312.07559) ![](https://img.shields.io/badge/arXiv-2023.12-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=8s8K26n203)
-   Retrieval-augmented generation for large language models: A survey [[Paper]](https://arxiv.org/abs/2312.10997) ![](https://img.shields.io/badge/arXiv-2023.12-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2312.10997)
-   Paperweaver: Enriching topical paper alerts by contextualizing recommended papers with user-collected papers [[Paper]](https://arxiv.org/abs/2403.02939) ![](https://img.shields.io/badge/arXiv-2024.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2403.02939)
-   The ai scientist: Towards fully automated open-ended scientific discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=6s5uXNWGIh)
-   Language agents achieve superhuman synthesis of scientific knowledge [[Paper]](https://arxiv.org/abs/2409.13740) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2409.13740)
-   Agent laboratory: Using Ilm agents as research assistants [[Paper]](https://arxiv.org/abs/2501.04227) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2501.04227)
-   Pasa: An Ilm agent for comprehensive academic paper search [[Paper]](https://arxiv.org/abs/2501.10120) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2501.10120)
-   Evaluating sakana's ai scientist for autonomous research: Wishful thinking or an emerging reality towards' artificial research intelligence' (ari)? [[Paper]](https://arxiv.org/abs/2502.14297) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.14297)
-   Towards an ai co-scientist [[Paper]](https://arxiv.org/abs/2502.18864) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=jHOmjP9L3u)
-   Dora ai scientist: Multi-agent virtual research team for scientific exploration discovery and automated report generation [[Paper]](https://www.biorxiv.org/content/10.1101/2025.03.06.641840v1) [No Review]
-   Codescientist: End-to-end semi-automated scientific discovery with code-based experimentation [[Paper]](https://arxiv.org/abs/2503.22708) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2503.22708)
-   Ai-researcher: Autonomous scientific innovation [[Paper]](https://arxiv.org/abs/2505.18705) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.18705)

#### 1.2.2. Knowledge Retrieval and Summarization

-   Bigpatent: A large-scale dataset for abstractive and coherent summarization [[Paper]](https://arxiv.org/abs/1906.03741) ![](https://img.shields.io/badge/arXiv-2019.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1906.03741)
-   TLDR: Extreme summarization of scientific documents [[Paper]](https://arxiv.org/abs/2004.15011) ![](https://img.shields.io/badge/arXiv-2020.04-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=V28j2iGfig)
-   X-scitldr: cross-lingual extreme summarization of scholarly documents [[Paper]](https://arxiv.org/abs/2205.15051) ![](https://img.shields.io/badge/arXiv-2022.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2205.15051)
-   Structured information extraction from scientific text with large language models [[Paper]](https://arxiv.org/abs/2212.05238) ![](https://img.shields.io/badge/arXiv-2022.12-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2212.05238)
-   Legobench: Scientific leaderboard generation benchmark [[Paper]](https://arxiv.org/abs/2401.06233) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=1By32y692h)
-   Litllm: A toolkit for scientific literature review [[Paper]](https://arxiv.org/abs/2402.01788) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2402.01788)
-   Data extraction from polymer literature using large language models [[Paper]](https://www.nature.com/articles/s43246-024-00708-9) [No Review]
-   Automated literature review using nlp techniques and Ilm-based retrieval-augmented generation [[Paper]](https://arxiv.org/abs/2411.18583) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2411.18583)
-   Llms for literature review: Are we there yet? [[Paper]](https://arxiv.org/abs/2412.15249) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=heeJqQXKg7)
-   Extracting knowledge from scientific texts on patient-derived cancer models using large language models: algorithm development and validation [[Paper]](https://www.biorxiv.org/content/10.1101/2025.01.28.634527v1.full) [No Review]
-   Lag: Llm agents for leaderboard auto generation on demanding [[Paper]](https://arxiv.org/abs/2502.18209) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=I3s5C9252g)
-   Can llms help uncover insights about llms? a large-scale, evolving literature analysis of frontier Ilms [[Paper]](https://arxiv.org/abs/2502.18791) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.18791)
-   Agentrxiv: Towards collaborative autonomous research [[Paper]](https://arxiv.org/abs/2503.18102) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=vF28hCUDG6)
-   How Deep Do Large Language Models Internalize Scientific Literature and Citation Practices? [[Paper]](https://arxiv.org/abs/2504.02767) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.02767)
-   SafeScientist: Toward Risk-Aware Scientific Discoveries by LLM Agents [[Paper]](https://arxiv.org/abs/2505.23559) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.23559)
-   The Budget AI Researcher and the Power of RAG Chains [[Paper]](https://arxiv.org/abs/2506.12317) ![](https://img.shields.io/badge/arXiv-2025.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2506.12317)

### 1.3. Evaluation

-   TLDR: Extreme summarization of scientific documents [[Paper]](https://arxiv.org/abs/2004.15011) ![](https://img.shields.io/badge/arXiv-2020.04-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=V28j2iGfig)
-   X-scitldr: cross-lingual extreme summarization of scholarly documents [[Paper]](https://arxiv.org/abs/2205.15051) ![](https://img.shields.io/badge/arXiv-2022.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2205.15051)
-   Appraising the potential uses and harms of llms for medical systematic reviews [[Paper]](https://arxiv.org/abs/2305.11828) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2305.11828)
-   Citeme: Can language models accurately cite scientific claims? [[Paper]](https://arxiv.org/abs/2407.12861) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=03Y7Z3L9d3)
-   CHIME: LLM-assisted hierarchical organization of scientific studies for literature review support [[Paper]](https://arxiv.org/abs/2407.16148) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=FdVXgSJhvz)
-   Litsearch: A retrieval benchmark for scientific literature search [[Paper]](https://arxiv.org/abs/2407.18940) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2407.18940)
-   Llms for literature review: Are we there yet? [[Paper]](https://arxiv.org/abs/2412.15249) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=heeJqQXKg7)

---

# 💡 2. Idea Generation

### 2.1. Methods

-   Unsupervised word embeddings capture latent knowledge from materials science literature [[Paper]](https://www.nature.com/articles/s41586-019-1335-8) [No Review]
-   Paperrobot: Incremental draft generation of scientific ideas [[Paper]](https://arxiv.org/abs/1905.07870) ![](https://img.shields.io/badge/arXiv-2019.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1905.07870)
-   Exploring the limits of transfer learning with a unified text-to-text transformer [[Paper]](https://arxiv.org/abs/1910.10683) ![](https://img.shields.io/badge/arXiv-2019.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1910.10683)
-   Agatha: automatic graph mining and transformer based hypothesis generation approach [[Paper]](https://arxiv.org/abs/2002.05635) ![](https://img.shields.io/badge/arXiv-2020.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2002.05635)
-   Literature-based discovery beyond the abc paradigm: a contrastive approach [[Paper]](https://www.biorxiv.org/content/10.1101/2021.09.22.461375v1) [No Review]
-   Chain-of-thought prompting elicits reasoning in large language models [[Paper]](https://arxiv.org/abs/2201.11903) ![](https://img.shields.io/badge/arXiv-2022.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2201.11903)
-   Knowledge integration and decision support for accelerated discovery of antibiotic resistance genes [[Paper]](https://www.nature.com/articles/s41467-022-29993-z) [No Review]
-   Reflexion: Language agents with verbal reinforcement learning [[Paper]](https://arxiv.org/abs/2303.11366) ![](https://img.shields.io/badge/arXiv-2023.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2303.11366)
-   SciMON: Scientific inspiration machines optimized for novelty [[Paper]](https://arxiv.org/abs/2305.14259) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2305.14259)
-   Large language models for automated open-domain scientific hypotheses discovery [[Paper]](https://arxiv.org/abs/2309.02726) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2309.02726)
-   Large language models are zero shot hypothesis proposers [[Paper]](https://arxiv.org/abs/2311.05965) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2311.05965)
-   The ai scientist: Towards fully automated open-ended scientific discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=6s5uXNWGIh)
-   Can llms generate novel research ideas? a large-scale human study with 100+ nlp researchers [[Paper]](https://arxiv.org/abs/2409.04109) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2409.04109)
-   MOOSE-chem: Large language models for rediscovering unseen chemistry scientific hypotheses [[Paper]](https://arxiv.org/abs/2410.07076) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2410.07076)
-   Chain of ideas: Revolutionizing research via novel idea development with Ilm agents [[Paper]](https://arxiv.org/abs/2410.13185) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=s5OQz12A2z)
-   Nova: An iterative planning and search approach to enhance novelty and diversity of Ilm generated ideas [[Paper]](https://arxiv.org/abs/2410.14255) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2410.14255)
-   Cycleresearcher: Improving automated research via automated review [[Paper]](https://arxiv.org/abs/2411.00816) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2411.00816)
-   Aigs: Generating science from ai-powered automated falsification [[Paper]](https://arxiv.org/abs/2411.11910) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2411.11910)
-   Towards an ai co-scientist [[Paper]](https://arxiv.org/abs/2502.18864) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=jHOmjP9L3u)
-   Codescientist: End-to-end semi-automated scientific discovery with code-based experimentation [[Paper]](https://arxiv.org/abs/2503.22708) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2503.22708)
-   The ai scientist-v2: Workshop-level automated scientific discovery via agentic tree search [[Paper]](https://arxiv.org/abs/2504.08066) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=6z4YKr0GK6)
-   Spark: A System for Scientifically Creative Idea Generation [[Paper]](https://arxiv.org/abs/2504.20090) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.20090)
-   Sparks of Science: Hypothesis Generation Using Structured Paper Data [[Paper]](https://arxiv.org/abs/2504.12976) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.12976)
-   Scientific Hypothesis Generation and Validation: Methods, Datasets, and Future Directions [[Paper]](https://arxiv.org/abs/2505.04651) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.04651)
-   Dynamic Knowledge Exchange and Dual-diversity Review: Concisely Unleashing the Potential of a Multi-Agent Research Team [[Paper]](https://arxiv.org/abs/2506.18348) ![](https://img.shields.io/badge/arXiv-2025.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2506.18348)
-   AlphaEvolve: A coding agent for scientific and algorithmic discovery [[Paper]](https://arxiv.org/abs/2506.13131) ![](https://img.shields.io/badge/arXiv-2025.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2506.13131)

### 2.2. Evaluation

-   Bleu: a method for automatic evaluation of machine translation [[Paper]](https://aclanthology.org/P02-1040/) [No Review]
-   Rouge: A package for automatic evaluation of summaries [[Paper]](https://aclanthology.org/W04-1013/) [No Review]
-   The perils of using mechanical turk to evaluate open-ended text generation [[Paper]](https://arxiv.org/abs/2109.06835) ![](https://img.shields.io/badge/arXiv-2021.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2109.06835)
-   Longeval: Guidelines for human evaluation of faithfulness in long-form summarization [[Paper]](https://arxiv.org/abs/2301.13298) ![](https://img.shields.io/badge/arXiv-2023.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2301.13298)
-   SciMON: Scientific inspiration machines optimized for novelty [[Paper]](https://arxiv.org/abs/2305.14259) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2305.14259)
-   Judging llm-as-a-judge with mt-bench and chatbot arena [[Paper]](https://arxiv.org/abs/2306.05685) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2306.05685)
-   Large language models for automated open-domain scientific hypotheses discovery [[Paper]](https://arxiv.org/abs/2309.02726) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2309.02726)
-   Detecting pretraining data from large language models [[Paper]](https://arxiv.org/abs/2310.16789) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2310.16789)
-   Large language models are zero shot hypothesis proposers [[Paper]](https://arxiv.org/abs/2311.05965) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2311.05965)
-   Exploring scientific hypothesis generation with mamba [[Paper]](https://aclanthology.org/2024.nlp4science-1.17/) [No Review]
-   Can llms generate novel research ideas? a large-scale human study with 100+ nlp researchers [[Paper]](https://arxiv.org/abs/2409.04109) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2409.04109)
-   MOOSE-chem: Large language models for rediscovering unseen chemistry scientific hypotheses [[Paper]](https://arxiv.org/abs/2410.07076) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2410.07076)
-   Chain of ideas: Revolutionizing research via novel idea development with Ilm agents [[Paper]](https://arxiv.org/abs/2410.13185) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=s5OQz12A2z)
-   Nova: An iterative planning and search approach to enhance novelty and diversity of Ilm generated ideas [[Paper]](https://arxiv.org/abs/2410.14255) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2410.14255)
-   An empirical analysis of uncertainty in large language model evaluations [[Paper]](https://arxiv.org/abs/2502.10709) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.10709)
-   Dynamic Knowledge Exchange and Dual-diversity Review: Concisely Unleashing the Potential of a Multi-Agent Research Team [[Paper]](https://arxiv.org/abs/2506.18348) ![](https://img.shields.io/badge/arXiv-2025.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2506.18348)
-   HypoBench: Towards Systematic and Principled Benchmarking for Hypothesis Generation [[Paper]](https://arxiv.org/abs/2504.11524) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.11524)
-   AI Idea Bench 2025: AI Research Idea Generation Benchmark [[Paper]](https://arxiv.org/abs/2504.14191) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.14191)
-   MegaScience: Pushing the Frontiers of Post-Training Datasets for Science Reasoning [[Paper]](https://arxiv.org/abs/2507.16812) ![](https://img.shields.io/badge/arXiv-2025.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2507.16812)

---

# 🔬 3. Verification and Falsification

-   Highly accurate protein structure prediction with alphafold [[Paper]](https://www.nature.com/articles/s41586-021-03819-2) [No Review]
-   The ai scientist: Towards fully automated open-ended scientific discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=6s5uXNWGIh)

### 3.1. Methods

-   Figureqa: An annotated figure dataset for visual reasoning [[Paper]](https://arxiv.org/abs/1710.07300) ![](https://img.shields.io/badge/arXiv-2017.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1710.07300)
-   Reviewergpt? an exploratory study on using large language models for paper reviewing [[Paper]](https://arxiv.org/abs/2306.00622) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2306.00622)
-   Swe-bench: Can language models resolve real-world github issues? [[Paper]](https://arxiv.org/abs/2310.06770) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=sE2O93W37I)
-   Teaching code llms to use autocompletion tools in repository-level code generation [[Paper]](https://arxiv.org/abs/2401.06391) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2401.06391)
-   Codeagent: Enhancing code generation with tool-integrated agent systems for real-world repo-level coding challenges [[Paper]](https://arxiv.org/abs/2401.07339) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2401.07339)
-   Multimodal arxiv: A dataset for improving scientific comprehension of large vision-language models [[Paper]](https://arxiv.org/abs/2403.00231) ![](https://img.shields.io/badge/arXiv-2024.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2403.00231)
-   Iterative refinement of project-level code context for precise code generation with compiler feedback [[Paper]](https://arxiv.org/abs/2403.16792) ![](https://img.shields.io/badge/arXiv-2024.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2403.16792)
-   Enhancing repository-level code generation with integrated contextual information [[Paper]](https://arxiv.org/abs/2406.03283) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.03283)
-   MMSci: A dataset for graduate-level multi-discipline multimodal scientific understanding [[Paper]](https://arxiv.org/abs/2407.04903) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2407.04903)
-   Scicode: A research coding benchmark curated by scientists [[Paper]](https://arxiv.org/abs/2407.13168) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=u84U8L82s7)
-   Mlr-copilot: Autonomous machine learning research based on large language models agents [[Paper]](https://arxiv.org/abs/2408.14033) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2408.14033)
-   Dsbench: How far are data science agents from becoming data science experts? [[Paper]](https://arxiv.org/abs/2409.07703) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2409.07703)
-   Scienceagentbench: Toward rigorous assessment of language agents for data-driven scientific discovery [[Paper]](https://arxiv.org/abs/2410.05080) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=0A812iG6Gg)
-   Repograph: Enhancing ai software engineering with repository-level code graph [[Paper]](https://arxiv.org/abs/2410.14684) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=2o2k13217G)
-   Llm-ref: Enhancing reference handling in technical writing with large language models [[Paper]](https://arxiv.org/abs/2411.00294) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2411.00294)
-   Mcx-llm: an experiment in bridging natural language problem descriptions with quantitative scientific simulations [[Paper]](https://www.researchgate.net/publication/381723924_MCX-LLM_an_experiment_in_bridging_natural_language_problem_descriptions_with_quantitative_scientific_simulations) [No Review]
-   Ai becomes a masterbrain scientist [[Paper]](https://www.biorxiv.org/content/10.1101/2023.04.19.537579v2.full) [No Review]
-   Zochi technical report [[Paper]](https://www.intology.ai/blog/zochi-tech-report) [No Review]
-   Aide: Ai-driven exploration in the space of code [[Paper]](https://arxiv.org/abs/2502.13138) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.13138)
-   Repocoder: Repository-level code completion through iterative retrieval and generation [[Paper]](https://arxiv.org/abs/2303.12570) ![](https://img.shields.io/badge/arXiv-2023.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2303.12570)
-   The ai scientist-v2: Workshop-level automated scientific discovery via agentic tree search [[Paper]](https://arxiv.org/abs/2504.08066) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=6z4YKr0GK6)
-   Autop2c: An Ilm-based agent framework for code repository generation from multimodal content in academic papers [[Paper]](https://arxiv.org/abs/2504.20115) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.20115)
-   Biomni: A general-purpose biomedical ai agent [[Paper]](https://www.biorxiv.org/content/10.1101/2025.05.30.656746v1) [No Review]
-   ResearchCodeAgent: An LLM Multi-Agent System for Automated Codification of Research Methodologies [[Paper]](https://arxiv.org/abs/2504.20117) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.20117)
-   Scientific Hypothesis Generation and Validation: Methods, Datasets, and Future Directions [[Paper]](https://arxiv.org/abs/2505.04651) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.04651)

### 3.2. Evaluation

-   Core-bench: Fostering the credibility of published research through a computational reproducibility agent benchmark [[Paper]](https://arxiv.org/abs/2409.11363) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2409.11363)
-   Mle-bench: Evaluating machine learning agents on machine learning engineering [[Paper]](https://arxiv.org/abs/2410.07095) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=3k74sH29l2)
-   Ml-dev-bench: Comparative analysis of ai agents on ml development workflows [[Paper]](https://arxiv.org/abs/2502.00964) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.00964)
-   Scireplicate-bench: Benchmarking llms in agent-driven algorithmic reproduction from research papers [[Paper]](https://arxiv.org/abs/2504.00255) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.00255)
-   Paperbench: Evaluating ai's ability to replicate ai research [[Paper]](https://arxiv.org/abs/2504.01848) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.01848)
-   MLRC-Bench: Can Language Agents Solve Machine Learning Research Challenges? [[Paper]](https://arxiv.org/abs/2504.09702) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2504.09702)
-   ScienceBoard: Evaluating Multimodal Autonomous Agents in Realistic Scientific Workflows [[Paper]](https://arxiv.org/abs/2505.19897) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.19897)
-   Benchmarking AI scientists in omics data-driven biological research [[Paper]](https://arxiv.org/abs/2505.08341) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.08341)
-   EXP-Bench: Can AI Conduct AI Research Experiments? [[Paper]](https://arxiv.org/abs/2505.24785) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.24785)

---

# ⚖️ 4. Review System

-   The toronto paper matching system: an automated paper-reviewer assignment system [[Paper]](https://www.semanticscholar.org/paper/The-Toronto-Paper-Matching-System%3A-An-automated-Charlin-Zemel/d5fa5bd2ae89296acbfd9766f50c909f2c42effe) [No Review]
-   Peerreview4all: Fair and accurate reviewer assignment in peer review [[Paper]](https://arxiv.org/abs/1806.06237) ![](https://img.shields.io/badge/arXiv-2018.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1806.06237)
-   Reviewrobot: Explainable paper review generation based on knowledge synthesis [[Paper]](https://arxiv.org/abs/2010.06119) ![](https://img.shields.io/badge/arXiv-2020.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2010.06119)
-   Towards fair, equitable, and efficient peer review [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17865) [No Review]
-   Investigating fairness disparities in peer review: A language model enhanced approach [[Paper]](https://arxiv.org/abs/2211.06398) ![](https://img.shields.io/badge/arXiv-2022.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2211.06398)
-   PlagBench: Exploring the duality of large language models in plagiarism generation and detection [[Paper]](https://arxiv.org/abs/2406.16288) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.16288)
-   Usefulness of llms as an author checklist assistant for scientific papers: Neurips'24 experiment [[Paper]](https://arxiv.org/abs/2411.03417) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2411.03417)
-   Openreviewer: A specialized large language model for generating critical scientific paper reviews [[Paper]](https://arxiv.org/abs/2412.11948) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=qY2XpL24sY)
-   Deepreview: Improving llm-based paper review with human-like deep thinking process [[Paper]](https://arxiv.org/abs/2503.08569) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=5J9Zg2o0s9)
-   Automated research review support using machine learning, large language models, and natural language processing [[Paper]](https://www.mdpi.com/2079-9292/14/2/256) [No Review]

### 4.1. Methods

-   Does my rebuttal matter? insights from a major nlp conference [[Paper]](https://arxiv.org/abs/1903.11367) ![](https://img.shields.io/badge/arXiv-2019.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/1903.11367)
-   Matching papers and reviewers at large conferences [[Paper]](https://arxiv.org/abs/2202.12273) ![](https://img.shields.io/badge/arXiv-2022.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2202.12273)
-   Has the machine learning review process become more arbitrary as the field has grown? the neurips 2021 consistency experiment [[Paper]](https://arxiv.org/abs/2306.03262) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2306.03262)
-   Marg: Multi-agent review generation for scientific papers [[Paper]](https://arxiv.org/abs/2401.04259) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2401.04259)
-   Zero-shot generative large language models for systematic review screening automation [[Paper]](https://arxiv.org/abs/2401.06320) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2401.06320)
-   Reviewer2: Optimizing review generation through prompt generation [[Paper]](https://arxiv.org/abs/2402.10886) ![](https://img.shields.io/badge/arXiv-2024.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2402.10886)
-   Prompting is all you need: Llms for systematic review screening [[Paper]](https://www.medrxiv.org/content/10.1101/2024.06.01.24308323v1.full) [No Review]
-   Autosurvey: Large language models can automatically write surveys [[Paper]](https://arxiv.org/abs/2406.10252) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.10252)
-   Relevai-reviewer: A benchmark on ai reviewers for survey paper relevance [[Paper]](https://arxiv.org/abs/2406.10294) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.10294)
-   AgentReview: Exploring peer review dynamics with LLM agents [[Paper]](https://arxiv.org/abs/2406.12708) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=hR2l3iQ931)
-   A systematic survey and critical review on evaluating large language models: Challenges, limitations, and recommendations [[Paper]](https://arxiv.org/abs/2407.04069) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2407.04069)
-   Review-llm: Harnessing large language models for personalized review generation [[Paper]](https://arxiv.org/abs/2407.07487) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2407.07487)
-   Cutting through the clutter: The potential of llms for efficient filtration in systematic literature reviews [[Paper]](https://arxiv.org/abs/2407.10652) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2407.10652)
-   Automated review generation method based on large language models [[Paper]](https://arxiv.org/abs/2407.20906) ![](https://img.shields.io/badge/arXiv-2024.07-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2407.20906)
-   Usefulness of Ilms as an author checklist assistant for scientific papers: Neurips'24 experiment [[Paper]](https://arxiv.org/abs/2411.03417) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2411.03417)
-   Are we there yet? revealing the risks of utilizing large language models in scholarly peer review [[Paper]](https://arxiv.org/abs/2412.01708) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2412.01708)
-   Metawriter: Exploring the potential and perils of ai writing support in scientific peer review [[Paper]](https://dl.acm.org/doi/10.1145/3637371) [No Review]
-   Surveyx: Academic survey automation via large language models [[Paper]](https://arxiv.org/abs/2502.14776) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.14776)
-   Reviewagents: Bridging the gap between human and ai-generated paper reviews [[Paper]](https://arxiv.org/abs/2503.08506) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=A34L9a9H29)
-   Lgar: Zero-shot llm-guided neural ranking for abstract screening in systematic literature reviews [[Paper]](https://arxiv.org/abs/2505.24757) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.24757)
-   Reviewriter: Ai-generated instructions for peer review writing [[Paper]](https://arxiv.org/abs/2506.04423) ![](https://img.shields.io/badge/arXiv-2025.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2506.04423)
-   The illusion of thinking: Understanding the strengths and limitations of reasoning models via the lens of problem complexity [[Paper]](https://arxiv.org/abs/2506.06941) ![](https://img.shields.io/badge/arXiv-2025.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2506.06941)

### 4.2. Evaluation Benchmarks

-   Can we automate scientific reviewing? [[Paper]](https://arxiv.org/abs/2102.00176) ![](https://img.shields.io/badge/arXiv-2021.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2102.00176)
-   Peersum: a peer review dataset for abstractive multi-document summarization [[Paper]](https://arxiv.org/abs/2203.01769) ![](https://img.shields.io/badge/arXiv-2022.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2203.01769)
-   React: A re view comment dataset for act ionability (and more) [[Paper]](https://arxiv.org/abs/2210.00443) ![](https://img.shields.io/badge/arXiv-2022.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2210.00443)
-   Moprd: A multidisciplinary open peer review dataset [[Paper]](https://arxiv.org/abs/2212.04972) ![](https://img.shields.io/badge/arXiv-2022.12-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2212.04972)
-   Scientific opinion summarization: Paper meta-review generation dataset, methods, and evaluation [[Paper]](https://arxiv.org/abs/2305.14647) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2305.14647)
-   Exploring jiu-jitsu argumentation for writing peer review rebuttals [[Paper]](https://arxiv.org/abs/2311.03998) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2311.03998)
-   Automatic analysis of substantiation in scientific peer reviews [[Paper]](https://arxiv.org/abs/2311.11967) ![](https://img.shields.io/badge/arXiv-2023.11-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2311.11967)
-   Politepeer: does peer review hurt? a dataset to gauge politeness intensity in the peer reviews [[Paper]](https://dl.acm.org/doi/10.1007/s10579-023-09662-3) [No Review]
-   Is Ilm a reliable reviewer? a comprehensive evaluation of Ilm on automatic paper reviewing tasks [[Paper]](https://aclanthology.org/2024.lrec-main.816/) [No Review]
-   Automated focused feedback generation for scientific writing assistance [[Paper]](https://arxiv.org/abs/2405.20477) ![](https://img.shields.io/badge/arXiv-2024.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2405.20477)
-   Peer review as a multi-turn and long-context dialogue with role-based interactions [[Paper]](https://arxiv.org/abs/2406.05688) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.05688)
-   Relevai-reviewer: A benchmark on ai reviewers for survey paper relevance [[Paper]](https://arxiv.org/abs/2406.10294) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.10294)
-   Aaar-1.0: Assessing ai's potential to assist research [[Paper]](https://arxiv.org/abs/2410.22394) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2410.22394)
-   Large language models for automated scholarly paper review: A survey [[Paper]](https://arxiv.org/abs/2501.10326) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2501.10326)
-   Peerqa: A scientific question answering dataset from peer reviews [[Paper]](https://arxiv.org/abs/2502.13668) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.13668)
-   Is your paper being reviewed by an llm? a new benchmark dataset and approach for detecting ai text in peer review [[Paper]](https://arxiv.org/abs/2502.19614) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2502.19614)
-   Automatic evaluation metrics for artificially generated scientific research [[Paper]](https://arxiv.org/abs/2503.05712) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2503.05712)

---

# 📈 5. Evolution

### 5.1. Methods

#### 5.1.1. Dynamic Planning

-   Discoveryworld: A virtual environment for developing and evaluating automated scientific discovery agents [[Paper]](https://arxiv.org/abs/2406.06769) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.06769)
-   Dolphin: Closed-loop open-ended auto-research through thinking, practice, and feedback [[Paper]](https://arxiv.org/abs/2501.03916) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2501.03916)
-   The ai scientist-v2: Workshop-level automated scientific discovery via agentic tree search [[Paper]](https://arxiv.org/abs/2504.08066) ![](https://img.shields.io/badge/arXiv-2025.04-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=6z4YKr0GK6)
-   Zochi technical report [[Paper]](https://www.intology.ai/blog/zochi-tech-report) [No Review]

#### 5.1.2. Autonomous Learning

-   Star: Bootstrapping reasoning with reasoning [[Paper]](https://arxiv.org/abs/2203.14465) ![](https://img.shields.io/badge/arXiv-2022.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2203.14465)
-   Constitutional ai: Harmlessness from ai feedback [[Paper]](https://arxiv.org/abs/2212.08073) ![](https://img.shields.io/badge/arXiv-2022.12-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2212.08073)
-   Large language models are better reasoners with self-verification [[Paper]](https://arxiv.org/abs/2212.09561) ![](https://img.shields.io/badge/arXiv-2022.12-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2212.09561)
-   Self-refine: Iterative refinement with self-feedback [[Paper]](https://arxiv.org/abs/2303.17651) ![](https://img.shields.io/badge/arXiv-2023.03-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2303.17651)
-   Automatically correcting large language models: Surveying the landscape of diverse automated correction strategies [[Paper]](https://arxiv.org/abs/2308.03188) ![](https://img.shields.io/badge/arXiv-2023.08-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2308.03188)
-   Mathematical discoveries from program search with large language models [[Paper]](https://www.nature.com/articles/s41586-023-06924-6) [No Review]
-   Cycleresearcher: Improving automated research via automated review [[Paper]](https://arxiv.org/abs/2406.18487) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2406.18487)
-   The ai scientist: Towards fully automated open-ended scientific discovery [[Paper]](https://arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=6s5uXNWGIh)
-   Researchtown: Simulator of human research community [[Paper]](https://arxiv.org/abs/2412.17767) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2412.17767)
-   Agentrxiv: Towards collaborative autonomous research [[Paper]](https://arxiv.org/abs/2503.18102) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv) [[Review]](https://openreview.net/forum?id=vF28hCUDG6)
-   Alphaevolve: A coding agent for scientific and algorithmic discovery [[Paper]](https://arxiv.org/abs/2506.13131) ![](https://img.shields.io/badge/arXiv-2025.06-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2506.13131)
-   Scientific Hypothesis Generation and Validation: Methods, Datasets, and Future Directions [[Paper]](https://arxiv.org/abs/2505.04651) ![](https://img.shields.io/badge/arXiv-2025.05-red?logo=arxiv) [[AI Review]](https://ai-researcher.net/abs/2505.04651)

# 📜 Survey

*   Hallucination, reliability, and the role of generative AI in science [[Paper]](https://arxiv.org/abs/2504.08526) [[AI Review]](https://ai-researcher.net/abs/2504.08526)
*   From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery [[Paper]](https://arxiv.org/abs/2505.13259) [[Review]](https://openreview.net/forum?id=8s0mU4Y02o)
*   Are Large Language Models Reliable AI Scientists? Assessing Reverse-Engineering of Black-Box Systems [[Paper]](https://arxiv.org/abs/2505.17968) [[Review]](https://openreview.net/forum?id=x79H3s0mR3)
*   AI Scientists Fail Without Strong Implementation Capability [[Paper]](https://arxiv.org/abs/2506.01372) [[AI Review]](https://ai-researcher.net/abs/2506.01372)
*   Position: Intelligent Science Laboratory Requires the Integration of Cognitive and Embodied AI [[Paper]](https://arxiv.org/abs/2506.19613) [[Review]](https://openreview.net/forum?id=lLa401mPz7)
*   The Singapore Consensus on Global AI Safety Research Priorities [[Paper]](https://arxiv.org/abs/2506.20702) [[Review]](https://openreview.net/forum?id=AAxIs3D2ZZ)
*   Agent4S: The Transformation of Research Paradigms from the Perspective of Large Language Models [[Paper]](https://arxiv.org/abs/2506.23692) [[AI Review]](https://ai-researcher.net/abs/2506.23692)
*   AI4Research: A Survey of Artificial Intelligence for Scientific Research [[Paper]](https://arxiv.org/abs/2507.01903) [[AI Review]](https://ai-researcher.net/abs/2507.01903)

# 🏆 Benchmarks

*   **AI2 Scientific Reasoning Challenge (ARC)** [[Dataset]](https://allenai.org/data/arc)
*   **MLAgentBench** [[Paper]](https://arxiv.org/abs/2310.03302) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv) [[Code](https://github.com/snap-stanford/MLAgentBench/)]
*   **SWE-bench** [[Paper]](https://openreview.net/forum?id=VTF8yNQM66) ![](https://img.shields.io/badge/ICLR-2024-blue) [[Code](https://github.com/swe-bench/SWE-bench)]
*   **ScienceAgentBench** [[Paper]](https://arxiv.org/abs/2410.05080) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv) [[Code](https://github.com/OSU-NLP-Group/ScienceAgentBench)]
*   **DSBench** [[Paper]](https://arxiv.org/abs/2409.07703) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv) [[Code](https://github.com/LiqiangJing/DSBench)]
*   **AAAR-1.0** [[Paper]](https://arxiv.org/abs/2410.22394) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
*   **MLGym** [[Paper]](https://arxiv.org/abs/2502.14499) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv) [[Code](https://github.com/facebookresearch/MLGym)]
*   **PaperBench** [[Paper]](https://cdn.openai.com/papers/22265bac-3191-44e5-b057-7aaacd8e90cd/paperbench.pdf) ![](https://img.shields.io/badge/OpenAI_Report-2025-brown) [[Code](https://github.com/openai/preparedness)]

---


# 🌐 Community

Connect with fellow researchers, share insights, and stay updated!

<!-- omit in toc -->
## 📅 Upcoming Events

We encourage you to get involved! Stay updated on the latest discussions and breakthroughs by joining these community events:

*   **(Upcoming)** **AIResearcher Workshop @ ICLR 2025** 🔥
    *   **Conference:** ![](https://img.shields.io/badge/ICLR-2025-blue)
    *   **Website:** [![Visit Site](https://img.shields.io/badge/Event_Website-blue)](https://ai-researcher.net/social-iclr-2025)

<!-- omit in toc -->
## 💬 Discussion Forums

Join the conversation and exchange ideas in these online communities:

*   **AI Research Discord:** [![Join Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/HeubHd6d)
    *   *An active community for general AI research discussions.*

*   **AI Scientist Research Discussion Group:** [![Platform](https://img.shields.io/badge/WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white)]() <!-- Removed placeholder link -->
    </br>
    <img src="https://raw.githubusercontent.com/ResearAI/Awesome-AI-Scientist/main/img/WeChat%20Group%20QR%20Code.jpg" alt="AI Scientist WeChat Group QR Code" width="150">
    </br>*(Scan QR Code to join. If expired, please contact maintainer via Email: 18856306350@163.com or WeChat: nauhcutnil)*



# 👋 Contributing

We welcome contributions! Please follow this workflow:

1.  **Fork** the repository.
2.  **Create a new branch:** `git checkout -b feature/your-contribution`
3.  **Add or modify resources.** Please try to follow the existing format, including adding conference/journal badges.
4.  **Submit a Pull Request (PR)** with a clear description of your changes.

*For detailed guidelines, please see `CONTRIBUTING.md`.*

# 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
