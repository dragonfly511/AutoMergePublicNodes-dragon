# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-15 19:02:55 |
| 运行耗时 | 250.0s |
| 订阅源总数 | 110 |
| 健康订阅源 | 90 |
| 原始节点 | 104609 |
| 去重后节点 | 35094 |
| TCP 可达 | 3000 |
| 真实可用 | 119 |
| Verified 输出 | 12 |
| Global 输出 | 122 |
| All 输出 | 35094 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 93.7 |
| probe | 81.8 |
| real_test | 32.9 |
| china_check | 19.3 |
| write_verified | 0.0 |
| generate | 13.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61895 |
| vmess | 17619 |
| trojan | 11635 |
| shadowsocks | 11270 |
| hysteria2 | 1759 |
| shadowsocksr | 153 |
| http | 138 |
| socks | 70 |
| hysteria | 37 |
| tuic | 18 |
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
| 89.34 | shadowsocks | 241.4 | 3.0 | 22.19 | 14.89 | 2.7 | 14.35 | 19.82 | dragon | 38.145.220.193 |
| 88.67 | shadowsocks | 248.5 | 0.2 | 22.02 | 14.99 | 2.79 | 14.35 | 19.82 | dragon | 23.150.152.38 |
| 88.15 | hysteria2 | 256.2 | 2.5 | 21.85 | 14.91 | 0.0 | 13.57 | 19.82 | dragon | 192.255.152.147 |
| 86.95 | shadowsocks | 234.4 | 1.9 | 22.35 | 14.93 | 0.0 | 14.35 | 19.82 | dragon | 137.184.89.151 |
| 86.51 | shadowsocks | 324.4 | 4.3 | 20.27 | 14.84 | 10.0 | 14.35 | 19.82 | dragon | 156.146.38.170 |
| 85.72 | trojan | 288.8 | 0.8 | 21.09 | 14.97 | 9.84 | 12.11 | 19.82 | dragon | 66.163.112.242 |
| 85.54 | shadowsocks | 487.7 | 2.2 | 16.49 | 14.92 | 10.0 | 14.35 | 19.82 | dragon | 15.204.246.132 |
| 83.91 | shadowsocks | 314.2 | 2.3 | 20.5 | 14.91 | 0.0 | 14.35 | 19.82 | dragon | 169.197.142.68 |
| 83.0 | hysteria2 | 352.6 | 2.0 | 19.62 | 14.93 | 0.0 | 13.57 | 19.82 | dragon | 206.189.229.48 |
| 82.23 | trojan | 375.0 | 0.6 | 19.1 | 14.98 | 4.17 | 12.11 | 19.82 | dragon | 66.23.203.21 |
| 81.58 | trojan | 481.7 | 3.3 | 16.63 | 14.88 | 9.36 | 12.11 | 19.82 | dragon | 154.90.62.70 |
| 80.56 | shadowsocks | 372.6 | 3.4 | 19.15 | 14.87 | 0.0 | 14.35 | 19.82 | dragon | 103.11.76.248 |
| 80.25 | shadowsocks | 362.2 | 1.8 | 19.39 | 14.93 | 0.0 | 14.35 | 19.82 | dragon | 167.17.67.171 |
| 79.87 | shadowsocks | 273.9 | 1.1 | 21.44 | 14.96 | 0.0 | 14.35 | 19.82 | dragon | 95.215.201.18 |
| 79.45 | hysteria2 | 260.4 | 26.8 | 21.75 | 13.99 | 0.0 | 13.57 | 11.14 | dragon2 | 66.94.121.46 |
| 78.91 | shadowsocks | 363.6 | 0.5 | 19.36 | 14.98 | 0.0 | 14.35 | 19.82 | dragon | 45.86.51.18 |
| 78.91 | shadowsocks | 380.2 | 1.7 | 18.98 | 14.94 | 0.0 | 14.35 | 19.82 | dragon | 38.128.66.32 |
| 78.91 | shadowsocks | 387.3 | 1.4 | 18.81 | 14.95 | 0.0 | 14.35 | 19.82 | dragon | 38.64.138.135 |
| 78.86 | shadowsocks | 437.4 | 0.9 | 17.65 | 14.97 | 0.0 | 14.35 | 19.82 | dragon | 167.88.62.56 |
| 78.34 | shadowsocks | 388.0 | 2.8 | 18.8 | 14.89 | 0.0 | 14.35 | 19.82 | dragon | 185.230.230.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.747 | 0.669 | 154 | 10000 | prefer |
| mheidari-all | 0.629 | 1.0 | 8 | 14826 | observe |
| dragon2 | 0.519 | 1.0 | 5 | 10000 | observe |
| Surfboard-tg-mixed | 0.349 | 0.667 | 3 | 9142 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4916 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3024 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11885 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6162 | observe |
| barry-far-vless | 0.255 | None | 0 | 6310 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4584 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 27 |
| test_one_timeout | 15.0s | - | 15 |
| 204 | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 13 | 12 | - |
| global | False | 177 | 122 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
