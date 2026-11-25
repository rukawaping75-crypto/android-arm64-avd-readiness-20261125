# Android ARM-translation AVD readiness probe

Generic GitHub Actions probe that starts an API 35 x86_64 Android emulator and
records whether its ABI translation layer advertises ARM support. It does not
download or install third-party APKs, use credentials, or send product traffic.

The workflow is manual-only and has read-only repository permissions. All
third-party actions are pinned to exact commits.
