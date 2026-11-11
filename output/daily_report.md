# AutoNodes 每日报告

生成时间：2026-11-11 06:52:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 102478 |
| 去重后节点数 | 34701 |
| TCP 可达数 | 3000 |
| 真测通过数 | 249 |
| verified 输出数 | 9 |
| global 输出数 | 250 |
| all 输出数 | 34701 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.5 |
| fetch | 7.7 |
| generate | 14.7 |
| geo | 1.5 |
| probe | 83.0 |
| real_test | 38.3 |
| tcp | 91.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 0 | 2 | 0.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 169 | 157 | 12 | 92.9% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 96 | 78 | 18 | 81.2% |
| vless | 3 | 3 | 0 | 100.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 3 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6706 |
| ConnectionRefusedError | 1027 |
| OSError | 246 |
| gaierror | 157 |
| ConnectionResetError | 1 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | prefer | 232 | 0.901 | 10000 |
| dragon2 | 0.886 | prefer | 34 | 0.824 | 10000 |
| mheidari-all | 0.529 | observe | 7 | 0.857 | 13964 |
| dragon3 | 0.404 | observe | 4 | 1.0 | 100 |
| ermaozi | 0.335 | observe | 2 | 1.0 | 601 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8415 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4955 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2620 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.123 | observe | 2 | 0.0 | 0 | 485 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 416 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 411 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 160 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 147 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 2 | 2 |
| dragon2 | 0.824 | 28 | 6 | 34 |
| mheidari-all | 0.857 | 6 | 1 | 7 |
| dragon | 0.901 | 209 | 23 | 232 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 2 | 0 | 2 |
| dragon3 | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13964 | yes | 4.52 | 0 |
| SoliSpirit-all | 11127 | yes | 4.81 | 0 |
| dragon | 10000 | yes | 7.0 | 0 |
| dragon2 | 10000 | yes | 4.76 | 0 |
| Surfboard-tg-mixed | 8415 | yes | 5.04 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.04 | 0 |
| barry-far-vless | 6562 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 6298 | yes | 2.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4955 | yes | 3.26 | 0 |
| mahdibland-V2RayAggregator | 4589 | yes | 2.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 9 |
| cn-block | 4 |
| geo | 1 |
