0.4.0
=====

* Fix functions with empty cells
* Allow pickling Logger objects
* Fix crash when pickling dynamic class cycles
* Ignore "None" mdoules added to sys.modules
* Support WeakSets and ABCMeta instances
* Remove non-standard `__transient__` support
* Catch exception from `pickle.whichmodule()`


0.3.1
=====

* Fix version information and ship a changelog

 0.3.0
=====

* Import submodules accessed by pickled functions
* Support recursive functions inside closures
* Fix `ResourceWarnings` and `DeprecationWarnings`
* Assume modules with `__file__` attribute are not dynamic

0.2.2
=====

* Support Python 3.6
* Support Tornado Coroutines
* Support builtin methods

0.2.1
=====

* Packaging fix

0.2.0
=====

* Support `method_descriptor`
* Support unbound instancemethods
* Fixes for PyPy3
* More support for pickling dynamic imports

0.1.0
=====

Released on 2015-04-16 from the (real) clouds somewhere between Montréal and
Atlanta.
