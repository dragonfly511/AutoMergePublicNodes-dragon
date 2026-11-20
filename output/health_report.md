# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-20 07:36:29 |
| 运行耗时 | 273.5s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 102563 |
| 去重后节点 | 35640 |
| TCP 可达 | 3000 |
| 真实可用 | 196 |
| Verified 输出 | 8 |
| Global 输出 | 206 |
| All 输出 | 35640 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.4 |
| tcp | 88.3 |
| probe | 72.1 |
| real_test | 70.1 |
| china_check | 24.9 |
| write_verified | 0.0 |
| generate | 10.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58910 |
| vmess | 18020 |
| trojan | 11829 |
| shadowsocks | 11633 |
| hysteria2 | 1744 |
| shadowsocksr | 172 |
| http | 130 |
| socks | 77 |
| hysteria | 20 |
| tuic | 16 |
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
| 91.99 | shadowsocks | 222.7 | 0.3 | 22.62 | 14.99 | 10.0 | 11.06 | 17.42 | dragon3 | 38.145.220.193 |
| 90.54 | shadowsocks | 234.5 | 1.6 | 22.35 | 14.94 | 10.0 | 11.06 | 17.42 | dragon3 | 104.238.140.45 |
| 88.59 | vless | 249.0 | 0.9 | 22.01 | 14.97 | 10.0 | 11.67 | 17.42 | dragon3 | 199.7.140.201 |
| 87.03 | vless | 398.4 | 0.8 | 18.56 | 14.97 | 10.0 | 11.67 | 17.42 | dragon3 | 148.135.86.162 |
| 86.67 | shadowsocks | 316.9 | 3.0 | 20.44 | 14.89 | 10.0 | 11.06 | 14.78 | dragon | 23.150.152.38 |
| 85.72 | shadowsocks | 247.9 | 1.2 | 22.04 | 14.96 | 10.0 | 11.06 | 14.78 | dragon | 169.197.142.68 |
| 84.45 | shadowsocks | 278.3 | 0.8 | 21.34 | 14.97 | 10.0 | 11.06 | 14.78 | dragon | 149.22.95.183 |
| 84.35 | shadowsocks | 280.3 | 0.0 | 21.29 | 15.0 | 9.92 | 11.06 | 14.78 | dragon | 173.244.56.9 |
| 84.18 | trojan | 268.2 | 0.2 | 21.57 | 14.99 | 10.0 | 5.53 | 17.42 | dragon3 | 167.88.61.198 |
| 84.09 | vless | 288.4 | 5.8 | 21.1 | 14.78 | 0.0 | 11.67 | 19.78 | dragon2 | 195.123.240.65 |
| 83.29 | hysteria2 | 501.5 | 7.3 | 16.17 | 14.73 | 9.99 | 12.5 | 14.78 | dragon | 34.24.25.1 |
| 82.46 | vless | 331.4 | 0.3 | 20.11 | 14.99 | 0.0 | 11.67 | 19.78 | dragon2 | 143.246.62.191 |
| 80.81 | shadowsocks | 339.0 | 0.5 | 19.93 | 14.98 | 9.81 | 11.06 | 14.78 | dragon | 216.106.178.169 |
| 80.68 | shadowsocks | 265.1 | 2.3 | 21.64 | 14.91 | 10.0 | 11.06 | 14.78 | dragon | 95.215.201.18 |
| 79.87 | vless | 281.5 | 3.0 | 21.26 | 14.89 | 0.0 | 11.67 | 19.78 | dragon2 | 216.227.161.95 |
| 79.76 | shadowsocks | 398.5 | 1.0 | 18.55 | 14.96 | 10.0 | 11.06 | 17.42 | dragon3 | 167.17.67.171 |
| 79.73 | hysteria2 | 477.8 | 1.7 | 16.72 | 14.94 | 9.35 | 12.5 | 14.78 | dragon | 62.210.124.146 |
| 79.3 | vless | 291.5 | 1.0 | 21.03 | 14.96 | 0.0 | 11.67 | 19.78 | dragon2 | 198.247.127.131 |
| 78.81 | shadowsocks | 307.6 | 4.4 | 20.66 | 14.83 | 9.73 | 11.06 | 14.78 | dragon | 38.128.66.32 |
| 78.53 | hysteria2 | 539.0 | 12.6 | 15.3 | 14.53 | 9.56 | 12.5 | 14.78 | dragon | 5.129.235.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.888 | 0.833 | 24 | 10000 | prefer |
| dragon2 | 0.681 | 0.601 | 271 | 10000 | observe |
| Surfboard-tg-mixed | 0.507 | 0.75 | 8 | 8500 | observe |
| dragon3 | 0.457 | 0.571 | 14 | 100 | observe |
| mheidari-all | 0.373 | 0.6 | 5 | 14360 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4935 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2728 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11813 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5726 | observe |
| barry-far-vless | 0.255 | None | 0 | 6117 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4501 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 70 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyError | - | 10 |
| cn-block | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 6 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 13 | 8 | - |
| global | False | 172 | 206 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
