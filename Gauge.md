# Gauge
The Gauge automated test framework is free and open-source, built as a modular suite for cross-platform testing.
**Testing Approach:** It is built using a behavior driven approach to testing.
**Testing Level:** It mainly targets the acceptance test level.
**Target application domain:** Web applications,

## Features
(Add: Bullet points describing the main features of your tool, typically 4-7 bullets)

- Tests are written in the Markdown language
- Cross-platform
- Extend with plugins
- Compatible with several programming language
- Behavior-driven testing, with support for data-driven testing

## Pros
(Add: Bullet points describing the main benefits/pros of the tool, typically 3-5 bullets)

- Tests are understandable by people who are not engineers.

## Cons
(Add: Bullet points describing the main drawbacks/cons of the tool, typically 3-5 bullets)

- No ability to write model-driven behavior tests

## Required information / models
(Add: Describe which input information and/or models that the tool needs in order to work. What does a tester need to provide in order to run/use the tool?)

As the tool is written using Markdown, there are no models used as input

## Target platform and dependencies
(Add: Description of the target platform, language, and/or environment that the tool assumes or targets.)

**Dependencies:** (Add: List the main dependencies of the tool)

## Updates
(Add: A sentence or two about how well the tool is updated/maintained)

- **Latest update:** (Add date for latest update of the tool)
- **First release date:**
**_1.0.0;_** released on 18th June, 2018.
**_0.0.1;_** released on 22nd May, 2014

## Licensing / Cost
(Add: A few sentences describing the license model or the costs of buying or using the tool)

Completely free and open source, according to the _GPL v3_ license.

## Tutorials and documentation
(Add: Links to tutorials and documentation of the tool with one sentence description of each.)

## Usage examples
(Add: A few descriptions of how the tool has been used, ideally linking to libraries or software that actively is using the tool. Here you will also link to your "use case".)

## Alternative tools
(Add: Link to a few alternative but related/similar tools that one could use instead of this tool for example to do similar testing for another target domain, language or environment.)

Cucumber?

## Part 2

I am currently doing an assignment in a course called "Model-driven testing" and am writing about gauge in a very basic manner. I have some questions I'd like to ask you, the team behind it:

Q1. What are your reasons for developing Gauge in the first place and why did you settle on the particular technology you're using for Gauge? (Behavior-driven testing or acceptance tests, using plugins etc)

This test is now reusable but not very readable because a programming language like Java adds syntax and OOP design noise like Classes, Objects, Methods, Variables etc.
It is often hard to use these patterns. It breaks the flow of writing tests because one needs to design first and and then write the test case.
It is also counterproductive adding eleven lines of code to reuse two lines.

Over time, teams over-engineer test suites with design opinions making it harder and harder to write new tests or maintain existing ones.
We feel it’s important to minimize or eliminate this design process.


Q2. What situations are Gauge good for, and less suitable for?
Q3. How mature do you think Gauge is as an automated testing tool? Is it suitable for use by companies developing real-world software at scale? Why / why not?
Q4. How do you plan to evolve and develop Gauge going forward? What are the main improvements needed to take the tool to the next level?

Thank you for you time!


https://gitter.im/getgauge/chat
https://gauge.org/2018/05/15/why-we-built-gauge/
