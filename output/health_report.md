# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-07 13:24:22 |
| 运行耗时 | 276.2s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 102406 |
| 去重后节点 | 34580 |
| TCP 可达 | 3000 |
| 真实可用 | 171 |
| Verified 输出 | 12 |
| Global 输出 | 174 |
| All 输出 | 34580 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.6 |
| tcp | 96.1 |
| probe | 93.8 |
| real_test | 39.5 |
| china_check | 18.3 |
| write_verified | 0.0 |
| generate | 17.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60107 |
| vmess | 17258 |
| trojan | 12389 |
| shadowsocks | 10477 |
| hysteria2 | 1758 |
| shadowsocksr | 152 |
| http | 132 |
| socks | 75 |
| anytls | 22 |
| hysteria | 21 |
| tuic | 15 |

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
| 87.93 | shadowsocks | 296.0 | 0.9 | 20.92 | 14.97 | 6.4 | 14.27 | 20.0 | dragon | 38.22.17.219 |
| 86.63 | shadowsocks | 250.9 | 2.8 | 21.97 | 14.89 | 0.0 | 14.27 | 20.0 | dragon | 167.17.67.171 |
| 86.19 | shadowsocks | 240.6 | 1.5 | 22.21 | 14.95 | 0.0 | 14.27 | 20.0 | dragon | 156.146.38.170 |
| 85.42 | shadowsocks | 294.0 | 1.0 | 20.97 | 14.96 | 0.0 | 14.27 | 20.0 | dragon | 45.86.51.18 |
| 85.23 | shadowsocks | 297.9 | 1.0 | 20.88 | 14.96 | 0.0 | 14.27 | 20.0 | dragon | 37.19.198.244 |
| 84.93 | shadowsocks | 298.5 | 5.6 | 20.87 | 14.79 | 0.0 | 14.27 | 20.0 | dragon | 156.146.38.169 |
| 83.65 | vless | 331.6 | 2.8 | 20.1 | 14.89 | 4.92 | 8.77 | 20.0 | dragon | 148.135.86.162 |
| 83.19 | shadowsocks | 293.1 | 5.0 | 20.99 | 14.81 | 0.0 | 14.27 | 20.0 | dragon | 38.121.43.225 |
| 83.14 | shadowsocks | 289.9 | 0.9 | 21.07 | 14.97 | 0.0 | 14.27 | 20.0 | dragon | 185.215.132.9 |
| 82.91 | vless | 406.7 | 0.2 | 18.36 | 14.99 | 5.03 | 8.77 | 20.0 | dragon | 169.40.42.74 |
| 82.67 | shadowsocks | 304.4 | 17.4 | 20.73 | 14.35 | 0.0 | 14.27 | 20.0 | dragon | 37.19.198.236 |
| 82.65 | shadowsocks | 308.5 | 0.4 | 20.64 | 14.98 | 0.0 | 14.27 | 20.0 | dragon | 185.230.230.18 |
| 82.21 | shadowsocks | 292.4 | 0.4 | 21.01 | 14.98 | 0.0 | 14.27 | 20.0 | dragon | 95.215.201.18 |
| 81.98 | vless | 354.8 | 14.5 | 19.56 | 14.46 | 4.98 | 8.77 | 20.0 | dragon | 2.24.124.64 |
| 81.94 | vless | 340.3 | 2.8 | 19.9 | 14.89 | 4.85 | 8.77 | 20.0 | dragon | 66.70.179.198 |
| 81.71 | shadowsocks | 269.2 | 3.0 | 21.55 | 14.89 | 0.0 | 14.27 | 20.0 | dragon | 156.146.38.168 |
| 81.58 | shadowsocks | 332.0 | 6.1 | 20.09 | 14.77 | 0.0 | 14.27 | 20.0 | dragon | 193.151.160.9 |
| 81.57 | vless | 459.9 | 4.7 | 17.13 | 14.83 | 5.03 | 8.77 | 20.0 | dragon | 169.40.42.163 |
| 81.21 | shadowsocks | 370.1 | 6.7 | 19.21 | 14.75 | 0.0 | 14.27 | 20.0 | dragon | 38.22.17.139 |
| 81.19 | shadowsocks | 305.9 | 0.1 | 20.7 | 15.0 | 0.0 | 14.27 | 20.0 | dragon | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.964 | 0.889 | 162 | 10000 | prefer |
| dragon2 | 0.629 | 1.0 | 8 | 10000 | observe |
| dragon3 | 0.548 | 0.818 | 11 | 100 | observe |
| mheidari-all | 0.507 | 0.75 | 8 | 14331 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 6752 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8637 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4866 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11009 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6148 | observe |
| barry-far-vless | 0.255 | None | 0 | 6359 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4522 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 15 |
| 204 | TimeoutError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 20 | 12 | - |
| global | False | 293 | 174 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
