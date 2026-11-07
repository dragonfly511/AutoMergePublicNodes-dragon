# AutoNodes 每日报告

生成时间：2026-11-07 13:24:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 102406 |
| 去重后节点数 | 34580 |
| TCP 可达数 | 3000 |
| 真测通过数 | 171 |
| verified 输出数 | 12 |
| global 输出数 | 174 |
| all 输出数 | 34580 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.3 |
| fetch | 9.3 |
| generate | 17.7 |
| geo | 1.6 |
| probe | 93.8 |
| real_test | 39.5 |
| tcp | 96.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 131 | 124 | 7 | 94.7% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 4 | 1 | 3 | 25.0% |
| vless | 41 | 31 | 10 | 75.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 15 |
| 204:TimeoutError | 3 |
| cn-block:TimeoutError | 3 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6690 |
| ConnectionRefusedError | 1035 |
| OSError | 234 |
| gaierror | 146 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.964 | prefer | 162 | 0.889 | 10000 |
| dragon2 | 0.629 | observe | 8 | 1.0 | 10000 |
| dragon3 | 0.548 | observe | 11 | 0.818 | 100 |
| mheidari-all | 0.507 | observe | 8 | 0.75 | 14331 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 6752 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8637 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4866 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 407 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 402 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 151 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 138 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.75 | 6 | 2 | 8 |
| dragon3 | 0.818 | 9 | 2 | 11 |
| dragon | 0.889 | 144 | 18 | 162 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| dragon2 | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14331 | yes | 6.44 | 0 |
| SoliSpirit-all | 11009 | yes | 3.17 | 0 |
| dragon | 10000 | yes | 8.45 | 0 |
| dragon2 | 10000 | yes | 5.53 | 0 |
| Surfboard-tg-mixed | 8637 | yes | 4.65 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.93 | 0 |
| barry-far-vless | 6359 | yes | 1.38 | 0 |
| Surfboard-tg-vless | 6148 | yes | 3.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4866 | yes | 1.68 | 0 |
| mahdibland-V2RayAggregator | 4522 | yes | 1.82 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 15 |
| 204 | 4 |
| cn-block | 4 |
