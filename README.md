# software-engineer-guidelines
## Objective

To establish guidelines for software engineers to follow when writing and reviewing clean testable code.

## Which metric to use

If the code is not clean and easy to read, then that indicates there's a problem.

<img src="code-review.png">

## Guidelines

The below guidelines are not all inclusive, but they should be referenced by both code writers / reviewers.

- [ ] Create a new branch for every different feature addition / change.
- [ ] Commit code as small commits with semantic versioning in mind.
- [ ] The code pretty much comments itself.
- [ ] The code is indented consistently.
- [ ] The code is not deeply nested with conditionals.
- [ ] The code is separated from the configuration.
- [ ] Files and folders are logically organized.
- [ ] Functions do one thing and one thing only.
- [ ] Functions should never be longer than 10 lines of code.
- [ ] Functions and properties are clearly named to describe their intent.
- [ ] Functions are verbs; Classes and variables are nouns.
- [ ] Functions are predicates in the case that it returns a boolean. (ie. isActive())
