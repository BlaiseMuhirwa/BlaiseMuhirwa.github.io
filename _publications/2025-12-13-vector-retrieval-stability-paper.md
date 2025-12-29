---
title: "Breaking the Curse of Dimensionality: On the Stability of Modern Vector Retrieval"
collection: publications
urlslug: "vector-retrieval-stability-paper"
permalink: /publication/2025-12-13-vector-retrieval-stability-paper
excerpt: 'Modern vector databases enable efficient retrieval over high-dimensional neural embeddings, powering applications from web search to retrieval-augmented generation. However, classical theory predicts such tasks should suffer from the curse of dimensionality, where distances between points become nearly indistinguishable, thereby crippling efficient nearest-neighbor search. We revisit this paradox through the lens of stability, the property that small perturbations to a query do not radically alter its nearest neighbors. Building on foundational results, we extend stability theory to three key retrieval settings widely used in practice: (i) multi-vector search, where we prove that the popular Chamfer distance metric preserves single-vector stability, while average pooling aggregation may destroy it; (ii) filtered vector search, where we show that sufficiently large penalties for mismatched filters can induce stability even when the underlying search is unstable; and (iii) sparse vector search, where we formalize and prove novel sufficient stability conditions. Across synthetic and real datasets, our experimental results match our theoretical predictions, offering concrete guidance for model and system design to avoid the curse of dimensionality.'
date: 2025-12-13
venue: '(Preprint)'
paperurl: 'https://arxiv.org/pdf/2512.12458'
citation: 'Vihan Lakshman, <u>Blaise Munyampirwa</u>, Julian Shun, Benjamin Coleman'
---
Modern vector databases enable efficient retrieval over high-dimensional neural embeddings, powering applications from web search to retrieval-augmented generation. However, classical theory predicts such tasks should suffer from the curse of dimensionality, where distances between points become nearly indistinguishable, thereby crippling efficient nearest-neighbor search. We revisit this paradox through the lens of stability, the property that small perturbations to a query do not radically alter its nearest neighbors. Building on foundational results, we extend stability theory to three key retrieval settings widely used in practice: (i) multi-vector search, where we prove that the popular Chamfer distance metric preserves single-vector stability, while average pooling aggregation may destroy it; (ii) filtered vector search, where we show that sufficiently large penalties for mismatched filters can induce stability even when the underlying search is unstable; and (iii) sparse vector search, where we formalize and prove novel sufficient stability conditions. Across synthetic and real datasets, our experimental results match our theoretical predictions, offering concrete guidance for model and system design to avoid the curse of dimensionality.

[Download](https://arxiv.org/pdf/2512.12458)

Authors: Vihan Lakshman, <u>Blaise Munyampirwa</u>, Julian Shun, Benjamin Coleman
