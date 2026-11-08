# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-08 22:22:23 |
| 运行耗时 | 305.0s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 101680 |
| 去重后节点 | 34166 |
| TCP 可达 | 3000 |
| 真实可用 | 324 |
| Verified 输出 | 27 |
| Global 输出 | 300 |
| All 输出 | 34166 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.6 |
| tcp | 93.2 |
| probe | 87.2 |
| real_test | 72.3 |
| china_check | 23.9 |
| write_verified | 0.0 |
| generate | 17.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59731 |
| vmess | 17304 |
| trojan | 12173 |
| shadowsocks | 10137 |
| hysteria2 | 1845 |
| http | 214 |
| shadowsocksr | 153 |
| socks | 58 |
| hysteria | 23 |
| tuic | 22 |
| anytls | 20 |

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
| 84.41 | shadowsocks | 259.6 | 4.1 | 21.77 | 14.85 | 5.26 | 13.45 | 16.08 | dragon | 156.146.38.168 |
| 82.67 | shadowsocks | 216.9 | 3.2 | 22.76 | 14.88 | 0.0 | 13.45 | 16.08 | dragon | 137.184.89.151 |
| 82.1 | shadowsocks | 245.9 | 0.3 | 22.08 | 14.99 | 0.0 | 13.45 | 16.08 | dragon | 167.88.62.203 |
| 82.1 | vless | 299.5 | 2.7 | 20.84 | 14.9 | 0.0 | 12.0 | 18.8 | dragon2 | 195.211.98.43 |
| 82.09 | shadowsocks | 246.9 | 0.1 | 22.06 | 15.0 | 0.0 | 13.45 | 16.08 | dragon | 167.17.67.171 |
| 82.03 | shadowsocks | 280.0 | 0.3 | 21.3 | 14.99 | 0.0 | 13.45 | 19.56 | dragon3 | 173.244.56.6 |
| 81.96 | shadowsocks | 273.4 | 2.6 | 21.45 | 14.9 | 0.0 | 13.45 | 19.56 | dragon3 | 173.244.56.9 |
| 81.54 | shadowsocks | 290.5 | 1.2 | 21.05 | 14.96 | 0.0 | 13.45 | 16.08 | dragon | 156.146.38.167 |
| 81.32 | shadowsocks | 259.9 | 0.9 | 21.76 | 14.97 | 0.0 | 13.45 | 16.08 | dragon | 38.145.220.193 |
| 81.29 | shadowsocks | 333.4 | 0.4 | 20.06 | 14.98 | 5.54 | 13.45 | 16.08 | dragon | 37.19.198.160 |
| 80.32 | shadowsocks | 303.5 | 1.1 | 20.75 | 14.96 | 0.0 | 13.45 | 18.8 | dragon2 | 185.215.132.18 |
| 80.24 | shadowsocks | 325.2 | 1.2 | 20.25 | 14.96 | 0.0 | 13.45 | 16.08 | dragon | 38.64.138.135 |
| 80.23 | shadowsocks | 259.5 | 1.0 | 21.77 | 14.96 | 0.0 | 13.45 | 16.08 | dragon | 67.220.73.178 |
| 79.81 | hysteria2 | 252.5 | 31.8 | 21.93 | 13.81 | 0.0 | 10.59 | 16.08 | dragon | 66.94.121.46 |
| 79.79 | shadowsocks | 261.7 | 2.2 | 21.72 | 14.92 | 0.0 | 13.45 | 18.8 | dragon2 | 156.146.38.169 |
| 79.56 | shadowsocks | 316.5 | 0.6 | 20.45 | 14.98 | 0.0 | 13.45 | 19.56 | dragon3 | 149.22.95.183 |
| 78.73 | vless | 433.7 | 3.2 | 17.74 | 14.88 | 0.0 | 12.0 | 18.8 | dragon2 | 159.89.87.21 |
| 78.15 | shadowsocks | 321.3 | 5.7 | 20.34 | 14.79 | 0.0 | 13.45 | 16.08 | dragon | 23.150.152.38 |
| 78.13 | shadowsocks | 274.7 | 2.4 | 21.42 | 14.91 | 0.0 | 13.45 | 16.08 | dragon | 95.215.201.18 |
| 77.5 | shadowsocks | 326.3 | 3.7 | 20.23 | 14.86 | 0.0 | 13.45 | 16.08 | dragon | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.953 | 128 | 10000 | prefer |
| dragon2 | 0.807 | 0.728 | 254 | 10000 | prefer |
| mheidari-all | 0.606 | 0.889 | 9 | 13955 | observe |
| dragon3 | 0.481 | 1.0 | 6 | 100 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| Surfboard-tg-mixed | 0.3 | 0.4 | 5 | 8189 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5035 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3024 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10983 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5913 | observe |
| barry-far-vless | 0.255 | None | 0 | 6123 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4597 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 50 |
| 204 | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 5 |
| cn-block | TimeoutError | - | 5 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 14 | 27 | - |
| global | False | 253 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
