# Big Heading

## Smaller Heading

- Bullet point
- Another point

**bold text**


# Week 1 Notes — Understanding LLMs

## What is an LLM?

LLM stands for Large Language Model. It is an AI system trained on massive amounts of text from books, websites, articles, and conversations. Instead of “thinking” like humans, it predicts the most likely next word based on patterns it learned during training.

Examples include ChatGPT, Claude, Gemini, and Llama.

An LLM is good at:
- answering questions
- summarizing information
- writing content
- coding
- reasoning through language tasks

But it does not truly “understand” facts or emotions the way humans do.

---

## What are tokens?

Tokens are small pieces of text that AI models process instead of full sentences.

A token can be:
- a word
- part of a word
- punctuation
- or even spaces

For example:

"ChatGPT is useful"

might become several tokens.

AI models read and generate tokens one at a time very quickly.

Why tokens matter:
- pricing is based on tokens
- model context windows are measured in tokens
- longer prompts use more tokens
- responses are also generated token-by-token

---

## What is hallucination?

Hallucination happens when an AI model confidently gives false or made-up information.

Examples:
- inventing statistics
- creating fake citations
- giving wrong facts
- making up APIs or company details

This happens because LLMs are prediction systems, not truth systems.

As product managers, hallucination matters because:
- users may trust incorrect answers
- confidence can look convincing
- high-risk workflows need verification layers

Common mitigation strategies:
- retrieval from trusted sources
- human review
- grounding with real data
- evaluation systems
- limiting open-ended generation

---

## Training vs Inference

Training:
The model learns patterns from massive datasets. This is expensive and happens before users interact with the model.

Inference:
The model generates answers in real time after deployment when users type prompts.

Training is learning.
Inference is using what was learned.

---

## My Key Takeaways

- LLMs are prediction engines trained on huge text datasets
- Tokens are the basic units AI models process
- Hallucination is one of the biggest product risks in AI systems
- AI product design is not just about intelligence — it is about reliability, trust, and workflow integration
