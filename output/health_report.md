# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-17 21:11:18 |
| 运行耗时 | 273.8s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 102368 |
| 去重后节点 | 35031 |
| TCP 可达 | 3000 |
| 真实可用 | 214 |
| Verified 输出 | 19 |
| Global 输出 | 215 |
| All 输出 | 35031 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.6 |
| tcp | 91.9 |
| probe | 95.1 |
| real_test | 38.9 |
| china_check | 19.0 |
| write_verified | 0.0 |
| generate | 18.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59923 |
| vmess | 18042 |
| trojan | 11238 |
| shadowsocks | 10962 |
| hysteria2 | 1709 |
| http | 194 |
| shadowsocksr | 179 |
| socks | 72 |
| hysteria | 19 |
| tuic | 18 |
| anytls | 12 |

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
| 94.08 | shadowsocks | 208.2 | 12.9 | 22.96 | 14.52 | 8.88 | 13.9 | 18.32 | dragon | 23.150.152.38 |
| 93.97 | shadowsocks | 216.2 | 2.9 | 22.77 | 14.89 | 8.59 | 13.9 | 18.32 | dragon | 137.184.89.151 |
| 93.69 | shadowsocks | 240.7 | 5.0 | 22.21 | 14.81 | 8.95 | 13.9 | 18.32 | dragon | 169.197.142.68 |
| 93.61 | shadowsocks | 229.6 | 7.9 | 22.46 | 14.7 | 8.73 | 13.9 | 18.32 | dragon | 95.215.201.18 |
| 90.87 | hysteria2 | 227.1 | 5.7 | 22.52 | 14.79 | 3.74 | 12.5 | 18.32 | dragon | 66.94.121.46 |
| 88.22 | shadowsocks | 189.7 | 1.7 | 23.39 | 14.94 | 1.77 | 13.9 | 18.32 | dragon | 38.145.220.193 |
| 86.15 | vless | 277.4 | 4.6 | 21.36 | 14.83 | 8.61 | 8.15 | 18.32 | dragon | 15.204.97.219 |
| 86.13 | vless | 288.7 | 1.2 | 21.1 | 14.96 | 8.6 | 8.15 | 18.32 | dragon | 15.204.97.209 |
| 86.08 | shadowsocks | 195.2 | 1.4 | 23.26 | 14.95 | 2.15 | 13.9 | 18.32 | dragon | 104.238.140.45 |
| 85.33 | shadowsocks | 354.6 | 5.9 | 19.57 | 14.78 | 8.49 | 13.9 | 18.32 | dragon | 167.88.62.203 |
| 85.21 | shadowsocks | 383.2 | 1.2 | 18.91 | 14.96 | 8.11 | 13.9 | 18.32 | dragon | 38.128.66.32 |
| 85.06 | shadowsocks | 428.3 | 14.9 | 17.86 | 14.44 | 8.35 | 13.9 | 18.32 | dragon | 156.146.38.168 |
| 84.73 | vless | 260.3 | 56.0 | 21.75 | 12.9 | 8.61 | 8.15 | 18.32 | dragon | 15.204.97.214 |
| 84.5 | shadowsocks | 342.7 | 9.8 | 19.85 | 14.63 | 8.32 | 13.9 | 18.32 | dragon | 156.146.38.169 |
| 84.41 | shadowsocks | 408.0 | 1.7 | 18.33 | 14.93 | 8.33 | 13.9 | 18.32 | dragon | 149.40.57.133 |
| 84.28 | shadowsocks | 379.0 | 0.2 | 19.01 | 14.99 | 7.95 | 13.9 | 18.32 | dragon | 185.230.230.18 |
| 84.21 | shadowsocks | 293.0 | 1.2 | 21.0 | 14.96 | 7.64 | 13.9 | 18.32 | dragon | 168.138.205.100 |
| 84.19 | vless | 372.4 | 1.1 | 19.16 | 14.96 | 8.6 | 8.15 | 18.32 | dragon | 15.204.97.195 |
| 84.08 | shadowsocks | 373.7 | 1.1 | 19.13 | 14.96 | 7.9 | 13.9 | 18.32 | dragon | 193.151.163.18 |
| 83.84 | shadowsocks | 428.2 | 1.1 | 17.87 | 14.96 | 8.23 | 13.9 | 18.32 | dragon | 149.40.57.134 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.992 | 0.916 | 203 | 10000 | prefer |
| dragon2 | 0.749 | 0.923 | 13 | 10000 | prefer |
| Surfboard-tg-mixed | 0.48 | 1.0 | 4 | 8416 | observe |
| tg-LonUp_M | 0.456 | 0.857 | 7 | 171 | observe |
| mheidari-all | 0.391 | 1.0 | 2 | 14572 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| dragon3 | 0.324 | 0.75 | 4 | 100 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4928 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2790 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11534 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5789 | observe |
| barry-far-vless | 0.255 | None | 0 | 6032 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4601 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| 204 | ProxyError | - | 2 |
| 204 | TimeoutError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 15 | 19 | - |
| global | False | 204 | 215 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
