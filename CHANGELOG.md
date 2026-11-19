# Changelog

What changed in each release of the catalog, newest first. Add your change under "Unreleased" in
the same pull request. To release, raise the version and rename "Unreleased" to that version and
the date.

## Unreleased

- First version of the catalog, with the eslint-plugin-cds plugin. It installs in Codex, GitHub
  Copilot CLI and Claude Code, and the skill installs in other agents with `npx skills add`.
- New cds-guard plugin. Its skill sets up `@cbs-consulting/cds-guard` and keeps the agent from
  changing protected CDS entities, annotations, code blocks and files by accident.
- New stack-sentinel plugin. Its skill sets up `@cbs-consulting/stack-sentinel`: a first scan,
  the weekly pipeline for GitHub Actions or Azure DevOps, and the settings the user makes.
