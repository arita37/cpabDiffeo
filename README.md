# cpabDiffeo
Finite-dimensional spaces of simple, fast, and highly-expressive diffeomorphisms, self-coined CPAB transformations, derived from parametric, continuously-defined, velocity fields.

Code is coming soon: 
We are making efforts to upload the code as soon as possible. 

**Current estimate for the code's release date: End of February 2016.In the meantime, you may want to try a [Julia implementation](https://github.com/angel8yu/cpab-diffeo-julia) written by my student, Angel Yu. His implementation has far less options than the one I will post here (e.g, it is only in 1D or 2D) and doesn't use GPU.**

This implementation is based on our recent paper, [\[Freifeld et al., ICCV '15\] ](http://people.csail.mit.edu/freifeld/publications.htm), but also contains some extensions and variants of that work that were not included in the ICCV paper due to page limits. 

For example, while the ICCV paper discusses only $R^n$ for n=1,2,3, the implementation here also supports higher values of $n$ (as to be expected, both the dimensionality of the representation and integration computing time increase with $n$ and thus values of $n$ that are too high will be impractical in terms of memory, inference, running time, etc.).
It also contains additional types of tessellations and bases. There are pros and cons for each choice.

**During Spring 2016 we will release an extended TR that will cover these options.**

