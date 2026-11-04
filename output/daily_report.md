# AutoNodes 每日报告

生成时间：2026-11-04 20:00:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 1/94 |
| 原始节点数 | 92735 |
| 去重后节点数 | 34159 |
| TCP 可达数 | 3000 |
| 真测通过数 | 204 |
| verified 输出数 | 12 |
| global 输出数 | 208 |
| all 输出数 | 34159 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.8 |
| fetch | 17.2 |
| generate | 17.7 |
| geo | 1.7 |
| probe | 95.7 |
| real_test | 43.8 |
| tcp | 98.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 187 | 169 | 18 | 90.4% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 32 | 19 | 13 | 59.4% |
| vless | 15 | 5 | 10 | 33.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 26 |
| 204:ProxyError | 7 |
| 204:TimeoutError | 5 |
| cn-block:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6275 |
| ConnectionRefusedError | 1028 |
| OSError | 233 |
| gaierror | 182 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.933 | prefer | 216 | 0.856 | 10000 |
| Surfboard-tg-mixed | 0.609 | observe | 12 | 0.75 | 8707 |
| Au1rxx-base64 | 0.505 | observe | 16 | 0.5 | 1751 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi | 0.315 | observe | 2 | 1.0 | 83 |
| mheidari-all | 0.287 | observe | 2 | 0.5 | 15192 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10836 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.134 | observe | 1 | 0.0 | 0 | 174 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 399 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 394 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 219 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 143 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 130 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.5 | 8 | 8 | 16 |
| Surfboard-tg-mixed | 0.75 | 9 | 3 | 12 |
| dragon | 0.856 | 185 | 31 | 216 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15192 | yes | 4.47 | 0 |
| SoliSpirit-all | 10836 | yes | 3.19 | 0 |
| dragon | 10000 | yes | 6.74 | 0 |
| Surfboard-tg-mixed | 8707 | yes | 3.16 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.11 | 0 |
| barry-far-vless | 6348 | yes | 1.15 | 0 |
| Surfboard-tg-vless | 6137 | yes | 2.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.84 | 0 |
| mahdibland-V2RayAggregator | 4608 | yes | 1.86 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 26 |
| 204 | 12 |
| cn-block | 6 |
| speed | 1 |
