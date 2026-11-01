# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 18:04:27 |
| 运行耗时 | 273.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 90 |
| 原始节点 | 92878 |
| 去重后节点 | 33661 |
| TCP 可达 | 3000 |
| 真实可用 | 62 |
| Verified 输出 | 38 |
| Global 输出 | 136 |
| All 输出 | 33661 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.5 |
| tcp | 91.1 |
| probe | 97.8 |
| real_test | 37.9 |
| china_check | 18.5 |
| generate | 17.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55225 |
| vmess | 14008 |
| trojan | 12660 |
| shadowsocks | 9042 |
| hysteria2 | 1513 |
| shadowsocksr | 147 |
| http | 143 |
| socks | 98 |
| anytls | 19 |
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
| 92.74 | trojan | 271.7 | 3.5 | 21.49 | 14.87 | 10.0 | 14.09 | 19.96 | dragon | 66.163.114.114 |
| 90.78 | trojan | 286.9 | 1.4 | 21.14 | 14.95 | 10.0 | 14.09 | 19.96 | dragon | 66.163.112.13 |
| 90.67 | trojan | 288.4 | 0.5 | 21.1 | 14.98 | 10.0 | 14.09 | 19.96 | dragon | 66.163.112.121 |
| 86.8 | trojan | 270.6 | 1.6 | 21.51 | 14.94 | 10.0 | 14.09 | 19.96 | dragon | 66.163.114.132 |
| 86.27 | trojan | 237.8 | 12.1 | 22.27 | 14.55 | 2.69 | 14.09 | 19.96 | dragon | 167.88.61.193 |
| 86.01 | hysteria2 | 331.9 | 3.3 | 20.09 | 14.88 | 4.63 | 10.91 | 19.96 | dragon | 129.213.91.185 |
| 84.68 | vless | 263.5 | 2.4 | 21.68 | 14.91 | 0.0 | 11.84 | 19.12 | Au1rxx-base64 | 144.202.126.147 |
| 84.58 | trojan | 288.2 | 0.0 | 21.11 | 15.0 | 2.77 | 14.09 | 19.96 | dragon | 66.163.112.142 |
| 84.14 | trojan | 280.3 | 1.6 | 21.29 | 14.94 | 2.95 | 14.09 | 19.96 | dragon | 66.163.114.106 |
| 84.02 | trojan | 466.8 | 2.6 | 16.97 | 14.9 | 10.0 | 14.09 | 19.96 | dragon | 169.197.140.169 |
| 83.91 | hysteria2 | 218.1 | 1.1 | 22.73 | 14.96 | 5.35 | 10.91 | 19.96 | dragon | 179.255.103.55 |
| 83.37 | trojan | 276.5 | 1.4 | 21.38 | 14.95 | 2.95 | 14.09 | 19.96 | dragon | 66.163.114.45 |
| 83.18 | trojan | 325.2 | 7.1 | 20.25 | 14.73 | 2.95 | 14.09 | 19.96 | dragon | 66.163.114.245 |
| 82.64 | shadowsocks | 346.5 | 0.3 | 19.76 | 14.99 | 5.3 | 12.0 | 19.96 | dragon | 185.215.132.9 |
| 82.55 | hysteria2 | 259.4 | 6.6 | 21.77 | 14.75 | 0.0 | 10.91 | 19.12 | Au1rxx-base64 | 66.94.121.46 |
| 82.1 | trojan | 274.3 | 1.4 | 21.43 | 14.95 | 2.95 | 14.09 | 19.96 | dragon | 66.163.114.126 |
| 82.04 | trojan | 343.7 | 8.0 | 19.82 | 14.7 | 6.25 | 14.09 | 19.96 | dragon | 38.102.234.153 |
| 81.82 | trojan | 287.5 | 0.1 | 21.12 | 15.0 | 2.81 | 14.09 | 19.96 | dragon | 66.163.112.242 |
| 81.56 | shadowsocks | 351.4 | 0.1 | 19.64 | 15.0 | 5.29 | 12.0 | 19.96 | dragon | 185.215.132.18 |
| 81.39 | trojan | 285.1 | 1.1 | 21.18 | 14.96 | 2.81 | 14.09 | 19.96 | dragon | 66.163.112.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.896 | 0.857 | 21 | 1751 | prefer |
| dragon | 0.775 | 0.702 | 57 | 10000 | prefer |
| mheidari-all | 0.421 | 0.667 | 6 | 15458 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3716 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10659 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5773 | observe |
| barry-far-vless | 0.255 | None | 0 | 5873 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4680 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 14 |
| 204 | ProxyError | - | 5 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 38 | 1 | 0.5 |
| global | True | 136 | 62 | 0.5 |

---

此文件由 `core.report.write_health_report()` 自动生成。
