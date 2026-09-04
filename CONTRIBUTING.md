# Contributing to MirrorMe Robotics

Thank you for helping improve the MirrorMe Robotics open-source projects. Contributions in English or Chinese are welcome.

## Before you start

1. Read the target repository's README, license, safety notes, and development status.
2. Search existing issues and pull requests to avoid duplicate work.
3. Open an issue before making a large change, changing a public API or model format, or introducing a new dependency.
4. Never include credentials, private robot data, proprietary files, or personal information in an issue or pull request.

## Reporting a bug

Use the bug-report form in the relevant repository. Include:

- Repository version, release, tag, or commit.
- Operating system, architecture, language/runtime version, and relevant hardware or firmware information.
- Minimal steps to reproduce the problem.
- Expected and actual behavior.
- Logs or screenshots with sensitive information removed.

For a security vulnerability, follow the [Security Policy](https://github.com/mirrormerobotics/.github/security/policy) instead of opening a public issue.

## Proposing a change

- Keep each pull request focused on one problem.
- Follow the target repository's existing style and structure.
- Add or update tests when behavior changes.
- Update documentation, examples, and changelogs when users are affected.
- Preserve license, copyright, provenance, and third-party notice files.
- Explain how the change was verified and list any hardware testing performed.

## Robotics safety

Changes that can affect physical motion require extra care:

- Default to a stopped, disarmed, read-only, or simulated state where practical.
- Validate command limits, timeouts, disconnect behavior, and shutdown behavior.
- Test in simulation or with offline fixtures before using physical hardware.
- Do not claim hardware validation unless the stated configuration was actually tested in a controlled area.
- Document remaining risks, unsupported behavior, and required operator precautions.

Maintainers may request additional evidence or split a change into smaller pull requests before review.

## Licensing

By submitting a contribution, you agree that it may be distributed under the license of the target repository. Do not submit code or assets that you do not have the right to contribute.
