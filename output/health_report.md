# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-27 08:53:52 |
| 运行耗时 | 251.4s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 98416 |
| 去重后节点 | 33308 |
| TCP 可达 | 3000 |
| 真实可用 | 129 |
| Verified 输出 | 15 |
| Global 输出 | 129 |
| All 输出 | 33308 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.6 |
| tcp | 86.8 |
| probe | 97.2 |
| real_test | 21.5 |
| china_check | 17.7 |
| write_verified | 0.0 |
| generate | 17.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56459 |
| vmess | 19906 |
| shadowsocks | 11133 |
| trojan | 8447 |
| hysteria2 | 1915 |
| http | 204 |
| shadowsocksr | 155 |
| socks | 116 |
| anytls | 46 |
| hysteria | 22 |
| tuic | 13 |

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
| 95.65 | shadowsocks | 250.0 | 2.4 | 21.99 | 14.91 | 9.91 | 13.3 | 19.54 | dragon | 37.19.198.236 |
| 95.58 | shadowsocks | 246.2 | 6.6 | 22.08 | 14.75 | 9.91 | 13.3 | 19.54 | dragon | 37.19.198.160 |
| 95.22 | shadowsocks | 243.9 | 6.7 | 22.13 | 14.75 | 10.0 | 13.3 | 19.54 | dragon | 185.230.230.18 |
| 94.91 | shadowsocks | 257.5 | 4.1 | 21.82 | 14.85 | 9.9 | 13.3 | 19.54 | dragon | 193.151.163.18 |
| 94.25 | shadowsocks | 251.5 | 7.0 | 21.96 | 14.74 | 9.91 | 13.3 | 19.54 | dragon | 37.19.198.243 |
| 94.11 | shadowsocks | 246.9 | 0.8 | 22.06 | 14.97 | 9.9 | 13.3 | 19.54 | dragon | 172.111.38.72 |
| 94.03 | shadowsocks | 301.7 | 12.0 | 20.79 | 14.55 | 9.85 | 13.3 | 19.54 | dragon | 198.98.53.130 |
| 93.36 | shadowsocks | 315.7 | 0.4 | 20.47 | 14.98 | 9.57 | 13.3 | 19.54 | dragon | 193.151.160.9 |
| 93.17 | shadowsocks | 330.0 | 4.4 | 20.14 | 14.83 | 9.86 | 13.3 | 19.54 | dragon | 149.40.57.134 |
| 93.1 | shadowsocks | 330.3 | 8.1 | 20.13 | 14.69 | 9.94 | 13.3 | 19.54 | dragon | 15.204.233.41 |
| 92.91 | shadowsocks | 300.0 | 2.2 | 20.83 | 14.92 | 9.57 | 13.3 | 19.54 | dragon | 193.151.160.18 |
| 92.88 | shadowsocks | 329.2 | 15.0 | 20.16 | 14.44 | 9.94 | 13.3 | 19.54 | dragon | 15.204.246.132 |
| 92.63 | shadowsocks | 334.8 | 14.0 | 20.03 | 14.47 | 9.79 | 13.3 | 19.54 | dragon | 38.128.66.32 |
| 92.55 | shadowsocks | 285.0 | 13.5 | 21.18 | 14.49 | 9.69 | 13.3 | 19.54 | dragon | 156.146.38.168 |
| 92.55 | shadowsocks | 352.7 | 5.1 | 19.61 | 14.81 | 9.79 | 13.3 | 19.54 | dragon | 149.40.57.133 |
| 91.83 | shadowsocks | 237.5 | 5.8 | 22.28 | 14.78 | 10.0 | 13.3 | 19.54 | dragon | 45.86.51.18 |
| 91.75 | shadowsocks | 391.6 | 6.3 | 18.71 | 14.76 | 9.94 | 13.3 | 19.54 | dragon | 15.204.246.108 |
| 91.05 | shadowsocks | 331.6 | 13.4 | 20.1 | 14.5 | 9.68 | 13.3 | 19.54 | dragon | 156.146.38.170 |
| 89.73 | shadowsocks | 384.0 | 0.8 | 18.89 | 14.97 | 9.79 | 13.3 | 19.54 | dragon | 38.91.107.188 |
| 89.15 | shadowsocks | 306.7 | 1.6 | 20.68 | 14.94 | 9.51 | 13.3 | 19.54 | dragon | 95.215.201.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.952 | 126 | 10000 | prefer |
| ermaozi | 0.67 | 1.0 | 11 | 422 | observe |
| Surfboard-tg-mixed | 0.446 | 0.8 | 5 | 8568 | observe |
| dragon3 | 0.413 | 0.833 | 6 | 100 | observe |
| tg-LonUp_M | 0.365 | 1.0 | 3 | 173 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 116 | observe |
| tg-proxy_mtm | 0.258 | 1.0 | 1 | 67 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4936 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11572 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5609 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4459 | observe |
| mheidari-all | 0.255 | None | 0 | 14315 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 5 |
| 204 | TimeoutError | - | 2 |
| 204 | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 17 | 15 | - |
| global | False | 256 | 129 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
