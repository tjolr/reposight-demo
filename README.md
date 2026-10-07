# reposight-demo

Demo repository for reviewing [RepoSight](https://reposight.vercel.app), a macOS menu bar app for GitHub Actions status.

It has three workflows that run on a schedule, so there is always fresh data:

| Workflow | Result |
|---|---|
| CI | Always passes |
| E2E tests | Always fails |
| Deploy | Runs for about 50 minutes every hour, so it is usually in progress |

Each one can also be started by hand from the Actions tab.
