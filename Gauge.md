# Gauge
The Gauge automated test framework is free and open-source, built as a modular suite for cross-platform testing.  

**Testing Approach:** It is built using a behavior driven approach to testing  
**Testing Level:** It mainly targets the acceptance test level  
**Target application domain:** Web applications, desktop applications  

## Features
- Tests are written in the Markdown language
- Cross-platform
- Extendable with plugins
- Compatible with several programming language
- Behavior-driven testing, with support for data-driven testing

## Pros
- Tests are understandable by people who are not engineers.
- Very simple syntax and therefore easy and fast to write
- Contains logic to 

## Cons

- As Gauge is only used for acceptance tests, you are still required to write, for instance, unit tests connecting to the Gauge scenarios
- Not as mature as other similar tools, which could mean that the tools is less stable and contains more bugs
- Various instructions (tutorials, install etc) are not as throrough as they could be

## Required information / models
(Add: Describe which input information and/or models that the tool needs in order to work. What does a tester need to provide in order to run/use the tool?)

As the tool is written using Markdown, there are no models used as input. It used so called _specification files_ to manage the testing environment, combined with _scenarios_ and

## Target platform and dependencies
(Add: Description of the target platform, language, and/or environment that the tool assumes or targets.)
Gauge is a cross-platform testing tool, available for Linux, MacOS and Windows.

As is is geared towards the acceptance level of testing, it is not dependant on any other programming language than the Markdown language it is written in. It can, however, be extended through plugins to work with the following programming languages:
- Java
- Javascript
- Python
- C#\.NET
- Ruby
- Golang

It is also possible to integrate Gauge with a few IDEs:
- Visual Studio
- Visual Studio Code
- IntelliJ

Finally it can also be integrated with both Maven and Gradle

**Dependencies:**

Generally, it is also recommended to use _npm_ (Node.js Package Manager) to install Gauge globally on a system.

## Updates
(Add: A sentence or two about how well the tool is updated/maintained)

- **Latest update:** (Add date for latest update of the tool)
- **First release date:** wsasd
- **_1.0.0;_** released on 18th June, 2018.
- **_0.0.1;_** released on 22nd May, 2014

## Licensing / Cost
(Add: A few sentences describing the license model or the costs of buying or using the tool)

Completely free and open source, according to the _GPL v3_ license.

## Tutorials and documentation
(Add: Links to tutorials and documentation of the tool with one sentence description of each.)

[Gauge Official Documentation][gaugedocs]

## Usage examples
(Add: A few descriptions of how the tool has been used, ideally linking to libraries or software that actively is using the tool. Here you will also link to your "use case".)

As Gauge is a new testing tool, it is not yet widely used in the industry

[Koodoo][koodoo]

## Alternative tools
(Add: Link to a few alternative but related/similar tools that one could use instead of this tool for example to do similar testing for another target domain, language or environment.)

- [SpecFlow (.NET)][spec]
- [Behave (Python)][behave]
- [Concordion (Java)][condord]

## References

https://www.joecolantonio.com/test-automation-using-gauge-framework/  
https://gauge.org/2018/05/15/why-we-built-gauge/  
https://medium.com/koodoo/the-gauge-move-ffa13f30472c  

[gaugedocs]: https://docs.gauge.org/latest/index.html
[koodoo]: https://koodoo.io/
[spec]: https://github.com/techtalk/SpecFlow
[behave]: https://github.com/behave/behave/
[condord]: https://github.com/concordion/concordion

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
