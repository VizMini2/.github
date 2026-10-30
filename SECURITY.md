# Security policy

## Supported versions

Only the **latest release** of VizMini2 receives fixes. When a version has a
security problem, the app can require an update before it can be used again.

## Reporting a vulnerability

Please **do not open a public issue**. Report it privately in one of these ways:

- GitHub: **Security → Report a vulnerability** in the affected repository.
- Email: `jc.manzanares.serrano [at] gmail.com`, with `[VizMini2 security]` in the subject.

Include the app version, the Android version and the steps to reproduce. You will
get an answer within 7 days. Once a fix is released, you will be credited in the
changelog if you wish.

## Scope

In scope: the VizMini2 Android app, its account and profile sync, and this
documentation website.

Out of scope: ROS 2 and DDS themselves. ROS 2 traffic is not encrypted unless
SROS2 / DDS Security is configured on your network; this is a property of ROS 2,
not a vulnerability of the app.
