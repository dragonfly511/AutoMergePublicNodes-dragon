# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-13 07:03:01 |
| 运行耗时 | 289.1s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 102720 |
| 去重后节点 | 34275 |
| TCP 可达 | 3000 |
| 真实可用 | 315 |
| Verified 输出 | 20 |
| Global 输出 | 300 |
| All 输出 | 34275 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.6 |
| tcp | 88.0 |
| probe | 89.7 |
| real_test | 63.4 |
| china_check | 24.1 |
| write_verified | 0.0 |
| generate | 14.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59985 |
| vmess | 18006 |
| trojan | 11730 |
| shadowsocks | 10715 |
| hysteria2 | 1719 |
| http | 284 |
| shadowsocksr | 153 |
| socks | 55 |
| hysteria | 35 |
| tuic | 23 |
| anytls | 15 |

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
| 89.29 | shadowsocks | 264.4 | 0.7 | 21.66 | 14.97 | 7.74 | 13.58 | 15.84 | dragon | 38.91.107.57 |
| 88.26 | shadowsocks | 279.7 | 0.2 | 21.3 | 14.99 | 7.75 | 13.58 | 15.84 | dragon | 67.220.73.178 |
| 88.23 | shadowsocks | 278.0 | 0.4 | 21.34 | 14.99 | 7.69 | 13.58 | 15.84 | dragon | 185.215.132.9 |
| 88.22 | shadowsocks | 273.9 | 3.2 | 21.44 | 14.88 | 7.65 | 13.58 | 15.84 | dragon | 185.215.132.18 |
| 87.85 | shadowsocks | 340.4 | 1.3 | 19.9 | 14.95 | 8.08 | 13.58 | 15.84 | dragon | 167.17.67.171 |
| 87.46 | shadowsocks | 340.2 | 6.2 | 19.9 | 14.77 | 7.87 | 13.58 | 15.84 | dragon | 38.91.107.19 |
| 86.6 | shadowsocks | 380.2 | 1.1 | 18.98 | 14.96 | 7.74 | 13.58 | 15.84 | dragon | 66.163.125.120 |
| 85.84 | shadowsocks | 361.6 | 3.2 | 19.41 | 14.88 | 6.63 | 13.58 | 15.84 | dragon | 167.88.63.39 |
| 85.1 | shadowsocks | 258.2 | 0.2 | 21.8 | 14.99 | 2.89 | 13.58 | 15.84 | dragon | 156.146.38.168 |
| 85.02 | shadowsocks | 272.1 | 4.1 | 21.48 | 14.84 | 3.78 | 13.58 | 15.84 | dragon | 172.111.38.72 |
| 85.01 | shadowsocks | 281.7 | 1.8 | 21.26 | 14.93 | 7.62 | 13.58 | 15.84 | dragon | 38.22.17.139 |
| 84.85 | shadowsocks | 308.5 | 1.0 | 20.64 | 14.96 | 4.33 | 13.58 | 15.84 | dragon | 149.40.57.134 |
| 84.38 | shadowsocks | 252.7 | 3.1 | 21.93 | 14.89 | 2.64 | 13.58 | 15.84 | dragon | 167.88.62.203 |
| 83.83 | shadowsocks | 298.1 | 2.1 | 20.88 | 14.92 | 3.11 | 13.58 | 15.84 | dragon | 38.22.17.129 |
| 83.76 | shadowsocks | 281.3 | 0.2 | 21.27 | 14.99 | 2.65 | 13.58 | 15.84 | dragon | 38.121.43.225 |
| 83.5 | shadowsocks | 362.2 | 3.6 | 19.39 | 14.87 | 8.02 | 13.58 | 15.84 | dragon | 38.64.138.135 |
| 83.13 | hysteria2 | 359.0 | 0.5 | 19.47 | 14.98 | 7.54 | 12.0 | 15.84 | dragon | 62.210.124.146 |
| 83.09 | shadowsocks | 321.0 | 0.7 | 20.35 | 14.97 | 2.35 | 13.58 | 15.84 | dragon | 156.146.38.167 |
| 83.09 | shadowsocks | 367.3 | 0.9 | 19.28 | 14.97 | 3.92 | 13.58 | 15.84 | dragon | 38.22.17.214 |
| 82.99 | shadowsocks | 308.2 | 0.8 | 20.64 | 14.97 | 2.46 | 13.58 | 15.84 | dragon | 149.40.57.138 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.976 | 0.899 | 248 | 10000 | prefer |
| dragon2 | 0.615 | 0.535 | 157 | 10000 | observe |
| mheidari-all | 0.446 | 0.8 | 5 | 13793 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8675 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4998 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2737 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11327 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6119 | observe |
| barry-far-vless | 0.255 | None | 0 | 6543 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4624 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 44 |
| speed | ClientOSError | - | 28 |
| 204 | ProxyError | - | 9 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | TimeoutError | - | 4 |
| geo | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 14 | 20 | - |
| global | False | 229 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
