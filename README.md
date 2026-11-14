# kops

[中文版本](./README.cn.md)

Kubernetes Operations (kOps) - Production Grade k8s Installation, Upgrades and Management

[![x-cmd/install — kops Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/kops.svg)](https://x-cmd.com/install/kops)

## Install

```sh
x install kops
```

## Code insight

Total: **3,661,914** lines of code across **13832** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 3,328,507 | 830,677 | 484,078 | 13151 |
| Json | 141,606 | 0 | 1 | 57 |
| Hcl | 79,662 | 0 | 7,741 | 81 |
| Yaml | 69,659 | 465 | 1,464 | 462 |
| AssemblyGAS | 20,441 | 1,504 | 3,368 | 81 |

## OpenSSF Scorecard

Overall score: **6.9 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/kubernetes/kops>
- **Homepage**: <https://kops.sigs.k8s.io/>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.37.0` (2026-11-10)
- **Last commit**: 2026-11-13
- **Assets in release**: 14

## Popularity

- **Stars**: 16,706 · **Forks**: 4,714 · **Open issues**: 5,370 · **Contributors**: 1,509

## Totals (cumulative)

- **Releases**: 241 · **Merged PRs**: 11850 · **Open PRs**: 47 · **Closed issues**: 5284 · **Open issues**: 86 · **Commits**: 24789

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-15 | 2 | 153 | 13 | 4 | 7 | 236 |
| last60d | 2026-09-15 | 2 | 199 | 19 | 6 | 8 | 334 |
| 90d | 2026-08-16 | 3 | 283 | 24 | 11 | 11 | 536 |
| last180d | 2026-05-18 | 12 | 551 | 39 | 27 | 14 | 1077 |
| 360d | 2025-11-19 | 19 | 1040 | 47 | 71 | 19 | 2037 |
| last720d | 2024-11-24 | 35 | 1534 | 47 | 189 | 22 | 2961 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [kops-darwin-amd64](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-darwin-amd64) | 80.3 MiB | `native/darwin/x64` |
| [kops-darwin-amd64.sha256](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-darwin-amd64.sha256) | 65 B | `native/darwin/x64` |
| [kops-darwin-arm64](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-darwin-arm64) | 74.3 MiB | `native/darwin/arm64` |
| [kops-darwin-arm64.sha256](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-darwin-arm64.sha256) | 65 B | `native/darwin/arm64` |
| [kops-linux-amd64](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-linux-amd64) | 78.2 MiB | `native/linux/x64` |
| [kops-linux-amd64.sha256](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-linux-amd64.sha256) | 65 B | `native/linux/x64` |
| [kops-linux-arm64](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-linux-arm64) | 71.6 MiB | `native/linux/arm64` |
| [kops-linux-arm64.sha256](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-linux-arm64.sha256) | 65 B | `native/linux/arm64` |
| [kops-windows-amd64](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-windows-amd64) | 79.7 MiB | `native/win/x64` |
| [kops-windows-amd64.sha256](https://github.com/kubernetes/kops/releases/download/v1.37.0/kops-windows-amd64.sha256) | 65 B | `native/win/x64` |
| [nodeup-linux-amd64.xz](https://github.com/kubernetes/kops/releases/download/v1.37.0/nodeup-linux-amd64.xz) | 8.3 MiB | `native/linux/x64` |
| [nodeup-linux-amd64.xz.sha256](https://github.com/kubernetes/kops/releases/download/v1.37.0/nodeup-linux-amd64.xz.sha256) | 65 B | `native/linux/x64` |
| [nodeup-linux-arm64.xz](https://github.com/kubernetes/kops/releases/download/v1.37.0/nodeup-linux-arm64.xz) | 7.0 MiB | `native/linux/arm64` |
| [nodeup-linux-arm64.xz.sha256](https://github.com/kubernetes/kops/releases/download/v1.37.0/nodeup-linux-arm64.xz.sha256) | 65 B | `native/linux/arm64` |

## Distribution status

Reported by **47** distros on [repology.org](https://repology.org/project/kops). **5** are ✅ on the latest upstream release, **20** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `1.37.0` | ✅ latest |
| Nix unstable | `1.36.2` | ⚠️ outdated |
| Void | `1.36.2` | ⚠️ outdated |

## Improve this data

Install metadata for kops lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `kops` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/kops.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261114.yml` · 2026-11-14T07:26:17Z._
