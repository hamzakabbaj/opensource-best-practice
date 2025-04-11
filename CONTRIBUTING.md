# 🤝 Contributing Guide

Thanks for taking the time to contribute! We welcome bug fixes, feature suggestions, documentation improvements, and everything in between.

Please follow these guidelines to help us maintain a consistent, high-quality codebase and workflow.

---

## 🐛 Reporting Issues

If you've found a bug or want to suggest a feature, please:

1. Use the appropriate [issue template](./.github/ISSUE_TEMPLATE)
2. Be clear and detailed
3. Add screenshots, logs, or environment info when possible

All new issues are labeled `triage` and reviewed by maintainers.

---

## 🛠️ Working on an Issue

Before writing code:

- Find an open issue labeled `help wanted` or `good first issue`, or open a new one
- Comment on the issue to claim it (or ask to be assigned)
- Wait for it to be marked `status: accepted` before starting work

When you’re ready:

1. **Fork** the repo (if you're not a collaborator)
2. **Create a feature branch** from `main`
   ```bash
   git checkout -b fix/login-issue-42
   ```

## 💡 Submitting a Pull Request

When you’re ready to submit a PR:

- Make sure your branch is up to date with main
- Write a clear title and description
- Link the issue in the PR body using:
  Fixes #<issue-number>, Closes #<issue-number>, etc.
- Push commits with clear messages:

```bash
git commit -m "Fix: handle null user in login flow"
```

- Add tests if needed
- Request a review or tag a maintainer

✅ GitHub will auto-close the linked issue when your PR is merged

## 🧪 Tests & Linting

If the project has test/lint setup (TBD), please run them before submitting:

```bash
npm run lint
npm run test
# or
python -m pytest
```

## 🧼 Code Style & Commit Tips

- Keep commits focused on one task
- Use conventional commit messages where possible:
  - init: project setup
  - api: add/change API endpoint
  - db: add/change database schema
  - ui: add/change UI component
  - auth: add/change authentication
  - fix: resolve login bug
  - feat: add dark mode toggle
  - docs: update README
  - refactor: improve code readability
  - chore: update dependencies
  - style: format code
  - perf: optimize performance
  - test: add missing tests
  - build: update build scripts
- Keep PRs small and focused. If it gets too big, break it up.

## 🗂️ Labels You’ll See

| Label              | Meaning                         |
| ------------------ | ------------------------------- |
| `triage`           | Needs review by maintainers     |
| `accepted`         | Approved and ready to work on   |
| `help wanted`      | Good for contributors           |
| `good first issue` | Easy entry-level issues         |
| `needs info`       | Needs more detail from reporter |

## 📣 Questions or Discussions?

Please use GitHub Discussions or open an issue if you’re unsure about anything.
