---
title: "FUSE: A Flow-based Mapping Between Shapes"
collection: publications
category: conferences
permalink: /publication/fuse
excerpt: 'Computing maps between shapes in any representation via flow matching.'
date: 2026-09-11
venue: 'European Conference on Computer Vision'
paperurl: 'https://arxiv.org/abs/2511.13431'
bibtexurl: ''
citation: 'Lorenzo Olearo, Giulio Viganò, Daniele Baieri, Filippo Maggioli, Simone Melzi. FUSE: A Flow-based Mapping Between Shapes. ECCV 2026.'
---

We introduce a novel neural representation for maps between 3D shapes based on flow-matching models, which is computationally efficient and supports cross-representation shape matching without large-scale training or data-driven procedures. 3D shapes are represented as the probability distribution induced by a continuous and invertible flow mapping from a fixed anchor distribution. Given a source and a target shape, the composition of the inverse flow (source to anchor) with the forward flow (anchor to target), we map points between the two surfaces. By encoding the shapes with a pointwise task-tailored embedding, this construction provides an invertible and modality-agnostic representation of maps between shapes across point clouds, meshes, signed distance fields (SDFs), and volumetric data. The resulting representation consistently achieves high coverage and accuracy across diverse benchmarks and challenging settings in shape matching. Beyond shape matching, our framework shows promising results in other tasks, including UV mapping and registration of raw point cloud scans of human bodies.

(Paper accepted, proceedings not yet published)