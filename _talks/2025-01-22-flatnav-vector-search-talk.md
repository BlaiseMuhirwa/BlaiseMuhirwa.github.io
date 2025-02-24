---
title: "Optimizing HNSW in the age of vector databases"
collection: talks
urlslug: "flatnav-vector-search-talk"
type: "Talk"
permalink: /talks/2025-01-22-flatnav-vector-search-talk
venue: "Amazon Search, Palo Alto, CA"
date: 2025-01-22
excerpt: 'Near neighbor search over vector embeddings is a linchpin of modern ML infrastructure, forming a core component of established applications to search and retrieval as well as emerging LLM applications via retrieval-augmented generation (RAG). The seminal Hierarchical Navigable Small World (HNSW) graph index is perhaps the most popular choice in current vector database implementations. In this talk, we share two methods to significantly optimize the HNSW memory consumption and query latency, by removing the hierarchical component of the index and reordering the graph layout. Our extensive benchmark studies show that these methods are simple, easy to productionize, and offer robust performance improvements (on the order of 20-30% peak memory and latency).'
slidesurl: 'https://blaisemuhirwa.github.io/files/flatnav-talk.pdf'
location: "Palo Alto, CA"
---

**Resources:** [[Slides](https://blaisemuhirwa.github.io/files/flatnav-talk.pdf)]

**Abstract:**
Near neighbor search over vector embeddings is a linchpin of modern ML infrastructure, forming a core component of established applications to search and retrieval as well as emerging LLM applications via retrieval-augmented generation (RAG). The seminal Hierarchical Navigable Small World (HNSW) graph index is perhaps the most popular choice in current vector database implementations. In this talk, we share two methods to significantly optimize the HNSW memory consumption and query latency, by removing the hierarchical component of the index and reordering the graph layout. Our extensive benchmark studies show that these methods are simple, easy to productionize, and offer robust performance improvements (on the order of 20-30% peak memory and latency).
