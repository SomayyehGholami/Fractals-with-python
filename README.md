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







<img src="https://github.com/SomayyehGholami/Fractals-with-python/blob/main/gif101.gif"> 

## Another Example

<img src="https://github.com/SomayyehGholami/Fractals-with-python/blob/main/gif201.gif"> 

## Van Gogh Style

<img src="https://github.com/SomayyehGholami/Fractals-with-python/blob/main/gif401.gif"> 
