# [Hypothesis](https://hypothesis.readthedocs.io/en/latest/index.html)
Hypothesis is a Python library for property-based testing developed by David R. MacIver. As a basis for Hypothesis serves the Haskell library Quickcheck, which introduced the concept of property-based testing in 1999. (Also expandsto fuzz testing)

**Testing Approach:** "Property-based testing (specification testing)"
**Testing Level:** "Unit testing (Class/Function level)"
**Target application domain:** "python programms/libraries"

## Features
(Add: Bullet points describing the main features of your tool, typically 4-7 bullets)
..* Test high-level requirements (properties)
..* automatic generation of test-cases, considering input specification
..*
..*
..* Failure case minimization 
..* handcrafted test cases can be explicitly included
..* supports integration of pytest, unittest, Coverage 

## Pros
(Add: Bullet points describing the main benefits/pros of the tool, typically 3-5 bullets)
..* test case generation much faster than if manually designed
..* covers probably many test cases, that can easily be forgotten by manual test design
..* makes developer/tester think hard about what properties the program should fulfill
..* Failure case minimization supports testers to find the faults 
..* very flexible test design

## Cons
(Add: Bullet points describing the main drawbacks/cons of the tool, typically 3-5 bullets)
..* defining general properties can be difficult
..* running a whole bunch of tests takes longer than running a few handcrafted tests
..* programming knowhow needed to use the tool

## Required information / models
(Add: Describe which input information and/or models that the tool needs in order to work. What does a tester need to provide in order to run/use the tool?)

## Target platform and dependencies
Hypothesis is a platform independet (tested on OS X, Windows and Linux) tool for usage in Python programming environments.

**Dependencies:** A version of CPython with upstream support, the Python library attrs and the Python library enum34 (enum34 required on Python 2.7)

## Updates
Hypothesis releases since 1.0 are semantically versioned.
Hypothesis gets updated frequently.Bugs get fixed on a best efford basis. Enhancements will be implemented against payment or can be implemented by oneself with support of the author.

**Latest update:** 4.14.2 - 2019-03-31
**First release date:** 2013-10-03

## Licensing / Cost
Open source

## Tutorials and documentation
(Add: Links to tutorials and documentation of the tool with one sentence description of each.)
Update policy:
https://hypothesis.readthedocs.io/en/latest/changes.html
Dependecies:
https://hypothesis.readthedocs.io/en/latest/packaging.html
## Usage examples
(Add: A few descriptions of how the tool has been used, ideally linking to libraries or software that actively is using the tool. Here you will also link to your "use case".)

## Alternative tools
(Add: Link to a few alternative but related/similar tools that one could use instead of this tool for example to do similar testing for another target domain, language or environment.)
