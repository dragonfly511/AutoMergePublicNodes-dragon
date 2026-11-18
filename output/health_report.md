# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-18 20:48:14 |
| 运行耗时 | 284.3s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 102775 |
| 去重后节点 | 35212 |
| TCP 可达 | 3000 |
| 真实可用 | 153 |
| Verified 输出 | 13 |
| Global 输出 | 154 |
| All 输出 | 35212 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| geo | 1.6 |
| tcp | 90.9 |
| probe | 100.0 |
| real_test | 41.7 |
| china_check | 22.1 |
| write_verified | 0.0 |
| generate | 18.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59956 |
| vmess | 17946 |
| shadowsocks | 11506 |
| trojan | 11236 |
| hysteria2 | 1754 |
| shadowsocksr | 155 |
| http | 112 |
| socks | 69 |
| hysteria | 16 |
| anytls | 13 |
| tuic | 12 |

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
| 90.42 | shadowsocks | 235.3 | 2.6 | 22.33 | 14.9 | 5.14 | 13.19 | 19.36 | dragon | 172.111.38.72 |
| 90.18 | shadowsocks | 254.3 | 2.8 | 21.89 | 14.9 | 5.34 | 13.19 | 19.36 | dragon | 193.151.163.18 |
| 90.01 | shadowsocks | 238.7 | 11.1 | 22.25 | 14.59 | 5.12 | 13.19 | 19.36 | dragon | 45.86.51.18 |
| 89.96 | shadowsocks | 245.4 | 8.2 | 22.1 | 14.69 | 5.12 | 13.19 | 19.36 | dragon | 185.230.230.18 |
| 88.93 | shadowsocks | 376.7 | 1.1 | 19.06 | 14.96 | 6.86 | 13.19 | 19.36 | dragon | 67.220.73.178 |
| 88.89 | shadowsocks | 299.1 | 4.1 | 20.85 | 14.85 | 5.14 | 13.19 | 19.36 | dragon | 38.91.100.39 |
| 88.33 | shadowsocks | 310.4 | 4.7 | 20.59 | 14.82 | 8.06 | 13.19 | 19.36 | dragon | 185.215.132.9 |
| 88.3 | vless | 354.8 | 0.9 | 19.57 | 14.97 | 9.91 | 12.55 | 19.36 | dragon | 69.48.201.136 |
| 87.95 | shadowsocks | 400.7 | 8.3 | 18.5 | 14.69 | 6.71 | 13.19 | 19.36 | dragon | 15.204.247.244 |
| 87.93 | shadowsocks | 343.5 | 2.4 | 19.83 | 14.91 | 5.14 | 13.19 | 19.36 | dragon | 15.204.246.108 |
| 87.9 | shadowsocks | 337.8 | 3.6 | 19.96 | 14.87 | 5.02 | 13.19 | 19.36 | dragon | 38.64.138.135 |
| 87.4 | shadowsocks | 340.7 | 8.7 | 19.89 | 14.67 | 4.79 | 13.19 | 19.36 | dragon | 149.40.57.133 |
| 87.3 | shadowsocks | 331.3 | 16.4 | 20.11 | 14.39 | 5.06 | 13.19 | 19.36 | dragon | 38.91.107.57 |
| 87.13 | shadowsocks | 305.8 | 0.7 | 20.7 | 14.98 | 5.23 | 13.19 | 19.36 | dragon | 193.151.160.18 |
| 87.11 | shadowsocks | 356.2 | 2.7 | 19.53 | 14.9 | 5.03 | 13.19 | 19.36 | dragon | 158.51.121.221 |
| 87.04 | shadowsocks | 364.5 | 10.4 | 19.34 | 14.61 | 5.04 | 13.19 | 19.36 | dragon | 149.40.57.135 |
| 86.63 | shadowsocks | 319.7 | 2.2 | 20.38 | 14.92 | 5.17 | 13.19 | 19.36 | dragon | 169.197.140.247 |
| 86.61 | shadowsocks | 320.5 | 4.2 | 20.36 | 14.84 | 6.72 | 13.19 | 19.36 | dragon | 185.215.132.18 |
| 86.48 | shadowsocks | 318.8 | 7.9 | 20.4 | 14.7 | 5.06 | 13.19 | 19.36 | dragon | 193.151.160.9 |
| 86.39 | shadowsocks | 402.6 | 6.8 | 18.46 | 14.74 | 5.14 | 13.19 | 19.36 | dragon | 15.204.246.132 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.99 | 0.915 | 153 | 10000 | prefer |
| Surfboard-tg-mixed | 0.556 | 0.667 | 12 | 8521 | observe |
| dragon3 | 0.398 | 0.6 | 10 | 100 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4919 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2925 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11959 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5794 | observe |
| barry-far-vless | 0.255 | None | 0 | 5945 | observe |
| dragon2 | 0.255 | None | 0 | 10000 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4458 | observe |
| mheidari-all | 0.255 | None | 0 | 14408 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 15 |
| cn-block | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 27 | 13 | - |
| global | False | 207 | 154 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
