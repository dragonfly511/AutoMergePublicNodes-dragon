# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 02:19:08 |
| 运行耗时 | 281.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 109310 |
| 去重后节点 | 35026 |
| TCP 可达 | 3000 |
| 真实可用 | 232 |
| Verified 输出 | 49 |
| Global 输出 | 235 |
| All 输出 | 35026 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.6 |
| tcp | 101.2 |
| probe | 88.1 |
| real_test | 43.6 |
| china_check | 24.1 |
| write_verified | 0.0 |
| generate | 15.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 67806 |
| vmess | 15115 |
| trojan | 12435 |
| shadowsocks | 11303 |
| hysteria2 | 2252 |
| shadowsocksr | 165 |
| http | 143 |
| socks | 49 |
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
| 95.85 | shadowsocks | 240.7 | 0.5 | 22.21 | 14.98 | 8.6 | 14.06 | 20.0 | dragon | 156.146.38.169 |
| 95.79 | shadowsocks | 245.6 | 1.0 | 22.09 | 14.96 | 8.68 | 14.06 | 20.0 | dragon | 156.146.38.168 |
| 94.47 | trojan | 378.4 | 1.4 | 19.02 | 14.95 | 10.0 | 13.5 | 20.0 | dragon | 66.23.203.21 |
| 94.22 | shadowsocks | 314.9 | 2.4 | 20.49 | 14.91 | 8.76 | 14.06 | 20.0 | dragon | 156.146.38.170 |
| 93.8 | shadowsocks | 301.2 | 8.4 | 20.8 | 14.69 | 8.54 | 14.06 | 20.0 | dragon | 37.19.198.160 |
| 93.04 | shadowsocks | 360.4 | 6.2 | 19.43 | 14.77 | 8.78 | 14.06 | 20.0 | dragon | 156.146.38.167 |
| 93.02 | shadowsocks | 302.0 | 3.2 | 20.79 | 14.88 | 8.54 | 14.06 | 20.0 | dragon | 37.19.198.244 |
| 91.85 | trojan | 265.4 | 0.5 | 21.64 | 14.98 | 9.28 | 13.5 | 20.0 | dragon | 66.163.114.45 |
| 91.55 | trojan | 321.6 | 0.4 | 20.33 | 14.98 | 9.84 | 13.5 | 20.0 | dragon | 216.106.186.32 |
| 90.99 | shadowsocks | 232.2 | 0.1 | 22.4 | 14.99 | 8.54 | 14.06 | 20.0 | dragon | 216.128.153.186 |
| 90.31 | trojan | 269.0 | 2.0 | 21.55 | 14.92 | 8.22 | 13.5 | 20.0 | dragon | 66.163.114.126 |
| 89.52 | shadowsocks | 403.8 | 3.2 | 18.43 | 14.88 | 8.54 | 14.06 | 20.0 | dragon | 185.230.230.18 |
| 89.35 | shadowsocks | 326.9 | 2.4 | 20.21 | 14.91 | 8.53 | 14.06 | 20.0 | dragon | 193.151.163.18 |
| 89.07 | shadowsocks | 368.6 | 3.0 | 19.24 | 14.89 | 8.53 | 14.06 | 20.0 | dragon | 15.204.233.41 |
| 88.9 | shadowsocks | 301.4 | 2.7 | 20.8 | 14.9 | 8.53 | 14.06 | 20.0 | dragon | 37.19.198.243 |
| 88.88 | shadowsocks | 319.3 | 21.4 | 20.39 | 14.2 | 8.86 | 14.06 | 20.0 | dragon | 173.244.56.6 |
| 88.72 | shadowsocks | 351.7 | 13.2 | 19.64 | 14.51 | 8.73 | 14.06 | 20.0 | dragon | 193.151.160.9 |
| 88.19 | shadowsocks | 336.8 | 21.1 | 19.98 | 14.21 | 8.88 | 14.06 | 20.0 | dragon | 173.244.56.9 |
| 88.17 | shadowsocks | 407.6 | 14.9 | 18.34 | 14.44 | 8.77 | 14.06 | 20.0 | dragon | 193.151.160.18 |
| 87.78 | hysteria2 | 305.5 | 16.0 | 20.71 | 14.4 | 0.0 | 14.17 | 20.0 | dragon | 129.213.91.185 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.927 | 193 | 10000 | prefer |
| ermaozi | 0.934 | 0.952 | 21 | 515 | prefer |
| Au1rxx-base64 | 0.735 | 0.679 | 28 | 1706 | prefer |
| mheidari-all | 0.57 | 0.727 | 11 | 33573 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 6752 | observe |
| Surfboard-tg-mixed | 0.352 | 0.5 | 6 | 7758 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2709 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10432 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5789 | observe |
| barry-far-vless | 0.255 | None | 0 | 6001 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1706 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 18 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 3 |
| geo | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 131 | 49 | - |
| global | False | 291 | 235 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
