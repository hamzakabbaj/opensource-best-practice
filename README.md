# This is a foundational project for open source best practices

Here’s a step-by-step checklist of everything we’ll configure — in smart order:

⸻

🔧 PROJECT FOUNDATION 1. 📁 Repository Structure
• Base folders, naming conventions, directory layout 2. 📄 Essential Files
• README.md – Clear, welcoming intro + setup
• LICENSE – Choose an open source license
• .gitignore – Ignore the right files
• CODE_OF_CONDUCT.md
• CONTRIBUTING.md

⸻

🚥 WORKFLOW & AUTOMATION 3. ⚙️ GitHub Actions
• Basic CI: test/lint/workflows
• Auto-label + triage setup
• PR + commit message best practices 4. 📝 Issue & PR Templates
• Bug, feature, question, documentation templates
• PR template for consistency 5. 🏷️ Labels & Projects
• Create helpful labels
• Set up GitHub Projects for issue tracking

⸻

📦 RELEASE & MAINTENANCE 6. 📜 CHANGELOG.md
• Setup with Keep a Changelog
• Manual or automated (release-drafter) 7. 🔖 Versioning & Releases
• Semantic versioning setup
• GitHub releases and tags
• Optional: auto-tagging tools

⸻

👥 COMMUNITY & COLLAB 8. 💬 Discussions & Community
• Enable GitHub Discussions
• Add a welcome message
• Add SECURITY.md for reporting vulnerabilities 9. ✨ Contributor Recognition
• Use all-contributors or GitHub built-ins
• Add badges and acknowledgments

## Labels creation script

```bash
gh label create "triage" --color cfd3d7 --description "Issue needs initial review"
gh label create "bug" --color d73a4a --description "Something isn't working"
gh label create "enhancement" --color a2eeef --description "New feature or improvement"
gh label create "question" --color d876e3 --description "Needs more info or clarification"
gh label create "documentation" --color 0075ca --description "Docs need updates or clarification"
gh label create "help wanted" --color 008672 --description "Open to external help"
gh label create "good first issue" --color 7057ff --description "Good entry-level contribution"
gh label create "priority: high" --color b60205 --description "Critical issue, fix ASAP"
gh label create "priority: low" --color ededed --description "Nice to fix eventually"
gh label create "needs info" --color fbca04 --description "More information is required to proceed"
gh label create "accepted" --color 0e8a16 --description "Issue has been accepted for implementation"
gh label create "ready" --color 5319e7 --description "Issue is ready for development"
gh label create "confirmed" --color 1d76db --description "Issue has been confirmed and validated"
gh label create "rejected" --color ff0000 --description "Issue has been rejected or won't be implemented"
```

# Automatic Semantic versioning

- install python-semantic-control
