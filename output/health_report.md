# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-25 08:56:53 |
| 运行耗时 | 245.3s |
| 订阅源总数 | 110 |
| 健康订阅源 | 89 |
| 原始节点 | 98234 |
| 去重后节点 | 34174 |
| TCP 可达 | 3000 |
| 真实可用 | 219 |
| Verified 输出 | 14 |
| Global 输出 | 224 |
| All 输出 | 34174 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 86.9 |
| probe | 69.9 |
| real_test | 41.8 |
| china_check | 28.5 |
| write_verified | 0.0 |
| generate | 11.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57518 |
| vmess | 19689 |
| shadowsocks | 10323 |
| trojan | 8231 |
| hysteria2 | 1905 |
| http | 203 |
| shadowsocksr | 177 |
| socks | 115 |
| anytls | 34 |
| hysteria | 23 |
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
| 93.4 | shadowsocks | 184.3 | 1.6 | 23.51 | 14.94 | 9.79 | 12.5 | 17.16 | dragon | 104.238.140.45 |
| 92.35 | shadowsocks | 232.6 | 0.3 | 22.39 | 14.99 | 9.81 | 12.5 | 17.16 | dragon | 23.150.152.38 |
| 92.18 | shadowsocks | 215.8 | 0.9 | 22.78 | 14.97 | 9.61 | 12.5 | 17.16 | dragon | 137.184.89.151 |
| 92.07 | shadowsocks | 220.9 | 0.4 | 22.67 | 14.98 | 9.63 | 12.5 | 17.16 | dragon | 169.197.142.68 |
| 91.19 | shadowsocks | 299.8 | 0.2 | 20.84 | 14.99 | 9.7 | 12.5 | 17.16 | dragon | 156.146.38.169 |
| 90.42 | shadowsocks | 236.5 | 2.6 | 22.3 | 14.9 | 9.56 | 12.5 | 17.16 | dragon | 173.244.56.6 |
| 89.81 | trojan | 218.7 | 3.5 | 22.72 | 14.87 | 9.56 | 10.0 | 17.16 | dragon | 167.88.61.85 |
| 89.4 | shadowsocks | 368.1 | 1.0 | 19.26 | 14.96 | 9.52 | 12.5 | 17.16 | dragon | 156.146.38.170 |
| 89.25 | trojan | 224.5 | 0.8 | 22.58 | 14.97 | 7.04 | 10.0 | 17.16 | dragon | 167.88.61.20 |
| 89.19 | shadowsocks | 240.4 | 0.3 | 22.21 | 14.99 | 8.71 | 12.5 | 17.16 | dragon | 173.244.56.9 |
| 88.91 | trojan | 215.0 | 0.1 | 22.8 | 15.0 | 6.45 | 10.0 | 17.16 | dragon | 167.88.61.198 |
| 88.76 | shadowsocks | 262.6 | 1.7 | 21.7 | 14.94 | 9.46 | 12.5 | 17.16 | dragon | 156.146.38.168 |
| 88.22 | trojan | 228.5 | 2.1 | 22.49 | 14.92 | 6.15 | 10.0 | 17.16 | dragon | 167.88.61.193 |
| 87.65 | trojan | 221.4 | 0.2 | 22.65 | 14.99 | 5.35 | 10.0 | 17.16 | dragon | 167.88.61.175 |
| 86.87 | trojan | 226.5 | 2.2 | 22.53 | 14.92 | 4.85 | 10.0 | 17.16 | dragon | 167.88.61.52 |
| 86.62 | shadowsocks | 192.5 | 0.6 | 23.32 | 14.98 | 9.6 | 12.5 | 17.16 | dragon | 95.215.201.18 |
| 85.99 | shadowsocks | 336.2 | 1.0 | 19.99 | 14.96 | 10.0 | 12.5 | 17.16 | dragon | 185.215.132.9 |
| 85.34 | shadowsocks | 364.6 | 0.8 | 19.34 | 14.97 | 10.0 | 12.5 | 17.16 | dragon | 169.197.140.247 |
| 85.01 | shadowsocks | 386.2 | 0.8 | 18.84 | 14.97 | 9.51 | 12.5 | 17.16 | dragon | 149.40.57.138 |
| 84.9 | shadowsocks | 362.7 | 0.1 | 19.38 | 15.0 | 9.43 | 12.5 | 17.16 | dragon | 38.91.107.57 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.926 | 0.849 | 245 | 10000 | prefer |
| ermaozi | 0.584 | 0.769 | 13 | 442 | observe |
| Surfboard-tg-mixed | 0.474 | 0.6 | 10 | 8136 | observe |
| dragon2 | 0.373 | 0.6 | 5 | 9831 | observe |
| ermaozi-get_subscribe | 0.326 | 1.0 | 2 | 376 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11514 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5440 | observe |
| barry-far-vless | 0.255 | None | 0 | 5649 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4463 | observe |
| mheidari-all | 0.255 | None | 0 | 14996 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 19 |
| test_one_timeout | 15.0s | - | 16 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| speed | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 18 | 14 | - |
| global | False | 269 | 224 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
