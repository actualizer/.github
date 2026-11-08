# Security Policy

This policy applies to every public Actualize repository that does not ship its own
`SECURITY.md`.

## Supported versions

Security fixes are released for the latest version of each plugin only. Please check that the
issue still occurs on the latest release before reporting it.

## Reporting a vulnerability

Please do **not** open a public issue for security problems.

Report it privately via GitHub instead: open the affected repository, go to the **Security**
tab and choose **Report a vulnerability**. Only you and the maintainers can see the report.
If you cannot use GitHub, send an email to plugin@actualize.de.

Please include:

- the plugin, its version and the Shopware version
- the steps to reproduce
- what an attacker gains

## What to expect

- An acknowledgement within 7 days.
- Once confirmed, a fix is released as a new version. The advisory is published after that
  release, crediting you unless you prefer otherwise.

## Scope

In scope are vulnerabilities in the plugin's own code: its Storefront and Administration
output, its routes and API endpoints, and the data it stores or sends.

Out of scope:

- Vulnerabilities in Shopware itself. Please report those to Shopware:
  <https://github.com/shopware/shopware/security/policy>.
- Vulnerabilities in other extensions, even when they interact with one of our plugins.
