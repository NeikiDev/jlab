# Security Policy

## Reporting a vulnerability

If you believe you have found a security vulnerability in JLab (the web app
at `jlab.threat.rip`, the public API, or any related infrastructure), please
report it privately.

**Email:** `admin@threat.rip`

**Please include:**

- A short description of the issue and its impact.
- Steps to reproduce, or a proof of concept.
- The affected URL, endpoint, or component.
- Your preferred contact for follow-up.

**Please do not:**

- File security issues in the public GitHub tracker.
- Attach live malware samples, exploit binaries, or credential dumps to public issues. Share them with the email above instead.
- Run automated scanners against the production service at a rate that disrupts other users. The public API is rate-limited to 15 requests per minute per IP; please stay well below that during testing.

## What to expect

We aim to acknowledge new reports within **3 working days** and to share a
remediation plan or timeline within **14 days** of acknowledgement. Complex
issues may take longer. We will keep you updated.

We are happy to credit reporters in release notes if you would like.

## Scope

In scope:

- `jlab.threat.rip` and any subdomain hosting JLab services.
- The public static-scan API documented at `jlab.threat.rip/api-docs.html`.

Out of scope:

- The desktop client, which has its own repository at
  [NeikiDev/jlab-desktop](https://github.com/NeikiDev/jlab-desktop). Report
  desktop-only issues there or to the same email.
- Findings that only affect outdated browser versions or require physical
  access to a user's device.
- Social engineering against staff or users.
