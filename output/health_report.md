# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-13 19:57:49 |
| 运行耗时 | 264.7s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 103409 |
| 去重后节点 | 34464 |
| TCP 可达 | 3000 |
| 真实可用 | 245 |
| Verified 输出 | 15 |
| Global 输出 | 246 |
| All 输出 | 34464 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 91.1 |
| probe | 84.3 |
| real_test | 39.6 |
| china_check | 26.6 |
| write_verified | 0.0 |
| generate | 14.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60397 |
| vmess | 17946 |
| trojan | 11826 |
| shadowsocks | 10970 |
| hysteria2 | 1734 |
| http | 253 |
| shadowsocksr | 149 |
| socks | 62 |
| hysteria | 34 |
| tuic | 22 |
| anytls | 16 |

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
| 90.33 | shadowsocks | 328.5 | 2.1 | 20.17 | 14.92 | 7.17 | 13.73 | 19.52 | dragon | 149.40.57.135 |
| 89.6 | shadowsocks | 256.8 | 4.4 | 21.83 | 14.84 | 4.18 | 13.73 | 19.52 | dragon | 172.111.38.72 |
| 89.21 | shadowsocks | 298.0 | 1.9 | 20.88 | 14.93 | 6.78 | 13.73 | 19.52 | dragon | 66.163.125.120 |
| 88.96 | shadowsocks | 401.1 | 2.5 | 18.49 | 14.91 | 6.9 | 13.73 | 19.52 | dragon | 38.91.107.57 |
| 88.37 | shadowsocks | 249.6 | 0.5 | 22.0 | 14.98 | 2.64 | 13.73 | 19.52 | dragon | 38.91.100.39 |
| 88.29 | shadowsocks | 247.7 | 0.3 | 22.04 | 14.99 | 2.51 | 13.73 | 19.52 | dragon | 149.40.57.138 |
| 88.22 | shadowsocks | 359.0 | 11.0 | 19.47 | 14.59 | 7.05 | 13.73 | 19.52 | dragon | 167.88.62.56 |
| 87.33 | hysteria2 | 253.7 | 2.6 | 21.91 | 14.9 | 0.0 | 12.0 | 19.52 | dragon | 206.189.229.48 |
| 87.24 | shadowsocks | 344.0 | 0.5 | 19.81 | 14.98 | 6.77 | 13.73 | 19.52 | dragon | 38.64.138.135 |
| 87.07 | shadowsocks | 317.3 | 2.0 | 20.43 | 14.92 | 4.26 | 13.73 | 19.52 | dragon | 149.40.57.134 |
| 86.9 | shadowsocks | 241.3 | 12.1 | 22.19 | 14.54 | 1.42 | 13.73 | 19.52 | dragon | 185.230.230.18 |
| 86.5 | shadowsocks | 371.5 | 10.8 | 19.18 | 14.59 | 7.12 | 13.73 | 19.52 | dragon | 167.17.67.171 |
| 86.21 | shadowsocks | 268.9 | 6.1 | 21.55 | 14.77 | 1.14 | 13.73 | 19.52 | dragon | 193.151.163.18 |
| 86.16 | shadowsocks | 354.7 | 20.1 | 19.57 | 14.25 | 6.97 | 13.73 | 19.52 | dragon | 67.220.73.178 |
| 86.11 | shadowsocks | 343.6 | 0.8 | 19.82 | 14.97 | 2.57 | 13.73 | 19.52 | dragon | 38.128.66.32 |
| 86.05 | shadowsocks | 327.8 | 6.3 | 20.19 | 14.76 | 6.62 | 13.73 | 19.52 | dragon | 185.215.132.18 |
| 86.04 | shadowsocks | 387.8 | 2.3 | 18.8 | 14.91 | 4.59 | 13.73 | 19.52 | dragon | 15.204.247.206 |
| 85.98 | vless | 299.9 | 0.9 | 20.84 | 14.97 | 3.52 | 8.2 | 19.52 | dragon | 66.70.179.198 |
| 85.62 | shadowsocks | 296.1 | 1.5 | 20.92 | 14.94 | 1.01 | 13.73 | 19.52 | dragon | 193.151.160.18 |
| 85.52 | shadowsocks | 324.0 | 4.6 | 20.28 | 14.83 | 6.63 | 13.73 | 19.52 | dragon | 185.215.132.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.926 | 0.849 | 271 | 10000 | prefer |
| dragon2 | 0.48 | 1.0 | 4 | 10000 | observe |
| mheidari-all | 0.438 | 1.0 | 3 | 14267 | observe |
| dragon3 | 0.413 | 0.833 | 6 | 100 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 6752 | observe |
| tg-LonUp_M | 0.276 | 0.667 | 3 | 175 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4900 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11528 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8804 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6228 | observe |
| barry-far-vless | 0.255 | None | 0 | 6409 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4624 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 31 |
| 204 | ProxyError | - | 4 |
| speed | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 20 | 15 | - |
| global | False | 300 | 246 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
