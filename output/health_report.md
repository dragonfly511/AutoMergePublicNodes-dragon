# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-17 08:13:34 |
| 运行耗时 | 213.2s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 103324 |
| 去重后节点 | 35081 |
| TCP 可达 | 3000 |
| 真实可用 | 201 |
| Verified 输出 | 15 |
| Global 输出 | 204 |
| All 输出 | 35081 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 69.5 |
| probe | 70.1 |
| real_test | 34.5 |
| china_check | 20.5 |
| write_verified | 0.0 |
| generate | 11.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60834 |
| vmess | 17777 |
| trojan | 11356 |
| shadowsocks | 11056 |
| hysteria2 | 1752 |
| http | 250 |
| shadowsocksr | 177 |
| socks | 70 |
| tuic | 21 |
| hysteria | 19 |
| anytls | 12 |

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
| 96.86 | shadowsocks | 227.4 | 3.2 | 22.51 | 14.88 | 10.0 | 14.07 | 19.9 | dragon | 45.86.51.18 |
| 96.75 | shadowsocks | 231.8 | 3.6 | 22.41 | 14.87 | 10.0 | 14.07 | 19.9 | dragon | 185.230.230.18 |
| 96.63 | shadowsocks | 237.8 | 3.0 | 22.27 | 14.89 | 10.0 | 14.07 | 19.9 | dragon | 172.111.38.72 |
| 96.59 | shadowsocks | 240.5 | 2.4 | 22.21 | 14.91 | 10.0 | 14.07 | 19.9 | dragon | 193.151.163.18 |
| 95.54 | shadowsocks | 286.3 | 2.1 | 21.15 | 14.92 | 10.0 | 14.07 | 19.9 | dragon | 193.151.160.18 |
| 95.41 | shadowsocks | 290.7 | 3.0 | 21.05 | 14.89 | 10.0 | 14.07 | 19.9 | dragon | 193.151.160.9 |
| 94.86 | shadowsocks | 315.6 | 2.1 | 20.47 | 14.92 | 10.0 | 14.07 | 19.9 | dragon | 38.91.100.39 |
| 94.81 | hysteria2 | 285.3 | 2.5 | 21.17 | 14.9 | 6.98 | 12.86 | 19.9 | dragon | 206.189.229.48 |
| 94.72 | shadowsocks | 296.8 | 2.4 | 20.91 | 14.91 | 9.43 | 14.07 | 19.9 | dragon | 67.220.73.178 |
| 94.62 | shadowsocks | 329.0 | 0.3 | 20.16 | 14.99 | 10.0 | 14.07 | 19.9 | dragon | 149.40.57.133 |
| 94.41 | shadowsocks | 335.4 | 1.9 | 20.01 | 14.93 | 10.0 | 14.07 | 19.9 | dragon | 149.40.57.134 |
| 94.05 | shadowsocks | 352.9 | 0.9 | 19.61 | 14.97 | 10.0 | 14.07 | 19.9 | dragon | 15.204.247.206 |
| 93.84 | shadowsocks | 286.6 | 0.4 | 21.14 | 14.98 | 9.65 | 14.07 | 19.9 | dragon | 185.215.132.9 |
| 93.8 | shadowsocks | 361.6 | 2.1 | 19.41 | 14.92 | 10.0 | 14.07 | 19.9 | dragon | 38.91.107.188 |
| 93.77 | shadowsocks | 262.7 | 1.1 | 21.7 | 14.96 | 9.64 | 14.07 | 19.9 | dragon | 15.204.247.244 |
| 93.53 | hysteria2 | 340.2 | 3.0 | 19.9 | 14.89 | 6.98 | 12.86 | 19.9 | dragon | 34.24.25.1 |
| 93.46 | shadowsocks | 339.8 | 0.9 | 19.91 | 14.97 | 10.0 | 14.07 | 19.9 | dragon | 38.22.17.219 |
| 93.29 | shadowsocks | 382.8 | 2.7 | 18.92 | 14.9 | 10.0 | 14.07 | 19.9 | dragon | 149.40.57.138 |
| 92.83 | shadowsocks | 303.8 | 0.4 | 20.74 | 14.98 | 8.33 | 14.07 | 19.9 | dragon | 38.22.17.139 |
| 92.8 | shadowsocks | 359.5 | 2.0 | 19.46 | 14.93 | 10.0 | 14.07 | 19.9 | dragon | 162.251.62.31 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.916 | 0.839 | 211 | 10000 | prefer |
| dragon3 | 0.623 | 1.0 | 10 | 100 | observe |
| ermaozi | 0.538 | 1.0 | 7 | 621 | observe |
| mheidari-all | 0.446 | 0.8 | 5 | 14792 | observe |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8623 | observe |
| Surfboard-tg-vless | 0.335 | 1.0 | 1 | 6028 | observe |
| dragon2 | 0.335 | 1.0 | 1 | 10000 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 169 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4964 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2915 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| Pawdroid | 0.255 | 1.0 | 1 | 12 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11532 | observe |
| barry-far-vless | 0.255 | None | 0 | 6053 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 24 |
| 204 | ProxyError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 19 | 15 | - |
| global | False | 230 | 204 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
