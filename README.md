<div align="center">

# 🌟 Awesome Arabic AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p>
  <strong>A curated list of awesome Arabic Artificial Intelligence resources</strong>
  <br>
  <em>LLMs · Datasets · Benchmarks · Speech · OCR · Tools · Research</em>
  <br><br>
  <strong>قائمة منسقة لأفضل موارد الذكاء الاصطناعي العربي</strong>
  <br>
  <em>نماذج لغوية · بيانات · تقييمات · صوت · رؤية · أدوات · أبحاث</em>
</p>

[![GitHub stars](https://img.shields.io/github/stars/OsamaALHajj/awesome-arabic-ai?style=social)](https://github.com/OsamaALHajj/awesome-arabic-ai/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/OsamaALHajj/awesome-arabic-ai?style=social)](https://github.com/OsamaALHajj/awesome-arabic-ai/network/members)
[![GitHub contributors](https://img.shields.io/github/contributors/OsamaALHajj/awesome-arabic-ai)](https://github.com/OsamaALHajj/awesome-arabic-ai/graphs/contributors)
[![GitHub last commit](https://img.shields.io/github/last-commit/OsamaALHajj/awesome-arabic-ai)](https://github.com/OsamaALHajj/awesome-arabic-ai/commits/main)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/OsamaALHajj/awesome-arabic-ai/blob/main/CONTRIBUTING.md)

</div>

---

## 📖 About | عن المشروع

The Arabic language is spoken by over **400 million people** worldwide, yet remains significantly underrepresented in the AI ecosystem. This repository aims to be the **single source of truth** for Arabic AI resources — bringing together state-of-the-art models, datasets, benchmarks, tools, and research from across the MENA region and beyond.

اللغة العربية يتحدث بها أكثر من **400 مليون شخص** حول العالم، لكنها لا تزال ممثَّلة بشكل ضعيف في منظومة الذكاء الاصطناعي. يهدف هذا المستودع إلى أن يكون **المرجع الموحَّد** لموارد الذكاء الاصطناعي العربي، جامعاً أحدث النماذج والبيانات وأدوات التقييم والأبحاث من المنطقة العربية والعالم.

> 💡 **Found this useful?** Give it a ⭐ to help others discover it!
> 💡 **هل أفادك المحتوى؟** ضع نجمة ⭐ لمساعدة الآخرين على اكتشافه!

---

## 📑 Contents | المحتويات

- [🤖 Large Language Models (LLMs)](#-large-language-models-llms)
  - [Open-Source Models](#open-source-models)
  - [Commercial & Closed Models](#commercial--closed-models)
  - [Fine-tuned & Specialized Models](#fine-tuned--specialized-models)
- [📊 Datasets](#-datasets)
  - [Pre-training Datasets](#pre-training-datasets)
  - [Instruction & SFT Datasets](#instruction--sft-datasets)
  - [Dialectal Arabic Datasets](#dialectal-arabic-datasets)
  - [Domain-Specific Datasets](#domain-specific-datasets)
- [🏆 Benchmarks & Leaderboards](#-benchmarks--leaderboards)
- [🔊 Speech & Audio](#-speech--audio)
  - [Speech Recognition (ASR)](#speech-recognition-asr)
  - [Text-to-Speech (TTS)](#text-to-speech-tts)
- [👁️ Vision & OCR](#️-vision--ocr)
- [🛠️ Libraries & Tools](#️-libraries--tools)
- [📚 Research Papers & Surveys](#-research-papers--surveys)
- [🎓 Courses & Tutorials](#-courses--tutorials)
- [🏢 Companies & Startups](#-companies--startups)
- [🌐 Communities & Conferences](#-communities--conferences)

## 🤖 Large Language Models (LLMs)

State-of-the-art Arabic and multilingual language models with strong Arabic capabilities.

### Open-Source Models

- **[Jais](https://huggingface.co/inceptionai)** — Family of bilingual Arabic-English LLMs (590M to 70B parameters) developed by Inception (G42) and MBZUAI. Apache 2.0 license. One of the most influential Arabic LLMs.
- **[Fanar-1](https://huggingface.co/QCRI)** — 9B parameter Arabic-focused LLM by QCRI (Qatar). Open weights under Apache 2.0. Strong performance on cultural and dialectal tasks.
- **[ALLaM](https://huggingface.co/ALLaM-AI)** — 7B model by SDAIA (Saudi Data and AI Authority). Apache 2.0. Optimized for Modern Standard Arabic and Saudi dialects.
- **[AceGPT](https://github.com/FreedomIntelligence/AceGPT)** — 7B/13B Arabic LLM by KAUST with RLAIF-based instruction tuning. Strong cultural alignment.
- **[Falcon-Arabic](https://falcon-lm.github.io/blog/falcon-arabic/)** — Multilingual model by TII (UAE) supporting Arabic, English, and more. Excellent at Arabic grammar and reasoning.
- **[SILMA-9B](https://huggingface.co/silma-ai/SILMA-9B-Instruct-v1.0)** — Open Arabic LLM optimized for instruction-following. Apache 2.0 license.
- **[Noor](https://www.tii.ae/news/technology-innovation-institute-launches-noor-worlds-largest-arabic-nlp-model)** — Large-scale Arabic NLP model by TII.
- **[Aragpt2](https://github.com/aub-mind/arabert)** — GPT-2 variants pre-trained on Arabic by AUB MIND Lab.
- **[AraBERT](https://github.com/aub-mind/arabert)** — BERT-based Arabic language understanding model. Foundational work, still widely used.
- **[CAMeLBERT](https://github.com/CAMeL-Lab/CAMeLBERT)** — Suite of BERT models for Arabic variants (MSA, DA, CA) by Columbia's CAMeL Lab.

### Commercial & Closed Models

- **[Cohere Command-R Arabic](https://cohere.com/)** — Strong multilingual model with excellent Arabic support.
- **[GPT-4 / GPT-4o](https://openai.com/)** — Leading commercial model with strong Arabic capabilities.
- **[Claude (Anthropic)](https://www.anthropic.com/)** — Excellent Arabic comprehension and generation.
- **[Gemini](https://gemini.google.com/)** — Google's multilingual model with native Arabic support.

### Fine-tuned & Specialized Models

- **[Arabic-Orca](https://huggingface.co/models?search=arabic-orca)** — Arabic instruction-tuned variants of Orca.
- **[Arabic-Mistral](https://huggingface.co/models?search=arabic+mistral)** — Community fine-tunes of Mistral on Arabic data.
- **[Arabic-Llama variants](https://huggingface.co/models?search=arabic+llama)** — Various Llama models fine-tuned for Arabic.

---

## 📊 Datasets

High-quality datasets for training, fine-tuning, and evaluating Arabic AI models.

### Pre-training Datasets

- **[101 Billion Arabic Words Dataset](https://huggingface.co/datasets/ClusterlabAi/101_billion_arabic_words_dataset)** — Massive web-scale Arabic corpus, one of the largest publicly available.
- **[ArabicWeb24](https://huggingface.co/datasets)** — Curated, deduplicated web crawl of Arabic content from 2024.
- **[OSCAR Arabic](https://oscar-project.org/)** — Multilingual web corpus with a substantial Arabic subset.
- **[mC4 Arabic](https://huggingface.co/datasets/mc4)** — Arabic portion of Google's multilingual C4.
- **[Arabic Wikipedia Dumps](https://dumps.wikimedia.org/arwiki/)** — Clean Arabic encyclopedia content.

### Instruction & SFT Datasets

- **[CIDAR](https://huggingface.co/datasets/arbml/CIDAR)** — High-quality Arabic instruction-tuning dataset, culturally aligned.
- **[Arabic Alpaca](https://huggingface.co/datasets?search=arabic+alpaca)** — Arabic translations of the Alpaca instruction dataset.
- **[InstAr-500k](https://huggingface.co/datasets/ClusterlabAi/InstAr-500k)** — 500k Arabic instructions for SFT.
- **[Arabic Dolly](https://huggingface.co/datasets?search=arabic+dolly)** — Arabic version of the Dolly instruction dataset.

### Dialectal Arabic Datasets

- **[MADAR](https://camel.abudhabi.nyu.edu/madar/)** — Multi-Arabic Dialect Applications and Resources covering 25 cities.
- **[NADI](https://nadi.dlnlp.ai/)** — Nuanced Arabic Dialect Identification shared task datasets.
- **[QADI](https://github.com/qcri/QADI)** — Qatari Arabic Dialect Identification dataset.
- **[Arabic Online Commentary (AOC)](https://www.cs.jhu.edu/~ozaidan/AOC/)** — Newspaper comments labeled by dialect.

### Domain-Specific Datasets

- **[Tashkeela](https://sourceforge.net/projects/tashkeela/)** — Large corpus for Arabic diacritization (75M+ words).
- **[ArabicaQA](https://huggingface.co/papers/2403.17848)** — Comprehensive Arabic Question Answering dataset.
- **[AraSum](https://huggingface.co/datasets?search=arasum)** — Arabic text summarization datasets.
- **[Arabic Sentiment Analysis datasets](https://huggingface.co/datasets?search=arabic+sentiment)** — Multiple sentiment-labeled corpora.
- **[Quran QA Datasets](https://sites.google.com/view/quran-qa-2023/)** — Religious-domain QA over the Holy Quran.

---

- [📰 Blogs & Newsletters](#-blogs--newsletters)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---
