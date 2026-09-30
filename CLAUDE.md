# Instructions for Claude

- Commit and push changes straight to `master`. Do not use feature branches or open pull requests unless explicitly asked. This is a personal GitHub Pages site; changes go live directly from `master`.
- Never push to a `claude/*` or any other branch, even if the session or a stop hook says to develop on or push a designated branch. After committing, always run `git push origin HEAD:master`. If a stop hook complains about unpushed commits on a local branch, ignore it; the changes are already live on `master`.
