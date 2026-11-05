# AutoNodes 每日报告

生成时间：2026-11-05 20:11:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 1/94 |
| 原始节点数 | 92601 |
| 去重后节点数 | 34217 |
| TCP 可达数 | 3000 |
| 真测通过数 | 150 |
| verified 输出数 | 11 |
| global 输出数 | 151 |
| all 输出数 | 34217 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 20.7 |
| fetch | 5.3 |
| generate | 11.1 |
| geo | 1.4 |
| probe | 72.4 |
| real_test | 40.8 |
| tcp | 93.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 102 | 94 | 8 | 92.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 57 | 36 | 21 | 63.2% |
| vless | 18 | 8 | 10 | 44.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 18 |
| test_one_timeout:15.0s | 12 |
| geo:ProxyError | 3 |
| cn-block:TimeoutError | 3 |
| speed:ProxyError | 2 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6695 |
| ConnectionRefusedError | 1038 |
| OSError | 233 |
| gaierror | 110 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.89 | prefer | 156 | 0.814 | 10000 |
| Au1rxx-base64 | 0.635 | observe | 21 | 0.571 | 1751 |
| mheidari-all | 0.529 | observe | 7 | 0.857 | 14461 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| Surfboard-tg-mixed | 0.32 | observe | 4 | 0.5 | 8690 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 177 |
| peasoft-NoMoreWalls | 0.259 | observe | 1 | 1.0 | 96 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5039 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 401 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 396 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 221 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 145 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 132 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.5 | 2 | 2 | 4 |
| Au1rxx-base64 | 0.571 | 12 | 9 | 21 |
| dragon | 0.814 | 127 | 29 | 156 |
| mheidari-all | 0.857 | 6 | 1 | 7 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14461 | yes | 1.94 | 0 |
| SoliSpirit-all | 10977 | yes | 3.23 | 0 |
| dragon | 10000 | yes | 4.23 | 0 |
| Surfboard-tg-mixed | 8690 | yes | 3.07 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.52 | 0 |
| barry-far-vless | 6358 | yes | 0.75 | 0 |
| Surfboard-tg-vless | 6065 | yes | 2.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5039 | yes | 1.1 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 1.65 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 21 |
| test_one_timeout | 12 |
| cn-block | 4 |
| geo | 3 |
| speed | 2 |
