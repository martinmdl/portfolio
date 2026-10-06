# Repository Guidelines

## Project Structure & Module Organization

This repository is currently a blank starting point; no application source, tests, or assets are checked in yet. As the project grows, keep production code in a clearly named source directory (such as `src/`), tests in `tests/` or alongside their modules, and static assets in `public/` or `assets/`. Keep configuration and documentation at the repository root. Update this guide when the actual structure is established.

## Build, Test, and Development Commands

No build system or package manifest is present, so there are no project commands to run yet. When adding a toolchain, document its install, local development, build, lint, and test commands here and in the package or task configuration. Run the relevant checks before submitting changes; do not introduce scripts that require undocumented local setup.

## Coding Style & Naming Conventions

Follow the formatter and lint rules adopted by the project once configured. Use consistent indentation and descriptive names that match the language conventions (for example, `PascalCase` for component types and `camelCase` for JavaScript functions). Prefer small modules with clear responsibilities, and avoid committing generated output or local environment files.

## Testing Guidelines

No test framework or test files are present yet. Add tests with new behavior and place them in the project’s documented test location. Use names that describe the behavior under test (for example, `navigation.test.ts`) and record the command contributors should run.

## Commit & Pull Request Guidelines

There is no Git history yet, so no repository-specific commit convention can be inferred. Write short, imperative commit subjects (for example, `Add portfolio landing page`). Pull requests should explain the change and its rationale, list validation performed, link related issues when applicable, and include screenshots for visible UI changes.

## Security & Configuration

Keep credentials and machine-specific settings out of version control. Provide safe examples in an environment template if configuration is introduced, and document required variables without including real secrets.
