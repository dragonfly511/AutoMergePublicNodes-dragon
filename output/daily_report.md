# AutoNodes 每日报告

生成时间：2026-11-24 10:11:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 99167 |
| 去重后节点数 | 34154 |
| TCP 可达数 | 3000 |
| 真测通过数 | 56 |
| verified 输出数 | 18 |
| global 输出数 | 269 |
| all 输出数 | 34154 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.7 |
| fetch | 7.5 |
| generate | 15.1 |
| geo | 1.7 |
| probe | 90.2 |
| real_test | 24.0 |
| tcp | 94.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 19 | 13 | 6 | 68.4% |
| socks | 12 | 12 | 0 | 100.0% |
| trojan | 52 | 30 | 22 | 57.7% |
| vless | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 18 |
| test_one_timeout:15.0s | 5 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7454 |
| ConnectionRefusedError | 1108 |
| OSError | 265 |
| gaierror | 176 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.7 | prefer | 77 | 0.623 | 10000 |
| Surfboard-tg-mixed | 0.593 | observe | 7 | 1.0 | 8220 |
| ermaozi | 0.567 | observe | 8 | 1.0 | 460 |
| mheidari-all | 0.391 | observe | 2 | 1.0 | 15386 |
| dragon2 | 0.335 | observe | 1 | 1.0 | 10000 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 167 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5064 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11363 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5327 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 443 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 438 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 321 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 187 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 174 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| dragon | 0.623 | 48 | 29 | 77 |
| dragon2 | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 2 | 0 | 2 |
| Surfboard-tg-mixed | 1.0 | 7 | 0 | 7 |
| ermaozi | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15386 | yes | 5.4 | 0 |
| SoliSpirit-all | 11363 | yes | 2.53 | 0 |
| dragon | 10000 | yes | 6.95 | 0 |
| dragon2 | 10000 | yes | 4.93 | 0 |
| Surfboard-tg-mixed | 8220 | yes | 3.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.11 | 0 |
| barry-far-vless | 5849 | yes | 0.83 | 0 |
| Surfboard-tg-vless | 5327 | yes | 2.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5064 | yes | 1.03 | 0 |
| mahdibland-V2RayAggregator | 4587 | yes | 1.53 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| real_ok_drop_50pct | real-test ok dropped from 265 to 56 |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 20 |
| test_one_timeout | 5 |
| cn-block | 3 |
| speed | 1 |
| geo | 1 |
