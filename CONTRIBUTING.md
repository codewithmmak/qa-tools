# Contributing

- [How to Contribute](#how-to-contribute)
  * [Getting Code](#getting-code)
  * [Code reviews](#code-reviews)
  * [Commit Messages](#commit-messages)


## How to Contribute

### Getting Code

Clone this repository

```bash
git clone https://github.com/codewithmmak/QATools
cd QATools
```

### Code reviews

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.

### Commit Messages

Commit messages should follow the Semantic Commit Messages format:

```
label: title

description

footer
```

1. *label* is one of the following:
    - `fix` - QATools bug fixes.
    - `feat` - QATools features.
    - `docs` - changes to docs, e.g. `docs(api.md): ..` to change documentation.
    - `test` - changes to QATools tests infrastructure.
    - `devops` - build-related work, e.g. CI related patches and general changes to the browser build infrastructure
    - `chore` - everything that doesn't fall under previous categories
2. *title* is a brief summary of changes.
3. *description* is **optional**, new-line separated from title and is in present tense.
4. *footer* is **optional**, new-line separated from *description* and contains "fixes" / "references" attribution to github issues.

Example:

```
docs: added API automation tool list

Added low code API automation tool list

Additional info goes here...
```


