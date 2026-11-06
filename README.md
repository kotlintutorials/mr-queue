# mr-queue

A test fixture: docs-only changes approved under policy and merged through a merge queue.

`main` takes changes through the merge queue, which requires the `test` check and no approvals. `.mergeready.yml` puts
`docs/**` and Markdown at `merge`, after a one-hour veto window.
