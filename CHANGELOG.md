# Changelog

What changed in each release of the catalog, newest first. Add your change under "Unreleased" in
the same pull request. To release, raise the version and rename "Unreleased" to that version and
the date.

## Unreleased

- First version of the catalog, with the eslint-plugin-cds plugin. It installs in Codex, GitHub
  Copilot CLI and Claude Code, and the skill installs in other agents with `npx skills add`.
- New cds-guard plugin. Its skill sets up `@cbs-consulting/cds-guard` and keeps the agent from
  changing protected CDS entities, annotations, code blocks and files by accident.
- New container-templates plugin. Its skill starts a new SAP BTP project from the cbs Dev
  Container Templates and helps when the container or the project generator does not start.
