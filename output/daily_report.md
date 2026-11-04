# AutoNodes 每日报告

生成时间：2026-11-04 06:47:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 13/1 |
| 清理建议：优先/观察 | 1/93 |
| 原始节点数 | 92804 |
| 去重后节点数 | 33964 |
| TCP 可达数 | 3000 |
| 真测通过数 | 261 |
| verified 输出数 | 18 |
| global 输出数 | 264 |
| all 输出数 | 33964 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.8 |
| fetch | 4.8 |
| generate | 11.1 |
| geo | 1.4 |
| probe | 63.7 |
| real_test | 46.6 |
| tcp | 99.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 17 | 10 | 7 | 58.8% |
| shadowsocks | 203 | 195 | 8 | 96.1% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 53 | 46 | 7 | 86.8% |
| vless | 30 | 9 | 21 | 30.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 18 |
| 204:ProxyError | 8 |
| geo:ClientOSError | 8 |
| cn-block:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6341 |
| ConnectionRefusedError | 985 |
| OSError | 233 |
| gaierror | 177 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.982 | prefer | 262 | 0.905 | 10000 |
| Au1rxx-base64 | 0.67 | observe | 23 | 0.609 | 1751 |
| Surfboard-tg-mixed | 0.622 | observe | 15 | 0.667 | 8544 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5017 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10853 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6022 |
| barry-far-vless | 0.255 | observe | 0 | None | 6238 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 398 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 393 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 223 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 142 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 129 | 连续死亡次数 >= 2 |
| downweight | mheidari-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.2 | 1 | 4 | 5 |
| Au1rxx-base64 | 0.609 | 14 | 9 | 23 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.667 | 10 | 5 | 15 |
| dragon | 0.905 | 237 | 25 | 262 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15179 | yes | 3.45 | 0 |
| SoliSpirit-all | 10853 | yes | 2.34 | 0 |
| dragon | 10000 | yes | 4.45 | 0 |
| Surfboard-tg-mixed | 8544 | yes | 2.29 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.93 | 0 |
| barry-far-vless | 6238 | yes | 1.33 | 0 |
| Surfboard-tg-vless | 6022 | yes | 2.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 5017 | yes | 1.22 | 0 |
| mahdibland-V2RayAggregator | 4608 | yes | 0.82 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 18 |
| 204 | 11 |
| geo | 8 |
| cn-block | 6 |
| speed | 2 |
