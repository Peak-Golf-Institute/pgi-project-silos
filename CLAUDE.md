# Notes for Claude

## Who you're working with

The owner is not a developer. Explain things in plain, everyday language and
avoid jargon. If a technical term is unavoidable, explain it in one short sentence.

## Always save work to GitHub

The owner works from two computers and uses cloud sessions, which are thrown
away after a while. Anything not pushed to GitHub is lost.

- After every finished task, or any change worth keeping, commit and push
  without being asked.
- Write commit messages in plain English that say what changed
  (e.g. "Update Talent Hub progress to 60%").
- After pushing, tell the owner in one line: "Saved to GitHub."

## Saved is not the same as live

The live site (https://pgi-project-silos.netlify.app) only updates from the
`main` branch. Cloud sessions usually save to a separate `claude/...` branch.

- After saving, say plainly whether the change is **live on the site** or
  **saved but not live yet**.
- If it isn't live, explain in one or two sentences what is needed to make it
  live, and offer to do it. Never put changes on `main` without the owner's
  OK in that conversation.
