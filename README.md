# Summarization
Academic Paper Summarization: Comparing different Extractive and Abstractive Models result

**Project Overview**
This project explores various summarization techniques to compare their performance and output quality, focusing specifically on academic paper summarization. Summarization models are broadly categorized into extractive and abstractive types, each suited to different use cases:

Extractive Models: Select key sentences directly from the input text. These methods are straightforward and preserve the original text's structure but may lack coherence.
Abstractive Models: Generate summaries by rephrasing and condensing the content, often producing more natural and coherent outputs at the cost of higher computational complexity.
The goal of this project is to analyze and compare different summarization methods to understand their suitability for academic text. Based on the type of input text, different models can be employed to achieve optimal results.

**Methods Implemented**
1. TextRank (Extractive)
A graph-based ranking algorithm inspired by PageRank.
Sentences are represented as nodes, and edges represent similarities between them.
Strengths: Simplicity and effectiveness for short, concise summaries.
Weaknesses: Tends to prefer longer sentences and may lack coherence in complex texts.
2. Word Frequency Model (Extractive)
Ranks sentences based on the frequency of important words within them.
Strengths: Fast and computationally efficient.
Weaknesses: Overemphasizes frequent terms and may ignore semantic meaning.
3. SBERTExt (Modified Extractive Model)
An enhanced version of SBERT designed to address extreme similarity problems.
Introduces a threshold for sentence similarity to improve diversity.
Strengths: Leverages transformers for semantic understanding and avoids redundancy.
4. Pegasus (Abstractive Model)
A state-of-the-art transformer model optimized for abstractive summarization.
Trained specifically for generating coherent summaries in contexts like academic papers.
Strengths: Produces human-like, coherent summaries.

**Key Insights**
The type of text plays a crucial role in choosing the appropriate summarization model.
Extractive models are effective for shorter, fact-based summaries, while abstractive models excel in generating cohesive, human-like summaries suitable for academic or narrative texts.
Pegasus was chosen for abstractive summarization due to its superior performance with academic papers.
