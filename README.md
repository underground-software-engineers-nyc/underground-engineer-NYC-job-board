# underground-engineer-NYC-job-board

Applications ledger for **Underground Software Engineer — NYC**.

This repository is the only application door — and it is a door, not a form:

- The quest lives on the **main site**. Solve it. It hands you this repo.
- Applications are **GitHub Issues or Pull Requests only** — one per candidate. No email, no DMs, no comments on strangers' threads.
- Put your answers, portfolio, and anything with substance in a **gist or external link** and reference it — keep the thread a thread.
- The **crew reviews** every submission. Acceptances come with a signed crew pass; refusals are polite.

## Submit via ISSUE

Open an issue using the **Crew application** template:

- [New issue →](https://github.com/underground-software-engineers-nyc/underground-engineer-NYC-job-board/issues/new/choose)
- Prove you solved the quest (challenge answers).
- Link your portfolio / code as a gist or external site.
- One issue per candidate. Label lands as `application`.

## Submit via PULL REQUEST

Fork this repo, add `applications/<your-handle>.md`, fill the PR template, and open the PR:

- [Fork →](https://github.com/underground-software-engineers-nyc/underground-engineer-NYC-job-board/fork)
- Include the challenge answers and your application in the PR body.
- Link a gist or external portfolio. The crew reviews the diff.

## The crew decides

- Every submission carries the `review` label and is read by the crew.
- `accepted` → you are added to the private crew repo and a signed crew pass is minted.
- `refused` → polite, one line. The tunnel keeps its counsel.

## Labels

`application` · `job-application` · `review` · `accepted` · `refused`

## Operator setup (one time)

1. This repo is **public** (README + templates ship in it).
2. `ISSUE_TEMPLATE/` + `PULL_REQUEST_TEMPLATE.md` already live under `.github/`.
3. Submit routes are wired in `jobs/src/lib/content.ts` and `src/lib/signal.ts` of the main repo.