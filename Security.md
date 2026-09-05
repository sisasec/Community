# Reporting Security Issues

This document outlines the security policy and procedures for projects under the Silicon Savannah Security (Sisasec) organization.

## Supported Versions

For each project, we aim to release security patches for the most recent version at an accelerated cadence. Please refer to the specific project repository for details on supported versions.

## Reporting a Vulnerability

We encourage the responsible reporting of security-related vulnerabilities. To report a suspected vulnerability in any sisasec project, please use one of the following methods:

- Submitting an **issue** to the relevant project repository.
- Submitting a **pull request** with a potential fix to the relevant project repository.
- Sending an email to **security@sisasec.com**.

Please do not disclose the vulnerability publicly until it has been triaged and a fix has been released.

## Disclosure and Mitigation Process

Upon receiving a security bug report, the issue will be triaged and assigned to a maintainer. The maintainer will coordinate the fix and release process, typically involving:

- Initial communication with the reporter to acknowledge receipt and provide status updates.
- Confirmation of the issue and determination of affected versions.
- Codebase audit to identify similar potential vulnerabilities.
- Preparation of patches for all supported versions.
  - Patches will be submitted through pull requests, flagged as security fixes.
  - After merging and successful post-merge testing, patches will be released accordingly.

## Comments and Suggestions

We welcome suggestions for improving this process. Please share your ideas by creating an issue in the relevant project repository.
