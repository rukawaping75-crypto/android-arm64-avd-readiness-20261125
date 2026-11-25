# ARM64 Android AVD readiness probe

Generic GitHub Actions probe that starts an ARM64 Android emulator and records
non-sensitive readiness facts. It does not download or install third-party APKs,
use credentials, or send product traffic.

The workflow is manual-only and has read-only repository permissions. All
third-party actions are pinned to exact commits.
