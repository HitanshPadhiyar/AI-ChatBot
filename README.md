# AI-Chatbot

## Commit Message Format

Each commit message has a special format that includes a **type**, and a **subject**:

```
<type>: <subject>
```

The commit message lines should not exceed 100 characters in length.

### Type

The type must be one of the following:

- **feat**: A new feature
  - Increments the minor version number (e.g., 1.0.0 -> 1.1.0)

- **fix**: A bug fix
  - Increments the patch version number (e.g., 1.0.0 -> 1.0.1)

- **docs**: Documentation-only changes
  - Does not affect the version number

- **style**: Changes that do not affect the code's meaning (e.g., white-space, formatting)
  - Does not affect the version number

- **refactor**: A code change that neither fixes a bug nor adds a feature
  - Does not affect the version number

- **perf**: A code change that improves performance
  - Does not affect the version number

- **test**: Adding missing or correcting existing tests
  - Does not affect the version number

- **chore**: Changes to the build process, auxiliary tools, or libraries
  - Does not affect the version number


### Subject

The subject should be a succinct description of the change. Please follow these guidelines:
- Use the imperative, present tense (e.g., "change" not "changed" or "changes")
- Do not capitalize the first letter
- Do not end with a dot (.)
