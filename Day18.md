# Day 18 - Getting Started with Ollama

## Today's Learning

Today, I learned about Ollama, an open-source tool that allows developers to run Large Language Models (LLMs) locally on their computers.

Instead of sending data to cloud-based AI services, Ollama enables users to download and run AI models directly on their own machine.

This is especially useful for developers who want to build AI applications while keeping their data private.

---

## What is Ollama?

Ollama is a lightweight platform for running open-source AI models locally.

It simplifies the process of downloading, managing, and interacting with Large Language Models (LLMs).

With Ollama, developers can build AI-powered applications without relying on cloud APIs.

---

## Why Use Ollama?

Ollama offers several advantages:

- Run AI models locally.
- Better privacy since data stays on your computer.
- No internet connection required after downloading the model.
- Lower cost by avoiding API usage.
- Easy integration with applications through a local API.

---

## Popular Models Supported by Ollama

Some popular models that can be used with Ollama include:

- Llama 3
- Mistral
- Gemma
- Phi
- DeepSeek
- Qwen

---

## Installing Ollama

Visit the official website and install Ollama for your operating system.

After installation, verify it by running:

```bash
ollama --version
```

---

## Running Your First Model

Download and run Llama 3:

```bash
ollama run llama3
```

Ollama will download the model (if not already installed) and start an interactive chat session.

---

## Useful Commands

List installed models:

```bash
ollama list
```

Run a model:

```bash
ollama run llama3
```

Remove a model:

```bash
ollama rm llama3
```

Show installed version:

```bash
ollama --version
```

---

## Applications of Ollama

Ollama can be used for:

- AI Chatbots
- Code Generation
- Resume Review
- Document Summarization
- Learning Assistant
- Offline AI Applications
- Building RAG Systems

---

## Key Takeaways

- Ollama allows developers to run LLMs locally.
- It improves privacy and reduces dependency on cloud services.
- It supports multiple open-source AI models.
- It is an excellent tool for building AI applications and experimenting with LLMs.

---

## Reflection

Today, I learned that I don't always need a cloud API to work with AI models. Ollama makes it easy to run powerful open-source models locally, helping developers build AI applications while maintaining privacy and reducing costs.

---

#100DaysOfSoftwareEngineering
#AI
#Ollama
#LLM
#LearningInPublic