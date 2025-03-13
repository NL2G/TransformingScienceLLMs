# Transforming Science with Large Language Models

[![arXiv](https://img.shields.io/badge/arXiv-2502.05151-b31b1b?logo=arxiv)](https://arxiv.org/pdf/2502.05151)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()
[![Contribution Welcome](https://img.shields.io/badge/Contributions-welcome-blue)]()

Welcome to the **Transforming Science with Large Language Models** repository! 
This repository is a collection of the most influential papers, AI models, and tools to empower researchers and academics worldwide to conduct their research more efficiently and effectively.

<!-- omit in toc -->
## 👥 Authors

#### [Steffen Eger](steffen.eger@utn.de), [Yong Cao](yong.cao@uni-tuebingen.de), [Jennifer D'Souza](jennifer.dsouza@tib.eu), [Andreas Geiger](a.geiger@uni-tuebingen.de), [Christian Greisinger](christian.greisinger@utn.de), [Stephanie Gross](stephanie.gross@ofai.at), [Yufang Hou](yufang.hou@it-u.at), [Brigitte Krenn](brigitte.krenn@ofai.at), [Anne Lauscher](anne.lauscher@uni-hamburg.de), [Yizhi Li](yizhi.li-2@manchester.ac.uk), [Chenghua Lin](chenghua.lin@manchester.ac.uk), [Nafise Sadat Moosavi](n.s.moosavi@sheffield.ac.uk), [Wei Zhao](wei.zhao@abdn.ac.uk), and [Tristan Miller](Tristan.Miller@umanitoba.ca)

<!-- omit in toc -->
## 📢 Updates

- **2024-01**: Our conference paper, **[AutomaTikZ: Text-Guided Synthesis of Scientific Vector Graphics with TikZ](https://openreview.net/forum?id=v3K5TVP8kZ)** has been accepted at ![](https://img.shields.io/badge/ICLR-2024-blue)
- **2024-09**: Our conference paper, **[DeTikZify: Synthesizing Graphics Programs for Scientific Figures and Sketches with TikZ](https://openreview.net/forum?id=bcVLFQCOjc)** has been accepted at ![](https://img.shields.io/badge/NeurIPS-2024-blue) as a <span style='color: red;'>Spotlight Paper</span>
- **2025-01**: Our conference paper, **[ScImage: How Good Are Multimodal Large Language Models at Scientific Text-to-Image Generation?](https://openreview.net/forum?id=ugyqNEOjoU)** has been accepted at ![](https://img.shields.io/badge/ICLR-2025-blue)
- **2025-02**: Our survey paper, **[Transforming Science with Large Language Models](https://arxiv.org/abs/2502.05151)**, is now available on ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)

<!-- omit in toc -->
## 👀 Introduction

Science is undergoing a transformation with AI-driven tools assisting researchers at every stage of the research cycle.

![image](./Images/overview_figure.png)

Our survey provides a comprehensive overview of LLMs role in scientific workflows, structured around five key areas: search and summarization, experimentation, unimodal and multimodal content generation, and peer review.

For a detailed introduction, please refer to [our survey paper](https://arxiv.org/abs/2502.05151).

<!-- omit in toc -->
## 📌 Table of Contents

- [🔍 Literature Search, Summarization, and Comparison](#literature-search-summarization-and-comparison)
    - [AI-Enhanced Search](#ai-enhanced-search)
    - [Graph-Based](#graph-based)
    - [Paper Chat](#paper-chat)
    - [Recommender](#recommender)
    - [Search Engines](#search-engines)
    - [Benchmarks](#benchmarks)
- [💡 AI-Driven Scientific Discovery: Ideation, Hypothesis Generation, and Experimentation](#ai-driven-scientific-discovery-ideation-hypothesis-generation-and-experimentation)
    - [Idea Generation](#idea-generation)
    - [Hypothesis Generation](#hypothesis-generation)
    - [Automated Experimentation](#automated-experimentation)
- [📝 Text-based Content Generation](#text-based-content-generation)
    - [Title](#title)
    - [Abstract](#abstract)
    - [Related Work](#related-work)
    - [Citation](#citation)
    - [Long Text](#long-text)
    - [Proof-Reading and Paraphrasing](#proof-reading-and-paraphrasing)
    - [Press Release](#press-release)
- [🎨 Multimodal Content Generation and Understanding](#multimodal-content-generation-and-understanding)
    - [Scientific Figure Understanding](#scientific-figure-understanding)
    - [Scientific Figure Generation](#scientific-figure-generation)
    - [Scientific Table Understanding](#scientific-table-understanding)
    - [Scientific Table Generation](#scientific-table-generation)
    - [Scientific Slides and Poster Generation](#scientific-slides-and-poster-generation)
- [✅ Peer Review](#peer-review)
    - [Analysis of Peer Reviews](#analysis-of-peer-reviews)
    - [Paper Feedback and Automatic Reviewing](#paper-feedback-and-automatic-reviewing)
    - [Scientific Rigor](#scientific-rigour)
    - [Scientific Claim Verification](#scientific-claim-verification)
    - [Meta Review Generation](#meta-review-generation)
- [🚀 End-to-End](#end-to-end)

# 🔍 Literature Search, Summarization, and Comparison

## AI-Enhanced Search
| Platform | Search | Reco-mmen-dations | Collec-tions | Citation Analysis | Trending Analysis | Author Profiles | Visual-ization Tools | Paper Chat | Idea Gener-ation | Paper Writing | Summa-rization | Paper Review | Data-sets | Code Reposi-tories | LLM Inte-gration | Web API | Personal-ization | Free |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| [**Elicit**](https://elicit.com/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**OpenSholar**](https://openscilm.allen.ai/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ |
| [**Undermind**](https://www.undermind.ai/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ |
| [**Perplexity**](https://www.perplexity.ai/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**Consensus**](https://consensus.app/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️❌ |
| [**SciSpace**](https://scispace.com/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**scienceQA**](https://www.scienceos.ai/) | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**PaperQA2**](https://github.com/Future-House/paper-qa) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ |
| [**Paperguide**](https://paperguide.ai/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**HyperWrite**](https://www.hyperwriteai.com/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ |
| [**ResearchKick**](https://www.researchkick.com/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ |

## Graph-Based
| Platform | Search | Reco-mmen-dations | Collec-tions | Citation Analysis | Trending Analysis | Author Profiles | Visual-ization Tools | Paper Chat | Idea Gener-ation | Paper Writing | Summa-rization | Paper Review | Data-sets | Code Reposi-tories | LLM Inte-gration | Web API | Personal-ization | Free |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| [**Connected Papers**](https://www.connectedpapers.com/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️❌ |
| [**ScholarGPS**](https://scholargps.com/) | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| [**CiteSpace**](https://citespace.podia.com/) | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️❌ |
| [**Sci2**](https://sci2.cns.iu.edu/) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| [**NLP KG**](https://nlpkg.sebis.cit.tum.de/) | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| [**ORKG ASK**](https://ask.orkg.org/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ |

## Paper Chat
| Platform | Search | Reco-mmen-dations | Collec-tions | Citation Analysis | Trending Analysis | Author Profiles | Visual-ization Tools | Paper Chat | Idea Gener-ation | Paper Writing | Summa-rization | Paper Review | Data-sets | Code Reposi-tories | LLM Inte-gration | Web API | Personal-ization | Free |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| [**ChatGPT**](https://chatgpt.com/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️❌ |
| [**Claude**](https://claude.ai/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️❌ |
| [**Deepseek**](https://chat.deepseek.com/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ |
| [**Research**](https://un.ms/research) | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**NotebookLM**](https://notebooklm.google/) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️❌ |
| [**EnagoRead**](https://www.read.enago.com/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️❌ |
| [**DocAnalyzer.AI**](https://docanalyzer.ai/) | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ❌ |
| [**CoralAI**](https://www.getcoralai.com/) | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**ExplainPaper**](https://www.explainpaper.com/) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️❌ |
| [**ChatPDF**](https://www.chatpdf.com/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ |

## Recommender
| Platform | Search | Reco-mmen-dations | Collec-tions | Citation Analysis | Trending Analysis | Author Profiles | Visual-ization Tools | Paper Chat | Idea Gener-ation | Paper Writing | Summa-rization | Paper Review | Data-sets | Code Reposi-tories | LLM Inte-gration | Web API | Personal-ization | Free |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| [**Arxiv Sanity**](https://arxiv-sanity-lite.com/) | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ |
| [**Scholar Inbox**](https://www.scholar-inbox.com/) | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ |
| [**ResearchTrend.ai**](https://researchtrend.ai/) | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️❌ |
| [**TrendingPapers**](https://trendingpapers.com/) | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ |
| [**Bytez**](https://dev.bytez.com/) | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ✔️❌ |
| [**Notesum.ai**](https://notesum.ai/) | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️❌ |
| [**Research Rabbit**](https://www.researchrabbit.ai/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |

## Search Engines
| Platform | Search | Reco-mmen-dations | Collec-tions | Citation Analysis | Trending Analysis | Author Profiles | Visual-ization Tools | Paper Chat | Idea Gener-ation | Paper Writing | Summa-rization | Paper Review | Data-sets | Code Reposi-tories | LLM Inte-gration | Web API | Personal-ization | Free |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| [**Google Sholar**](https://scholar.google.com/) | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ |
| [**Semantic Sholar**](https://www.semanticscholar.org/) | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ |
| [**Baidu Sholar**](https://xueshu.baidu.com/) | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️❌ |
| [**BASE**](https://www.base-search.net/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ |
| [**Internet Archive Sholar**](https://scholar.archive.org/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ |
| [**Scilit**](https://www.scilit.com/) | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| [**The Lens**](https://www.lens.org/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️❌ |
| [**Science.gov**](https://science.gov/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| [**Academia.eu**](https://www.academia.edu/) | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️❌ |
| [**OpenAlex**](https://openalex.org/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️❌ |
| [**AceMap**](https://acemap.info/) | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| [**PubTator3**](https://www.ncbi.nlm.nih.gov/research/pubtator3/) | ✔️ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ |

## Benchmarks
| Platform | Search | Reco-mmen-dations | Collec-tions | Citation Analysis | Trending Analysis | Author Profiles | Visual-ization Tools | Paper Chat | Idea Gener-ation | Paper Writing | Summa-rization | Paper Review | Data-sets | Code Reposi-tories | LLM Inte-gration | Web API | Personal-ization | Free |
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| [**Papers with Code**](https://portal.paperswithcode.com/) | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ |
| [**ScienceAgentBench**](https://github.com/OSU-NLP-Group/ScienceAgentBench) | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ |
| [**ORKG Benchmarks**](https://orkg.org/benchmarks) | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ✔️ |
| [**Huggingface**](https://huggingface.co/) | ✔️ | ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️❌ |

# 💡 AI-Driven Scientific Discovery: Ideation, Hypothesis Generation, and Experimentation

## Idea Generation
* The IDEA Challenge 2022 dataset [[Dataset]](https://research-information.bris.ac.uk/en/datasets/the-idea-challenge-2022-dataset) ![](https://img.shields.io/badge/Zenodo-2023-brown)
* SPACE-IDEAS: A Dataset for Salient Information Detection in Space Innovation [[Paper]](https://aclanthology.org/2024.lrec-main.1311/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Nova: An Iterative Planning and Search Approach to Enhance Novelty and Diversity of LLM Generated Ideas [[Paper]](https://arxiv.org/abs/2410.14255) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* Chain of Ideas: Revolutionizing Research Via Novel Idea Development with LLM Agents [[Paper]](https://arxiv.org/abs/2410.13185) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination [[Paper]](https://arxiv.org/abs/2409.14634) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv)
* Many Heads Are Better Than One: Improved Scientific Idea Generation by A LLM-Based Multi-Agent System [[Paper]](https://arxiv.org/abs/2410.09403) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)

## Hypothesis Generation
* Large Language Models are Zero Shot Hypothesis Proposers [[Paper]](https://openreview.net/forum?id=EAuteBjTMw) ![](https://img.shields.io/badge/NeurIPS_Workshop-2023-blue)
* Hypothesis Generation with Large Language Models [[Paper]](https://aclanthology.org/2024.nlp4science-1.10/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Exploring Scientific Hypothesis Generation with Mamba [[Paper]](https://aclanthology.org/2024.nlp4science-1.17/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Large Language Models for Automated Open-domain Scientific Hypotheses Discovery [[Paper]](https://aclanthology.org/2024.findings-acl.804/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Large Language Models as Biomedical Hypothesis Generators: A Comprehensive Evaluation [[Paper]](https://openreview.net/forum?id=q36rpGlG9X) ![](https://img.shields.io/badge/COLM-2024-blue)
* Improving Scientific Hypothesis Generation with Knowledge Grounded Large Language Models [[Paper]](https://arxiv.org/abs/2411.02382) ![](https://img.shields.io/badge/arXiv-2024.11-red?logo=arxiv)
* Towards an AI co-scientist [[Paper]](https://storage.googleapis.com/coscientist_paper/ai_coscientist.pdf) ![](https://img.shields.io/badge/Google-2025-brown)
* MOOSE-Chem: Large Language Models for Rediscovering Unseen Chemistry Scientific Hypotheses [[Paper]](https://openreview.net/forum?id=X9OfMNNepI) ![](https://img.shields.io/badge/ICLR-2025-blue)
* Literature Meets Data: A Synergistic Approach to Hypothesis Generation [[Paper]](https://arxiv.org/abs/2410.17309) ![](https://img.shields.io/badge/arXiv-2025.01-red?logo=arxiv)

## Automated Experimentation
* AutoML-GPT: Large Language Model for AutoML [[Paper]](https://arxiv.org/abs/2309.01125) ![](https://img.shields.io/badge/arXiv-2023.09-red?logo=arxiv)
* MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation [[Paper]](https://arxiv.org/abs/2310.03302) ![](https://img.shields.io/badge/arXiv-2024.04-red?logo=arxiv)
* SWE-bench: Can Language Models Resolve Real-world Github Issues? [[Paper]](https://openreview.net/forum?id=VTF8yNQM66) ![](https://img.shields.io/badge/ICLR-2024-blue)
* MLCopilot: Unleashing the Power of Large Language Models in Solving Machine Learning Tasks [[Paper]](https://aclanthology.org/2024.eacl-long.179/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Automatic benchmarking of large multimodal models via iterative experiment programming [[Paper]](https://arxiv.org/abs/2406.12321) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv)
* Agent-as-a-Judge: Evaluate Agents with Agents [[Paper]](https://arxiv.org/abs/2410.10934) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery [[Paper]](https://arxiv.org/abs/2410.05080) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* AutoML-Agent: A Multi-Agent LLM Framework for Full-Pipeline AutoML [[Paper]](https://arxiv.org/abs/2410.02958) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* Tree Search for Language Model Agents [[Paper]](https://arxiv.org/abs/2407.01476) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* SELA: Tree-Search Enhanced LLM Agents for Automated Machine Learning [[Paper]](https://arxiv.org/abs/2410.17238) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* OpenHands: An Open Platform for AI Software Developers as Generalist Agents [[Paper]](https://arxiv.org/abs/2407.16741) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* AI agents in chemical research: GVIM - an intelligent research assistant system [[Paper]](https://pubs.rsc.org/en/content/articlelanding/2025/dd/d4dd00398e) ![](https://img.shields.io/badge/Digital_Discovery-2025-brown)
* SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains? [[Paper]](https://openreview.net/forum?id=riTiq3i21b) ![](https://img.shields.io/badge/ICLR-2025-blue)
* AIDE: AI-Driven Exploration in the Space of Code [[Paper]](https://arxiv.org/abs/2502.13138) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)
* MLGym: A New Framework and Benchmark for Advancing AI Research Agents [[Paper]](https://arxiv.org/abs/2502.14499) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)
* DrugAgent: Automating AI-aided Drug Discovery Programming through LLM Multi-Agent Collaboration [[Paper]](https://arxiv.org/abs/2411.15692) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv)

# 📝 Text-based Content Generation

## Title
* PaperRobot: Incremental Draft Generation of Scientific Ideas [[Paper]](https://aclanthology.org/P19-1191/) ![](https://img.shields.io/badge/ACL-2019-blue)
* Automatic Title Generation for Text with Pre-trained Transformer Language Model [[Paper]](https://ieeexplore.ieee.org/abstract/document/9364613) ![](https://img.shields.io/badge/IEEE-2021-blue)
* Transformers Go for the LOLs: Generating (Humourous) Titles from Scientific Abstracts End-to-End [[Paper]](https://aclanthology.org/2023.eval4nlp-1.6/) ![](https://img.shields.io/badge/ACL-2023-blue)

## Abstract
* PaperRobot: Incremental Draft Generation of Scientific Ideas [[Paper]](https://aclanthology.org/P19-1191/) ![](https://img.shields.io/badge/ACL-2019-blue)
* Comparing scientific abstracts generated by ChatGPT to real abstracts with detectors and blinded human reviewers [[Paper]](https://www.nature.com/articles/s41746-023-00819-6) ![](https://img.shields.io/badge/Nature-2023-green)
* How trustworthy is ChatGPT? The case of bibliometric analyses [[Paper]](https://doaj.org/article/d90a79755b5e4f63af6f9c2bfccef6f2) ![](https://img.shields.io/badge/DOAJ-2023-green)
* Can ChatGPT assist authors with abstract writing in medical journals? Evaluating the quality of scientific abstracts generated by ChatGPT and original abstracts [[Paper]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0297701) ![](https://img.shields.io/badge/PLOS-2024-green)

## Related Work
* Towards Automated Related Work Summarization [[Paper]](https://aclanthology.org/C10-2049/) ![](https://img.shields.io/badge/ACL-2010-blue)
* Neural Related Work Summarization with a Joint Context-driven Attention Mechanism [[Paper]](https://aclanthology.org/D18-1204/) ![](https://img.shields.io/badge/ACL-2018-blue)
* ScisummNet: A Large Annotated Corpus and Content-Impact Models for Scientific Paper Summarization with Citation Networks [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4727) ![](https://img.shields.io/badge/AAAI-2019-blue)
* PaperRobot: Incremental Draft Generation of Scientific Ideas [[Paper]](https://aclanthology.org/P19-1191/) ![](https://img.shields.io/badge/ACL-2019-blue)
* Automatic related work section generation: experiments in scientific document abstracting [[Paper]](https://link.springer.com/article/10.1007/s11192-020-03630-2) ![](https://img.shields.io/badge/Springer-2020-green)
* Automatic Generation of Related Work Sections in Scientific Papers: An Optimization Approach [[Paper]](https://ceur-ws.org/Vol-2871/paper8.pdf) ![](https://img.shields.io/badge/AII_Workshop-2021-blue)
* CORWA: A Citation-Oriented Related Work Annotation Dataset [[Paper]](https://aclanthology.org/2022.naacl-main.397/) ![](https://img.shields.io/badge/ACL-2022-blue)
* Automatic generation of related work through summarizing citations [[Paper]](https://onlinelibrary.wiley.com/doi/10.1002/cpe.4261) ![](https://img.shields.io/badge/CCPE-2023-green)
* CiteBench: A Benchmark for Scientific Citation Text Generation [[Paper]](https://aclanthology.org/2023.emnlp-main.455/) ![](https://img.shields.io/badge/ACL-2023-blue)
* ToC-RWG: Explore the Combination of Topic Model and Citation Information for Automatic Related Work Generation [[Paper]](https://ieeexplore.ieee.org/abstract/document/8931592) ![](https://img.shields.io/badge/IEEE-2023-blue)

## Citation
* Fabrication and errors in the bibliographic citations generated by ChatGPT [[Paper]](https://www.nature.com/articles/s41598-023-41032-5) ![](https://img.shields.io/badge/Nature-2023-green)
* Cited Text Spans for Scientific Citation Text Generation [[Paper]](https://aclanthology.org/2024.sdp-1.9/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Systematic Task Exploration with LLMs: A Study in Citation Text Generation [[Paper]](https://aclanthology.org/2024.acl-long.265/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Citation: A Key to Building Responsible and Accountable Large Language Models [[Paper]](https://aclanthology.org/2024.findings-naacl.31/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Citation-Enhanced Generation for LLM-based Chatbots [[Paper]](https://aclanthology.org/2024.acl-long.79/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Related Work and Citation Text Generation: A Survey [[Paper]](https://aclanthology.org/2024.emnlp-main.767/) ![](https://img.shields.io/badge/ACL-2024-blue)

## Long Text
* LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs [[Paper]](https://arxiv.org/abs/2408.07055) ![](https://img.shields.io/badge/arXiv-2024.08-red?logo=arxiv)
* LongReward: Improving Long-context Large Language Models with AI Feedback [[Paper]](https://arxiv.org/abs/2410.21252) ![](https://img.shields.io/badge/arXiv-2024.10-red?logo=arxiv)
* LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm [[Paper]](https://arxiv.org/abs/2502.19103) ![](https://img.shields.io/badge/arXiv-2025.03-red?logo=arxiv)

## Proof-Reading and Paraphrasing
* Can artificial intelligence help for scientific writing? [[Paper]](https://link.springer.com/article/10.1186/s13054-023-04380-2) ![](https://img.shields.io/badge/Springer-2023-green)
* Good Practices for Scientific Article Writing with ChatGPT and Other Artificial Intelligence Language Models [[Paper]](https://www.mdpi.com/2673-687X/3/2/9) ![](https://img.shields.io/badge/MDPI-2023-green)
* The role of ChatGPT in scientific communication: writing better scientific review articles [[Paper]](https://pmc.ncbi.nlm.nih.gov/articles/PMC10164801/) ![](https://img.shields.io/badge/NIH-2023-green)
* Using ChatGPT for language editing in scientifc articles [[Paper]](https://link.springer.com/content/pdf/10.1186/s40902-023-00381-x.pdf) ![](https://img.shields.io/badge/Springer-2023-green)
* The Ability of ChatGPT in Paraphrasing Texts and Reducing Plagiarism: A Descriptive Analysis [[Paper]](https://pmc.ncbi.nlm.nih.gov/articles/PMC11250043/) ![](https://img.shields.io/badge/NIH-2024-green)

## Press Release
* Expertise Style Transfer: A New Task Towards Better Communication between Experts and Laymen [[Paper]](https://aclanthology.org/2020.acl-main.100/) ![](https://img.shields.io/badge/ACL-2020-blue)
* Making Science Simple: Corpora for the Lay Summarisation of Scientific Literature [[Paper]](https://aclanthology.org/2022.emnlp-main.724/) ![](https://img.shields.io/badge/ACL-2022-blue)
* ‘Don’t Get Too Technical with Me’: A Discourse Structure-Based Framework for Automatic Science Journalism [[Paper]](https://aclanthology.org/2023.emnlp-main.76/) ![](https://img.shields.io/badge/ACL-2023-blue)

# 🎨 Multimodal Content Generation and Understanding

## Scientific Figure Understanding
* A Diagram is Worth a Dozen Images [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_15) ![](https://img.shields.io/badge/ECCV-2016-blue)
* A simple neural network module for relational reasoning [[Paper]](https://papers.nips.cc/paper_files/paper/2017/hash/e6acf4b0f69f6f6e60e9a815938aa1ff-Abstract.html) ![](https://img.shields.io/badge/NeurIPS-2017-blue)
* FigureQA: An Annotated Figure Dataset for Visual Reasoning [[Paper]](https://arxiv.org/abs/1710.07300) ![](https://img.shields.io/badge/arXiv-2018.02-red?logo=arxiv)
* ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning [[Paper]](https://aclanthology.org/2022.findings-acl.177/) ![](https://img.shields.io/badge/ACL-2022-blue)
* ChartSumm: A Comprehensive Benchmark for Automatic Chart Summarization of Long and Short Summaries [[Paper]](https://arxiv.org/abs/2304.13620) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv)
* Multimodal ArXiv: A Dataset for Improving Scientific Comprehension of Large Vision-Language Models [[Paper]](https://aclanthology.org/2024.acl-long.775/) ![](https://img.shields.io/badge/ACL-2024-blue)
* SciMMIR: Benchmarking Scientific Multi-modal Information Retrieval [[Paper]](https://aclanthology.org/2024.findings-acl.746/) ![](https://img.shields.io/badge/ACL-2024-blue)
* SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers [[Paper]](https://openreview.net/forum?id=h3lddsY5nf#discussion) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs [[Paper]](https://openreview.net/forum?id=cy8mq7QYae#discussion) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* ChartAdapter: Large Vision-Language Model for Chart Summarization [[Paper]](https://arxiv.org/abs/2412.20715) ![](https://img.shields.io/badge/arXiv-2024.12-red?logo=arxiv)

## Scientific Figure Generation
* Data2Vis: Automatic Generation of Data Visualizations Using Sequence-to-Sequence Recurrent Neural Networks [[Paper]](https://ieeexplore.ieee.org/document/8744242) ![](https://img.shields.io/badge/IEEE-2019-blue)
* ADVISor: Automatic Visualization Answer for Natural-Language Question on Tabular Data [[Paper]](https://ieeexplore.ieee.org/document/9438784) ![](https://img.shields.io/badge/IEEE-2021-blue)
* Sevi: Speech-to-Visualization through Neural Machine Translation [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3514221.3520150) ![](https://img.shields.io/badge/SIGMOD-2022-blue)
* Chat2VIS: Generating Data Visualizations via Natural Language Using ChatGPT, Codex and GPT-3 Large Language Models [[Paper]](https://ieeexplore.ieee.org/abstract/document/10121440) ![](https://img.shields.io/badge/IEEE-2023-blue)
* AutomaTikZ: Text-Guided Synthesis of Scientific Vector Graphics with TikZ [[Paper]](https://openreview.net/forum?id=v3K5TVP8kZ) ![](https://img.shields.io/badge/ICLR-2024-blue)
* SciDoc2Diagrammer-MAF: Towards Generation of Scientific Diagrams from Documents guided by Multi-Aspect Feedback Refinement [[Paper]](https://aclanthology.org/2024.findings-emnlp.780/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Plots Made Quickly: An Efficient Approach for Generating Visualizations from Natural Language Queries [[Paper]](https://aclanthology.org/2024.lrec-main.1119/) ![](https://img.shields.io/badge/ACL-2024-blue)
* DiagrammerGPT: Generating Open-Domain, Open-Platform Diagrams via LLM Planning [[Paper]](https://openreview.net/forum?id=NV8yRJRET1#discussion) ![](https://img.shields.io/badge/COLM-2024-blue)
* DeTikZify: Synthesizing Graphics Programs for Scientific Figures and Sketches with TikZ [[Paper]](https://openreview.net/forum?id=bcVLFQCOjc) ![](https://img.shields.io/badge/NeurIPS-2024-blue)
* ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation [[Paper]](https://arxiv.org/abs/2406.09961) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)
* ScImage: How Good Are Multimodal Large Language Models at Scientific Text-to-Image Generation? [[Paper]](https://openreview.net/forum?id=ugyqNEOjoU) ![](https://img.shields.io/badge/ICLR-2025-blue)

## Scientific Table Understanding
* ToTTo: A Controlled Table-To-Text Generation Dataset [[Paper]](https://aclanthology.org/2020.emnlp-main.89/) ![](https://img.shields.io/badge/ACL-2020-blue)
* SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables [[Paper]](https://openreview.net/forum?id=Jul-uX7EV_I) ![](https://img.shields.io/badge/NeurIPS-2021-blue)
* Towards Table-to-Text Generation with Numerical Reasoning [[Paper]](https://aclanthology.org/2021.acl-long.115/) ![](https://img.shields.io/badge/ACL-2021-blue)
* SciXGen: A Scientific Paper Dataset for Context-Aware Text Generation [[Paper]](https://aclanthology.org/2021.findings-emnlp.128/) ![](https://img.shields.io/badge/ACL-2021-blue)
* Structure-Aware Pre-Training for Table-to-Text Generation [[Paper]](https://aclanthology.org/2021.findings-acl.200/) ![](https://img.shields.io/badge/ACL-2021-blue)
* Table-To-Text generation and pre-training with TabT5 [[Paper]](https://aclanthology.org/2022.findings-emnlp.503/) ![](https://img.shields.io/badge/ACL-2022-blue)
* Few-shot Table-to-text Generation with Prefix-Controlled Generator [[Paper]](https://aclanthology.org/2022.coling-1.565/) ![](https://img.shields.io/badge/ACL-2022-blue)
* Robust (Controlled) Table-to-Text Generation with Structure-Aware Equivariance Learning [[Paper]](https://aclanthology.org/2022.naacl-main.371/) ![](https://img.shields.io/badge/ACL-2022-blue)
* SORTIE: Dependency-Aware Symbolic Reasoning for Logical Data-to-text Generation [[Paper]](https://aclanthology.org/2023.findings-acl.715/) ![](https://img.shields.io/badge/ACL-2023-blue)
* LoFT: Enhancing Faithfulness and Diversity for Table-to-Text Generation via Logic Form Control [[Paper]](https://aclanthology.org/2023.eacl-main.40/) ![](https://img.shields.io/badge/ACL-2023-blue)
* Arithmetic-Based Pretraining Improving Numeracy of Pretrained Language Models [[Paper]](https://aclanthology.org/2023.starsem-1.42/) ![](https://img.shields.io/badge/ACL-2023-blue)
* Structure-aware Table-to-Text Generation with Prefix-tuning [[Paper]](https://dlnext.acm.org/doi/10.1145/3622896.3622919) ![](https://img.shields.io/badge/IEEE-2023-blue)
* Table-to-Text Using Pre-trained Large Language Model and LoRA [[Paper]](https://ieeexplore.ieee.org/document/10707812) ![](https://img.shields.io/badge/IEEE-2024-blue)
* Unifying Structured Data as Graph for Data-to-Text Pre-Training [[Paper]](https://aclanthology.org/2024.tacl-1.12/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Integrating Table Representations into Large Language Models for Improved Scholarly Document Comprehension [[Paper]](https://aclanthology.org/2024.sdp-1.28/) ![](https://img.shields.io/badge/ACL-2024-blue)

## Scientific Table Generation
* gTBLS: Generating Tables from Text by Conditional Question Answering [[Paper]](https://arxiv.org/abs/2403.14457) ![](https://img.shields.io/badge/arXiv-2024.03-red?logo=arxiv)
* ArxivDIGESTables: Synthesizing Scientific Literature into Tables using Language Models [[Paper]](https://aclanthology.org/2024.emnlp-main.538/) ![](https://img.shields.io/badge/ACL-2024-blue)
* OpenTE: Open-Structure Table Extraction From Text [[Paper]](https://ieeexplore.ieee.org/document/10448427) ![](https://img.shields.io/badge/IEEE-2024-blue)
* Is This a Bad Table? A Closer Look at the Evaluation of Table Generation from Text [[Paper]](https://aclanthology.org/2024.emnlp-main.1239/) ![](https://img.shields.io/badge/ACL-2024-blue)
* LATTE: Improving Latex Recognition for Tables and Formulae with Iterative Refinement [[Paper]](https://arxiv.org/abs/2409.14201) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)

## Scientific Slides and Poster Generation
* SlidesGen: Automatic Generation of Presentation Slides for a Technical Paper Using Summarization [[Paper]](https://aaai.org/papers/flairs-2009-22/) ![](https://img.shields.io/badge/FLAIRS-2009-blue)
* PPSGen: learning to generate presentation slides for academic papers [[Paper]](https://dl.acm.org/doi/10.5555/2540128.2540430) ![](https://img.shields.io/badge/IJCAI-2013-blue)
* Learning to Generate Posters of Scientific Papers [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/10000) ![](https://img.shields.io/badge/AAAI-2016-blue)
* Phrase-Based Presentation Slides Generation for Academic Papers [[Paper]](https://aaai.org/papers/10481-aaai-31-2017/) ![](https://img.shields.io/badge/AAAI-2017-blue)
* D2S: Document-to-Slide Generation Via Query-Based Text Summarization [[Paper]](https://aclanthology.org/2021.naacl-main.111/) ![](https://img.shields.io/badge/ACL-2021-blue)
* Towards Topic-Aware Slide Generation For Academic Papers With Unsupervised Mutual Learning [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17564) ![](https://img.shields.io/badge/AAAI-2021-blue)
* DOC2PPT: Automatic Presentation Slides Generation from Scientific Documents [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/19943) ![](https://img.shields.io/badge/AAAI-2022-blue)
* PosterBot: A System for Generating Posters of Scientific Papers with Neural Models [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/21738) ![](https://img.shields.io/badge/AAAI-2022-blue)
* Presentations by the Humans and For the Humans: Harnessing LLMs for Generating Persona-Aware Slides from Documents [[Paper]](https://aclanthology.org/2024.eacl-long.163/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Enhancing Presentation Slide Generation by LLMs with a Multi-Staged End-to-End Approach [[Paper]](https://aclanthology.org/2024.inlg-main.18/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Presentations are not always linear! GNN meets LLM for Text Document-to-Presentation Transformation with Attribution [[Paper]](https://aclanthology.org/2024.findings-emnlp.936/) ![](https://img.shields.io/badge/ACL-2024-blue)

# ✅ Peer Review

## Analysis of Peer Reviews
* Argument Mining for Understanding Peer Reviews [[Paper]](https://aclanthology.org/N19-1219/) ![](https://img.shields.io/badge/ACL-2019-blue)
* Aspect-based Sentiment Analysis of Scientific Reviews [[Paper]](https://dl.acm.org/doi/10.1145/3383583.3398541) ![](https://img.shields.io/badge/IEEE-2020-blue)
* APE: Argument Pair Extraction from Peer Review and Rebuttal via Multi-task Learning [[Paper]](https://aclanthology.org/2020.emnlp-main.569/) ![](https://img.shields.io/badge/ACL-2020-blue)
* Argument Mining Driven Analysis of Peer-Reviews [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16607) ![](https://img.shields.io/badge/AAAI-2021-blue)
* HedgePeer: A Dataset for Uncertainty Detection in Peer Reviews [[Paper]](https://ieeexplore.ieee.org/document/9852963) ![](https://img.shields.io/badge/IEEE-2022-blue)
* PolitePEER: does peer review hurt? A dataset to gauge politeness intensity in the peer reviews [[Paper]](https://link.springer.com/article/10.1007/s10579-023-09662-3) ![](https://img.shields.io/badge/Springer-2023-green)
* Automatic Analysis of Substantiation in Scientific Peer Reviews [[Paper]](https://aclanthology.org/2023.findings-emnlp.684/) ![](https://img.shields.io/badge/ACL-2023-blue)
* Exploring Jiu-Jitsu Argumentation for Writing Peer Review Rebuttals [[Paper]](https://aclanthology.org/2023.emnlp-main.894/) ![](https://img.shields.io/badge/ACL-2023-blue)

## Paper Feedback and Automatic Reviewing
* DeepSentiPeer: Harnessing Sentiment in Review Texts to Recommend Peer Review Decisions [[Paper]](https://aclanthology.org/P19-1106/) ![](https://img.shields.io/badge/ACL-2019-blue)
* Exploring the Potential of GPT-2 for Generating Fake Reviews of Research Papers [[Paper]](https://ebooks.iospress.nl/doi/10.3233/FAIA200717) ![](https://img.shields.io/badge/IOS_Press-2020-green)
* Multi-task Peer-Review Score Prediction [[Paper]](https://aclanthology.org/2020.sdp-1.14/) ![](https://img.shields.io/badge/ACL-2020-blue)
* ReviewRobot: Explainable Paper Review Generation based on Knowledge Synthesis [[Paper]](https://aclanthology.org/2020.inlg-1.44/) ![](https://img.shields.io/badge/ACL-2020-blue)
* PEERAssist: Leveraging on Paper-Review Interactions to Predict Peer Review Decisions [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-91669-5_33) ![](https://img.shields.io/badge/Springer-2021-green)
* Can We Automate Scientific Reviewing? [[Paper]](https://dl.acm.org/doi/10.1613/jair.1.12862) ![](https://img.shields.io/badge/JAIR-2022-blue)
* ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing [[Paper]](https://arxiv.org/abs/2306.00622) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv)
* GPT4 is Slightly Helpful for Peer-Review Assistance: A Pilot Study [[Paper]](https://arxiv.org/abs/2307.05492) ![](https://img.shields.io/badge/arXiv-2023.06-red?logo=arxiv)
* Can large language models provide useful feedback on research papers? A large-scale empirical analysis [[Paper]](https://arxiv.org/abs/2310.01783) ![](https://img.shields.io/badge/arXiv-2023.10-red?logo=arxiv)
* MARG: Multi-Agent Review Generation for Scientific Papers [[Paper]](https://arxiv.org/abs/2401.04259) ![](https://img.shields.io/badge/arXiv-2024.01-red?logo=arxiv)

## Scientific Rigour
* Online software spots genetic errors in cancer papers [[Paper]](https://www.nature.com/articles/nature.2017.23003) ![](https://img.shields.io/badge/Nature-2017-green)
* SciScore [[Tool]](https://sciscore.com/) ![](https://img.shields.io/badge/SciScore-2019-brown)
* Assessing Scientific Research Papers with Knowledge Graphs [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3477495.3531879) ![](https://img.shields.io/badge/SIGIR-2022-blue)
* On the Rigour of Scientific Writing: Criteria, Analysis, and Insights [[Paper]](https://aclanthology.org/2024.findings-emnlp.380/) ![](https://img.shields.io/badge/ACL-2024-blue)

## Scientific Claim Verification
* SciFact-Open: Towards open-domain scientific claim verification [[Paper]](https://arxiv.org/abs/2210.13777) ![](https://img.shields.io/badge/arXiv-2022.10-red?logo=arxiv)
* Scientific Fact-Checking: A Survey of Resources and Approaches [[Paper]](https://arxiv.org/abs/2305.16859) ![](https://img.shields.io/badge/arXiv-2023.05-red?logo=arxiv)
* The Intended Uses of Automated Fact-Checking Artefacts: Why, How and Who [[Paper]](https://aclanthology.org/2023.findings-emnlp.577/) ![](https://img.shields.io/badge/ACL-2023-blue)
* Missci: Reconstructing Fallacies in Misrepresented Science [[Paper]](https://aclanthology.org/2024.acl-long.240/) ![](https://img.shields.io/badge/ACL-2024-blue)
* Overview of the Context24 Shared Task on Contextualizing Scientific Claims [[Paper]](https://aclanthology.org/2024.sdp-1.3/) ![](https://img.shields.io/badge/ACL-2024-blue)
* How We Refute Claims: Automatic Fact-Checking through Flaw Identification and Explanation [[Paper]](https://dl.acm.org/doi/10.1145/3589335.3651521) ![](https://img.shields.io/badge/SIGWEB-2024-blue)
* Claim Verification in the Age of Large Language Models: A Survey [[Paper]](https://arxiv.org/abs/2408.14317) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)
* Grounding Fallacies Misrepresenting Scientific Publications in Evidence [[Paper]](https://arxiv.org/abs/2408.12812) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)

## Meta Review Generation
* Uncertainty-aware machine support for paper reviewing on the interspeech 2019 submission corpus [[Paper]](https://www.isca-archive.org/interspeech_2020/stappen20_interspeech.html) ![](https://img.shields.io/badge/ISCA-2020-blue)
* A Deep Neural Architecture for Decision-Aware Meta-Review Generation [[Paper]](https://ieeexplore.ieee.org/document/9651825) ![](https://img.shields.io/badge/IEEE-2021-blue)
* Summarizing Multiple Documents with Conversational Structure for Meta-Review Generation [[Paper]](https://aclanthology.org/2023.findings-emnlp.472/) ![](https://img.shields.io/badge/ACL-2023-blue)
* Scientific Opinion Summarization: Paper Meta-review Generation Dataset, Methods, and Evaluation [[Paper]](https://arxiv.org/abs/2305.14647v3) ![](https://img.shields.io/badge/arXiv-2024.06-red?logo=arxiv)
* LLMs as Meta-Reviewers' Assistants: A Case Study [[Paper]](https://arxiv.org/abs/2402.15589) ![](https://img.shields.io/badge/arXiv-2025.02-red?logo=arxiv)

# 🚀 End-to-End
* Scientific discovery in the age of artificial intelligence [[Paper]](https://www.nature.com/articles/s41586-023-06221-2) ![](https://img.shields.io/badge/Nature-2023-green)
* The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery [[Paper]](https://export.arxiv.org/abs/2408.06292) ![](https://img.shields.io/badge/arXiv-2024.09-red?logo=arxiv)

<!-- omit in toc -->
# Citation
```bib
@article{eger2025transforming,
  title={Transforming Science with Large Language Models: A Survey on AI-assisted Scientific Discovery, Experimentation, Content Generation, and Evaluation},
  author={Eger, Steffen and Cao, Yong and D'Souza, Jennifer and Geiger, Andreas and Greisinger, Christian and Gross, Stephanie and Hou, Yufang and Krenn, Brigitte and Lauscher, Anne and Li, Yizhi and others},
  journal={arXiv preprint arXiv:2502.05151},
  year={2025}
}
```