---
title: "Word Embedding, Language Model and BLUE score"
date: "2024-05-15"
categories:
  - Blog
tags:
  - Idea from the internet
  - Reread it
---

Simplified: Word Embeddings does not consider context, Language Models does.

E.g Word2Vec, GloVe, or fastText has one fixed vector per word.

Think of the following two sentences:

The fish ate the cat.

and

The cat ate the fish.

If you averaged their word embeddings, they would have the same vector, but, in reality, their meaning (semantics) is very different.

Then the concept of contextualized word embeddings arose with language models that do consider the context, and give different embeddings depending on the context.

Both word embeddings (e.g. Word2Vec) and language models (e.g. BERT) are ways of representing text, whereas language models capture more information and are considered state-of-the-art for representing natural language in a vectorized format.

BLEU score is an algorithm for evaluating the quality of text which has been machine-translated from one natural language to another. Which is not directly related to the difference between traditional word embeddings and contextualized word embeddings (aka language models).

