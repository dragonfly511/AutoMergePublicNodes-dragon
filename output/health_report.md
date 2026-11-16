# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-16 06:55:49 |
| 运行耗时 | 293.1s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 103090 |
| 去重后节点 | 34686 |
| TCP 可达 | 3000 |
| 真实可用 | 228 |
| Verified 输出 | 12 |
| Global 输出 | 229 |
| All 输出 | 34686 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.7 |
| tcp | 97.3 |
| probe | 100.2 |
| real_test | 35.7 |
| china_check | 30.7 |
| write_verified | 0.0 |
| generate | 18.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60049 |
| vmess | 17895 |
| trojan | 11712 |
| shadowsocks | 11229 |
| hysteria2 | 1791 |
| shadowsocksr | 153 |
| http | 114 |
| socks | 64 |
| hysteria | 36 |
| anytls | 26 |
| tuic | 21 |

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
| 90.16 | hysteria2 | 235.3 | 0.9 | 22.33 | 14.96 | 4.72 | 14.21 | 14.94 | dragon | 192.255.152.147 |
| 87.04 | hysteria2 | 301.7 | 0.7 | 20.79 | 14.97 | 4.98 | 14.21 | 14.94 | dragon | 206.189.229.48 |
| 84.29 | shadowsocks | 257.0 | 0.1 | 21.83 | 15.0 | 4.33 | 12.19 | 14.94 | dragon | 156.146.38.169 |
| 84.15 | shadowsocks | 260.9 | 0.6 | 21.74 | 14.98 | 4.3 | 12.19 | 14.94 | dragon | 156.146.38.168 |
| 83.63 | hysteria2 | 277.7 | 18.1 | 21.35 | 14.32 | 5.35 | 14.21 | 14.94 | dragon | 66.94.121.46 |
| 82.65 | shadowsocks | 289.0 | 4.6 | 21.09 | 14.83 | 4.74 | 12.19 | 14.94 | dragon | 156.146.38.170 |
| 79.92 | shadowsocks | 308.3 | 0.5 | 20.64 | 14.98 | 4.56 | 12.19 | 14.94 | dragon | 185.215.132.18 |
| 79.32 | shadowsocks | 326.4 | 2.2 | 20.22 | 14.92 | 4.64 | 12.19 | 14.94 | dragon | 167.88.63.99 |
| 79.27 | shadowsocks | 221.3 | 1.4 | 22.66 | 14.95 | 0.0 | 12.19 | 14.94 | dragon | 38.145.220.193 |
| 78.81 | shadowsocks | 365.0 | 0.0 | 19.33 | 15.0 | 5.09 | 12.19 | 14.94 | dragon | 38.22.17.219 |
| 78.7 | hysteria2 | 401.3 | 5.5 | 18.49 | 14.79 | 4.75 | 14.21 | 14.94 | dragon | 34.24.25.1 |
| 78.48 | shadowsocks | 356.1 | 0.1 | 19.53 | 15.0 | 4.42 | 12.19 | 14.94 | dragon | 38.121.43.231 |
| 77.6 | shadowsocks | 381.1 | 0.4 | 18.96 | 14.99 | 5.08 | 12.19 | 14.94 | dragon | 38.121.43.225 |
| 77.41 | shadowsocks | 256.2 | 0.6 | 21.85 | 14.98 | 4.27 | 12.19 | 14.94 | dragon | 156.146.38.167 |
| 77.4 | shadowsocks | 339.9 | 0.5 | 19.91 | 14.98 | 3.6 | 12.19 | 14.94 | dragon | 193.151.160.18 |
| 77.02 | shadowsocks | 386.4 | 5.8 | 18.83 | 14.78 | 4.75 | 12.19 | 14.94 | dragon | 15.204.246.132 |
| 76.98 | shadowsocks | 269.6 | 1.8 | 21.54 | 14.93 | 2.82 | 12.19 | 14.94 | dragon | 95.215.201.18 |
| 76.82 | shadowsocks | 338.5 | 0.7 | 19.94 | 14.97 | 2.73 | 12.19 | 14.94 | dragon | 45.86.51.18 |
| 76.29 | shadowsocks | 416.8 | 5.6 | 18.13 | 14.79 | 4.6 | 12.19 | 14.94 | dragon | 38.91.107.188 |
| 76.15 | shadowsocks | 284.0 | 1.6 | 21.2 | 14.94 | 2.78 | 12.19 | 14.94 | dragon | 137.184.89.151 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.973 | 0.896 | 241 | 10000 | prefer |
| mheidari-all | 0.438 | 1.0 | 3 | 14209 | observe |
| mahdibland-V2RayAggregator | 0.391 | 1.0 | 2 | 4545 | observe |
| tg-LonUp_M | 0.365 | 1.0 | 3 | 164 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| dragon3 | 0.315 | 1.0 | 2 | 100 | observe |
| dragon2 | 0.287 | 0.5 | 2 | 10000 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4916 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2960 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11553 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6113 | observe |
| barry-far-vless | 0.255 | None | 0 | 6294 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 17 |
| 204 | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 12 | 12 | - |
| global | False | 122 | 229 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
