# Daily workflow

1. Open the current daily note and state the available time (30–60 minutes).
2. Tell the assistant: "Day N, X minutes. Last result: … Current question: …"
3. Read one relevant section and implement one bounded change.
4. Record the discussion in your own words. Separate confirmed claims from hypotheses.
5. Link code, capture summaries, diagnostics, and sources as evidence.
6. Update the note's status and PROGRESS.md based on actual completion.
7. Review the diff, commit the session, and push after a remote is configured.

```powershell
git status --short
git diff
# Stage only the paths relevant to this session, for example:
git add notes/week-01/day-01.md PROGRESS.md
git diff --cached
git commit -m "day-01: record API mapping and starter findings"
git push
```

Commit small coherent changes. Code can be committed separately from the discussion
summary. Never label a result measured or validated without evidence. At the weekly
review, promote durable findings to conclusions/ using the conclusion template.

## Remote repository

The repository uses main and preserves the existing GitHub history and license.
Origin: https://github.com/pasu/DX_tutorial.git

```powershell
git remote -v
git pull --ff-only
git push
```

Commit or stash local changes before pulling. If histories diverge, fetch and inspect
before integrating; do not force-push over existing work.

## Capture and asset hygiene

Keep large captures, builds, proprietary assets, credentials, and local paths out of
commits. Write compact capture summaries with hardware, driver, build/configuration,
workload, timings, and conclusions. Keep third-party sample licenses and attribution.
