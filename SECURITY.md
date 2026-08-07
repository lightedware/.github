# Security policy

This policy applies to each repository of the Lightedware organization. GitHub reads it from
`lightedware/.github`, thus a repository with no policy of its own shows this one.

A repository that needs different terms keeps its own `SECURITY.md`. A local file wins over this
default.

## How to report a defect

**Do not open a public issue for a defect in security.**

1. Send mail to `security@lightedware.com`.
2. Or use the private report form of the repository that holds the defect. Open the *Security*
   tab of that repository, and then *Report a vulnerability*.

Give this information:

- What the defect lets a person do.
- How to see it. Name the file, the resource, or the record.
- The repository, and the commit or the date that you looked at.

You get an answer in 3 days. Keep the defect private until the fix is ready.

## What is in scope

- A defect in a Lightedware product, service, or repository is in scope.
- A defect in a product of a different company is not. Report it to that company.
- A report from an automated tool, with no analysis of what the defect lets a person do, is not a
  report.

## If a secret goes into a commit

Speed is more important than a clean history.

1. Revoke the secret first. A commit that you remove is still in each clone and in each fork.
2. Then report it, and then clean the history.
