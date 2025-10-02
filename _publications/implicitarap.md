---
title: "Implicit-ARAP: Efficient Handle-Guided Neural Field Deformation via Local Patch Meshing"
collection: publications
category: conferences
permalink: /publication/implicitarap
excerpt: 'A fast handle-guided deformation method for 3D geometry encoded as neural fields.'
date: 2025-12-16
venue: 'The Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: ''
bibtexurl: ''
citation: 'Daniele Baieri, Filippo Maggioli, Emanuele Rodolà, Simone Melzi and Zorah Lähner. Implicit-ARAP: Efficient Handle-Guided Neural Field Deformation via Local Patch Meshing. In Advances in Neural Information Processing Systems, 2026'
---

Neural fields have emerged as a powerful representation for 3D geometry, enabling compact and continuous modeling of complex shapes. Despite their expressive power, manipulating neural fields in a controlled and accurate manner -- particularly under spatial constraints -- remains an open challenge, as existing approaches struggle to balance surface quality, robustness, and efficiency. We address this by introducing a novel method for handle-guided neural field deformation, which leverages discrete local surface representations to optimize the As-Rigid-As-Possible deformation energy. To this end, we propose the local patch mesh representation, which discretizes level sets of a neural signed distance field by projecting and deforming flat mesh patches guided solely by the SDF and its gradient. We conduct a comprehensive evaluation showing that our method consistently outperforms baselines in deformation quality, robustness, and computational efficiency. We also present experiments that motivate our choice of discretization over marching cubes. By bridging classical geometry processing and neural representations through local patch meshing, our work enables scalable, high-quality deformation of neural fields and paves the way for extending other geometric tasks to neural domains.