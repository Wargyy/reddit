# Software Engineering - Reddit
https://github.com/Wargyy/reddit

**Year:** 2015 **Class:** 3MIEIC3

**Group:**
* Daniel Couceiro
* Diogo Cardoso
* Pedro Albano
* Pedro Faria

## Navigation

* [Degree of Testability of the Software](#degree-of-testability-of-the-software)
* [Test Statistics](#test-statistics)

[... Return to Chapter Select](Chapter_Select.md)

## Degree of Testability of the Software
The Reddit software makes use of a collection of Unit tests that verify nearly all or most of the core functionalities of it, and can be found under the ``reddit/r2/r2/tests/`` directory of the repository.

#####Controllability
The existing tests available for the software are very simple, most of them create a new instance of the feature to be tested,
and verify if it was initialized properly or if it reproduces the expected result, making the tests very straightforward without offering much control over them.

#####Observability
As mentioned in the Controllability section, the simplicity of the tests causes them not to offer a lot more than the final results of them, namely, if they are suceeding or not, as they don't offer an intermediate analysis of the process.

#####Isolateability
By default, all the tests are performed, however, the testing tools used and the design of them allow to select which tests are to be performed, making it possible to perform an isolated analysis of determinated components.

#####Separation of Concerns
Depending on the features tested, some of them are tested singularely, as in, that specific feature of a module is analysed, others don't go so deep, as only scenarios of proper initialization of more general classes and modules are verified.

#####Understandability
The documentation for most of the components is scarse or non-existing, making the understanding of what they do highly reliable on the users knowledge and usage of the software.

#####Heterogeneity
The way the software was conceived does not require for several testing methods, as most of the technologies used provide embed functionallity to the core of the software, making it only necessary to test around it.

###Overall Degree of Testability
With the considerations taken above, its fair to say that the overall degree of testability is set to a basic level, allowing to identify critical problems in the software functionality, but not allowing to locate more specific and smaller issues within it, which would require further expansion of the testing environment.

## Test Statistics [TODO]
Number of tests (# tests unitários; # tests de sistema, # tests de desempenho, ...)
% coverage (given by tools like EclEmma)
Code coverage: is it any good? (see http://avandeursen.com/2013/11/19/test-coverage-not-for-managers/)
