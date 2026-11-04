# Security

Report a vulnerability privately: open a [private security advisory](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) on the affected repository, or email the repository's code owner. Do not open a public issue.

Include the repository, the affected file or URL, steps to reproduce and the impact. We acknowledge within 3 business days.

## In every repository
- Secrets live in local `.env` files or the platform's secret store (GitHub Actions secrets, Cloudflare, Shopify). Never commit them.
- Dependabot alerts and security updates are on; high and critical alerts are fixed through a pull request.
- Changes reach the default branch only through a pull request.
