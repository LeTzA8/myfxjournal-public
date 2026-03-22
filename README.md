# MyFXJournal

This public repository is a selective public mirror for MyFXJournal.

It includes a curated subset of the app structure, routes, templates, and static assets.

Key production modules are intentionally private. That includes:

- MT5 setup, sync, and account-linking workflows
- AI prompt, review-generation, and related dashboard logic
- import/parsing, analytics, and deduplication logic
- background workers, internal routes, and operational tooling
- database schema, migrations, and test coverage

This repo is kept curated on purpose so the project can be shared publicly without exposing the parts we consider core moat or operationally sensitive.

It is not intended to be a full runnable production mirror.
