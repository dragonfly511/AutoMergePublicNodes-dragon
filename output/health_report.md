# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-24 00:10:28 |
| 运行耗时 | 304.6s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 100323 |
| 去重后节点 | 35158 |
| TCP 可达 | 3000 |
| 真实可用 | 265 |
| Verified 输出 | 11 |
| Global 输出 | 269 |
| All 输出 | 35158 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.9 |
| tcp | 100.5 |
| probe | 94.8 |
| real_test | 46.6 |
| china_check | 33.0 |
| write_verified | 0.0 |
| generate | 18.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58770 |
| vmess | 19443 |
| shadowsocks | 10828 |
| trojan | 9005 |
| hysteria2 | 1820 |
| shadowsocksr | 149 |
| http | 121 |
| socks | 109 |
| anytls | 32 |
| hysteria | 32 |
| tuic | 14 |

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
| 92.16 | shadowsocks | 275.3 | 2.5 | 21.41 | 14.91 | 10.0 | 14.11 | 19.34 | dragon | 173.244.56.9 |
| 92.09 | shadowsocks | 326.8 | 1.2 | 20.21 | 14.95 | 7.98 | 14.11 | 19.34 | dragon | 216.106.178.169 |
| 91.87 | shadowsocks | 268.8 | 0.6 | 21.55 | 14.98 | 6.39 | 14.11 | 19.34 | dragon | 137.184.89.151 |
| 88.04 | hysteria2 | 243.5 | 3.4 | 22.14 | 14.87 | 0.0 | 12.69 | 19.34 | dragon | 66.94.121.46 |
| 87.96 | shadowsocks | 308.6 | 4.3 | 20.64 | 14.84 | 5.92 | 14.11 | 19.34 | dragon | 23.150.152.38 |
| 87.73 | shadowsocks | 345.1 | 0.5 | 19.79 | 14.98 | 8.22 | 14.11 | 19.34 | dragon | 15.204.246.111 |
| 87.06 | shadowsocks | 319.4 | 3.6 | 20.38 | 14.87 | 5.84 | 14.11 | 19.34 | dragon | 37.19.198.243 |
| 86.29 | shadowsocks | 280.6 | 1.1 | 21.28 | 14.96 | 6.01 | 14.11 | 19.34 | dragon | 156.146.38.168 |
| 86.24 | shadowsocks | 274.3 | 18.3 | 21.43 | 14.31 | 5.23 | 14.11 | 19.34 | dragon | 169.197.142.68 |
| 86.14 | shadowsocks | 341.1 | 6.1 | 19.88 | 14.77 | 5.8 | 14.11 | 19.34 | dragon | 185.230.230.18 |
| 85.93 | shadowsocks | 339.2 | 7.8 | 19.93 | 14.71 | 5.8 | 14.11 | 19.34 | dragon | 45.86.51.18 |
| 85.73 | shadowsocks | 328.4 | 5.6 | 20.18 | 14.79 | 5.18 | 14.11 | 19.34 | dragon | 37.19.198.236 |
| 85.64 | shadowsocks | 257.6 | 3.1 | 21.81 | 14.88 | 0.0 | 14.11 | 19.34 | dragon | 104.238.140.45 |
| 85.37 | shadowsocks | 384.2 | 17.8 | 18.88 | 14.33 | 5.83 | 14.11 | 19.34 | dragon | 37.19.198.160 |
| 85.22 | shadowsocks | 393.2 | 1.6 | 18.68 | 14.94 | 9.64 | 14.11 | 19.34 | dragon | 149.22.87.204 |
| 84.74 | shadowsocks | 368.7 | 1.1 | 19.24 | 14.96 | 5.8 | 14.11 | 19.34 | dragon | 193.151.160.18 |
| 84.72 | shadowsocks | 360.3 | 9.7 | 19.44 | 14.63 | 5.88 | 14.11 | 19.34 | dragon | 38.22.17.219 |
| 84.59 | shadowsocks | 375.4 | 1.9 | 19.09 | 14.93 | 5.8 | 14.11 | 19.34 | dragon | 193.151.160.9 |
| 84.11 | shadowsocks | 384.2 | 10.2 | 18.88 | 14.62 | 5.81 | 14.11 | 19.34 | dragon | 193.151.163.18 |
| 84.08 | shadowsocks | 508.7 | 14.8 | 16.0 | 14.45 | 8.22 | 14.11 | 19.34 | dragon | 15.204.247.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.943 | 265 | 10000 | prefer |
| Surfboard-tg-mixed | 0.446 | 0.8 | 5 | 8626 | observe |
| mheidari-all | 0.446 | 0.8 | 5 | 15543 | observe |
| dragon2 | 0.421 | 0.667 | 6 | 10000 | observe |
| SoliSpirit-all | 0.349 | 0.667 | 3 | 11809 | observe |
| ermaozi-get_subscribe | 0.324 | 1.0 | 2 | 330 | observe |
| dragon3 | 0.296 | 0.444 | 9 | 100 | observe |
| ermaozi | 0.272 | 1.0 | 1 | 420 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 88 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5064 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5667 | observe |
| barry-far-vless | 0.255 | None | 0 | 5847 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4514 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| geo | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| 204 | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 16 | 11 | - |
| global | False | 227 | 269 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
