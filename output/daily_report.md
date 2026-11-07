# AutoNodes 每日报告

生成时间：2026-11-07 22:07:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 101697 |
| 去重后节点数 | 34659 |
| TCP 可达数 | 3000 |
| 真测通过数 | 44 |
| verified 输出数 | 12 |
| global 输出数 | 174 |
| all 输出数 | 34659 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.1 |
| fetch | 9.0 |
| generate | 17.9 |
| geo | 1.6 |
| probe | 94.6 |
| real_test | 18.1 |
| tcp | 84.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 18 | 16 | 2 | 88.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 3 | 3 | 0 | 100.0% |
| vless | 18 | 11 | 7 | 61.1% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6465 |
| ConnectionRefusedError | 1062 |
| OSError | 238 |
| gaierror | 195 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.83 | prefer | 22 | 0.773 | 10000 |
| dragon3 | 0.731 | prefer | 20 | 0.75 | 100 |
| mheidari-all | 0.606 | observe | 9 | 0.889 | 14235 |
| dragon2 | 0.4 | observe | 4 | 0.75 | 10000 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4866 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11058 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5923 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 408 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 403 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 152 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 139 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| dragon2 | 0.75 | 3 | 1 | 4 |
| dragon3 | 0.75 | 15 | 5 | 20 |
| dragon | 0.773 | 17 | 5 | 22 |
| mheidari-all | 0.889 | 8 | 1 | 9 |
| xiaoji235-airport-v2ray-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14235 | yes | 6.42 | 0 |
| SoliSpirit-all | 11058 | yes | 3.16 | 0 |
| dragon | 10000 | yes | 8.33 | 0 |
| dragon2 | 10000 | yes | 3.85 | 0 |
| Surfboard-tg-mixed | 8421 | yes | 4.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.79 | 0 |
| barry-far-vless | 6134 | yes | 1.47 | 0 |
| Surfboard-tg-vless | 5923 | yes | 3.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 4866 | yes | 1.96 | 0 |
| mahdibland-V2RayAggregator | 4529 | yes | 1.63 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| real_ok_drop_50pct | real-test ok dropped from 171 to 44 |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 9 |
| 204 | 3 |
| geo | 1 |
