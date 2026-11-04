# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-04 06:47:03 |
| 运行耗时 | 248.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 92804 |
| 去重后节点 | 33964 |
| TCP 可达 | 3000 |
| 真实可用 | 261 |
| Verified 输出 | 18 |
| Global 输出 | 264 |
| All 输出 | 33964 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 99.1 |
| probe | 63.7 |
| real_test | 46.6 |
| china_check | 21.8 |
| write_verified | 0.0 |
| generate | 11.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55914 |
| vmess | 13969 |
| trojan | 11425 |
| shadowsocks | 9487 |
| hysteria2 | 1641 |
| shadowsocksr | 147 |
| http | 94 |
| socks | 77 |
| hysteria | 18 |
| tuic | 16 |
| anytls | 16 |

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
| 87.35 | hysteria2 | 221.5 | 2.0 | 22.65 | 14.92 | 0.0 | 12.0 | 18.78 | dragon | 88.216.195.188 |
| 85.87 | shadowsocks | 232.9 | 0.7 | 22.39 | 14.97 | 0.0 | 13.73 | 18.78 | dragon | 156.146.38.167 |
| 85.65 | hysteria2 | 276.5 | 0.2 | 21.38 | 14.99 | 0.0 | 12.0 | 18.78 | dragon | 129.213.91.185 |
| 85.23 | shadowsocks | 260.5 | 0.7 | 21.75 | 14.97 | 0.0 | 13.73 | 18.78 | dragon | 156.146.38.169 |
| 85.2 | trojan | 269.6 | 1.1 | 21.54 | 14.96 | 4.32 | 10.1 | 18.78 | dragon | 216.152.155.158 |
| 84.89 | trojan | 354.4 | 0.9 | 19.57 | 14.96 | 6.03 | 10.1 | 18.78 | dragon | 170.101.101.53 |
| 84.53 | shadowsocks | 290.6 | 0.7 | 21.05 | 14.97 | 0.0 | 13.73 | 18.78 | dragon | 156.146.38.170 |
| 84.49 | shadowsocks | 271.2 | 1.0 | 21.5 | 14.96 | 0.0 | 13.73 | 18.78 | dragon | 156.146.38.168 |
| 84.32 | shadowsocks | 294.3 | 0.9 | 20.96 | 14.97 | 0.0 | 13.73 | 18.78 | dragon | 37.19.198.236 |
| 84.28 | shadowsocks | 288.7 | 0.2 | 21.1 | 14.99 | 0.0 | 13.73 | 18.78 | dragon | 37.19.198.244 |
| 83.71 | shadowsocks | 280.3 | 0.6 | 21.29 | 14.98 | 0.0 | 13.73 | 18.78 | dragon | 37.19.198.160 |
| 83.29 | trojan | 242.5 | 0.3 | 22.16 | 14.99 | 0.0 | 10.1 | 18.78 | dragon | 66.163.114.132 |
| 83.27 | shadowsocks | 291.1 | 0.7 | 21.04 | 14.98 | 0.0 | 13.73 | 18.78 | dragon | 37.19.198.243 |
| 83.02 | trojan | 263.0 | 1.3 | 21.69 | 14.95 | 0.0 | 10.1 | 18.78 | dragon | 216.152.155.59 |
| 83.01 | trojan | 263.6 | 1.4 | 21.68 | 14.95 | 0.0 | 10.1 | 18.78 | dragon | 216.152.155.131 |
| 82.58 | shadowsocks | 292.3 | 0.4 | 21.01 | 14.98 | 0.0 | 13.73 | 18.78 | dragon | 185.215.132.9 |
| 82.51 | hysteria2 | 297.5 | 7.6 | 20.89 | 14.72 | 0.0 | 12.0 | 18.78 | dragon | 66.94.121.46 |
| 82.48 | hysteria2 | 258.7 | 2.1 | 21.79 | 14.92 | 3.27 | 12.0 | 18.78 | dragon | 67.216.207.144 |
| 82.46 | shadowsocks | 294.0 | 3.2 | 20.97 | 14.88 | 3.6 | 13.73 | 18.78 | dragon | 167.17.67.171 |
| 82.2 | trojan | 300.6 | 0.1 | 20.82 | 15.0 | 0.0 | 10.1 | 18.78 | dragon | 170.101.101.211 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.982 | 0.905 | 262 | 10000 | prefer |
| Au1rxx-base64 | 0.67 | 0.609 | 23 | 1751 | observe |
| Surfboard-tg-mixed | 0.622 | 0.667 | 15 | 8544 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5017 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10853 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6022 | observe |
| barry-far-vless | 0.255 | None | 0 | 6238 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4608 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| mheidari-all | 0.226 | 0.2 | 5 | 15179 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 18 |
| 204 | ProxyError | - | 8 |
| geo | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 11 | 18 | - |
| global | False | 174 | 264 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
