# EDA Contest – Semitronix Self-built Cases

2026 EDA 精英挑战赛（广立微 Scan Insertion 赛题）自建测试 case 包。

| 文件 | 日期 | 内容 |
|---|---|---|
| `selfbuilt_cases_verified_20261029.zip` | 2026-10-29 | 11 个设计（aes_core、faraday_dma、ISCAS s9234/s13207/s15850/s35932/s38417/s38584、spi、systemcaes、usb_funct），附 `run_all.sh`，已验证 |
| `selfbuilt_task2_cases_20261103.zip` | 2026-11-03 | 上述设计的 task2 版本，附 `generation_summary.json` |
| `capability_cases_20261104.zip` | 2026-11-04 | C1–C11 能力测试 case（skew/lockup、retiming、hard IP wrapper、ECO cleanup、incremental 等），附 `ablate_result.json` |
| `newcases_t1t2_20261105.zip` | 2026-11-05 | 新增 task1 / task2 case，含 `_bases`、`tools` 及验证 / 复查结果 |

每个包内有各自的 README 说明运行方式。运行需要基础镜像 `scan-agent-base:ubuntu24`（linux/amd64），并能访问比赛提供的 scan insertion license server（通过环境变量 `SCANINSERTION_LICENSE_SERVER` 指定）。
