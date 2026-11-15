# AutoNodes 每日报告

生成时间：2026-11-15 19:03:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 19/1 |
| 清理建议：优先/观察 | 1/89 |
| 原始节点数 | 104609 |
| 去重后节点数 | 35094 |
| TCP 可达数 | 3000 |
| 真测通过数 | 119 |
| verified 输出数 | 12 |
| global 输出数 | 122 |
| all 输出数 | 35094 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.3 |
| fetch | 7.3 |
| generate | 13.5 |
| geo | 1.5 |
| probe | 81.8 |
| real_test | 32.9 |
| tcp | 93.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 110 | 90 | 20 | 81.8% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 42 | 10 | 32 | 23.8% |
| vless | 7 | 2 | 5 | 28.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 27 |
| test_one_timeout:15.0s | 15 |
| 204:ClientOSError | 6 |
| 204:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:TimeoutError | 1 |
| speed:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6832 |
| ConnectionRefusedError | 988 |
| OSError | 240 |
| gaierror | 166 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.747 | prefer | 154 | 0.669 | 10000 |
| mheidari-all | 0.629 | observe | 8 | 1.0 | 14826 |
| dragon2 | 0.519 | observe | 5 | 1.0 | 10000 |
| Surfboard-tg-mixed | 0.349 | observe | 3 | 0.667 | 9142 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4916 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11885 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6162 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 179 |
| ermaozi | 0.149 | observe | 1 | 0.0 | 0 | 544 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 426 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 421 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 170 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 157 | 连续死亡次数 >= 2 |
| downweight | dragon3 | 0.208 | 6 | 0.333 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.0 | 0 | 1 | 1 |
| dragon3 | 0.333 | 2 | 4 | 6 |
| Surfboard-tg-mixed | 0.667 | 2 | 1 | 3 |
| dragon | 0.669 | 103 | 51 | 154 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| dragon2 | 1.0 | 5 | 0 | 5 |
| mheidari-all | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14826 | yes | 3.23 | 0 |
| SoliSpirit-all | 11885 | yes | 2.29 | 0 |
| dragon | 10000 | yes | 6.27 | 0 |
| dragon2 | 10000 | yes | 4.15 | 0 |
| Surfboard-tg-mixed | 9142 | yes | 2.54 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.48 | 0 |
| barry-far-vless | 6310 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 6162 | yes | 3.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 4916 | yes | 1.4 | 0 |
| mahdibland-V2RayAggregator | 4584 | yes | 1.61 | 0 |

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
| 204 | 36 |
| test_one_timeout | 15 |
| cn-block | 5 |
| speed | 1 |
| geo | 1 |
