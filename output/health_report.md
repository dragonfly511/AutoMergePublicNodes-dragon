# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 22:17:29 |
| 运行耗时 | 280.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 92899 |
| 去重后节点 | 34033 |
| TCP 可达 | 3000 |
| 真实可用 | 111 |
| Verified 输出 | 38 |
| Global 输出 | 116 |
| All 输出 | 34033 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 1.6 |
| tcp | 89.8 |
| probe | 96.0 |
| real_test | 47.3 |
| china_check | 20.6 |
| generate | 16.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55008 |
| vmess | 13976 |
| trojan | 12839 |
| shadowsocks | 9063 |
| hysteria2 | 1533 |
| http | 205 |
| shadowsocksr | 156 |
| socks | 77 |
| anytls | 19 |
| tuic | 12 |
| hysteria | 11 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 86.38 | trojan | 282.0 | 1.8 | 21.25 | 14.93 | 10.0 | 9.2 | 15.5 | dragon | 66.163.114.114 |
| 85.75 | trojan | 274.7 | 2.2 | 21.42 | 14.92 | 10.0 | 9.2 | 15.5 | dragon | 38.102.234.153 |
| 82.85 | trojan | 320.0 | 2.6 | 20.37 | 14.9 | 10.0 | 9.2 | 15.5 | dragon | 170.101.101.211 |
| 82.09 | vless | 321.8 | 0.5 | 20.33 | 14.98 | 0.0 | 11.84 | 17.92 | Au1rxx-base64 | 195.123.240.65 |
| 79.86 | trojan | 319.1 | 14.0 | 20.39 | 14.47 | 10.0 | 9.2 | 15.5 | dragon | 170.101.101.53 |
| 79.48 | vless | 370.0 | 0.7 | 19.21 | 14.97 | 0.48 | 11.84 | 17.92 | Au1rxx-base64 | 167.17.69.171 |
| 79.11 | vless | 237.7 | 0.5 | 22.28 | 14.98 | 2.15 | 11.84 | 15.5 | dragon | 85.155.179.206 |
| 79.08 | vless | 378.5 | 1.0 | 19.02 | 14.96 | 0.0 | 11.84 | 17.92 | Au1rxx-base64 | 5.34.178.120 |
| 78.84 | trojan | 326.3 | 0.3 | 20.23 | 14.99 | 10.0 | 9.2 | 15.5 | dragon | 66.163.112.31 |
| 78.62 | trojan | 391.1 | 0.0 | 18.72 | 15.0 | 10.0 | 9.2 | 15.5 | dragon | 216.152.147.74 |
| 78.28 | vless | 326.6 | 3.2 | 20.22 | 14.88 | 0.0 | 11.84 | 15.5 | dragon | 195.123.235.183 |
| 77.68 | vless | 271.7 | 1.3 | 21.49 | 14.95 | 2.66 | 11.84 | 15.5 | dragon | 67.209.184.133 |
| 77.64 | vless | 332.5 | 3.4 | 20.08 | 14.87 | 0.0 | 11.84 | 17.92 | Au1rxx-base64 | ww13.levikogjgfdd.ir |
| 76.57 | vless | 374.6 | 1.7 | 19.11 | 14.94 | 0.0 | 11.84 | 17.92 | Au1rxx-base64 | 209.200.246.148 |
| 75.81 | vless | 532.8 | 2.6 | 15.45 | 14.9 | 0.46 | 11.84 | 17.92 | Au1rxx-base64 | 159.89.87.21 |
| 72.71 | hysteria2 | 517.1 | 1.9 | 15.81 | 14.93 | 0.0 | 12.0 | 17.92 | Au1rxx-base64 | 192.142.23.46 |
| 72.69 | vless | 461.3 | 0.7 | 17.1 | 14.98 | 0.08 | 11.84 | 17.92 | Au1rxx-base64 | 18.183.215.124 |
| 72.51 | vless | 304.0 | 1.1 | 20.74 | 14.96 | 0.63 | 11.84 | 15.5 | dragon | 208.84.100.209 |
| 71.99 | vless | 315.3 | 1.3 | 20.48 | 14.95 | 0.44 | 11.84 | 15.5 | dragon | 47.254.125.171 |
| 71.58 | vless | 531.9 | 1.0 | 15.46 | 14.96 | 0.0 | 11.84 | 17.92 | Au1rxx-base64 | xray1-direct-mci1-fs-ce.freesocks.work |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.825 | 0.755 | 49 | 10000 | prefer |
| Au1rxx-base64 | 0.781 | 0.716 | 81 | 1751 | prefer |
| Surfboard-tg-mixed | 0.568 | 0.875 | 8 | 8273 | observe |
| mheidari-all | 0.568 | 0.875 | 8 | 15206 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 3716 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10614 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 5986 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4800 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 23 |
| cn-block | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |
| speed | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 38 | 9 | 0.5 |
| global | False | 136 | 116 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
