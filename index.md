title: PAPARAZZI: Surface Editing by way of Multi-View Image Processing
author: Hsueh-Ti Derek Liu, Michael Tao, Alec Jacobson
html header: <meta property="og:image" content="http://www.dgp.toronto.edu/projects/paparazzi/paparazzi-teaser.jpg" />
<meta property="og:description" content="The image processing pipeline boasts a wide variety of complex filters and effects. Translating an individual effect to operate on 3D surface geometry inevitably results in a bespoke algorithm. Instead, we propose a general-purpose back-end optimization that allows users to edit an input 3D surface by simply selecting an off-the-shelf image processing filter. We achieve this by constructing a differentiable triangle mesh renderer, with which we can back propagate changes in the image domain to the 3D mesh vertex positions. The given image processing technique is applied to the entire shape via stochastic snapshots of the shape: hence, we call our method Paparazzi. We provide simple yet important design considerations to construct the Paparazzi renderer and optimization algorithms. The power of this rendering-based surface editing is demonstrated via the variety of image processing filters we apply. Each application uses an off-the-shelf implementation of an image processing method without requiring modification to the core Paparazzi algorithm." />
<meta name="twitter:card" content="summary"></meta>
<meta name="og:title" content="Paparazzi: Surface Editing by way of Multi-View Image Processing"></meta>
css: style.css

# PAPARAZZI: Surface Editing by way of Multi-View Image Processing _SIGGRAPH Asia 2018_

<div class=authors>

HSUEH-TI DEREK LIU, MICHAEL TAO, ALEC JACOBSON, University of Toronto

</div>

![](paparazzi-teaser.jpg)

## Abstract
The image processing pipeline boasts a wide variety of complex filters and effects. Translating an individual effect to operate on 3D surface geometry inevitably results in a bespoke algorithm. Instead, we propose a general-purpose back-end optimization that allows users to
edit an input 3D surface by simply selecting an off-the-shelf image processing filter. We achieve this by constructing a differentiable triangle mesh renderer, with which we can back propagate changes in the image domain to the 3D mesh vertex positions. The given image processing technique is applied to the entire shape via stochastic snapshots of the shape: hence, we call our method Paparazzi. We provide simple yet important design considerations to construct the Paparazzi renderer and optimization algorithms. The power of this rendering-based surface editing is demonstrated via the variety of image processing filters we apply. Each application uses an off-the-shelf implementation of an image processing method without requiring modification to the core Paparazzi algorithm.

## Downloads

 - [Paper](paparazzi-surface-editing-by-way-of-multi-view-image-processing-siggraph-asia-2018-liu-et-al.pdf)
 - [Paper (low res)](paparazzi-surface-editing-by-way-of-multi-view-image-processing-siggraph-asia-2018-compressed-liu-et-al.pdf)
 - [Video]()
 - [Slides]()
 - [Code]()

<!-- ## Video -->

<!-- Embed Youtube video here -->

## BibTeX

```
@article{Liu:Paparazzi:2018,
  title = {Paparazzi: Surface Editing by way of Multi-View Image Processing},
  author = {Hsueh-Ti Derek Liu and Michael Tao and Alec Jacobson},
  year = {2018},
  journal = {ACM Transactions on Graphics}, 
}
```

## Acknowledgements 
This work is funded in part by NSERC Discovery Grants (RGPIN2017-05235, RGPAS-2017-507938, RGPIN-2017-05524), NSERC DAS (RGPAS-2017-507909), Connaught Funds (NR2016-17), the Canada Research Chairs Program, and gifts by Adobe Systems Inc, Autodesk Inc, and Fields Institute. We thank members of Dynamic Graphics Project, including R. Abdrashitov, R. Arora, G. Barill, E. Corman, L. Fulton, T. Jeruzalski, J. Kenji, S. Kushner, D. Levin, J. Li, V. Modi, D. Moore, R. Schmidt, M. Wei, for early feedback and draft reviews; D. Nowrouzezahrai and M. McGuire for discussions about differentiable renderers and their applications.

