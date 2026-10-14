# Commands to understand before submitting

The lab was completed with AI assistance, disclosed in the report.

| Command | Purpose |
| --- | --- |
| git init -b main | Start local version history on main. |
| git status --short | Inspect staged, unstaged, and untracked files. |
| git add app.js | Stage only the JavaScript file. |
| git diff | Compare working files with the staging area. |
| git diff --cached | Compare the staging area with the last commit. |
| git commit -m "message" | Save staged changes as a local commit. |
| git switch -c feature/about | Create and switch to the feature branch. |
| git switch main | Return to main. |
| git merge --no-ff feature/about | Integrate the feature and record a merge. |
| git remote add origin URL | Name the remote GitHub repository origin. |
| git push -u origin main | Publish main and set its upstream. |
| git fetch origin | Download remote commits without integrating them. |
| git rev-list --left-right --count main...origin/main | Count local-only and remote-only commits. |
| git pull --ff-only origin main | Fetch and advance main when no divergence exists. |
| git log --graph --oneline --all --decorate | Inspect concise branch history. |
| git check-ignore -v app.log | Identify the ignore rule matching a file. |

` M style.css` means unstaged modification; `M  app.js` means staged modification.
`*.log` ignores logs; the later `!important.log` exception keeps that file eligible.
Ignoring a file does not remove it if it is already tracked.

Before submitting, read the report, inspect the evidence, and explain staging versus
committing, committing versus pushing, and fetching versus pulling in your own words.
