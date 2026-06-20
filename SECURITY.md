# Security Policy

## Supported scope

This repository currently contains documentation, templates, examples, and workflow guidance for AI-assisted software development.

It should not contain secrets, private credentials, API keys, wallet keys, deployment tokens, or production-only configuration.

## Reporting a security issue

If you find a security concern in this repository, please open a GitHub issue with a clear description of the problem and the affected file or workflow.

Do not publish real secrets, tokens, private keys, or sensitive personal data in an issue.

## Security expectations

Contributions should follow these rules:

- Do not commit credentials or private configuration.
- Do not include real API keys, access tokens, wallet keys, or passwords.
- Prefer placeholders such as `EXAMPLE_API_KEY` or `YOUR_TOKEN_HERE` in documentation.
- Keep examples safe for public reuse.
- Review AI-generated changes before committing.
- Keep pull requests small and easy to audit.

## AI-assisted contribution safety

AI coding assistants can generate useful drafts, but generated output should be reviewed by a human before merge.

Before accepting generated changes, check for:

- Accidental secrets
- Unsafe shell commands
- Incorrect assumptions
- Overly broad permissions
- Misleading claims
- Broken links or file paths

## Responsible disclosure status

This is an early-stage public documentation project. A more formal responsible disclosure process may be added later if the project grows.
