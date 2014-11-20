engineeringdojo
===============

Software engineering dojo

Steps
-----

* Create a github account
* Fork this repository
* Write a new library **libmym**
  * Create a function `newtan(double x)`, which calculates  tangent using `sin(x)` and `cos(x)`
  * Write in C, C++ or Fortran ..
* Use CMake to build the library
  * make sure `make install` incl. headers works
    * optional: give the library a soname
    * optional: write a pkg-config file
  * check for `sin(x)` and `cos(x)` in user given `libm`
* Write a little test program reading a number as 1st argument an output `newtan(argument1)` as output
* enable testing
  * use test program to write a handful tests
* create a travis-ci.org account
* enable continuous integration for your repository
* create a `.travis.yml` to test your build
* create a coveralls account
* make a `gcov` build
* update load output using `cpp-coveralls`
