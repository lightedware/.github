<!--
A pull request that FINISHES an issue writes `Closes #<n>` here, with a hash and the number.
Do not write `Closes GH-<n>`. GitHub reads a closing keyword only as `#<n>`, as
`<owner>/<repo>#<n>`, or as a URL. `GH-<n>` is the key of the tracker: it goes in the branch and
in each commit subject. A pull request with `Closes GH-<n>` merges, and it closes no issue.

A keyword closes an issue only when the base is the default branch. Thus a SLICE keeps the
`Refs GH-<n>` below, and only the pull request of the parent closes.
-->

Refs GH-

## What changed

<!-- One paragraph. Say the outcome, and not the steps. -->

## Verification

<!--
Give the commands that you ran, and their output. A pull request with no output gets no review.
-->

```text
```

## Checklist

- [ ] The branch name and each commit message trace to an issue: `GH-<number>`.
- [ ] The line at the top says `Closes #<n>` when this pull request finishes its issue.
- [ ] The body above gives the verification that I did, and its output.
- [ ] No secret value and no token is in the diff.
- [ ] A new document has a link from a document that exists.
