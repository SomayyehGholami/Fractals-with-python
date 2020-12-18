# Fractals-with-python

It's a project of the course ''Advance programming concept'' VUB Brussels University 

Lecturer:Bart Jansen(bjansen@etrovub.be)

Teaching assistant:Taylor Frantz (tfrantz@etrovub.be)

Teaching assistant:Redona Brahimetaj(rbrahime@etrovub.be)

_________________________________________________________________________________________________

# Part 1 - Chaos game & Iterated Function System (IFS)

# Chaos game
In mathematics, the term chaos game originally referred to a method of creating a fractal, using a polygon and an initial point selected at random inside it. The fractal is created by iteratively creating a sequence of points, starting with the initial random point, in which each point in the sequence is a given fraction of the distance between the previous point and one of the vertices of the polygon; the vertex is chosen at random in each iteration. Repeating this iterative process a large number of times, selecting the vertex at random on each iteration, and throwing out the first few points in the sequence, will often (but not always) produce a fractal shape. https://en.wikipedia.org/wiki/Chaos_game

# Affine transformation
In Euclidean geometry, an affine transformation, or an affinity (from the Latin, affinis, "connected with"), is a geometric transformation that preserves lines and parallelism (but not necessarily distances and angles).

More generally, an affine transformation is an automorphism of an affine space (Euclidean spaces are specific affine spaces), that is, a function which maps an affine space onto itself while preserving both the dimension of any affine subspaces (meaning that it sends points to points, lines to lines, planes to planes, and so on) and the ratios of the lengths of parallel line segments. Consequently, sets of parallel affine subspaces remain parallel after an affine transformation. An affine transformation does not necessarily preserve angles between lines or distances between points, though it does preserve ratios of distances between points lying on a straight line.

If X is the point set of an affine space, then every affine transformation on X can be represented as the composition of a linear transformation on X and a translation of X. Unlike a purely linear transformation, an affine transformation need not preserve the origin of the affine space. Thus, every linear transformation is affine, but not every affine transformation is linear.

Examples of affine transformations include translation, scaling, homothety, similarity, reflection, rotation, shear mapping, and compositions of them in any combination and sequence. https://en.wikipedia.org/wiki/Affine_transformation

# Iterated function system
In mathematics, iterated function systems (IFSs) are a method of constructing fractals; the resulting fractals are often self-similar. IFS fractals are more related to set theory than fractal geometry. They were introduced in 1981.

IFS fractals, as they are normally called, can be of any number of dimensions, but are commonly computed and drawn in 2D. The fractal is made up of the union of several copies of itself, each copy being transformed by a function (hence "function system"). The canonical example is the Sierpiński triangle. The functions are normally contractive, which means they bring points closer together and make shapes smaller. Hence, the shape of an IFS fractal is made up of several possibly-overlapping smaller copies of itself, each of which is also made up of copies of itself, ad infinitum. This is the source of its self-similar fractal nature. https://en.wikipedia.org/wiki/Iterated_function_system

# Description of the book: "Introduction to Programming in Python"
An iterated function system (IFS) is a general way to produce fractals like the Sierpinski triangle and the Barnsley Fern. As a first example, consider the following simple process: start by plotting a point at one of the vertices of an equilateral triangle. Then pick one of the three vertices at random and plot a new point halfway between the point just plotted and that vertex. Continue performing the same operation.

<img src="https://github.com/SomayyehGholami/Fractals-with-python/blob/main/ChaosTiny.png"> 

Also, the Modules of this book are used in this notebook.

https://introcs.cs.princeton.edu/python/code/

# The Collage Theorem
That the terms of mathematics may be confusing is often claimed even by professional mathematicians. As an example, spaces and sets contain points. Yet there are spaces whose "points" are themselves sets. Functions map points to points but also comprise (function) spaces where each is considered an indivisible one. From the mathematician's view point, the advantage of abstracting a point from its diverse incarnations is in the achieved generality. A statement is proven only once and then applied repeatedly in various disguises.

Case in point - contraction mappings and the related convergence theorems. Contraction mappings are defined on metric spaces by the property that they decrease the distance between points. In complete spaces, any contraction mapping has a unique fixed point that can be found by (necessarily) convergent iterations. Convergence estimates relate proximity of iterations to the selection of the initial point. These general estimates apply as much to the solutions of integral and differential equations, matrices, and more general operators. Iterated Function Systems (IFSs) is another rewarding topic that capitalizes on the general theory.

An Iterated Function System is a finite collection of contractions Fi: XX defined on a metric space X. Each extends to a mapping (different but denoted by the same letter) Fi: H(X)H(X), where H(X) is the space whose points are nonempty compact subsets of X. When endowed with the Hausdorff metric, H(X) is complete if so was X. In addition, contractions FiXX remain contractions as mappings of H(X). Together, {Fi} define another contraction F: H(X)H(X), by the following formula: for every AH(X), F(A) = ∪Fi(A). From the general theory, for a complete metric space X, F has a fixed point AF: F(AF) = AF, that can be reached by successive approximations from any starting location. Fixed points of IFSs are variously called attractors or invariant sets.

Two problems arise. One is to find the fixed point of a given IFS. The other is the inverse of the first: for a given set AH(X), find an IFS {Fi} that has A as its fixed point. In the general framework, the first problem is solved by what is known as the deterministic algorithm. Start with a set A0∈H(X) and compute successively Ak = ∪Fi(Ak-1) = F(Ak-1), k > 1. The sequence {Ak) converges to the fixed point AF of {Fi} as k. The mathematics of the second, random iteration algorithm, is more complex but implementation is more straightforward. Assign positive frequencies pi to the mappings Fi. Start with an arbitrary point x0∈X. At every step k+1, select xk+1 from the set {Fi(xk)}. Fj(xk) is selected with the probability pj /pi. In a sense that is made precise in [Barnsley], the sequence {xk} converges to AF. In practical terms, to depict an approximation of AF on a computer, the points of the sequence are displayed starting with a reasonably large index. The numbers {pi} have no effect on the fixed point AF but influence significantly the rendering of its approximations.

The inverse problem is solved approximately by the Collage Theorem. In the words of M. Barnsley, the theorem tells us that to find an IFS whose attractor is "close to" or "looks like" a given set, one must endeavor to find a set of transformations - contraction mappings on a suitable set within which the given set lies - such that the union, or collage, of the images of the given set under transformations is near to the given set.

http://www.cut-the-knot.org/ctk/ifs.shtml

________________________________________________________________________________________________________________________________________________________________________________





<img src="https://github.com/SomayyehGholami/Fractals-with-python/blob/main/gif101.gif"> 

## Another Example

<img src="https://github.com/SomayyehGholami/Fractals-with-python/blob/main/gif201.gif"> 

## Van Gogh Style

<img src="https://github.com/SomayyehGholami/Fractals-with-python/blob/main/gif401.gif"> 
