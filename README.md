# osac-ci-rehearsal

A scratch repository to rehearse the shared workflows of osac-ci (the native pull request flow) with stub suites, including
fork pull requests and the merge queue, without touching a real repository. Nothing here is a product. It can be deleted.

- `CI` is a stub check; the suites `alpha` and `beta` are stubs (`beta` runs only when a file under `beta/` changes and
  fails when `beta/fail` exists).
- The callers in `.github/workflows` call the shared workflows of osac-ci by a pinned commit.
