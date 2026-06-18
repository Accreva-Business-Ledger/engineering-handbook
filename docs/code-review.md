# Code review

## Author responsibilities

The author defines the scope, explains the design choice, and supplies evidence from tests or manual checks. The author removes unrelated changes before requesting review.

The pull request description must identify:

- the issue or maintenance task
- the affected components
- the checks that ran
- known risks or follow-up work

## Reviewer responsibilities

The reviewer checks behavior, security boundaries, data ownership, and test coverage. Style feedback should match an existing project rule or improve readability.

Reviewers request changes for defects that can affect:

- authorization or tenant separation
- financial accuracy or audit records
- data loss or irreversible behavior
- API compatibility
- deployment safety

## Merge requirements

The default branch requires a pull request and one approval. Authors resolve review conversations before merge. New commits dismiss stale approvals when they change reviewed code.
