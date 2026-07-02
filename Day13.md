# Day 13 - Tokens and Context Window

## Today's Learning

Today, I learned about Tokens and Context Window, two important concepts that determine how Large Language Models (LLMs) process information.

Understanding these concepts helps in writing better prompts and managing long conversations with AI.

---

## What are Tokens?

A token is the smallest unit of text that an AI model processes.

A token can be:
- A word
- Part of a word
- A punctuation mark
- A number
- A symbol

For example:

Sentence:

```
Prompt Engineering is amazing.
```

This sentence is divided into multiple tokens before being processed by the AI model.

Instead of reading complete sentences, AI reads and understands tokens.

---

## What is a Context Window?

A Context Window is the maximum number of tokens an AI model can process at one time.

The context window includes:

- System instructions
- User prompts
- Previous conversation
- AI responses

When the total number of tokens exceeds the context window, older information may be forgotten or removed.

---

## Why is Context Window Important?

A larger context window allows AI to:

- Remember longer conversations
- Analyze large documents
- Generate better summaries
- Maintain conversation continuity
- Work with large codebases

---

## Example

### Short Prompt

```
Explain Java Collections.
```

The AI only processes this single request.

---

### Long Conversation

If you continue chatting for hundreds of messages, the AI eventually reaches its context limit.

Older messages may no longer be considered while generating new responses.

---

## Tips for Better Prompting

To make the best use of the context window:

- Keep prompts clear and concise.
- Include only relevant information.
- Provide necessary context instead of unnecessary details.
- Break large tasks into smaller prompts.
- Summarize previous information when continuing long conversations.

---

## Applications in Software Engineering

Understanding tokens and context windows helps in:

- Writing better prompts
- Generating large code snippets
- Debugging code
- Summarizing documentation
- Reviewing source code
- Building AI-powered applications

---

## Key Takeaways

- AI processes text as tokens, not entire sentences.
- Every prompt and response consumes tokens.
- The context window defines how much information AI can remember during a conversation.
- Efficient prompts improve AI performance and make better use of the available context.

---

## Reflection

Today, I learned that AI doesn't "remember" conversations like humans do. It processes information within a limited context window. By understanding tokens and context limits, I can write more effective prompts and communicate with AI more efficiently.

---

#100DaysOfSoftwareEngineering
#PromptEngineering
#LearningInPublic