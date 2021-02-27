# Software Engineer Guidelines
## Objective

To establish guidelines for software engineers to follow when writing and reviewing clean testable code.

## Which metric to use

If the code is not clean and easy to read, then that indicates there's a problem. Period.

<img src="code-review.png">

## Guidelines

These below guidelines should be kept in mind when both writing and reviewing code.

- [ ] Well written code should pretty much tell you what it does.
- [ ] Well written code should be indented & formatted consistently.
- [ ] Well written code should not have deeply nested control logic.
- [ ] Well written code should be separate from the configuration.
- [ ] Well written code should be logically organized based on domain.
- [ ] Well written code should consist of function which do one thing and one thing only.
- [ ] Well written code should consist of function that are not greater than 10 lines of code.
- [ ] Well written code should consist of functions and properties with clear naming that describes their intent.
- [ ] One branch per every new feature added.
- [ ] Functions are verbs; Classes and variables are nouns.
- [ ] Functions are predicates in the case that it returns a boolean. (ie. isActive())
