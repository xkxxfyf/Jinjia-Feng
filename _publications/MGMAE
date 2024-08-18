---
title: "MGMAE: Molecular Representation Learning by Reconstructing Heterogeneous Graphs with A High Mask Ratio"
collection: publications
category: manuscripts
permalink: /publication/MGMAE
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-08-03
venue: '31rd ACM International Conference on Information and Knowledge Management'
---

**Abstract:**
Masked autoencoder (MAE), as an effective self-supervised learner for computer vision and natural language processing, has been recently applied to molecule representation learning.
In this paper, we identify two issues in applying MAE to pre-train Transformer-based models on molecular graphs that existing works have ignored.
(1) As only atoms are abstracted as tokens and then reconstructed, the chemical bonds are not decided in the decoded molecule, making molecules with different arrangements of the same atoms indistinguishable.
(2) Although a high mask ratio that corresponds to a challenging reconstruction task has been proved beneficial in the vision domain, it cannot be trivially leveraged on molecular graphs as there is less redundancy of information in graph data.
To resolve these issues, we propose a novel framework, \textbf{M}olecular \textbf{G}raph \textbf{M}ask \textbf{A}uto\textbf{E}ncoder (MGMAE).
As the first step in MGMAE, we transform each molecular graph into a heterogeneous atom-bond graph to fully use the bond attributes and design unidirectional position encoding for such graphs.
Then we propose a hybrid masking mechanism that exploits the complementary nature between atoms' attributive and spatial features.
Meanwhile, we compensate for the mask embedding by a dynamic aggregation representation that exploits the correlations between topologically adjacent tokens.
As a result, MGMAE can reconstruct the masked atoms, the masked bonds, and the relative distance among atoms simultaneously, with a high mask ratio.
We compare MGMAE with the state-of-the-art methods on various molecular benchmarks and show the competitiveness of MGMAE in both regression and classification tasks.
