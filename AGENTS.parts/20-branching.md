# Branching

This project is trunk-based: `main` is the only long-lived branch in every
repo. There are no `staging` or `dev` branches — use short-lived feature
branches off `main` and merge back promptly. Downstream consumers (e.g. the
openbase-coder workspace) pin this project's repos to `main` via multi.json
`fixedBranch`, and their CI always checks these repos out at `main`, so
whatever lands on `main` is what every consumer builds against.
