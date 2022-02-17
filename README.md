# Aux Standard Quality

Aux Standard Quality is a minimalistic approach based on the Dutch Pragmatism.

## Linter

Every project must have a Linter.

* Flutter
* JavaScript/ TypeScript https://eslint.org

### Style

Every Linter must be configured to check and reformat a standard style.

We use the following standard style ...

### Cyclomatic Complexity

https://en.wikipedia.org/wiki/Cyclomatic_complexity

* Flutter
* JavaScript/ TypeScript https://eslint.org/docs/rules/complexity

Every project must have a Cyclomatic Complexity (CC) checked by the Linter.

For new projects a max CC is set and no commit is allowed w/ a higher CC.

For existing projects a max CC is set and no commit is allowed w/ a higher CC, unless they reduce it.

## Husky

Enforces the Linter rules on local commits.
