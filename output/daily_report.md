# AutoNodes 每日报告

生成时间：2026-11-26 08:42:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/110 |
| 清理建议：禁用/降权 | 19/1 |
| 清理建议：优先/观察 | 1/89 |
| 原始节点数 | 98680 |
| 去重后节点数 | 33229 |
| TCP 可达数 | 3000 |
| 真测通过数 | 219 |
| verified 输出数 | 15 |
| global 输出数 | 223 |
| all 输出数 | 33229 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.8 |
| fetch | 5.8 |
| generate | 10.6 |
| geo | 1.0 |
| probe | 68.7 |
| real_test | 44.0 |
| tcp | 78.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 2 | 3 | 40.0% |
| hysteria2 | 6 | 6 | 0 | 100.0% |
| shadowsocks | 221 | 198 | 23 | 89.6% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 15 | 10 | 5 | 66.7% |
| vless | 3 | 2 | 1 | 66.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 17 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 3 |
| 204:TimeoutError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6631 |
| ConnectionRefusedError | 1099 |
| OSError | 378 |
| gaierror | 339 |
| ConnectionResetError | 1 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.971 | prefer | 228 | 0.895 | 10000 |
| Surfboard-tg-mixed | 0.529 | observe | 7 | 0.857 | 8442 |
| dragon2 | 0.465 | observe | 7 | 0.714 | 9795 |
| dragon3 | 0.413 | observe | 9 | 0.667 | 100 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14817 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11584 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5447 |
| barry-far-vless | 0.255 | observe | 0 | None | 5694 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 447 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 442 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 325 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 191 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 178 | 连续死亡次数 >= 2 |
| downweight | ermaozi-get_subscribe | 0.234 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| ermaozi | 0.5 | 1 | 1 | 2 |
| dragon3 | 0.667 | 6 | 3 | 9 |
| dragon2 | 0.714 | 5 | 2 | 7 |
| Surfboard-tg-mixed | 0.857 | 6 | 1 | 7 |
| dragon | 0.895 | 204 | 24 | 228 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14817 | yes | 3.87 | 0 |
| SoliSpirit-all | 11584 | yes | 2.06 | 0 |
| dragon | 10000 | yes | 5.07 | 0 |
| dragon2 | 9795 | yes | 3.52 | 0 |
| Surfboard-tg-mixed | 8442 | yes | 2.41 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.36 | 0 |
| barry-far-vless | 5694 | yes | 0.79 | 0 |
| Surfboard-tg-vless | 5447 | yes | 2.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 0.93 | 0 |
| mahdibland-V2RayAggregator | 4485 | yes | 1.77 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 17 |
| 204 | 8 |
| cn-block | 6 |
| speed | 3 |
