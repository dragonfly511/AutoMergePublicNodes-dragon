# AutoNodes 每日报告

生成时间：2026-11-18 07:48:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 101649 |
| 去重后节点数 | 35043 |
| TCP 可达数 | 3000 |
| 真测通过数 | 205 |
| verified 输出数 | 27 |
| global 输出数 | 207 |
| all 输出数 | 35043 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.9 |
| fetch | 5.3 |
| generate | 11.9 |
| geo | 1.4 |
| probe | 71.2 |
| real_test | 39.4 |
| tcp | 96.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 172 | 152 | 20 | 88.4% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 1 | 0 | 1 | 0.0% |
| vless | 47 | 40 | 7 | 85.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 23 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6781 |
| ConnectionRefusedError | 961 |
| OSError | 238 |
| gaierror | 174 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.968 | prefer | 195 | 0.892 | 10000 |
| dragon2 | 0.804 | prefer | 27 | 0.741 | 10000 |
| tg-LonUp_M | 0.484 | observe | 6 | 1.0 | 166 |
| mheidari-all | 0.349 | observe | 3 | 0.667 | 14456 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| dragon3 | 0.315 | observe | 2 | 1.0 | 100 |
| ermaozi | 0.275 | observe | 1 | 1.0 | 502 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4928 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2790 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Surfboard-tg-mixed | 0.17 | observe | 3 | 0.0 | 0 | 8419 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 431 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 426 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 309 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 175 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 162 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.667 | 2 | 1 | 3 |
| dragon2 | 0.741 | 20 | 7 | 27 |
| dragon | 0.892 | 174 | 21 | 195 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| dragon3 | 1.0 | 2 | 0 | 2 |
| tg-LonUp_M | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14456 | yes | 3.49 | 0 |
| SoliSpirit-all | 11512 | yes | 2.61 | 0 |
| dragon | 10000 | yes | 4.54 | 0 |
| dragon2 | 10000 | yes | 2.96 | 0 |
| Surfboard-tg-mixed | 8419 | yes | 1.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.07 | 0 |
| barry-far-vless | 5907 | yes | 0.57 | 0 |
| Surfboard-tg-vless | 5726 | yes | 2.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 4928 | yes | 1.28 | 0 |
| mahdibland-V2RayAggregator | 4458 | yes | 1.54 | 0 |

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
| test_one_timeout | 23 |
| 204 | 6 |
| cn-block | 2 |
| geo | 1 |
