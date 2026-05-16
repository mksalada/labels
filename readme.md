# Labels

Pull Request (PR) labels keep your repository organized, automate project tracking, and communicate status at a glance.

The most effective label strategy categorizes PRs by Size, Status/Priority, Type of Work, and Impact.

## 1. By Type of Work

These labels explain what the PR actually contains.

- `type: bug` - Fixes an unintended error or flaw.
- `type: feature` - Adds completely new functionality.
- `type: enhancement` - Improves or iterates on an existing feature.
- `type: refactor` - Cleans up code without changing its behavior.
- `type: docs` - Updates documentation, README, or comments.
- `type: dependencies` - Bumps, updates, or adds a third-party package.
- `type: chore` - Routine tasks, maintenance, or tooling updates.

## 2. By Status & Priority

These labels indicate where the PR is in the workflow and how urgent it is.

- `status: draft / WIP` - Work in progress; not ready for review.
- `status: needs review` - Ready for maintainers to look over.
- `status: changes requested` - The reviewer found issues that need fixing.
- `status: approved` - The PR has been reviewed and cleared.
- `status: blocked` - Waiting on another PR, design, or external dependency.
- `priority: high / urgent` - Needs immediate attention and merging.

## 3. By Size (Scope)

These labels help reviewers gauge the time and effort required to review the code.

- `size: XS` (1–10 lines) - Trivial change, quick review.
- `size: S` (10–50 lines) - Small, simple change.
- `size: M` (50–200 lines) - Moderate, requires some scrutiny.
- `size: L` (200–500 lines) - Large, requires careful reviewing.
- `size: XL` (500+ lines) - Massive change, ideally broken down if possible.

## 4. By Component / Area

Great for large codebases to automatically route PRs to the right team.

- `area: frontend` - Changes affect the UI.
- `area: backend` - Changes affect server, database, or API logic.
- `area: api` - Modifies endpoints.
- `area: infrastructure` - DevOps, CI/CD, or deployment changes.

## 5. By Impact & Merge Rules

- `do not merge` - Safety label used while testing or if a PR breaks main.
- `breaking change` - Alters existing functionality / requires a major version bump.
- `needs tests` - Missing unit or integration tests.

---

For more comprehensive guidance on configuring and applying these workflows, refer to the [GitHub Managing Labels Documentation](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels) or the [Graphite Guide to PR Labels](https://graphite.com/guides/guide-to-github-pr-labels).

https://share.google/aimode/fvXFwa171tximfIzQ
