#Git Learning Summary

## What is Git?
A version control system that tracks changes to code over time,
letting you save snapshots, undo mistakes, and collaborate with others.

## The three zones
- **Working directory** — where you edit files
- **Staging area** — changes queued for the next commit (git add)
- **Local repository** — saved snapshots (git commit)

## Key Commands I Learned
'git init' : Start a new Git repo
'git add .' : Stage all changes
'git commit -m "message"' : Save a snapshot
'git push' : Upload commits to GitHub
'git pull' : Download latest changes
'git checkout -b name' : Create and switch to a branch

## Branching strategy
- `main` — production code, always deployable
- `dev` — integration branch, latest collective work
- `feature/*` — one branch per task, merged into dev via Pull Request

## What Git solves
- Simultaneous editing without overwriting each other's work
- Full history of what changed, when, and why
- Safe experimentation — any state is recoverable
- Decouples working from sharing, enabling code review