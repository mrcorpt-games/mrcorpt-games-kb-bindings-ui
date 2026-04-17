# Contributing to mrcorpt-games-kb-bindings-ui

Thank you for your interest in contributing to `mrcorpt-games-kb-bindings-ui`! This document explains the preferred process for contributing code, reporting issues, and suggesting improvements.

## How to Contribute

1. Fork the repository.
2. Create a branch for your change: `git checkout -b my-feature`.
3. Make your changes in a clean and focused manner.
4. Run the existing checks and tests.
5. Submit a pull request to the `master` branch.

## Reporting Issues

If you find a bug or want to request a feature, please open an issue with:

- A concise title.
- A clear description of the problem or enhancement.
- Steps to reproduce, if applicable.
- Any relevant environment details.

## Pull Request Guidance

When submitting a pull request, please include:

- A short summary of what changed.
- The motivation for the change.
- Any relevant issue references.
- Confirmation that tests were run.

Use the pull request template provided by this repository.

## Code Style

- Keep changes small and focused.
- Use clear and descriptive commit messages.
- Follow existing style and formatting in `bindings-ui.js`.

## Testing

This repository uses a minimal validation check via Node.js.

Run:

```bash
npm test
```

If your change adds or modifies functionality, ensure that it is tested and does not break the existing behavior.

## Security

If you discover a security vulnerability, please follow the instructions in `SECURITY.md` rather than opening a public issue.

## Thank You

Contributions are welcome from everyone. If you are unsure how to proceed, feel free to open an issue before writing code.
