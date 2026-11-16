# AutoNodes 每日报告

生成时间：2026-11-16 06:56:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 103090 |
| 去重后节点数 | 34686 |
| TCP 可达数 | 3000 |
| 真测通过数 | 228 |
| verified 输出数 | 12 |
| global 输出数 | 229 |
| all 输出数 | 34686 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.7 |
| fetch | 9.3 |
| generate | 18.1 |
| geo | 1.7 |
| probe | 100.2 |
| real_test | 35.7 |
| tcp | 97.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 18 | 13 | 5 | 72.2% |
| shadowsocks | 195 | 183 | 12 | 93.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 1 | 1 | 0 | 100.0% |
| vless | 38 | 29 | 9 | 76.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 17 |
| 204:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| 204:ProxyError | 2 |
| geo:ClientOSError | 1 |
| speed:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6707 |
| ConnectionRefusedError | 957 |
| OSError | 237 |
| gaierror | 184 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.973 | prefer | 241 | 0.896 | 10000 |
| mheidari-all | 0.438 | observe | 3 | 1.0 | 14209 |
| mahdibland-V2RayAggregator | 0.391 | observe | 2 | 1.0 | 4545 |
| tg-LonUp_M | 0.365 | observe | 3 | 1.0 | 164 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| dragon3 | 0.315 | observe | 2 | 1.0 | 100 |
| dragon2 | 0.287 | observe | 2 | 0.5 | 10000 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4916 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2960 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 3 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 427 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 422 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 305 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 171 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 158 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 2 | 2 |
| dragon2 | 0.5 | 1 | 1 | 2 |
| dragon | 0.896 | 216 | 25 | 241 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| dragon3 | 1.0 | 2 | 0 | 2 |
| mahdibland-V2RayAggregator | 1.0 | 2 | 0 | 2 |
| tg-LonUp_M | 1.0 | 3 | 0 | 3 |
| mheidari-all | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14209 | yes | 6.64 | 0 |
| SoliSpirit-all | 11553 | yes | 5.2 | 0 |
| dragon | 10000 | yes | 8.68 | 0 |
| dragon2 | 10000 | yes | 5.71 | 0 |
| Surfboard-tg-mixed | 8824 | yes | 1.18 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.82 | 0 |
| barry-far-vless | 6294 | yes | 0.76 | 0 |
| Surfboard-tg-vless | 6113 | yes | 4.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4916 | yes | 3.06 | 0 |
| mahdibland-V2RayAggregator | 4545 | yes | 2.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 17 |
| 204 | 7 |
| geo | 2 |
| speed | 1 |
| cn-block | 1 |
