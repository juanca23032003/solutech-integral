# SOLUTECH INTEGRAL website workflow

- When the user requests website changes and you modify files, validate the result, commit only the files related to that request, and push the commit to `origin/main`. The user has opted in to publishing website changes from this workspace.
- The local `.githooks/post-commit` hook pushes each commit. Do not issue a redundant second push after a successful commit.
- Confirm that the push succeeded before saying changes are live. GitHub Pages deploys from `main` and may take a few minutes.
- Saved, uncommitted edits are not public. Do not commit unrelated changes, credentials, private customer information, or installation details that could expose a customer's security.
- Do not publish when the user asks only for advice, requests that changes remain drafts, or has not approved a specific sensitive or potentially identifying addition.
