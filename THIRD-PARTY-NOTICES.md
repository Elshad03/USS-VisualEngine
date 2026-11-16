# THIRD-PARTY NOTICES

This file contains attribution, academic references, and license information for third-party material used in USS-VisualEngine.

---

## 1. ACES RRT/ODT Fit

USS-VisualEngine includes an adapted implementation of the `rrt_odt_fit` function from the following source:

**Original source:**

https://github.com/selfshadow/ltc_code/blob/master/webgl/shaders/ltc/ltc_blit.fs

**Original repository:**

https://github.com/selfshadow/ltc_code

**Copyright (c) 2017, Eric Heitz, Jonathan Dupuy, Stephen Hill and David Neubelt.**

### Required Academic Reference

Real-Time Polygonal-Light Shading with Linearly Transformed Cosines.

Eric Heitz, Jonathan Dupuy, Stephen Hill and David Neubelt.

ACM Transactions on Graphics (Proceedings of ACM SIGGRAPH 2016), 35(4), 2016.

Project page:

https://eheitzresearch.wordpress.com/415-2/

### Original License Terms

Copyright (c) 2017, Eric Heitz, Jonathan Dupuy, Stephen Hill and David Neubelt.

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. If you use (or adapt) the source code in your own work, please include a reference to the paper:

   Real-Time Polygonal-Light Shading with Linearly Transformed Cosines.

   Eric Heitz, Jonathan Dupuy, Stephen Hill and David Neubelt.

   ACM Transactions on Graphics (Proceedings of ACM SIGGRAPH 2016) 35(4), 2016.

   Project page: https://eheitzresearch.wordpress.com/415-2/

2. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

3. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

---

## 2. Color Vision Simulation

The color vision simulation matrices used in USS-VisualEngine are based on the scientific model described in the following publication:

**Authors:**

Gustavo M. Machado, Manuel M. Oliveira, and Leandro A. F. Fernandes.

**Publication:**

"A Physiologically-based Model for Simulation of Color Vision Deficiency."

IEEE Transactions on Visualization and Computer Graphics, Volume 15, Issue 6, 2009, pages 1291–1298.

**DOI:**

https://doi.org/10.1109/TVCG.2009.113

This citation acknowledges the scientific model underlying the color vision simulation matrices.

The additional color assistance and remapping operations are implemented within USS-VisualEngine. This notice does not claim that the paper's software source code is included in the project.

---

## 3. Project License

Except for third-party material identified in this document, the original code, shader implementations, and other original contributions of USS-VisualEngine are distributed under the MIT License included in the repository.

Third-party material remains subject to its respective copyright notices, attribution requirements, and license terms.

The MIT License does not replace or override the license conditions applicable to third-party material.

---

## 4. Source Distribution Notice

When redistributing the USS-VisualEngine source file containing the adapted `rrt_odt_fit` implementation, include this `THIRD-PARTY-NOTICES.md` file in the same source distribution.

This preserves the required copyright notice, license conditions, disclaimer, and academic reference.

For complete license information, refer to both this document and the repository's `LICENSE` file.

---

**USS-VisualEngine**

Universal Screen-Space Visual Engine

Project Author & Maintainer: Elshad03

AI Development Assistant: ChatGPT (OpenAI)
