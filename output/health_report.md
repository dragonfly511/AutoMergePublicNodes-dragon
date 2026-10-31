# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 17:22:23 |
| 运行耗时 | 296.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 91402 |
| 去重后节点 | 33519 |
| TCP 可达 | 3000 |
| 真实可用 | 171 |
| Verified 输出 | 52 |
| Global 输出 | 171 |
| All 输出 | 33519 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.5 |
| tcp | 95.1 |
| probe | 98.5 |
| real_test | 56.2 |
| china_check | 18.0 |
| write_verified | 0.0 |
| generate | 17.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54504 |
| vmess | 13803 |
| trojan | 12303 |
| shadowsocks | 8928 |
| hysteria2 | 1472 |
| http | 162 |
| shadowsocksr | 146 |
| socks | 48 |
| anytls | 13 |
| tuic | 12 |
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
| 85.27 | trojan | 340.5 | 2.7 | 19.9 | 14.9 | 3.54 | 11.76 | 18.22 | dragon | 66.23.203.21 |
| 85.13 | trojan | 325.7 | 6.8 | 20.24 | 14.74 | 7.32 | 11.76 | 18.22 | dragon | 216.106.186.33 |
| 84.18 | hysteria2 | 274.9 | 5.4 | 21.41 | 14.8 | 0.0 | 11.25 | 18.22 | dragon | 129.213.91.185 |
| 84.18 | trojan | 302.2 | 1.5 | 20.78 | 14.94 | 10.0 | 11.76 | 18.22 | dragon | 167.88.61.20 |
| 84.0 | shadowsocks | 244.3 | 0.5 | 22.12 | 14.98 | 0.0 | 12.68 | 18.22 | dragon | 156.146.38.167 |
| 83.91 | shadowsocks | 241.9 | 4.6 | 22.18 | 14.83 | 0.0 | 12.68 | 18.22 | dragon | 156.146.38.169 |
| 83.85 | shadowsocks | 249.2 | 1.6 | 22.01 | 14.94 | 0.0 | 12.68 | 18.22 | dragon | 156.146.38.168 |
| 83.81 | shadowsocks | 246.7 | 4.3 | 22.07 | 14.84 | 0.0 | 12.68 | 18.22 | dragon | 156.146.38.170 |
| 83.75 | shadowsocks | 374.6 | 3.2 | 19.11 | 14.88 | 10.0 | 12.68 | 18.22 | dragon | 51.222.107.43 |
| 81.89 | shadowsocks | 313.8 | 0.6 | 20.51 | 14.98 | 0.0 | 12.68 | 18.22 | dragon | 45.86.51.18 |
| 81.75 | trojan | 314.9 | 3.7 | 20.49 | 14.86 | 5.19 | 11.76 | 18.22 | dragon | 130.94.19.95 |
| 81.27 | shadowsocks | 310.2 | 1.5 | 20.6 | 14.94 | 0.0 | 12.68 | 18.22 | dragon | 37.19.198.244 |
| 80.9 | shadowsocks | 315.5 | 21.6 | 20.48 | 14.19 | 0.0 | 12.68 | 18.22 | dragon | 37.19.198.160 |
| 79.86 | shadowsocks | 296.7 | 7.3 | 20.91 | 14.72 | 0.0 | 12.68 | 18.22 | dragon | 37.19.198.243 |
| 79.49 | shadowsocks | 544.4 | 1.2 | 15.18 | 14.96 | 4.34 | 12.68 | 18.22 | dragon | 15.204.247.206 |
| 78.98 | shadowsocks | 297.0 | 0.8 | 20.9 | 14.97 | 0.0 | 12.68 | 18.22 | dragon | 173.244.56.6 |
| 78.86 | shadowsocks | 282.4 | 1.3 | 21.24 | 14.95 | 0.06 | 12.68 | 18.22 | dragon | 185.215.132.9 |
| 78.55 | shadowsocks | 330.7 | 2.4 | 20.12 | 14.91 | 0.0 | 12.68 | 18.22 | dragon | 193.151.160.9 |
| 78.34 | trojan | 579.9 | 10.3 | 14.35 | 14.61 | 8.67 | 11.76 | 18.22 | dragon | 45.130.125.190 |
| 78.28 | shadowsocks | 318.0 | 0.6 | 20.42 | 14.98 | 0.0 | 12.68 | 18.22 | dragon | 193.151.163.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.902 | 0.826 | 172 | 10000 | prefer |
| Au1rxx-base64 | 0.493 | 0.417 | 24 | 1751 | observe |
| mheidari-all | 0.373 | 0.6 | 5 | 14848 | observe |
| peasoft-NoMoreWalls | 0.365 | 0.346 | 26 | 206 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 6752 | observe |
| tg-Farah_VPN | 0.319 | 1.0 | 2 | 200 | observe |
| Surfboard-tg-mixed | 0.281 | 0.214 | 14 | 7984 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10813 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5777 | observe |
| barry-far-vless | 0.255 | None | 0 | 5990 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 53 |
| geo | ClientOSError | - | 12 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 55 | 52 | - |
| global | False | 187 | 171 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
