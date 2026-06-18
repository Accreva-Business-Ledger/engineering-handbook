# Testing and verification

Each repository defines commands that match its stack. A change should pass the smallest relevant checks during development and the full repository checks before merge.

## Evidence

Pull requests record commands and results. A failed or skipped check needs a reason that a reviewer can assess.

## Product checks

ACCREVA product repositories use automated checks for backend tests, frontend tests, type checks, builds, and migration validation. Teams add focused tests when a change affects a domain rule.

## Manual checks

Use manual checks for user workflows, visual behavior, and integrations that cannot run in an isolated test. Record the scenario, expected result, and observed result.
