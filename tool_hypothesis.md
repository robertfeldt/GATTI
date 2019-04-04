# [Hypothesis](https://hypothesis.readthedocs.io/en/latest/index.html)
Hypothesis is a Python library for property-based testing developed by David R. MacIver. As a basis for Hypothesis serves the Haskell library Quickcheck, which introduced the concept of property-based testing in 1999.

**Testing Approach:** "Property-based testing (specification testing)"
**Testing Level:** "Unit testing (Class/Function level)"
**Target application domain:** "Python programms/libraries"

## Features
  - Test high-level requirements of program (properties)
  - Randomly generated test-cases, considering input specification
  - Tries to find test-cases that make the test fail
  - Failure case minimization 
  - Handcrafted test-cases can be included explicitly as [@examples](https://hypothesis.readthedocs.io/en/latest/reproducing.html#hypothesis.example)
  - Supports integration of e.g. [pytest](https://docs.pytest.org/en/latest/), [unittest](https://docs.python.org/3/library/unittest.html) and [coverage](https://pypi.org/project/coverage/) 
  - [Health checks](https://hypothesis.readthedocs.io/en/latest/healthchecks.html)

## Pros
  - Test-case generation of many test-cases much faster than if manually designed
  - Covers probably many test-cases, that can easily be forgotten by manual test design
  - Makes developer/tester think hard about what properties the program should fulfill
  - Failure case minimization supports testers to find the faults 
  - Very flexible test design

## Cons
  - Defining general properties can be difficult
  - Running a whole bunch of tests takes longer than running a few handcrafted tests
  - Programming knowhow needed to use the tool

## Required information / models
Hypothesis is a black-box testing tool. So the tester doesn't have to have any knowledge about how the software under test is modeled in detail. The tester only has to know about the "correct" input to output mapping. To tell the test tool what "correct" means, the tester has to define the "correct" behaviour in form of logical statements (the properties) about the outputs. These properties should preferably hold for all possible input data. But it's also possible to tell the Hypothesis tests for which inputs it shouldn't throw an assertion (e.g for NaN).

## Target platform and dependencies
Hypothesis is a platform independet tool (tested on OS X, Windows and Linux) for usage in Python programming environments.

**Dependencies:** A version of CPython with upstream support, the Python library attrs and the Python library enum34 (enum34 required on Python 2.7). Dependencies can be found [here](https://hypothesis.readthedocs.io/en/latest/packaging.html) 

## Updates
Hypothesis releases since 1.0 are semantically versioned.
Hypothesis gets updated frequently. Bugs get fixed on a best efford basis. Enhancements will be implemented against payment or can be implemented by oneself with support of the author.

**Latest update:** 4.14.2 - 2019-03-31
**First release date:** 2013-10-03

## Licensing / Cost
It's an open source library (Mozilla Public License 2.0).

## Tutorials and documentation
Hypothesis [documentation](https://hypothesis.readthedocs.io/en/latest/index.html)

Hypothesis [repository on GitHub](https://github.com/HypothesisWorks)

[Getting started](https://hypothesis.works/articles/getting-started-with-hypothesis/) with Hypothesis

[YouTube talk](https://www.youtube.com/watch?v=mg5BeeYGjY0) about property-based testing with Hypothesis by Jeremy Thurgood

## Usage examples
  - How the tool has been used in a lot of [open source projects](https://hypothesis.readthedocs.io/en/latest/usage.html)
  - An example is the [cryptography library](https://cryptography.io/en/latest/) for python (see also the case study)

## Alternative tools
[Link to a list](https://hypothesis.works/articles/quickcheck-in-every-language/) of model-based testing tools in different languages

The original model-based testing library QuickCheck in Haskell can be found [here](http://www.cse.chalmers.se/~rjmh/QuickCheck/)

