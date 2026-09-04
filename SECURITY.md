# Security Policy

## Supported versions

Security fixes are generally applied to the latest maintained release or the current default branch of each repository. Older releases may no longer receive fixes. Check the repository's releases and documentation for project-specific support information.

## Reporting a vulnerability

Please do not open a public GitHub issue for a suspected security vulnerability.

Email [support@mirrormetech.com](mailto:support@mirrormetech.com) with the subject prefix `[Security]`. Include as much of the following information as possible:

- Affected repository, release, version, or commit.
- A clear description of the vulnerability and its potential impact.
- Reproduction steps or a minimal proof of concept.
- Relevant operating system, architecture, robot model, firmware, and network configuration.
- Suggested mitigations, if known.
- A safe way to contact you for follow-up.

Reports involving unsafe actuation, command validation, authentication, network exposure, dependency compromise, or sensitive-data disclosure are considered security-relevant.

Allow the maintainers time to investigate and coordinate a fix before public disclosure. We will communicate status and disclosure plans through the contact information supplied in the report.

## Safety

If a suspected vulnerability could cause unexpected physical motion, stop testing on hardware immediately, place the robot in a safe state using the documented procedure, and continue investigation only with simulation, replay data, or other non-actuating methods.
