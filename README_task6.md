# alpha_ai-alpha_ai_task6

Task 6: NLP

Given any two blog posts, find similarity among the posts based on examining
two text entities, images etc. and determining whether they have the same
meaning. In order to obtain high accuracy on this task, thorough syntactic and
semantic analysis of the two text entities is required.

For this tasks, I've used the following blogs:

BLOG 1: A Brief Inquiry into Independent Indian Music using the Spotify API
by Pratyush Sinha (myself)

Link:https://pratyushsinha0811.wordpress.com/2021/06/18/retro-cameras/

BLOG 2: Getting started with Spotify's API and Spotipy
by Max Tingle

Link: https://medium.com/@maxtingle/getting-started-with-spotifys-api-spotipy-197c3dc6353b

For the model, I've used Embeddings from Language Models(ELMo)

ELMo is an NLP framework developed by AllenNLP. ELMo word vectors are calculated using a two-layer bidirectional language model (biLM). Each layer comprises forward and backward pass.
Unlike Glove and Word2Vec, ELMo represents embeddings for a word using the complete sentence containing that word. Therefore, ELMo embeddings are able to capture the context of the word used in the sentence and can generate different embeddings for the same word used in a different context in different sentences.

*This task didn't require me to pre-process, lemmatize, stem or perform a custom feature extraction as I've used Transfer Learning with Elmo Embeddings with a retraining using 'trainable=True'

*To obtain similarity between two word vectors, I've used Cosine Similarity.
