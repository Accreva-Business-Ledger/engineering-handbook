# Repository stewardship

## Access

Grant repository access by role and current work. Remove access when the work ends. Keep automation permissions limited to the repositories and actions that need them.

## Default branch

Protect the default branch. Require pull requests, review, and resolved conversations. Block force pushes and branch deletion.

## Dependencies

Track dependency updates through pull requests. Review release notes and test the affected component before merge. Enable dependency alerts and secret scanning where GitHub supports them.

## Sensitive information

Keep credentials, customer data, internal addresses, and production logs out of Git history. Revoke a leaked credential before rewriting or removing the exposed value.
