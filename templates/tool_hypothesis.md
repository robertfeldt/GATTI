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
  - Handcrafted test-cases can be included explicitly
  - Supports integration of e.g. pytest, unittest and Coverage 

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
Hypothesis is a black-box testing tool. So the tester doesn't has to have any knowledge about how the software under test is modeled in detail. The tester only has to know about the "correct" input to output mapping. To tell the test tool what "correct" means, the tester has to define the "correct" behaviour in form of logical statements (the properties) about the outputs. These properties should preferably hold for all possible input data. But it's also possible to tell the Hypothesis tests for which inputs it shouldn't throw an assertion (e.g for NaN).

## Target platform and dependencies
Hypothesis is a platform independet tool (tested on OS X, Windows and Linux) for usage in Python programming environments.

**Dependencies:** A version of CPython with upstream support, the Python library attrs and the Python library enum34 (enum34 required on Python 2.7)

## Updates
Hypothesis releases since 1.0 are semantically versioned.
Hypothesis gets updated frequently. Bugs get fixed on a best efford basis. Enhancements will be implemented against payment or can be implemented by oneself with support of the author.

**Latest update:** 4.14.2 - 2019-03-31
**First release date:** 2013-10-03

## Licensing / Cost
It's an open source library (Mozilla Public License 2.0).

## Tutorials and documentation
Documentation:
https://hypothesis.readthedocs.io/en/latest/index.html

Hypothesis repository on GitHub:
https://github.com/HypothesisWorks

Getting started with Hypothesis:
https://hypothesis.works/articles/getting-started-with-hypothesis/

Update policy:
https://hypothesis.readthedocs.io/en/latest/changes.html

Dependecies:
https://hypothesis.readthedocs.io/en/latest/packaging.html

YouTube talk about property-based testing with Hypothesis by Jeremy Thurgood.
https://www.youtube.com/watch?v=mg5BeeYGjY0

## Usage examples
(Add: A few descriptions of how the tool has been used, ideally linking to libraries or software that actively is using the tool. Here you will also link to your "use case".)

## Alternative tools
Link to a list of model-based testing tools in different languages:
https://hypothesis.works/articles/quickcheck-in-every-language/

The original model-based testing library QuickCheck in Haskell:
http://www.cse.chalmers.se/~rjmh/QuickCheck/
