.. Read the Docs Template documentation master file, created by
   sphinx-quickstart on Tue Aug 26 14:19:49 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Read the Docs Template's documentation!
==================================================

Contents:

.. toctree::
   :maxdepth: 2
   :glob:

   history
   ssssss


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Indices and tables1
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
Now that we have studied $L^{2}(\mathbb{R})$ and the Fourier transformation, we can start constructing

wavelets. Toward this end, we seek to decompose $L^{2}(\mathbb{R})$ into two nested sequences of subspaces.

The sequence  $V_j  \subset V_{j+1}$   are *approximation spaces*. As $j$ tends to infinity, the space $V_j$ provides a

better approximation to an arbitrary function $f(t) \in L^{2}(\mathbb{R})$. The spaces $W_j  \subset W_{j+1}$   are detail

spaces——Wj is a subset of $V_{j+i}$, and if we approximate  is  $f_{j+1}(t) \in V_{j+1}$, by $f_{j}(t) \in V_j$, then

$w_{j}(t) \in W_{j}$ holds the details we need to combine with $f_{j}(t)$ to recover $f_{j+1}(t)$ That is,  

$f_{j+1}(t) =f_{j}(t) +w_{j}(t)$  .

We can iterate the decomposition process and write $f_{M}(t) \in V_{M}$ as a coarse approximation 

$f_{m}(t) \in V_{m}$, and $m< M$ and detail functions $w_{m}(t), w_{m+1}(t),...,w_{M-1}(t)$. In applications,

we can quantize the detail information to perform signal image compression. Alternatively, we

might analyze the detail information to look for jumps in $f_M(t)$ or one of its derivatives.
