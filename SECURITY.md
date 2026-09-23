# Security Policy

Security is a core requirement of Hermes Pro Max.

This project may integrate AI providers, external services, local tools, memory systems, authentication mechanisms and self-hosted infrastructure. Security issues affecting credentials, user data, model access or infrastructure should therefore be handled responsibly.

## Supported Versions

Hermes Pro Max is currently under active development.

Security fixes will primarily target the latest version of the main development branch.

## Reporting a Vulnerability

Please do not publicly disclose vulnerabilities that could expose:

- API keys
- Access tokens
- Authentication credentials
- Private user data
- Infrastructure secrets
- Local files
- Cloud resources
- Model-provider accounts
- Remote execution capabilities
- Privileged tool access

If you discover a security vulnerability, contact the project maintainer privately before publishing technical details.

Until a dedicated security reporting channel is available, please use GitHub's private vulnerability reporting feature when enabled.

## Secrets and Credentials

Never commit:

- `.env` files
- API keys
- OAuth tokens
- access tokens
- passwords
- private certificates
- private keys
- service-account credentials
- cloud provider secrets
- database credentials

Environment examples must contain placeholders only.

## Responsible Disclosure

When reporting a vulnerability, include:

- A clear description of the issue
- Affected component
- Reproduction steps
- Potential security impact
- Suggested mitigation, if known

Do not include real credentials or sensitive user information in vulnerability reports.

## Security Principles

Hermes Pro Max aims to follow these principles:

- Least-privilege access
- Explicit permission boundaries
- Secure secret handling
- Dependency auditing
- Input validation
- Isolation of tool execution
- Defense against prompt injection
- Controlled external network access
- Auditable agent actions
- Safe defaults
- Reproducible deployments
- Minimal exposure of personal data

## AI Agent Security

Agentic systems introduce additional security risks.

Integrations should consider:

- Prompt injection
- Tool misuse
- Unauthorized actions
- Data exfiltration
- Malicious documents or web content
- Excessive permissions
- Cross-provider data exposure
- Unsafe code execution
- Persistence of sensitive information in memory

High-impact actions should require explicit authorization and appropriate safeguards.

## Dependencies

Dependencies should be reviewed for:

- Known vulnerabilities
- Maintenance status
- Licensing
- Supply-chain risk
- Unnecessary privileges

Security-sensitive dependencies should be kept current whenever practical.

## Disclosure

Confirmed vulnerabilities should be fixed before public disclosure whenever reasonably possible.

Security improvements and responsible vulnerability reports are welcome.
