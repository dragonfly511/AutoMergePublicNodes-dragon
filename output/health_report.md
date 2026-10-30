# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 02:50:16 |
| 运行耗时 | 286.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 109194 |
| 去重后节点 | 35032 |
| TCP 可达 | 3000 |
| 真实可用 | 230 |
| Verified 输出 | 39 |
| Global 输出 | 231 |
| All 输出 | 35032 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| geo | 1.5 |
| tcp | 104.0 |
| probe | 92.5 |
| real_test | 45.5 |
| china_check | 18.8 |
| write_verified | 0.0 |
| generate | 16.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 67630 |
| vmess | 15128 |
| trojan | 12484 |
| shadowsocks | 11310 |
| hysteria2 | 2242 |
| shadowsocksr | 165 |
| http | 143 |
| socks | 50 |
| tuic | 16 |
| anytls | 15 |
| hysteria | 11 |

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
| 96.28 | shadowsocks | 224.6 | 1.1 | 22.58 | 14.96 | 8.82 | 13.92 | 20.0 | dragon | 173.244.56.6 |
| 95.71 | shadowsocks | 227.2 | 14.3 | 22.52 | 14.46 | 8.81 | 13.92 | 20.0 | dragon | 173.244.56.9 |
| 95.62 | shadowsocks | 251.6 | 0.4 | 21.95 | 14.99 | 8.76 | 13.92 | 20.0 | dragon | 156.146.38.170 |
| 95.41 | shadowsocks | 257.2 | 1.3 | 21.82 | 14.95 | 8.73 | 13.92 | 20.0 | dragon | 156.146.38.169 |
| 95.29 | shadowsocks | 260.1 | 3.2 | 21.76 | 14.88 | 8.73 | 13.92 | 20.0 | dragon | 156.146.38.167 |
| 94.38 | trojan | 274.7 | 13.4 | 21.42 | 14.5 | 10.0 | 13.26 | 20.0 | dragon | 216.106.186.32 |
| 93.24 | shadowsocks | 336.2 | 1.4 | 20.0 | 14.95 | 8.87 | 13.92 | 20.0 | dragon | 95.215.201.18 |
| 91.17 | trojan | 282.4 | 2.3 | 21.24 | 14.91 | 8.69 | 13.26 | 20.0 | dragon | 216.106.186.33 |
| 90.47 | shadowsocks | 265.9 | 2.7 | 21.62 | 14.9 | 8.73 | 13.92 | 20.0 | dragon | 156.146.38.168 |
| 89.2 | hysteria2 | 274.6 | 11.6 | 21.42 | 14.57 | 0.0 | 14.21 | 20.0 | dragon | 66.94.121.46 |
| 89.14 | trojan | 486.1 | 16.3 | 16.53 | 14.39 | 10.0 | 13.26 | 20.0 | dragon | 66.23.203.21 |
| 88.78 | trojan | 278.5 | 0.3 | 21.33 | 14.99 | 8.72 | 13.26 | 20.0 | dragon | 66.163.114.45 |
| 88.78 | shadowsocks | 343.0 | 1.1 | 19.84 | 14.96 | 8.66 | 13.92 | 20.0 | dragon | 193.151.160.18 |
| 88.41 | shadowsocks | 348.7 | 0.7 | 19.71 | 14.97 | 8.57 | 13.92 | 20.0 | dragon | 37.19.198.160 |
| 88.23 | trojan | 282.2 | 1.0 | 21.24 | 14.96 | 7.85 | 13.26 | 20.0 | dragon | 66.163.114.126 |
| 88.17 | shadowsocks | 395.6 | 2.3 | 18.62 | 14.91 | 8.66 | 13.92 | 20.0 | dragon | 185.215.132.9 |
| 87.89 | shadowsocks | 356.2 | 0.9 | 19.53 | 14.97 | 8.5 | 13.92 | 20.0 | dragon | 37.19.198.244 |
| 87.6 | shadowsocks | 358.0 | 17.9 | 19.49 | 14.33 | 8.62 | 13.92 | 20.0 | dragon | 185.230.230.18 |
| 86.97 | trojan | 338.2 | 1.8 | 19.95 | 14.93 | 10.0 | 13.26 | 20.0 | dragon | 216.238.80.100 |
| 86.69 | shadowsocks | 369.2 | 4.7 | 19.23 | 14.82 | 8.51 | 13.92 | 20.0 | dragon | 193.151.163.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.955 | 200 | 10000 | prefer |
| Au1rxx-base64 | 0.874 | 0.824 | 34 | 1709 | prefer |
| mheidari-all | 0.586 | 0.8 | 10 | 33573 | observe |
| Surfboard-tg-mixed | 0.287 | 0.5 | 2 | 7756 | observe |
| tg-Farah_VPN | 0.263 | 1.0 | 1 | 200 | observe |
| xiaoji235-airport-v2ray-all | 0.259 | 0.333 | 3 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2709 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10432 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5941 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1709 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 11 |
| 204 | ProxyError | - | 3 |
| geo | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 49 | 39 | - |
| global | False | 235 | 231 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
