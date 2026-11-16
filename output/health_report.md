# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-16 22:24:58 |
| 运行耗时 | 218.4s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 103358 |
| 去重后节点 | 35002 |
| TCP 可达 | 3000 |
| 真实可用 | 229 |
| Verified 输出 | 19 |
| Global 输出 | 230 |
| All 输出 | 35002 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 71.9 |
| probe | 76.4 |
| real_test | 31.9 |
| china_check | 19.9 |
| write_verified | 0.0 |
| generate | 11.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60508 |
| vmess | 17935 |
| trojan | 11617 |
| shadowsocks | 11109 |
| hysteria2 | 1753 |
| shadowsocksr | 156 |
| http | 118 |
| socks | 96 |
| hysteria | 32 |
| tuic | 20 |
| anytls | 14 |

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
| 95.8 | hysteria2 | 228.0 | 17.6 | 22.5 | 14.34 | 10.0 | 10.5 | 19.46 | dragon | 206.189.229.48 |
| 95.27 | shadowsocks | 228.1 | 0.3 | 22.5 | 14.99 | 8.81 | 14.01 | 19.46 | dragon | 185.230.230.18 |
| 95.11 | vless | 356.7 | 3.1 | 19.52 | 14.88 | 10.0 | 11.25 | 19.46 | dragon | 169.40.42.202 |
| 95.08 | shadowsocks | 234.4 | 1.5 | 22.35 | 14.95 | 8.81 | 14.01 | 19.46 | dragon | 45.86.51.18 |
| 94.97 | shadowsocks | 237.8 | 2.2 | 22.27 | 14.92 | 8.81 | 14.01 | 19.46 | dragon | 193.151.163.18 |
| 94.81 | shadowsocks | 278.5 | 10.4 | 21.33 | 14.61 | 9.9 | 14.01 | 19.46 | dragon | 15.204.247.124 |
| 94.41 | vless | 298.1 | 2.0 | 20.88 | 14.92 | 10.0 | 11.25 | 19.46 | dragon | 169.40.42.74 |
| 93.73 | hysteria2 | 336.9 | 3.1 | 19.98 | 14.88 | 9.91 | 10.5 | 19.46 | dragon | 34.24.25.1 |
| 93.58 | shadowsocks | 299.9 | 0.6 | 20.84 | 14.98 | 8.79 | 14.01 | 19.46 | dragon | 193.151.160.18 |
| 93.34 | shadowsocks | 311.0 | 3.0 | 20.58 | 14.89 | 9.9 | 14.01 | 19.46 | dragon | 15.204.246.107 |
| 92.66 | shadowsocks | 348.6 | 3.2 | 19.71 | 14.88 | 9.1 | 14.01 | 19.46 | dragon | 15.204.246.132 |
| 92.64 | shadowsocks | 357.9 | 1.5 | 19.49 | 14.94 | 9.24 | 14.01 | 19.46 | dragon | 15.204.246.108 |
| 92.61 | shadowsocks | 237.3 | 0.1 | 22.29 | 15.0 | 5.85 | 14.01 | 19.46 | dragon | 37.19.198.244 |
| 92.33 | shadowsocks | 252.0 | 0.4 | 21.94 | 14.98 | 9.43 | 14.01 | 19.46 | dragon | 15.204.247.206 |
| 92.22 | shadowsocks | 355.2 | 0.5 | 19.55 | 14.98 | 8.72 | 14.01 | 19.46 | dragon | 66.163.125.120 |
| 91.91 | shadowsocks | 318.8 | 0.2 | 20.4 | 14.99 | 8.95 | 14.01 | 19.46 | dragon | 156.146.38.168 |
| 91.75 | shadowsocks | 333.8 | 1.1 | 20.05 | 14.96 | 9.29 | 14.01 | 19.46 | dragon | 51.222.136.236 |
| 91.6 | vless | 292.2 | 3.2 | 21.01 | 14.88 | 10.0 | 11.25 | 19.46 | dragon | 136.176.65.251 |
| 91.47 | shadowsocks | 388.2 | 0.9 | 18.79 | 14.97 | 9.69 | 14.01 | 19.46 | dragon | 162.251.62.31 |
| 91.22 | shadowsocks | 285.4 | 2.4 | 21.17 | 14.91 | 9.66 | 14.01 | 19.46 | dragon | 185.215.132.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.995 | 0.918 | 232 | 10000 | prefer |
| mheidari-all | 0.557 | 1.0 | 6 | 14735 | observe |
| dragon3 | 0.404 | 1.0 | 4 | 100 | observe |
| dragon2 | 0.391 | 1.0 | 2 | 10000 | observe |
| Surfboard-tg-vless | 0.335 | 1.0 | 1 | 6010 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi | 0.333 | 1.0 | 2 | 548 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 170 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4964 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2915 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11743 | observe |
| barry-far-vless | 0.255 | None | 0 | 6209 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4545 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 14 |
| 204 | TimeoutError | - | 3 |
| 204 | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 12 | 19 | - |
| global | False | 229 | 230 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
