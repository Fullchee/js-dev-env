# js-dev-env

This is my personal JavaScript Development Environment.

[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

## What's in it?
- StandardJS Linting
- babel (transpiles)
- documentation.js for documentation auto-generation
- mocha and mocha-generators for unit testing
- npm-run-all for scripts in package.json
- nsp: security check
- nyc: code coverage
- pre-commit: only allows a commit if all unit tests pass
- rewire: used to access private functions when requiring, useful when testing

Wow, this is really out of date
Jest
Enzyme (if using React)
nsp is now a part of npm
husky (can customize your pre-commit work), don't need pre-comit
comment-lint: using with husky: criticize the quality of the commit
