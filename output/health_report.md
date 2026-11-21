# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-21 07:31:19 |
| 运行耗时 | 295.3s |
| 订阅源总数 | 110 |
| 健康订阅源 | 91 |
| 原始节点 | 102434 |
| 去重后节点 | 35244 |
| TCP 可达 | 3000 |
| 真实可用 | 134 |
| Verified 输出 | 8 |
| Global 输出 | 138 |
| All 输出 | 35244 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.6 |
| tcp | 94.4 |
| probe | 101.9 |
| real_test | 50.2 |
| china_check | 19.6 |
| write_verified | 0.0 |
| generate | 18.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59047 |
| vmess | 18210 |
| shadowsocks | 11785 |
| trojan | 11202 |
| hysteria2 | 1760 |
| shadowsocksr | 152 |
| http | 136 |
| socks | 90 |
| hysteria | 24 |
| tuic | 17 |
| anytls | 11 |

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
| 89.65 | shadowsocks | 300.4 | 0.1 | 20.82 | 15.0 | 9.4 | 13.24 | 17.98 | dragon | 185.215.132.18 |
| 88.51 | shadowsocks | 327.8 | 0.0 | 20.19 | 15.0 | 10.0 | 13.24 | 17.98 | dragon | 38.22.17.214 |
| 87.6 | hysteria2 | 263.3 | 3.1 | 21.68 | 14.88 | 0.0 | 14.06 | 17.98 | dragon | 206.189.229.48 |
| 85.86 | vless | 373.9 | 15.4 | 19.12 | 14.42 | 7.14 | 12.86 | 17.98 | dragon | 179.254.92.190 |
| 85.34 | trojan | 295.3 | 4.3 | 20.94 | 14.84 | 10.0 | 4.85 | 17.98 | dragon | 69.164.240.85 |
| 85.32 | shadowsocks | 343.1 | 2.3 | 19.84 | 14.91 | 3.85 | 13.24 | 17.98 | dragon | 167.88.62.203 |
| 83.21 | shadowsocks | 292.0 | 0.7 | 21.02 | 14.97 | 0.0 | 13.24 | 17.98 | dragon | 156.146.38.169 |
| 83.08 | trojan | 215.6 | 1.0 | 22.79 | 14.96 | 10.0 | 4.85 | 17.98 | dragon | 216.152.155.59 |
| 83.07 | shadowsocks | 275.0 | 1.7 | 21.41 | 14.94 | 0.0 | 13.24 | 17.98 | dragon | 193.151.163.18 |
| 82.93 | vless | 331.2 | 1.2 | 20.11 | 14.95 | 7.19 | 12.86 | 17.98 | dragon | 179.254.92.134 |
| 82.93 | shadowsocks | 389.4 | 0.7 | 18.76 | 14.97 | 7.13 | 13.24 | 17.98 | dragon | 38.121.43.18 |
| 82.85 | shadowsocks | 262.1 | 5.6 | 21.71 | 14.79 | 0.0 | 13.24 | 17.98 | dragon | 167.17.67.171 |
| 82.68 | shadowsocks | 271.9 | 0.5 | 21.48 | 14.98 | 0.0 | 13.24 | 17.98 | dragon | 37.19.198.244 |
| 82.62 | shadowsocks | 296.6 | 0.4 | 20.91 | 14.99 | 0.0 | 13.24 | 17.98 | dragon | 216.106.178.169 |
| 82.34 | shadowsocks | 308.0 | 0.9 | 20.65 | 14.97 | 0.0 | 13.24 | 17.98 | dragon | 167.88.62.56 |
| 82.3 | shadowsocks | 383.9 | 4.7 | 18.89 | 14.82 | 5.3 | 13.24 | 17.98 | dragon | 38.121.43.225 |
| 82.29 | shadowsocks | 309.1 | 0.4 | 20.62 | 14.99 | 0.0 | 13.24 | 17.94 | dragon3 | 38.64.138.135 |
| 82.08 | shadowsocks | 316.6 | 2.5 | 20.45 | 14.91 | 0.0 | 13.24 | 17.98 | dragon | 45.86.51.18 |
| 81.89 | shadowsocks | 322.6 | 3.8 | 20.31 | 14.86 | 0.0 | 13.24 | 17.98 | dragon | 185.230.230.18 |
| 81.65 | shadowsocks | 293.8 | 1.4 | 20.98 | 14.95 | 0.0 | 13.24 | 17.98 | dragon | 38.128.66.32 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.809 | 0.732 | 168 | 10000 | prefer |
| Surfboard-tg-mixed | 0.643 | 0.9 | 10 | 8565 | observe |
| mheidari-all | 0.4 | 0.75 | 4 | 14439 | observe |
| dragon3 | 0.37 | 0.8 | 5 | 100 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5045 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11789 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5496 | observe |
| barry-far-vless | 0.255 | None | 0 | 5914 | observe |
| dragon2 | 0.255 | None | 0 | 10000 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4482 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 42 |
| cn-block | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 11 | 8 | - |
| global | False | 185 | 138 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
