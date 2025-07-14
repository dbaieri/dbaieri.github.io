---
title: "GSEdit: Efficient Text-Guided Editing of 3D Objects via Gaussian Splatting"
collection: publications
category: preprint
permalink: /publication/gsedit
excerpt: 'A fast method for text-driven editing of 3D Gaussian Splatting models based on Score Distillation Sampling.'
date: 2024-05-21
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2403.05154'
bibtexurl: '/files/gsedit-bibtex.bib'
citation: 'Francesco Palandra, Andrea Sanchietti, Daniele Baieri, and Emanuele Rodolà. Gsedit: Efficient text-guided editing of 3d objects via gaussian splatting. arXiv preprint. arXiv:2403.05154, 2024'
---

We present GSEdit, a pipeline for text-guided 3D object editing based on Gaussian Splatting models. Our method enables the editing of the style and appearance of 3D objects without altering their main details, all in a matter of minutes on consumer hardware. We tackle the problem by leveraging Gaussian splatting to represent 3D scenes, and we optimize the model while progressively varying the image supervision by means of a pretrained image-based diffusion model. The input object may be given as a 3D triangular mesh, or directly provided as Gaussians from a generative model such as DreamGaussian. GSEdit ensures consistency across different viewpoints, maintaining the integrity of the original object's information. Compared to previously proposed methods relying on NeRF-like MLP models, GSEdit stands out for its efficiency, making 3D editing tasks much faster. Our editing process is refined via the application of the SDS loss, ensuring that our edits are both precise and accurate. Our comprehensive evaluation demonstrates that GSEdit effectively alters object shape and appearance following the given textual instructions while preserving their coherence and detail.