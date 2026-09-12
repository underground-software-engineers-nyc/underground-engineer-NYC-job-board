# underground-engineer-NYC-job-board

Applications and job listings ledger for **Underground Software Engineer — NYC**.

- The public door is the **signal** on the main site. Solve it to find this repo.
- Applications are **GitHub issues only**. One issue per candidate. No email, no DMs.
- The **board is crew-only**: accepted developers get a signed crew pass and are added to the private crew repository.
- Refusals are polite. Acceptances come with a pass.

## Operator setup (one time)

1. Create this repo as **public** (this README ships in it).
2. Copy `ISSUE_TEMPLATE/` from the jobs app's `repo-seed/` here:

```bash
mkdir -p .github/ISSUE_TEMPLATE
cp /path/to/underground-engineer/jobs/repo-seed/ISSUE_TEMPLATE/* .github/ISSUE_TEMPLATE/
```

3. Labels to create: `application`, `job-application`, `review`, `accepted`, `refused`.
4. The jobs site links point here: `https://github.com/EnzoVezzaro/underground-engineer-NYC-job-board/issues`
   (already wired in `jobs/src/lib/content.ts` and `src/lib/signal.ts` of the main repo).
