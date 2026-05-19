<div align="center">

<img src="banner.png" alt="Awesome Arabic AI Banner" width="100%"/>

<br>

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
- [📰 Blogs & Newsletters](#-blogs--newsletters)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)


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
## 🏆 Benchmarks & Leaderboards

Standardized evaluation suites for measuring Arabic AI model performance.

- **[Open Arabic LLM Leaderboard (OALL)](https://huggingface.co/spaces/OALL/Open-Arabic-LLM-Leaderboard)** — The official HuggingFace leaderboard for Arabic LLMs. Real-time rankings and evaluations.
- **[AlGhafa Benchmark](https://huggingface.co/datasets/OALL/AlGhafa-Arabic-LLM-Benchmark-Native)** — Multiple-choice benchmark for zero-shot and few-shot evaluation of Arabic LLMs.
- **[ArabicMMLU](https://huggingface.co/datasets/MBZUAI/ArabicMMLU)** — Arabic version of the popular MMLU benchmark, covering 40+ subjects.
- **[HELM Arabic](https://crfm.stanford.edu/helm/arabic/latest/)** — Stanford CRFM's Holistic Evaluation of Language Models for Arabic.
- **[ABB - Arabic Broad Benchmark](https://silma.ai/arabic-llm-benchmark)** — Comprehensive benchmark by SILMA.AI covering diverse Arabic tasks.
- **[ArabicaQA Benchmark](https://huggingface.co/papers/2403.17848)** — Question answering benchmark with extensive LLM evaluations.
- **[AraSTS](https://huggingface.co/datasets?search=arasts)** — Arabic Semantic Textual Similarity benchmark.
- **[ARCD](https://huggingface.co/datasets/arcd)** — Arabic Reading Comprehension Dataset.
- **[CIDAR-EVAL](https://huggingface.co/datasets/arbml/CIDAR-EVAL-100)** — Cultural alignment evaluation for Arabic LLMs.

---

## 🔊 Speech & Audio

Arabic speech recognition, synthesis, and audio processing resources.

### Speech Recognition (ASR)

- **[Whisper Arabic Fine-tunes](https://huggingface.co/models?language=ar&pipeline_tag=automatic-speech-recognition)** — Collection of Whisper models fine-tuned for Arabic ASR.
- **[ArTST](https://github.com/mbzuai-nlp/ArTST)** — Arabic Text and Speech Transformer by MBZUAI. Unified speech model for Arabic.
- **[MGB-2 Dataset](https://arabicspeech.org/mgb2/)** — Large-scale Arabic broadcast news corpus for ASR.
- **[MGB-3 Dataset](https://arabicspeech.org/mgb3/)** — Egyptian dialect ASR challenge dataset.
- **[Common Voice Arabic](https://commonvoice.mozilla.org/ar)** — Mozilla's crowdsourced Arabic speech dataset.
- **[QASR](https://arabicspeech.org/qasr/)** — Largest transcribed Arabic speech corpus (2000+ hours).

### Text-to-Speech (TTS)

- **[ClArTTS](https://www.clartts.com/)** — Classical Arabic text-to-speech corpus and models.
- **[Arabic SpeechT5](https://huggingface.co/MBZUAI/speecht5_tts_clartts_ar)** — SpeechT5 adapted for Arabic TTS.
- **[Tacotron2-Arabic](https://github.com/youssefsharief/arabic-tacotron-tts)** — Arabic implementation of Tacotron 2.
- **[XTTS Arabic](https://huggingface.co/coqui/XTTS-v2)** — Coqui XTTS supporting Arabic voice cloning.

---

## 👁️ Vision & OCR

Optical Character Recognition and computer vision for Arabic script.

- **[QARI-OCR](https://huggingface.co/NAMAA-Space/Qari-OCR-0.3-Arabic-2B-Instruct)** — High-accuracy open-source Arabic OCR model with strong performance on handwritten and printed text.
- **[Kraken OCR (Arabic models)](https://kraken.re/)** — Open-source OCR engine with trained Arabic models.
- **[EasyOCR Arabic](https://github.com/JaidedAI/EasyOCR)** — Easy-to-use OCR library with Arabic support.
- **[Tesseract Arabic](https://github.com/tesseract-ocr/tessdata)** — Google's Tesseract OCR with Arabic language data.
- **[KHATT Database](http://khatt.ideas2serve.net/)** — Arabic handwritten text database for research.
- **[Arabic Document Layout Analysis](https://github.com/topics/arabic-document-analysis)** — Tools for understanding Arabic document structure.

---

## 🛠️ Libraries & Tools

Production-ready libraries for Arabic text processing and NLP.

- **[CAMeL Tools](https://github.com/CAMeL-Lab/camel_tools)** — Comprehensive Python toolkit for Arabic NLP by Columbia University. Includes tokenization, morphology, dialect ID, NER, and more.
- **[Farasa](https://farasa.qcri.org/)** — Fast and accurate Arabic NLP toolkit by QCRI. Segmentation, POS, NER, diacritization.
- **[MADAMIRA](https://camel.abudhabi.nyu.edu/madamira/)** — Morphological analyzer and disambiguator for Arabic.
- **[PyArabic](https://github.com/linuxscout/pyarabic)** — Python library for Arabic text processing utilities.
- **[Tashaphyne](https://github.com/linuxscout/tashaphyne)** — Arabic light stemmer and root extractor.
- **[Tnkeeh](https://github.com/ARBML/tnkeeh)** — Arabic text preprocessing library with normalization tools.
- **[Maha](https://github.com/TRoboto/Maha)** — Text processing library with rich Arabic support.
- **[ar-corrector](https://github.com/Sirine26/Spell-Checker-for-Arabic)** — Arabic spell-checker and corrector.
- **[Arabic-Stopwords](https://github.com/mohataher/arabic-stop-words)** — Comprehensive Arabic stopwords list.
- **[arabic-reshaper](https://github.com/mpcabd/python-arabic-reshaper)** — Reshape Arabic text for correct display.
- **[python-bidi](https://github.com/MeirKriheli/python-bidi)** — Bidirectional text handling for Arabic.

---
## 📚 Research Papers & Surveys

Foundational and recent academic work on Arabic AI and NLP.

- **[The Landscape of Arabic Large Language Models](https://cacm.acm.org/arab-world-regional-special-section/the-landscape-of-arabic-large-language-models/)** — Comprehensive ACM survey of Arabic LLM development, architectures, and challenges.
- **[Evaluating Arabic Large Language Models: A Survey](https://arxiv.org/html/2510.13430v1)** — Systematic review of Arabic LLM evaluation methodologies and benchmarks.
- **[A Review of Arabic Post-Training Datasets and Their Limitations](https://arxiv.org/html/2507.14688v2)** — Critical analysis of instruction-tuning datasets for Arabic.
- **[Jais Technical Report](https://arxiv.org/abs/2308.16149)** — Original paper introducing the Jais family of Arabic LLMs.
- **[AceGPT Paper](https://arxiv.org/abs/2309.12053)** — Technical details of AceGPT and its RLAIF approach.
- **[AraBERT Paper](https://arxiv.org/abs/2003.00104)** — Foundational paper on transformer-based Arabic language understanding.
- **[CAMeLBERT Paper](https://arxiv.org/abs/2103.06678)** — Variant-aware BERT models for Modern Standard, Dialectal, and Classical Arabic.
- **[ArabicaQA Paper](https://arxiv.org/abs/2403.17848)** — Large-scale Arabic question answering dataset and benchmark.
- **[ArXiv Arabic NLP Papers](https://arxiv.org/search/?query=arabic+nlp&start=0)** — Live feed of latest Arabic NLP research on ArXiv.

---

## 🎓 Courses & Tutorials

Learning resources for getting started with Arabic AI development.

- **[HuggingFace Arabic NLP Course](https://huggingface.co/learn)** — Free course covering NLP fundamentals applicable to Arabic.
- **[Arabic NLP with Python (CAMeL Tools Tutorials)](https://github.com/CAMeL-Lab/camel_tools/tree/master/docs/tutorials)** — Hands-on tutorials for Arabic text processing.
- **[Arabic Speech Recognition Tutorial](https://huggingface.co/blog/fine-tune-whisper)** — Fine-tuning Whisper for Arabic ASR (adaptable guide).
- **[Fine-tuning LLMs for Arabic](https://huggingface.co/blog/silma-ai)** — SILMA AI's blog series on Arabic LLM development.
- **[Arabic NLP Resources by ARBML](https://github.com/ARBML)** — Open-source organization with Arabic NLP tutorials and tools.
- **[Stanford CS224N Lectures](https://web.stanford.edu/class/cs224n/)** — General NLP course; concepts transfer well to Arabic work.

---

## 🏢 Companies & Startups

Leading organizations driving Arabic AI innovation in the MENA region and beyond.

### Research Institutes & Government-Backed

- **[TII - Technology Innovation Institute](https://www.tii.ae/)** (UAE) — Creators of Falcon and Noor LLMs.
- **[MBZUAI](https://mbzuai.ac.ae/)** (UAE) — Leading AI research university, behind Jais and ArTST.
- **[QCRI - Qatar Computing Research Institute](https://www.hbku.edu.qa/en/qcri)** (Qatar) — Creators of Fanar and Farasa.
- **[SDAIA](https://sdaia.gov.sa/)** (Saudi Arabia) — Creators of ALLaM, national AI authority.
- **[KAUST AI Initiative](https://cemse.kaust.edu.sa/ai)** (Saudi Arabia) — Research behind AceGPT.

### Startups & Companies

- **[Inception (G42)](https://www.inceptionai.ai/)** (UAE) — Behind Jais; one of the largest AI companies in MENA.
- **[Humain](https://humain.ai/)** (Saudi Arabia) — State-backed AI company under PIF.
- **[SILMA AI](https://silma.ai/)** (Saudi Arabia) — Arabic LLM and benchmark provider.
- **[Mozn](https://mozn.com/)** (Saudi Arabia) — AI solutions and Arabic NLP.
- **[Intella](https://www.intella.ai/)** (Saudi Arabia) — Arabic voice AI and ASR.
- **[Synapse Analytics](https://synapse-analytics.io/)** (Egypt) — AI platform with Arabic capabilities.
- **[Bayzat](https://www.bayzat.com/)** (UAE) — HR-Tech leveraging Arabic NLP.
- **[Cequens](https://www.cequens.com/)** (Egypt) — Communications platform with Arabic AI features.

---

## 🌐 Communities & Conferences

Connect with the Arabic AI community.

### Conferences & Workshops

- **[ArabicNLP Conference](https://arabicnlp2024.sigarab.org/)** — Premier annual conference for Arabic NLP research.
- **[WANLP Workshop](https://sites.google.com/view/wanlp)** — Workshop on Arabic Natural Language Processing (co-located with major venues).
- **[OSACT Workshop](https://www.lrec-conf.org/proceedings/lrec2022/workshops/OSACT/)** — Open-Source Arabic Corpora and Processing Tools workshop.

### Communities

- **[HuggingFace Arabic Community](https://huggingface.co/CohereForAI)** — Arabic AI models, datasets, and discussions.
- **[ARBML on GitHub](https://github.com/ARBML)** — Open-source Arabic ML organization.
- **[SIGARAB](https://sigarab.org/)** — ACL Special Interest Group on Arabic NLP.
- **[Arabic AI Discord Servers](https://discord.gg/)** — Multiple community servers for Arabic AI discussions.
- **[r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/)** — Active discussions including Arabic LLMs.

---

## 📰 Blogs & Newsletters

Stay updated on Arabic AI developments.

- **[SILMA AI Blog](https://huggingface.co/blog/silma-ai)** — Regular posts on Arabic LLMs, benchmarks, and best practices.
- **[Middle East AI News](https://www.middleeastainews.com/)** — News and analysis on AI in the MENA region.
- **[TII Blog](https://www.tii.ae/news)** — Updates from the Technology Innovation Institute.
- **[Inception Blog](https://www.inceptionai.ai/insights)** — Insights from the team behind Jais.
- **[MAGNiTT](https://magnitt.com/)** — MENA startup ecosystem coverage including AI.
- **[Hub71 Insights](https://www.hub71.com/latest-news)** — Abu Dhabi tech ecosystem and AI startup news.

---
## 🤝 Contributing

Contributions are **warmly welcomed**! This list grows stronger with community input.

**How to contribute:**

1. **Found a great resource we missed?** Open a [Pull Request](https://github.com/OsamaALHajj/awesome-arabic-ai/pulls).
2. **Spotted a broken link or outdated info?** Open an [Issue](https://github.com/OsamaALHajj/awesome-arabic-ai/issues).
3. **Want to suggest a new category?** Start a [Discussion](https://github.com/OsamaALHajj/awesome-arabic-ai/discussions).

Please read our [Contribution Guidelines](CONTRIBUTING.md) before submitting.

**Quick rules:**
- ✅ Resource must be related to Arabic AI/NLP/Speech/Vision.
- ✅ Add resources in alphabetical or logical order within their section.
- ✅ Include a clear, concise one-line description.
- ✅ Prefer open-source and actively maintained projects.
- ❌ No duplicate entries.
- ❌ No paid courses or affiliate links without disclosure.

---

## 🌟 Show Your Support

If this list helped you, please consider:

- ⭐ **Starring** the repository
- 🔄 **Sharing** it with your network
- 🤝 **Contributing** a resource or improvement
- 💬 **Joining** the discussion to shape the future of Arabic AI

Every star helps more Arabic AI builders discover these resources! 🚀

---

## 🙏 Acknowledgments

This list stands on the shoulders of giants. Special thanks to:

- The **Arabic NLP research community** for decades of foundational work.
- **MBZUAI, TII, QCRI, SDAIA, KAUST**, and other institutions advancing Arabic AI.
- **Open-source contributors** who make Arabic AI accessible to everyone.
- **[Sindre Sorhus](https://github.com/sindresorhus)** for creating the Awesome List standard.
- **Every contributor** who helps keep this list current and comprehensive.

---

## 📜 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This work is licensed under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — you may freely use, modify, and distribute this content without restriction.

---

## 👤 Maintainer

**Osama AL Hajj**

[![GitHub](https://img.shields.io/badge/GitHub-OsamaALHajj-181717?style=flat&logo=github)](https://github.com/OsamaALHajj)

---

<div align="center">

### ⭐ If you find this list valuable, please star it to help others discover it!

**Made with ❤️ for the Arabic AI community**

**صُنع بكل حب لمجتمع الذكاء الاصطناعي العربي**

[⬆ Back to Top](#-awesome-arabic-ai-)

</div>

---
