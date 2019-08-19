# Gauge

The [Gauge][gauge] automated test framework is free and open-source, built as a modular suite for cross-platform testing.  

**Testing Approach:** Behavior-driven and data-driven testing  
**Testing Level:** Acceptance testing  
**Target application domain:** Web applications, desktop applications  

## Features

- Tests are written in the Markdown language
- Cross-platform
- Extendable with plugins
- Compatible with several programming language
- Behavior-driven testing, with support for data-driven testing

## Pros

- Tests are understandable by people who are not engineers
- Very simple syntax and therefore easy and fast to write
- Allows for the reuse of parts of tests (aka scenarios)
- Support for sharing states between steps
- Support for different report formats for the test results

## Cons

- As Gauge is only used for acceptance tests, you are still required to write, for instance, unit tests connecting to the Gauge acceptance tests  
- Not as mature as other similar tools, which could mean that the tools is less stable and contains more bugs  
- Limited amount of tutorials
- Limited amount of troubleshooting guides

## Required information / models

As the tool is written using Markdown, there are no models used as input. It uses so called _specification files_ to manage the testing environment, combined with _scenarios_ and _steps_ inside those files to specify each test.

## Target platform and dependencies

As Gauge is a cross-platform tool, it can be used on Linux, MacOS and Windows. It is not required to install any other software beside the Gauge core to use it for acceptance testing.

It is not dependent on any other programming language than the Markdown language it is written in. It can, however, be extended through plugins to work with the following programming languages:
- Java
- Javascript
- Python
- C#\.NET
- Ruby
- Golang

It is also possible to integrate Gauge with the following IDEs:
- Visual Studio
- Visual Studio Code
- IntelliJ

Finally it can also be integrated with both Maven and Gradle.

**Dependencies:**  

Generally, it is also recommended to use _npm_ (Node.js Package Manager) to install Gauge globally on a system.

## Updates

- **Latest update:**  
  - **_1.0.4;_** released on 25th of January, 2019
- **First release dates:**
  - **_1.0.0;_** released on 18th of June, 2018  
  - **_0.0.1;_** released on 22nd of May, 2014

## Licensing / Cost

Completely free and open source, according to the _GPL v3_ license.

## Tutorials and documentation

[Gauge Official Documentation][gaugedocs] is the resource of official installation instructions and the basic API of Gauge.  
The [Gauge Git repository][gaugegit] contains the source code for Gauge.

## Usage examples

As Gauge is a new testing tool, it is not yet widely used in the industry

[Koodoo][koodoo]

## Alternative tools

- [SpecFlow (.NET)][spec]
- [Behave (Python)][behave]
- [Concordion (Java)][condord]

## References

https://www.joecolantonio.com/test-automation-using-gauge-framework/  
https://gauge.org/2018/05/15/why-we-built-gauge/  
https://medium.com/koodoo/the-gauge-move-ffa13f30472c  

[gauge]: https://gauge.org/
[gaugedocs]: https://docs.gauge.org/latest/index.html  
[koodoo]: https://koodoo.io/  
[spec]: https://github.com/techtalk/SpecFlow  
[behave]: https://github.com/behave/behave/  
[condord]: https://github.com/concordion/concordion  
[gaugegit]: https://github.com/getgauge/gauge  
