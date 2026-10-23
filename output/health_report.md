# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-23 10:15:07 |
| 运行耗时 | 282.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 98769 |
| 去重后节点 | 29477 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 154 |
| Global 输出 | 300 |
| All 输出 | 29477 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 82.2 |
| probe | 87.9 |
| real_test | 73.3 |
| china_check | 16.6 |
| write_verified | 0.1 |
| generate | 13.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57684 |
| vmess | 16931 |
| shadowsocks | 12214 |
| trojan | 10021 |
| hysteria2 | 1324 |
| http | 328 |
| shadowsocksr | 165 |
| socks | 54 |
| anytls | 25 |
| hysteria | 17 |
| tuic | 6 |

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
| 87.33 | http | 262.4 | 5.5 | 21.7 | 14.79 | 0.0 | 14.3 | 19.54 | ermaozi | 149.88.21.140 |
| 86.5 | hysteria2 | 222.3 | 2.5 | 22.63 | 14.91 | 0.0 | 13.24 | 17.22 | Au1rxx-base64 | 129.213.91.185 |
| 84.89 | http | 360.3 | 3.2 | 19.44 | 14.88 | 0.0 | 14.3 | 19.54 | ermaozi | 68.235.56.59 |
| 84.73 | http | 296.1 | 1.0 | 20.92 | 14.96 | 0.0 | 14.3 | 19.54 | ermaozi | 12.202.180.118 |
| 84.41 | http | 393.2 | 2.8 | 18.68 | 14.89 | 0.0 | 14.3 | 19.54 | ermaozi | 154.47.25.78 |
| 84.1 | http | 419.2 | 3.9 | 18.07 | 14.85 | 0.0 | 14.3 | 19.54 | ermaozi | 193.239.236.134 |
| 83.76 | shadowsocks | 237.3 | 3.7 | 22.28 | 14.86 | 0.0 | 13.4 | 17.22 | Au1rxx-base64 | 37.19.198.244 |
| 83.61 | http | 376.2 | 1.5 | 19.07 | 14.94 | 0.0 | 14.3 | 19.54 | ermaozi | 149.88.98.81 |
| 83.6 | http | 415.4 | 1.5 | 18.16 | 14.94 | 0.0 | 14.3 | 19.54 | ermaozi | 206.223.183.16 |
| 83.17 | http | 345.1 | 3.5 | 19.79 | 14.87 | 0.0 | 14.3 | 19.54 | ermaozi | 68.235.56.51 |
| 83.16 | shadowsocks | 259.4 | 6.0 | 21.77 | 14.77 | 0.0 | 13.4 | 17.22 | Au1rxx-base64 | 37.19.198.236 |
| 83.13 | shadowsocks | 239.2 | 6.0 | 22.24 | 14.77 | 0.0 | 13.4 | 17.22 | Au1rxx-base64 | 185.230.230.18 |
| 83.01 | shadowsocks | 253.4 | 0.5 | 21.91 | 14.98 | 0.0 | 13.4 | 17.22 | Au1rxx-base64 | 193.151.163.18 |
| 82.37 | http | 501.6 | 0.5 | 16.17 | 14.98 | 0.0 | 14.3 | 19.54 | ermaozi | 121.127.34.82 |
| 81.98 | http | 518.3 | 3.7 | 15.78 | 14.86 | 0.0 | 14.3 | 19.54 | ermaozi | 198.44.135.27 |
| 81.9 | vless | 256.3 | 2.2 | 21.84 | 14.92 | 0.0 | 7.92 | 17.22 | Au1rxx-base64 | 159.89.87.21 |
| 81.54 | shadowsocks | 303.8 | 8.8 | 20.75 | 14.67 | 0.0 | 13.4 | 17.22 | Au1rxx-base64 | 45.86.51.18 |
| 81.46 | shadowsocks | 318.7 | 1.7 | 20.4 | 14.94 | 0.0 | 13.4 | 17.22 | Au1rxx-base64 | 64.42.181.102 |
| 81.1 | shadowsocks | 324.0 | 7.9 | 20.28 | 14.7 | 0.0 | 13.4 | 17.22 | Au1rxx-base64 | 15.204.233.41 |
| 80.82 | vless | 305.8 | 0.6 | 20.7 | 14.98 | 0.0 | 7.92 | 17.22 | Au1rxx-base64 | 195.123.235.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.977 | 0.961 | 103 | 609 | prefer |
| Au1rxx-base64 | 0.902 | 0.844 | 218 | 1537 | prefer |
| mheidari-all | 0.761 | 0.687 | 67 | 23755 | prefer |
| Surfboard-tg-mixed | 0.757 | 0.68 | 97 | 6855 | prefer |
| dragon | 0.48 | 1.0 | 4 | 3000 | observe |
| DeltaKronecker-all | 0.45 | 0.5 | 12 | 3871 | observe |
| tg-oneclickvpnkeys | 0.361 | 1.0 | 3 | 83 | observe |
| tg-LonUp_M | 0.327 | 0.75 | 4 | 166 | observe |
| zhangkai | 0.256 | 1.0 | 1 | 24 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| Epodonios-all | 0.255 | None | 0 | 7492 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10291 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5326 | observe |
| barry-far-vless | 0.255 | None | 0 | 5662 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 60 |
| geo | ClientOSError | - | 12 |
| 204 | ProxyError | - | 6 |
| 204 | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 146 | 154 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
