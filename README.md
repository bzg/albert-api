<div id="toc">
  <ul align="center" style="list-style: none">
    <summary><h1>🚀 Albert API</h1></summary>

*French version below*

**Enterprise-ready Generative AI API Gateway | Open Source | Sovereign Infrastructure**

**Developed by the French Government 🇫🇷**

[![Code Coverage](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/etalab-ia/albert-api/refs/heads/main/.github/badges/coverage.json)](https://github.com/etalab-ia/albert-api)

[**Documentation**](https://albert.api.etalab.gouv.fr/documentation) | [**Playground**](https://albert.api.etalab.gouv.fr/playground) | [**API Status**](https://albert.api.etalab.gouv.fr/status) | [**Swagger**](https://albert.api.etalab.gouv.fr/swagger)

  </ul>
</div>

## 🔥 Why Albert API?

Albert API is an **enterprise-ready open-source gateway** for deploying **generative AI models** on your infrastructure:

* 🚦 **Robust API Gateway:** Load balancing, authentication, and seamless integration with OpenAI, vLLM, HuggingFace TEI.
* 📚 **Advanced Features:** Built-in Retrieval-Augmented Generation (RAG), OCR, audio transcription, and more.
* 🌐 **Open Standards:** Compatible with OpenAI APIs, LangChain, and LlamaIndex.
* 🛠️ **Deployment Flexibility:** Host generative AI securely on your own infrastructure, ensuring full data sovereignty.

## 🎯 Key Features

### API Gateway

* **Unified Access:** Single API gateway for multiple generative AI model backends:

  * **OpenAI** (Language, Embeddings, Reranking, Transcription)
  * **vLLM** (Language)
  * **HuggingFace TEI** (Embeddings, Reranking)

### Advanced AI Capabilities

* **RAG Integration:** Efficiently query vector databases using Elasticsearch or Qdrant.
* **Audio & Vision:** Transcribe audio (Whisper) and perform OCR on PDF documents.
* **Enhanced Security:** Built-in API key authentication.

## 📊 Comparison

| Feature              | Albert API ✅ | LiteLLM   | OpenRouter | OpenAI API |
| -------------------- | ------------ | --------- | ---------- | ---------- |
| Fully Open Source    | ✔️           | Partially | ❌          | ❌          |
| Data Sovereignty     | ✔️           | ✔️        | ❌          | ❌          |
| Multiple AI Backends | ✔️           | ✔️        | ✔️         | ❌          |
| Built-in RAG         | ✔️           | ❌         | ❌          | ❌          |
| Built-in OCR         | ✔️           | ❌         | ❌          | ❌          |
| Audio Transcription  | ✔️           | ❌         | ❌          | ✔️         |
| Flexible Deployment  | ✔️           | ✔️        | ❌          | ❌          |
| OpenAI Compatibility | ✔️           | ✔️        | ✔️         | ✔️         |

## 🚀 Quickstart

Deploy Albert API quickly on your own infrastructure:

* [Deployment Guide](./docs/deployment.md)

## 📘 Tutorials & Guides

Explore practical use cases:

* [**Chat Completions**](https://colab.research.google.com/github/etalab-ia/albert-api/blob/main/docs/tutorials/chat_completions.ipynb)
* [**Multi-Model Access**](https://colab.research.google.com/github/etalab-ia/albert-api/blob/main/docs/tutorials/models.ipynb)
* [**Retrieval-Augmented Generation (RAG)**](https://colab.research.google.com/github/etalab-ia/albert-api/blob/main/docs/tutorials/retrieval_augmented_generation.ipynb)
* [**Knowledge Database Import**](https://colab.research.google.com/github/etalab-ia/albert-api/blob/main/docs/tutorials/import_knowledge_database.ipynb)
* [**Audio Transcriptions**](https://colab.research.google.com/github/etalab-ia/albert-api/blob/main/docs/tutorials/audio_transcriptions.ipynb)
* [**PDF OCR**](https://colab.research.google.com/github/etalab-ia/albert-api/blob/main/docs/tutorials/pdf_ocr.ipynb)

## 🤝 Contribute

Albert API thrives on open-source contributions. Join our community!

* [Contribution Guide](./CONTRIBUTING.md)

---

# 🇫🇷 Albert API (version française)

**API open source pour modèles d'IA générative | Infrastructure souveraine**

Albert API, porté par l'[OPI de la DINUM](https://www.numerique.gouv.fr/dinum/), est le service d'IA générative de référence de l'État français, homologué pour des traitements sécurisés. Il propose une solution prête pour la production destinée à l’hébergement souverain et performant d’IA génératives avancées sur votre infrastructure.

## Points forts

* 🔐 Sécurité et souveraineté des données
* 🧩 API unique compatible OpenAI, vLLM et HuggingFace
* 🔎 Recherche avancée par RAG et vector stores

Consultez la [documentation](https://albert.api.etalab.gouv.fr/documentation) ou déployez rapidement votre instance via le [guide de déploiement](./docs/deployment.md).

[Contribuez au projet !](./CONTRIBUTING.md)
