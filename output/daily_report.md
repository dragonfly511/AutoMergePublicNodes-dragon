# AutoNodes 每日报告

生成时间：2026-11-08 06:25:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 3/89 |
| 原始节点数 | 101613 |
| 去重后节点数 | 34872 |
| TCP 可达数 | 3000 |
| 真测通过数 | 135 |
| verified 输出数 | 12 |
| global 输出数 | 135 |
| all 输出数 | 34872 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.8 |
| fetch | 7.9 |
| generate | 15.3 |
| geo | 1.7 |
| probe | 87.9 |
| real_test | 21.8 |
| tcp | 90.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 0 | 2 | 0.0% |
| hysteria2 | 16 | 11 | 5 | 68.8% |
| shadowsocks | 54 | 51 | 3 | 94.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 74 | 68 | 6 | 91.9% |
| vless | 6 | 4 | 2 | 66.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| geo:ClientOSError | 2 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 1 |
| speed:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6853 |
| ConnectionRefusedError | 1047 |
| OSError | 238 |
| gaierror | 149 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.983 | prefer | 29 | 0.931 | 10000 |
| dragon | 0.958 | prefer | 88 | 0.886 | 10000 |
| dragon3 | 0.924 | prefer | 23 | 0.957 | 100 |
| mheidari-all | 0.53 | observe | 10 | 0.7 | 14505 |
| Surfboard-tg-mixed | 0.287 | observe | 2 | 0.5 | 8112 |
| xiaoji235-airport-v2ray-all | 0.259 | observe | 3 | 0.333 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4866 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10963 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi | 0.152 | observe | 1 | 0.0 | 0 | 613 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 409 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 404 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 153 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 140 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.7 | 7 | 3 | 10 |
| dragon | 0.886 | 78 | 10 | 88 |
| dragon2 | 0.931 | 27 | 2 | 29 |
| dragon3 | 0.957 | 22 | 1 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14505 | yes | 5.3 | 0 |
| SoliSpirit-all | 10963 | yes | 3.71 | 0 |
| dragon | 10000 | yes | 7.29 | 0 |
| dragon2 | 10000 | yes | 4.83 | 0 |
| Surfboard-tg-mixed | 8112 | yes | 3.17 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.26 | 0 |
| barry-far-vless | 6061 | yes | 1.31 | 0 |
| Surfboard-tg-vless | 5849 | yes | 3.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 4866 | yes | 1.5 | 0 |
| mahdibland-V2RayAggregator | 4529 | yes | 2.33 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 3 |
| geo | 3 |
| speed | 1 |
