# Project workflow rules

## Git / GitHub Actions
- Pushes to `main` trigger GitHub Actions, so to save usage, **only push once changes are finalized**. Commit locally as often as needed, but don't push in-progress work.
- Do not push until the user has reviewed the preview and confirmed everything checks out. Once approved, run `git push`.

## Previewing changes
- For every change the user requests, **show a preview** of it before considering it done (e.g. open `index.html` locally in the browser or start a local static server and share the preview).
- Wait for the user's approval of the preview, then commit and push.
