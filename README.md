# animoto/.github

Organization-wide defaults for Animoto repositories.

## What is here

| File | Purpose |
| --- | --- |
| `PULL_REQUEST_TEMPLATE.md` | Default pull request description for every Animoto repository |

## How the defaults apply

GitHub uses a file from this repository in any Animoto repository that does not have its own file of the same type. A repository's own file always wins.

For the pull request template, that means a repository uses this default only when it has no pull request template of its own, in its root, `docs/` or `.github/` directory.

To adopt the default in a repository that has its own template, delete the repository's template. Keep it only if it asks for something repository-specific that the default does not.

## Changing a default

Open a pull request here. A change reaches every repository that uses the default as soon as it merges, so treat it as an organization-wide change.
