# JLab Issue Tracker

Bug reports and feature requests for **JLab** (Java Lab), the public static
JAR scanner at [jlab.threat.rip](https://jlab.threat.rip/).

JLab scans a single `.jar` file (up to 50 MB) for known malware signatures
and returns the matched results grouped by severity. The API is public and
free, rate-limited to **15 requests per minute per IP**. Full reference:
[jlab.threat.rip/api-docs.html](https://jlab.threat.rip/api-docs.html).

## Where to file an issue

| You are reporting an issue with… | File it here |
| --- | --- |
| The **web app** (jlab.threat.rip) or the **public API** | This repo. Open a [new issue](https://github.com/NeikiDev/jlab/issues/new/choose). |
| The **desktop client** (Windows / macOS / Linux app) | [NeikiDev/jlab-desktop](https://github.com/NeikiDev/jlab-desktop/issues). |
| A **security vulnerability** | Do **not** open a public issue. See [SECURITY.md](./SECURITY.md). |

## Before you file

A short checklist so we can act on the report:

- Reproduce the problem once more in a clean browser session (no extensions, or use a private window).
- If the scan returned a result, copy the **scan ID** from the URL or response.
- If it failed, note the **HTTP status** (visible in the browser dev tools, Network tab) and the time in UTC.
- Do **not** attach malicious JAR samples to the issue. Share them via the security email instead, see [SECURITY.md](./SECURITY.md).
- Search [existing issues](https://github.com/NeikiDev/jlab/issues?q=is%3Aissue) first.

## Contact

- General: `jlab-issues@threat.rip`
- Community: [threat.rip/discord](https://www.threat.rip/discord)
- Security: see [SECURITY.md](./SECURITY.md)

## License

This repository hosts issue tracking only. JLab itself is operated as a hosted service at jlab.threat.rip.
