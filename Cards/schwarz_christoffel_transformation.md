Is a way to change the shape of a flat surface, like a piece of paper, into a different shape, like a triangle or a circle.

Imagine you have a piece of paper with a straight line drawn across it. You want to transform it into a triangle. The Schwarz-Christoffel transformation tell you how to do this in a special way.

The function $f$ maps the real axis to the edges of the polygon. If the polygon has interior angles $\alpha, \beta, \gamma,\dots$ , then the transformation is given by:

$$f(\zeta) = \int^\zeta \frac{K}{(w-a)^{1-(\alpha/\pi)}(w-b)^{1-(\beta/\pi)}(w-c)^{1-(\gamma/\pi)}\cdots}\ dw$$ 

Where $K$  is a constant, and $a<b<c<\dots$ are the values, along the real axis of the $\zeta$ plane, of corresponding to the vertices of the polygon in the $z$ plane.

The Schwarz-Christoffel transformation works because it is based on a fundamental theorem of complex analysis, called the [riemman_mapping_theorem](riemman_mapping_theorem.md).


