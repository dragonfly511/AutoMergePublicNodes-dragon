# AutoNodes 每日报告

生成时间：2026-11-12 20:13:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 103598 |
| 去重后节点数 | 34704 |
| TCP 可达数 | 3000 |
| 真测通过数 | 228 |
| verified 输出数 | 14 |
| global 输出数 | 229 |
| all 输出数 | 34704 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.2 |
| fetch | 6.0 |
| generate | 10.5 |
| geo | 1.4 |
| probe | 69.0 |
| real_test | 41.3 |
| tcp | 84.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 198 | 180 | 18 | 90.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 61 | 30 | 31 | 49.2% |
| vless | 8 | 6 | 2 | 75.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 23 |
| test_one_timeout:15.0s | 15 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6347 |
| ConnectionRefusedError | 1028 |
| OSError | 364 |
| gaierror | 319 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.982 | prefer | 131 | 0.908 | 10000 |
| dragon | 0.792 | prefer | 123 | 0.715 | 10000 |
| dragon3 | 0.658 | observe | 14 | 0.857 | 100 |
| mheidari-all | 0.465 | observe | 7 | 0.714 | 14228 |
| Surfboard-tg-mixed | 0.373 | observe | 5 | 0.6 | 8770 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4998 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2737 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11515 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 5 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 419 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 414 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 163 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 150 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.6 | 3 | 2 | 5 |
| mheidari-all | 0.714 | 5 | 2 | 7 |
| dragon | 0.715 | 88 | 35 | 123 |
| dragon3 | 0.857 | 12 | 2 | 14 |
| dragon2 | 0.908 | 119 | 12 | 131 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14228 | yes | 3.94 | 0 |
| SoliSpirit-all | 11515 | yes | 2.31 | 0 |
| dragon | 10000 | yes | 5.17 | 0 |
| dragon2 | 10000 | yes | 3.4 | 0 |
| Surfboard-tg-mixed | 8770 | yes | 3.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.9 | 0 |
| barry-far-vless | 6555 | yes | 1.83 | 0 |
| Surfboard-tg-vless | 6332 | yes | 2.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 4998 | yes | 0.88 | 0 |
| mahdibland-V2RayAggregator | 4618 | yes | 1.41 | 0 |

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
| 204 | 28 |
| test_one_timeout | 15 |
| cn-block | 6 |
| speed | 3 |
| geo | 2 |
