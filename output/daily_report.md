# AutoNodes 每日报告

生成时间：2026-11-13 07:03:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/1 |
| 清理建议：优先/观察 | 1/89 |
| 原始节点数 | 102720 |
| 去重后节点数 | 34275 |
| TCP 可达数 | 3000 |
| 真测通过数 | 315 |
| verified 输出数 | 20 |
| global 输出数 | 300 |
| all 输出数 | 34275 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.1 |
| fetch | 7.5 |
| generate | 14.8 |
| geo | 1.6 |
| probe | 89.7 |
| real_test | 63.4 |
| tcp | 88.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 222 | 204 | 18 | 91.9% |
| trojan | 2 | 0 | 2 | 0.0% |
| vless | 181 | 99 | 82 | 54.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 44 |
| speed:ClientOSError | 28 |
| 204:ProxyError | 9 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:TimeoutError | 4 |
| geo:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:TimeoutError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6123 |
| ConnectionRefusedError | 1019 |
| gaierror | 300 |
| OSError | 257 |
| SSRFBlocked | 3 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.976 | prefer | 248 | 0.899 | 10000 |
| dragon2 | 0.615 | observe | 157 | 0.535 | 10000 |
| mheidari-all | 0.446 | observe | 5 | 0.8 | 13793 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8675 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4998 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2737 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11327 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6119 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 420 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 415 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 164 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 151 | 连续死亡次数 >= 2 |
| downweight | dragon3 | 0.196 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon3 | 0.286 | 2 | 5 | 7 |
| dragon2 | 0.535 | 84 | 73 | 157 |
| mheidari-all | 0.8 | 4 | 1 | 5 |
| dragon | 0.899 | 223 | 25 | 248 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13793 | yes | 5.01 | 0 |
| SoliSpirit-all | 11327 | yes | 4.68 | 0 |
| dragon | 10000 | yes | 7.07 | 0 |
| dragon2 | 10000 | yes | 4.59 | 0 |
| Surfboard-tg-mixed | 8675 | yes | 3.33 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.83 | 0 |
| barry-far-vless | 6543 | yes | 0.94 | 0 |
| Surfboard-tg-vless | 6119 | yes | 2.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 4998 | yes | 1.93 | 0 |
| mahdibland-V2RayAggregator | 4624 | yes | 2.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 44 |
| speed | 30 |
| 204 | 18 |
| cn-block | 6 |
| geo | 6 |
