# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-24 22:42:15 |
| 运行耗时 | 269.3s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 98281 |
| 去重后节点 | 33853 |
| TCP 可达 | 3000 |
| 真实可用 | 68 |
| Verified 输出 | 18 |
| Global 输出 | 269 |
| All 输出 | 33853 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.6 |
| tcp | 88.1 |
| probe | 99.2 |
| real_test | 35.9 |
| china_check | 17.9 |
| generate | 17.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57448 |
| vmess | 19607 |
| shadowsocks | 10416 |
| trojan | 8406 |
| hysteria2 | 1952 |
| shadowsocksr | 172 |
| http | 105 |
| socks | 90 |
| anytls | 46 |
| hysteria | 23 |
| tuic | 16 |

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
| 85.43 | vless | 364.7 | 4.7 | 19.33 | 14.82 | 6.28 | 12.0 | 14.0 | dragon | 185.95.231.156 |
| 85.08 | shadowsocks | 228.4 | 4.6 | 22.49 | 14.83 | 7.76 | 10.0 | 14.0 | dragon | 37.19.198.244 |
| 85.0 | shadowsocks | 237.7 | 1.1 | 22.28 | 14.96 | 7.76 | 10.0 | 14.0 | dragon | 37.19.198.243 |
| 84.79 | shadowsocks | 238.8 | 6.0 | 22.25 | 14.78 | 7.76 | 10.0 | 14.0 | dragon | 37.19.198.160 |
| 84.47 | shadowsocks | 237.7 | 0.8 | 22.28 | 14.97 | 7.72 | 10.0 | 14.0 | dragon | 185.230.230.18 |
| 84.45 | shadowsocks | 232.7 | 5.3 | 22.39 | 14.8 | 7.76 | 10.0 | 14.0 | dragon | 45.86.51.18 |
| 84.16 | shadowsocks | 251.6 | 0.5 | 21.95 | 14.98 | 7.73 | 10.0 | 14.0 | dragon | 193.151.163.18 |
| 84.09 | shadowsocks | 282.3 | 5.9 | 21.24 | 14.78 | 8.07 | 10.0 | 14.0 | dragon | 37.19.198.236 |
| 83.17 | shadowsocks | 230.8 | 5.2 | 22.44 | 14.81 | 8.42 | 10.0 | 14.0 | dragon | 172.111.38.72 |
| 82.95 | shadowsocks | 316.0 | 4.4 | 20.46 | 14.84 | 8.15 | 10.0 | 14.0 | dragon | 38.91.100.39 |
| 82.32 | shadowsocks | 343.7 | 2.1 | 19.82 | 14.92 | 8.08 | 10.0 | 14.0 | dragon | 149.40.57.133 |
| 82.01 | shadowsocks | 255.9 | 6.8 | 21.86 | 14.75 | 7.73 | 10.0 | 14.0 | dragon | 149.40.57.138 |
| 80.32 | shadowsocks | 392.5 | 14.2 | 18.69 | 14.47 | 8.22 | 10.0 | 14.0 | dragon | 51.222.141.125 |
| 80.18 | vless | 411.3 | 1.3 | 18.26 | 14.95 | 5.47 | 12.0 | 14.0 | dragon | 45.138.100.248 |
| 77.87 | shadowsocks | 324.7 | 2.0 | 20.26 | 14.92 | 8.55 | 10.0 | 14.0 | dragon | 173.244.56.9 |
| 77.15 | shadowsocks | 336.3 | 0.3 | 19.99 | 14.99 | 7.67 | 10.0 | 14.0 | dragon | 149.40.57.134 |
| 76.74 | hysteria2 | 333.4 | 1.6 | 20.06 | 14.94 | 3.53 | 12.5 | 14.0 | dragon | 8.209.247.109 |
| 76.31 | shadowsocks | 399.2 | 0.7 | 18.54 | 14.98 | 7.77 | 10.0 | 14.0 | dragon | 167.88.63.99 |
| 76.13 | shadowsocks | 408.6 | 2.0 | 18.32 | 14.92 | 7.81 | 10.0 | 14.0 | dragon | 38.22.17.219 |
| 75.88 | hysteria2 | 525.7 | 1.0 | 15.61 | 14.96 | 5.73 | 12.5 | 14.0 | dragon | 185.156.44.99 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.858 | 0.786 | 70 | 10000 | prefer |
| Surfboard-tg-mixed | 0.421 | 0.667 | 6 | 8239 | observe |
| mheidari-all | 0.391 | 1.0 | 2 | 14970 | observe |
| dragon3 | 0.389 | 0.714 | 7 | 100 | observe |
| ermaozi | 0.27 | 1.0 | 1 | 366 | observe |
| dragon2 | 0.259 | 0.333 | 3 | 9953 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11536 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5468 | observe |
| barry-far-vless | 0.255 | None | 0 | 5508 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4546 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ermaozi-get_subscribe | 0.253 | 0.5 | 4 | 322 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 18 | 7 | 0.5 |
| global | True | 269 | 68 | 0.5 |

---

此文件由 `core.report.write_health_report()` 自动生成。
