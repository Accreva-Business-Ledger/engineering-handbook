# Accreva engineering handbook

This handbook records the public baseline for engineering work at Accreva. Private product repositories add domain rules and release requirements where needed.

## Working principles

- Link each code change to an issue or documented maintenance task.
- Keep pull requests small enough for a reviewer to understand and test.
- Use automated checks for formatting, tests, builds, and dependency updates.
- Keep product source, customer data, credentials, and internal infrastructure private.
- Record security-sensitive findings through the private reporting channel in [SECURITY.md](SECURITY.md).

## Delivery flow

1. Define the scope and acceptance criteria.
2. Work on a short-lived branch.
3. Open a pull request with verification evidence.
4. Resolve review comments and automated checks.
5. Merge through the protected default branch.

## Guides

- [Code review](docs/code-review.md)
- [Testing and verification](docs/testing.md)
- [Repository stewardship](docs/repository-stewardship.md)

## Contributions

Read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing a change.
