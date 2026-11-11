# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-11 19:49:21 |
| 运行耗时 | 277.0s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 102998 |
| 去重后节点 | 34661 |
| TCP 可达 | 3000 |
| 真实可用 | 195 |
| Verified 输出 | 14 |
| Global 输出 | 198 |
| All 输出 | 34661 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.5 |
| tcp | 89.6 |
| probe | 95.1 |
| real_test | 41.3 |
| china_check | 22.7 |
| write_verified | 0.0 |
| generate | 17.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61003 |
| vmess | 17388 |
| trojan | 11821 |
| shadowsocks | 10462 |
| hysteria2 | 1746 |
| http | 297 |
| shadowsocksr | 151 |
| socks | 60 |
| hysteria | 34 |
| tuic | 21 |
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
| 93.93 | shadowsocks | 242.5 | 2.6 | 22.16 | 14.9 | 7.97 | 13.86 | 19.54 | dragon | 172.111.38.72 |
| 93.6 | trojan | 313.7 | 6.9 | 20.52 | 14.74 | 10.0 | 12.09 | 19.54 | dragon | 169.197.140.245 |
| 92.48 | trojan | 377.6 | 5.1 | 19.04 | 14.81 | 10.0 | 12.09 | 19.54 | dragon | 69.164.240.85 |
| 91.9 | shadowsocks | 325.7 | 2.0 | 20.24 | 14.92 | 7.84 | 13.86 | 19.54 | dragon | 149.40.57.134 |
| 91.39 | shadowsocks | 335.0 | 5.2 | 20.02 | 14.81 | 7.66 | 13.86 | 19.54 | dragon | 38.128.66.32 |
| 91.29 | trojan | 321.8 | 1.1 | 20.33 | 14.96 | 7.58 | 12.09 | 19.54 | dragon | 169.197.140.218 |
| 90.97 | trojan | 311.1 | 2.4 | 20.58 | 14.91 | 9.45 | 12.09 | 19.54 | dragon | 66.23.203.21 |
| 90.26 | trojan | 314.4 | 11.2 | 20.5 | 14.58 | 7.79 | 12.09 | 19.54 | dragon | 169.197.140.224 |
| 90.25 | shadowsocks | 305.3 | 10.8 | 20.71 | 14.6 | 7.65 | 13.86 | 19.54 | dragon | 38.91.107.188 |
| 89.86 | shadowsocks | 313.1 | 59.4 | 20.53 | 12.77 | 7.66 | 13.86 | 19.54 | dragon | 67.220.73.178 |
| 89.86 | trojan | 321.3 | 7.2 | 20.34 | 14.73 | 7.56 | 12.09 | 19.54 | dragon | 169.197.140.169 |
| 88.41 | shadowsocks | 400.9 | 0.4 | 18.5 | 14.98 | 7.61 | 13.86 | 19.54 | dragon | 167.17.67.171 |
| 88.39 | shadowsocks | 360.9 | 0.5 | 19.42 | 14.98 | 7.59 | 13.86 | 19.54 | dragon | 167.88.62.56 |
| 87.89 | trojan | 377.1 | 1.1 | 19.05 | 14.96 | 10.0 | 12.09 | 19.54 | dragon | 66.163.112.147 |
| 87.54 | hysteria2 | 257.1 | 13.9 | 21.83 | 14.48 | 0.0 | 12.69 | 19.54 | dragon | 206.189.229.48 |
| 87.45 | shadowsocks | 453.2 | 0.9 | 17.29 | 14.97 | 7.02 | 13.86 | 19.54 | dragon | 169.197.140.247 |
| 87.27 | shadowsocks | 422.1 | 1.5 | 18.01 | 14.94 | 7.65 | 13.86 | 19.54 | dragon | 66.163.125.120 |
| 87.22 | shadowsocks | 355.4 | 1.6 | 19.55 | 14.94 | 7.01 | 13.86 | 19.54 | dragon | 172.111.36.123 |
| 87.03 | shadowsocks | 243.0 | 0.3 | 22.15 | 14.99 | 0.99 | 13.86 | 19.54 | dragon | 193.151.163.18 |
| 86.98 | shadowsocks | 233.1 | 7.7 | 22.38 | 14.71 | 0.99 | 13.86 | 19.54 | dragon | 45.86.51.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.899 | 0.822 | 197 | 10000 | prefer |
| dragon2 | 0.811 | 0.75 | 24 | 10000 | prefer |
| dragon3 | 0.471 | 0.778 | 9 | 100 | observe |
| mheidari-all | 0.465 | 0.714 | 7 | 14491 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8393 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4981 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2629 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11151 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6306 | observe |
| barry-far-vless | 0.255 | None | 0 | 6516 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4589 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 16 |
| test_one_timeout | 15.0s | - | 15 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 9 | 14 | - |
| global | False | 250 | 198 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
