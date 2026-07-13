## Change Overview
- Provide a concise description of the changes introduced by this PR and why they are necessary.
- Jira Ticket Link: REL-XXXX (or linked Sprint Task)
---
## Change Management & Risk Assessment (SOC 2)
### 1. Risk Level Classification
Check the box that best applies to this deployment:
- [ ] High Risk: Involves database schema changes, core authentication/security updates, or impacts critical customer data processing.
- [ ] Medium Risk: Involves API contract updates, changing third-party integrations, or major UI overhauls.
- [ ] Low Risk: Minor bug fixes, documentation updates, or CSS/styling tweaks.
### 2. Business & Security Impact Analysis
Describe the potential downstream effects if this deployment fails or introduces a bug.
### 3. Explicit Rollback & Contingency Plan
- Auditors require a step-by-step procedure to safely revert this change if production smoke tests fail. Do not leave this blank.
- Primary Rollback Action: (e.g., Run `git revert <commit_hash>` / Redeploy previous tag `v1.2.3`)
- Feature Flag Toggle (if applicable): (e.g., Set flag `ff_new_checkout` to OFF)
- Data Mitigation: (e.g., Is a database rollback script required? Yes/No)
---
## Testing Evidence & Verification
Prove that this code is safe to deploy. Paste logs, screenshots, or links to test runs.
- Automated Test Results: (e.g., CI/CD pipeline link or green check verification)
- Manual Verification Steps performed:
- Staging Environment Link/Proof:
---
## Peer Review Sign-Off
By approving this PR, the reviewer confirms they have evaluated both the code quality and the adequacy of the rollback plan listed above.
- Name of Approver:
