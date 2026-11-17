# Security policy

## Supported versions

Only the **latest release** of VizMini2 receives fixes. When a version has a
security problem, the app can require an update before it can be used again.

## Reporting a vulnerability

Please **do not open a public issue**. Report it privately in one of these ways:

- GitHub: **Security → Report a vulnerability** in the affected repository (for the
  apps: <https://github.com/VizMini2/VizMini2/security/advisories/new>).
- Email: `jc.manzanares.serrano [at] gmail.com`, with `[VizMini2 security]` in the subject.

Include the app version, the platform (Android or desktop, and its version) and the
steps to reproduce. You will
get an answer within 7 days. Once a fix is released, you will be credited in the
changelog if you wish.

## Scope

In scope: the VizMini2 Android and desktop apps, the ROS 2 package, the account and
profile sync, the documentation website, and VizMini2's build of jros2 (problems that
also affect the original ihmcrobotics/jros2 are reported there too).

Out of scope: ROS 2 and DDS themselves. ROS 2 traffic is not encrypted unless
SROS2 / DDS Security is configured on your network; this is a property of ROS 2,
not a vulnerability of the app.
