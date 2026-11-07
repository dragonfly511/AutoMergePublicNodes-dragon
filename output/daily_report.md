# AutoNodes 每日报告

生成时间：2026-11-07 06:20:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 101936 |
| 去重后节点数 | 33986 |
| TCP 可达数 | 3000 |
| 真测通过数 | 289 |
| verified 输出数 | 20 |
| global 输出数 | 293 |
| all 输出数 | 33986 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.9 |
| fetch | 9.2 |
| generate | 18.0 |
| geo | 1.5 |
| probe | 96.3 |
| real_test | 65.3 |
| tcp | 91.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 203 | 194 | 9 | 95.6% |
| socks | 2 | 1 | 1 | 50.0% |
| vless | 140 | 82 | 58 | 58.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 46 |
| 204:ProxyError | 7 |
| cn-block:TimeoutError | 6 |
| 204:TimeoutError | 3 |
| geo:ProxyError | 2 |
| geo:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6451 |
| ConnectionRefusedError | 1038 |
| OSError | 233 |
| gaierror | 180 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 124 | 0.944 | 10000 |
| dragon2 | 0.798 | prefer | 214 | 0.72 | 10000 |
| mheidari-all | 0.606 | observe | 9 | 0.889 | 13634 |
| dragon3 | 0.553 | observe | 8 | 1.0 | 100 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8637 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4934 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2768 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| roosterkid-openproxylist-v2ray | 0.133 | observe | 1 | 0.0 | 0 | 150 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 406 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 401 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 150 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 137 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| dragon2 | 0.72 | 154 | 60 | 214 |
| mheidari-all | 0.889 | 8 | 1 | 9 |
| dragon | 0.944 | 117 | 7 | 124 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| dragon3 | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13634 | yes | 5.02 | 0 |
| SoliSpirit-all | 11015 | yes | 4.3 | 0 |
| dragon | 10000 | yes | 8.5 | 0 |
| dragon2 | 10000 | yes | 5.34 | 0 |
| Surfboard-tg-mixed | 8637 | yes | 3.67 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.03 | 0 |
| barry-far-vless | 6359 | yes | 1.94 | 0 |
| Surfboard-tg-vless | 6148 | yes | 3.9 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 2.16 | 0 |
| mahdibland-V2RayAggregator | 4540 | yes | 3.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 46 |
| 204 | 11 |
| cn-block | 7 |
| geo | 3 |
| speed | 2 |
