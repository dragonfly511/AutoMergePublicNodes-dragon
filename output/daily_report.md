# AutoNodes 每日报告

生成时间：2026-11-12 07:32:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 103786 |
| 去重后节点数 | 34510 |
| TCP 可达数 | 3000 |
| 真测通过数 | 293 |
| verified 输出数 | 12 |
| global 输出数 | 295 |
| all 输出数 | 34510 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.2 |
| fetch | 9.5 |
| generate | 19.1 |
| geo | 1.7 |
| probe | 95.0 |
| real_test | 50.3 |
| tcp | 90.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 217 | 197 | 20 | 90.8% |
| trojan | 93 | 80 | 13 | 86.0% |
| vless | 8 | 3 | 5 | 37.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 9 |
| cn-block:ProxyError | 4 |
| speed:ClientOSError | 3 |
| 204:TimeoutError | 3 |
| 204:ClientOSError | 3 |
| cn-block:TimeoutError | 2 |
| speed:TimeoutError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6843 |
| ConnectionRefusedError | 994 |
| OSError | 248 |
| gaierror | 131 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.962 | prefer | 167 | 0.886 | 10000 |
| dragon2 | 0.96 | prefer | 148 | 0.885 | 10000 |
| mheidari-all | 0.557 | observe | 6 | 1.0 | 14005 |
| dragon3 | 0.398 | observe | 10 | 0.6 | 100 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 167 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4981 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2629 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11526 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 418 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 413 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 162 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 149 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon3 | 0.6 | 6 | 4 | 10 |
| dragon2 | 0.885 | 131 | 17 | 148 |
| dragon | 0.886 | 148 | 19 | 167 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14005 | yes | 6.33 | 0 |
| SoliSpirit-all | 11526 | yes | 3.55 | 0 |
| dragon | 10000 | yes | 8.99 | 0 |
| dragon2 | 10000 | yes | 3.83 | 0 |
| Surfboard-tg-mixed | 8783 | yes | 5.76 | 0 |
| barry-far-vless | 6775 | yes | 0.9 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.96 | 0 |
| Surfboard-tg-vless | 6596 | yes | 4.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4981 | yes | 2.25 | 0 |
| mahdibland-V2RayAggregator | 4595 | yes | 3.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 15 |
| test_one_timeout | 13 |
| cn-block | 6 |
| speed | 5 |
| geo | 1 |
