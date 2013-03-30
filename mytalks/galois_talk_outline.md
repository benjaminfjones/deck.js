Architecture of an Open Source Applicaiton: Sage
================================================

What is Sage
------------

* Audience
* Influences
* history

Basic architecture
------------------

* Python
* Scientific python community
  * numpy
  * scipy
  * sympy
     -full featured CAS in pure python
    - easy to extend
    - not as fast as specialized CAS (Maxima, Ginac, ...) but much
      easier to extend and use from a Python environment
    - powerfull enough to be used for real world problems
    - symbolic limits in 300 sloc
* IPython for interactive development
* spkg system
* interfaces to other systems
	* maxima
	* ginac
	* matplotlib
	* jmol
	* PARI/GP
	* Flint
	* Singular
	* GAP
	* etc..

Demo
----

* tour of sage
* tour of combinatorics
	* graphs
	* generator objects for partitions and compositions
* tour of symbolics

Symbolics
---------

* ginac / pynac backend
* symbolic ring / coersion framework
* symbolic functions
	* symbolic function class structure
    * example mixing Sage, Pynac, Maxima, SymPy
	* examples of Sage -> Maxima -> Sage -> mpmath -> matplotlib



