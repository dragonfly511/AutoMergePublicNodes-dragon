# AutoNodes 每日报告

生成时间：2026-11-21 19:34:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 103359 |
| 去重后节点数 | 35301 |
| TCP 可达数 | 3000 |
| 真测通过数 | 75 |
| verified 输出数 | 5 |
| global 输出数 | 76 |
| all 输出数 | 35301 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.6 |
| fetch | 6.6 |
| generate | 13.4 |
| geo | 1.6 |
| probe | 79.0 |
| real_test | 22.2 |
| tcp | 101.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| hysteria2 | 14 | 11 | 3 | 78.6% |
| shadowsocks | 18 | 15 | 3 | 83.3% |
| socks | 10 | 9 | 1 | 90.0% |
| vless | 55 | 48 | 7 | 87.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 8 |
| 204:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| 204:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7135 |
| ConnectionRefusedError | 1056 |
| gaierror | 301 |
| OSError | 238 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.937 | prefer | 61 | 0.869 | 10000 |
| dragon3 | 0.638 | observe | 12 | 0.917 | 100 |
| Surfboard-tg-mixed | 0.606 | observe | 9 | 0.889 | 8779 |
| dragon2 | 0.446 | observe | 5 | 0.8 | 10000 |
| mheidari-all | 0.421 | observe | 6 | 0.667 | 14536 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi | 0.327 | observe | 2 | 1.0 | 403 |
| ermaozi-get_subscribe | 0.267 | observe | 1 | 1.0 | 303 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5030 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2989 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 176 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 438 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 433 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 316 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 182 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 169 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.667 | 4 | 2 | 6 |
| dragon2 | 0.8 | 4 | 1 | 5 |
| dragon | 0.869 | 53 | 8 | 61 |
| Surfboard-tg-mixed | 0.889 | 8 | 1 | 9 |
| dragon3 | 0.917 | 11 | 1 | 12 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14536 | yes | 4.2 | 0 |
| SoliSpirit-all | 12097 | yes | 3.03 | 0 |
| dragon | 10000 | yes | 5.82 | 0 |
| dragon2 | 10000 | yes | 2.77 | 0 |
| Surfboard-tg-mixed | 8779 | yes | 2.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.01 | 0 |
| barry-far-vless | 5966 | yes | 1.39 | 0 |
| Surfboard-tg-vless | 5784 | yes | 3.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 5030 | yes | 1.54 | 0 |
| mahdibland-V2RayAggregator | 4482 | yes | 1.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 8 |
| 204 | 4 |
| cn-block | 2 |
