# AutoNodes 每日报告

生成时间：2026-11-10 19:57:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 102872 |
| 去重后节点数 | 34243 |
| TCP 可达数 | 3000 |
| 真测通过数 | 222 |
| verified 输出数 | 13 |
| global 输出数 | 225 |
| all 输出数 | 34243 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.6 |
| fetch | 6.9 |
| generate | 13.4 |
| geo | 1.6 |
| probe | 78.6 |
| real_test | 47.4 |
| tcp | 91.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 173 | 165 | 8 | 95.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 52 | 33 | 19 | 63.5% |
| vless | 13 | 8 | 5 | 61.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| 204:ProxyError | 11 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6585 |
| ConnectionRefusedError | 1067 |
| OSError | 239 |
| gaierror | 153 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.961 | prefer | 217 | 0.885 | 10000 |
| dragon2 | 0.745 | prefer | 17 | 0.765 | 10000 |
| Surfboard-tg-mixed | 0.583 | observe | 14 | 0.643 | 8562 |
| mheidari-all | 0.529 | observe | 7 | 0.857 | 14274 |
| dragon3 | 0.404 | observe | 4 | 1.0 | 100 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4955 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2620 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11116 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6459 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 415 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 410 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 159 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 146 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.643 | 9 | 5 | 14 |
| dragon2 | 0.765 | 13 | 4 | 17 |
| mheidari-all | 0.857 | 6 | 1 | 7 |
| dragon | 0.885 | 192 | 25 | 217 |
| dragon3 | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14274 | yes | 2.89 | 0 |
| SoliSpirit-all | 11116 | yes | 3.44 | 0 |
| dragon | 10000 | yes | 6.15 | 0 |
| dragon2 | 10000 | yes | 4.1 | 0 |
| Surfboard-tg-mixed | 8562 | yes | 4.28 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.38 | 0 |
| barry-far-vless | 6491 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 6459 | yes | 3.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4955 | yes | 1.81 | 0 |
| mahdibland-V2RayAggregator | 4667 | yes | 1.34 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 13 |
| test_one_timeout | 12 |
| speed | 4 |
| cn-block | 4 |
| geo | 2 |
