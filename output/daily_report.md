# AutoNodes 每日报告

生成时间：2026-11-06 18:53:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 102664 |
| 去重后节点数 | 34625 |
| TCP 可达数 | 3000 |
| 真测通过数 | 311 |
| verified 输出数 | 13 |
| global 输出数 | 300 |
| all 输出数 | 34625 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.0 |
| fetch | 8.7 |
| generate | 16.9 |
| geo | 1.6 |
| probe | 96.6 |
| real_test | 67.7 |
| tcp | 89.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 208 | 195 | 13 | 93.8% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 7 | 2 | 5 | 28.6% |
| vless | 165 | 102 | 63 | 61.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 57 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 8 |
| cn-block:TimeoutError | 5 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6661 |
| ConnectionRefusedError | 1099 |
| OSError | 233 |
| gaierror | 194 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon3 | 0.975 | prefer | 32 | 1.0 | 100 |
| dragon2 | 0.843 | prefer | 336 | 0.765 | 10000 |
| dragon | 0.72 | prefer | 15 | 0.8 | 10000 |
| mheidari-all | 0.507 | observe | 8 | 0.75 | 14184 |
| Surfboard-tg-mixed | 0.489 | observe | 6 | 0.833 | 8758 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4934 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2768 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 404 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 399 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 148 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 135 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.75 | 6 | 2 | 8 |
| dragon2 | 0.765 | 257 | 79 | 336 |
| dragon | 0.8 | 12 | 3 | 15 |
| Surfboard-tg-mixed | 0.833 | 5 | 1 | 6 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |
| dragon3 | 1.0 | 32 | 0 | 32 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14184 | yes | 3.91 | 0 |
| SoliSpirit-all | 10962 | yes | 3.65 | 0 |
| dragon | 10000 | yes | 7.84 | 0 |
| dragon2 | 10000 | yes | 4.81 | 0 |
| Surfboard-tg-mixed | 8758 | yes | 4.14 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.19 | 0 |
| barry-far-vless | 6479 | yes | 2.1 | 0 |
| Surfboard-tg-vless | 6135 | yes | 3.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 4703 | yes | 2.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 57 |
| 204 | 20 |
| cn-block | 5 |
| geo | 2 |
| speed | 1 |
