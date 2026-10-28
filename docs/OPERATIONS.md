# Student-Registration: verification and operations

Reviewed against [default-branch commit b018d1f366ba](https://github.com/noel-ult/Student-Registration/commit/b018d1f366ba2b58ae8c3f7df692a73895f4852e) on 2026-10-28. Start with the [developer guide](../README.md) for installation and architecture, and the [source reference](REFERENCE.md) for exact scripts, configuration readers, routes, and source locations.

## Static form

Open the form, tab through labelled fields, exercise required controls, and inspect the sample student table. A submission does not persist a registration.

These are acceptance scenarios for a maintainer to run in the documented environment. Their inclusion is not a claim that live integrations or production credentials were tested during this documentation update.

## Deployment and failure diagnosis

Serve index.html from a static host. A working form layout does not establish an application endpoint.

## Maintaining the contract

When behavior changes, update the guide and examples in the same PR. Check the entry point and working directory before copying commands. Use the linked source readers to distinguish build-time configuration from process environment. For failures, capture the first application error, runtime version, selected mode, and redacted configuration names before later proxy or port errors.

Keep changes tied to evidence: a declared command is not proof it passes, a process health response is not a successful end-to-end workflow, and a historical report describes its own revision. Record actual check results and any unavailable external services in the PR.
