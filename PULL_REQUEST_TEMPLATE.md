## What and why

<!-- What this changes and the reason. Link the issue. -->

## How it was checked

<!-- Tests run, and what you saw working. A green check is not the same as seeing it work. -->

## Rules this touches

<!-- Tick what applies, or write "none" for docs-only changes. -->

- [ ] Personal data and payment credentials stay in the vault: never in our database or logs
- [ ] Money and identity changes write an audit record (who, what, when, outcome)
- [ ] Authorization is checked in the handler, on the role
- [ ] Migrations are new files only; no applied migration was edited
- [ ] Secrets come from Secret Manager, not source
- [ ] Infrastructure changes are in Terraform
- [ ] Sanctions screening still sits in the payout path and fails closed
