# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-08 13:46:13 |
| 运行耗时 | 275.1s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 101940 |
| 去重后节点 | 34837 |
| TCP 可达 | 3000 |
| 真实可用 | 252 |
| Verified 输出 | 14 |
| Global 输出 | 253 |
| All 输出 | 34837 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.5 |
| tcp | 87.2 |
| probe | 91.1 |
| real_test | 46.4 |
| china_check | 22.2 |
| write_verified | 0.0 |
| generate | 17.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59979 |
| vmess | 17084 |
| trojan | 12328 |
| shadowsocks | 10179 |
| hysteria2 | 1841 |
| http | 252 |
| shadowsocksr | 158 |
| socks | 59 |
| hysteria | 24 |
| anytls | 20 |
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
| 97.8 | trojan | 208.4 | 7.7 | 22.95 | 14.71 | 9.86 | 13.62 | 19.16 | dragon | 216.152.155.23 |
| 94.16 | trojan | 245.0 | 3.0 | 22.11 | 14.89 | 9.88 | 13.62 | 19.16 | dragon | 170.101.101.237 |
| 93.93 | shadowsocks | 251.1 | 8.0 | 21.96 | 14.7 | 8.86 | 13.93 | 18.48 | dragon3 | 156.146.38.167 |
| 93.81 | shadowsocks | 255.0 | 8.2 | 21.88 | 14.69 | 8.83 | 13.93 | 18.48 | dragon3 | 156.146.38.169 |
| 93.71 | shadowsocks | 271.1 | 1.8 | 21.5 | 14.93 | 8.87 | 13.93 | 18.48 | dragon3 | 37.19.198.236 |
| 93.56 | shadowsocks | 257.2 | 1.3 | 21.82 | 14.95 | 8.88 | 13.93 | 18.48 | dragon3 | 167.17.67.171 |
| 93.48 | trojan | 271.9 | 0.4 | 21.48 | 14.98 | 9.74 | 13.62 | 19.16 | dragon | 66.163.114.132 |
| 93.35 | shadowsocks | 261.5 | 4.6 | 21.72 | 14.83 | 8.89 | 13.93 | 18.48 | dragon3 | 172.111.38.72 |
| 93.26 | shadowsocks | 291.7 | 1.3 | 21.03 | 14.95 | 8.87 | 13.93 | 18.48 | dragon3 | 156.146.38.170 |
| 93.24 | shadowsocks | 270.1 | 2.0 | 21.52 | 14.92 | 8.89 | 13.93 | 18.48 | dragon3 | 149.40.57.133 |
| 93.17 | shadowsocks | 271.0 | 4.1 | 21.5 | 14.85 | 8.91 | 13.93 | 18.48 | dragon3 | 185.230.230.18 |
| 93.1 | trojan | 325.2 | 3.1 | 20.25 | 14.88 | 9.53 | 13.62 | 19.16 | dragon | 169.197.140.218 |
| 93.07 | trojan | 315.7 | 0.9 | 20.47 | 14.97 | 9.29 | 13.62 | 19.16 | dragon | 169.197.140.224 |
| 93.06 | shadowsocks | 298.7 | 2.2 | 20.86 | 14.92 | 8.87 | 13.93 | 18.48 | dragon3 | 37.19.198.243 |
| 92.9 | shadowsocks | 292.4 | 1.0 | 21.01 | 14.96 | 9.02 | 13.93 | 18.48 | dragon3 | 38.64.138.135 |
| 92.74 | shadowsocks | 298.4 | 1.7 | 20.87 | 14.94 | 9.02 | 13.93 | 18.48 | dragon3 | 67.220.73.178 |
| 92.71 | trojan | 208.8 | 0.7 | 22.94 | 14.97 | 9.52 | 13.62 | 19.16 | dragon | 216.152.155.59 |
| 91.57 | shadowsocks | 342.2 | 2.7 | 19.86 | 14.9 | 8.9 | 13.93 | 18.48 | dragon3 | 149.40.57.134 |
| 91.5 | shadowsocks | 342.6 | 1.5 | 19.85 | 14.94 | 8.85 | 13.93 | 18.48 | dragon3 | 167.88.62.56 |
| 91.24 | shadowsocks | 356.6 | 1.1 | 19.52 | 14.96 | 8.85 | 13.93 | 18.48 | dragon3 | 167.88.62.203 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon3 | 0.978 | 1.0 | 37 | 100 | prefer |
| dragon2 | 0.94 | 0.864 | 177 | 10000 | prefer |
| dragon | 0.804 | 0.73 | 74 | 10000 | prefer |
| mheidari-all | 0.547 | 0.778 | 9 | 14420 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5035 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3024 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10990 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5786 | observe |
| barry-far-vless | 0.255 | None | 0 | 5999 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 22 |
| 204 | ProxyError | - | 8 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 12 | 14 | - |
| global | False | 135 | 253 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
