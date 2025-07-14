---
title: "Newton’s Fractals on Surfaces via Bicomplex Algebra"
collection: publications
category: conferences
permalink: /publication/newton
excerpt: "A generalization of the 2D Newton's fractal pattern to three dimensions for pattern generation."
date: 2022-07-22
venue: "SIGGRAPH '22"
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3532719.3543211'
bibtexurl: '/files/newton-bibtex.bib'
citation: "Filippo Maggioli, Daniele Baieri, Simone Melzi, and Emanuele Rodolà. 2022. Newton’s Fractals on Surfaces via Bicomplex Algebra. In ACM SIGGRAPH 2022 Posters (SIGGRAPH '22). Association for Computing Machinery, New York, NY, USA, Article 65, 1–2"
---

Since bicomplex functions in the form $$f : \mathbb{BC} → \mathbb{BC}$$ can be expanded with Taylor, and the Taylor series in BC converges, we can use the classical proof of the Newton-Raphson method to show that Newton's iteration converges to the root of a function: this allows us to generalize Newton’s fractal to bicomplex numbers, and use it to generate 4-dimensional patterns. In the complex plane, the roots of the polynomial $$c^n − 1 = 0$$ lie on the unit circle and are equispaced, and the interesting patterns arising from this particular family of polynomials are shown in most visualizations of Newton's fractal. This still holds in $$\mathbb{BC}$$, where the roots of $$z^n − 1 = 0$$ are equispaced on the unitary 4-dimensional hyper-sphere. This polynomial has $$n^2$$ closed form solutions. Applying the Newton-Raphson method to solve bicomplex polynomials in the form $$z^n − 1 = 0$$ produces the same patterns of the complex plane, but it extends to 4 dimensions. By using the 3D coordinates of the visualized points, we can generate interesting and complex patterns, while using the fourth coordinate either as a tunable parameter or as a time dependency, allowing for an additional degree of freedom.