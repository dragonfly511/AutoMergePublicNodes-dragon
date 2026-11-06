# AutoNodes 每日报告

生成时间：2026-11-06 19:39:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 102663 |
| 去重后节点数 | 34652 |
| TCP 可达数 | 3000 |
| 真测通过数 | 312 |
| verified 输出数 | 14 |
| global 输出数 | 300 |
| all 输出数 | 34652 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 17.9 |
| fetch | 9.1 |
| generate | 18.1 |
| geo | 1.5 |
| probe | 96.5 |
| real_test | 66.8 |
| tcp | 89.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 207 | 192 | 15 | 92.8% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 3 | 0 | 3 | 0.0% |
| vless | 174 | 106 | 68 | 60.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 56 |
| 204:TimeoutError | 15 |
| 204:ProxyError | 6 |
| cn-block:TimeoutError | 5 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6743 |
| ConnectionRefusedError | 1097 |
| OSError | 234 |
| gaierror | 172 |
| ConnectionResetError | 2 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.845 | prefer | 339 | 0.767 | 10000 |
| dragon3 | 0.782 | prefer | 34 | 0.794 | 100 |
| dragon | 0.714 | prefer | 12 | 0.917 | 10000 |
| mheidari-all | 0.606 | observe | 9 | 0.889 | 14184 |
| Surfboard-tg-mixed | 0.519 | observe | 5 | 1.0 | 8758 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 179 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 405 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 400 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 149 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 136 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon2 | 0.767 | 260 | 79 | 339 |
| dragon3 | 0.794 | 27 | 7 | 34 |
| mheidari-all | 0.889 | 8 | 1 | 9 |
| dragon | 0.917 | 11 | 1 | 12 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| Surfboard-tg-mixed | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14184 | yes | 5.89 | 0 |
| SoliSpirit-all | 10962 | yes | 4.31 | 0 |
| dragon | 10000 | yes | 8.23 | 0 |
| dragon2 | 10000 | yes | 4.71 | 0 |
| Surfboard-tg-mixed | 8758 | yes | 3.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.93 | 0 |
| barry-far-vless | 6479 | yes | 1.79 | 0 |
| Surfboard-tg-vless | 6135 | yes | 3.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4703 | yes | 2.68 | 0 |

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
| test_one_timeout | 56 |
| 204 | 22 |
| cn-block | 7 |
| speed | 3 |
