# Branch naming policy

## Last change

- **Author**: Mahammad Taghizada
- **Date**: 14.04.2024

The default branch of the repository should be called `main`.

There are three core types of branches:

1. **feature** - any branch that is related to the new feature development.
2. **update** - any branch that is related to the update development of existing feature.
3. **fix** - any branch that is related to the bugfixing of an existing feature.

Therefore, each branch name should be as following: `coretype/branch-name`.

The branch name should be written in **kebab case** (this is isn't a joke). You can read more about kebab case here: https://developer.mozilla.org/en-US/docs/Glossary/Kebab_case

Here is an example of the branch names using this policy:

- feature/create-user-endpoint
- update/create-user-input-validation
- fix/create-user-db-transaction
