# Scaling SpecFlow

These are the slides for my talk on how to scale a SpecFlow codebase with proper architecture. The slides use [Reveal JS](https://revealjs.com) - an HTML presentation framework.

[View the Slides](https://joebuschmann.github.io/scaling-your-specflow-codebase/)

## Abstract

So your team has implemented BDD to generate acceptance criteria for its applications. Developers are binding the Gherkin using SpecFlow, and your small suite of acceptance tests are proving their worth. But as the number of automated tests grows, cracks start to emerge. Developers find themselves spending more time maintaining the tests than the application. What can you do to fix this? Like any other code base, automated tests require proper archtecture to scale as the number of scenarios grows. In this talk, I will present best practices for creating modular reusable SpecFlow bindings in C#. You'll learn how to use regular expressions, dependency injection, step argument transformations, and more to create a set of flexible bindings that can scale with your application.
