# AutoNodes 每日报告

生成时间：2026-11-25 21:56:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/1 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 98445 |
| 去重后节点数 | 34215 |
| TCP 可达数 | 3000 |
| 真测通过数 | 244 |
| verified 输出数 | 14 |
| global 输出数 | 249 |
| all 输出数 | 34215 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.0 |
| fetch | 7.0 |
| generate | 14.0 |
| geo | 1.6 |
| probe | 84.0 |
| real_test | 48.2 |
| tcp | 82.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 3 | 2 | 60.0% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 215 | 197 | 18 | 91.6% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 49 | 32 | 17 | 65.3% |
| vless | 8 | 3 | 5 | 37.5% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 5 |
| speed:ProxyError | 4 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6608 |
| ConnectionRefusedError | 1154 |
| gaierror | 354 |
| OSError | 267 |
| ConnectionResetError | 2 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.95 | prefer | 274 | 0.872 | 10000 |
| tg-LonUp_M | 0.416 | observe | 6 | 0.833 | 173 |
| dragon2 | 0.349 | observe | 3 | 0.667 | 9790 |
| ermaozi-get_subscribe | 0.307 | observe | 5 | 0.6 | 356 |
| ermaozi | 0.271 | observe | 1 | 1.0 | 403 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11598 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5378 |
| barry-far-vless | 0.255 | observe | 0 | None | 5559 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| dragon3 | 0.077 | downweight | 5 | 0.0 | 0 | 100 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 446 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 441 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 324 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 190 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 177 | 连续死亡次数 >= 2 |
| downweight | dragon3 | 0.077 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| dragon3 | 0.0 | 0 | 5 | 5 |
| ermaozi-get_subscribe | 0.6 | 3 | 2 | 5 |
| dragon2 | 0.667 | 2 | 1 | 3 |
| tg-LonUp_M | 0.833 | 5 | 1 | 6 |
| dragon | 0.872 | 239 | 35 | 274 |
| ermaozi | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15044 | yes | 4.05 | 0 |
| SoliSpirit-all | 11598 | yes | 1.64 | 0 |
| dragon | 10000 | yes | 6.53 | 0 |
| dragon2 | 9790 | yes | 3.25 | 0 |
| Surfboard-tg-mixed | 8209 | yes | 3.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.73 | 0 |
| barry-far-vless | 5559 | yes | 0.64 | 0 |
| Surfboard-tg-vless | 5378 | yes | 2.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4463 | yes | 2.05 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 16 |
| cn-block | 6 |
| speed | 4 |
