# AutoNodes 每日报告

生成时间：2026-11-08 22:22:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 101680 |
| 去重后节点数 | 34166 |
| TCP 可达数 | 3000 |
| 真测通过数 | 324 |
| verified 输出数 | 27 |
| global 输出数 | 300 |
| all 输出数 | 34166 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.9 |
| fetch | 9.3 |
| generate | 17.5 |
| geo | 1.6 |
| probe | 87.2 |
| real_test | 72.3 |
| tcp | 93.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 220 | 207 | 13 | 94.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 6 | 4 | 2 | 66.7% |
| vless | 159 | 97 | 62 | 61.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 50 |
| 204:TimeoutError | 7 |
| cn-block:ProxyError | 5 |
| cn-block:TimeoutError | 5 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6418 |
| ConnectionRefusedError | 1054 |
| OSError | 237 |
| gaierror | 214 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 128 | 0.953 | 10000 |
| dragon2 | 0.807 | prefer | 254 | 0.728 | 10000 |
| mheidari-all | 0.606 | observe | 9 | 0.889 | 13955 |
| dragon3 | 0.481 | observe | 6 | 1.0 | 100 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| Surfboard-tg-mixed | 0.3 | observe | 5 | 0.4 | 8189 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5035 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10983 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 411 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 406 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 155 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 142 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.4 | 2 | 3 | 5 |
| dragon2 | 0.728 | 185 | 69 | 254 |
| mheidari-all | 0.889 | 8 | 1 | 9 |
| dragon | 0.953 | 122 | 6 | 128 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| dragon3 | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13955 | yes | 5.76 | 0 |
| SoliSpirit-all | 10983 | yes | 4.35 | 0 |
| dragon | 10000 | yes | 8.65 | 0 |
| dragon2 | 10000 | yes | 4.84 | 0 |
| Surfboard-tg-mixed | 8189 | yes | 4.13 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 5.19 | 0 |
| barry-far-vless | 6123 | yes | 2.74 | 0 |
| Surfboard-tg-vless | 5913 | yes | 4.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 5035 | yes | 2.97 | 0 |
| mahdibland-V2RayAggregator | 4597 | yes | 2.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 50 |
| cn-block | 13 |
| 204 | 13 |
| geo | 2 |
| speed | 1 |
