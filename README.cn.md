# kops

[English version](./README.md)

Kubernetes Operations (kOps) - Production Grade k8s Installation, Upgrades and Management

[![x-cmd/install — kops Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/kops.svg?lang=zh)](https://x-cmd.com/install/kops)

## 安装

```sh
x install kops
```

## 代码洞察

合计: **3,662,093** 行代码（覆盖前 5 种语言、共 **13833** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 3,328,667 | 830,724 | 484,089 | 13152 |
| Json | 141,606 | 0 | 1 | 57 |
| Hcl | 79,662 | 0 | 7,741 | 81 |
| Yaml | 69,677 | 465 | 1,464 | 462 |
| AssemblyGAS | 20,441 | 1,504 | 3,368 | 81 |

## OpenSSF Scorecard 评分

总评分: **6.9 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/kubernetes/kops>
- **官网**: <https://kops.sigs.k8s.io/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.37.0` (2026-11-10)
- **最近提交**: 2026-11-17
- **Release 含资产**: 14 个

## 流行度

- **Star**: 16,710 · **Fork**: 4,715 · **开放 issue**: 5,370 · **贡献者**: 1,512

## 累计统计

- **发布数**: 241 · **已合并 PR**: 11853 · **开放 PR**: 51 · **已关闭 issue**: 5284 · **开放 issue**: 86 · **提交数**: 24800

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-18 | 2 | 147 | 17 | 3 | 8 | 188 |
| last60d | 2026-09-18 | 2 | 203 | 23 | 6 | 9 | 341 |
| 90d | 2026-08-19 | 3 | 270 | 28 | 10 | 10 | 484 |
| last180d | 2026-05-21 | 12 | 531 | 42 | 26 | 14 | 1024 |
| 360d | 2025-11-22 | 19 | 1043 | 51 | 70 | 20 | 2032 |
| last720d | 2024-11-27 | 35 | 1531 | 51 | 188 | 22 | 2967 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 改进这些数据

kops 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `kops` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/kops.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261117.yml` · 2026-11-17T10:38:12Z._
