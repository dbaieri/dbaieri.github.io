---
title: "Rematching: Low-Resolution Representations for Scalable Shape Correspondence"
collection: publications
category: conferences
permalink: /publication/rematching
excerpt: 'Scaling shape correspondence algorithms through a very efficient, topology- and geometry-preserving remeshing algorithm.'
date: 2024-12-02
venue: 'European Conference on Computer Vision'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-72913-3_11'
bibtexurl: 'https://citation-needed.springer.com/v2/references/10.1007/978-3-031-72913-3_11?format=bibtex&flavour=citation'
citation: 'Filippo Maggioli, Daniele Baieri, Emanuele Rodolà, Simone Melzi. ReMatching: Low-Resolution Representations for Scalable Shape Correspondence. ECCV 2024. Lecture Notes in Computer Science, vol 15095.'
---

We introduce ReMatching, a novel shape correspondence solution based on the functional maps framework. Our method, by exploiting a new and appropriate re-meshing paradigm, can target shape-matching tasks even on meshes counting millions of vertices, where the original functional maps does not apply or requires a massive computational cost. The core of our procedure is a time-efficient remeshing algorithm which constructs a low-resolution geometry while acting conservatively on the original topology and metric. These properties allow translating the functional maps optimization problem on the resulting low-resolution representation, thus enabling efficient computation of correspondences with functional map approaches. Finally, we propose an efficient technique for extending the estimated correspondence to the original meshes. We show that our method is more efficient and effective through quantitative and qualitative comparisons, outperforming state-of-the-art pipelines in quality and computational cost.