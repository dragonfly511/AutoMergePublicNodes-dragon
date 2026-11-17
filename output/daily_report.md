# AutoNodes 每日报告

生成时间：2026-11-17 08:13:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 103324 |
| 去重后节点数 | 35081 |
| TCP 可达数 | 3000 |
| 真测通过数 | 201 |
| verified 输出数 | 15 |
| global 输出数 | 204 |
| all 输出数 | 35081 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 20.5 |
| fetch | 5.9 |
| generate | 11.3 |
| geo | 1.4 |
| probe | 70.1 |
| real_test | 34.5 |
| tcp | 69.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 175 | 163 | 12 | 93.1% |
| socks | 5 | 5 | 0 | 100.0% |
| trojan | 1 | 0 | 1 | 0.0% |
| vless | 44 | 24 | 20 | 54.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 24 |
| 204:ProxyError | 3 |
| cn-block:TimeoutError | 3 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |
| geo:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5478 |
| ConnectionRefusedError | 1028 |
| gaierror | 450 |
| OSError | 376 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.916 | prefer | 211 | 0.839 | 10000 |
| dragon3 | 0.623 | observe | 10 | 1.0 | 100 |
| ermaozi | 0.538 | observe | 7 | 1.0 | 621 |
| mheidari-all | 0.446 | observe | 5 | 0.8 | 14792 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8623 |
| Surfboard-tg-vless | 0.335 | observe | 1 | 1.0 | 6028 |
| dragon2 | 0.335 | observe | 1 | 1.0 | 10000 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 169 |
| Pawdroid | 0.255 | observe | 1 | 1.0 | 12 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.146 | observe | 1 | 0.0 | 0 | 457 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 429 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 424 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 307 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 173 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 160 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.8 | 4 | 1 | 5 |
| dragon | 0.839 | 177 | 34 | 211 |
| Pawdroid | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-vless | 1.0 | 1 | 0 | 1 |
| dragon2 | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 7 | 0 | 7 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14792 | yes | 4.12 | 0 |
| SoliSpirit-all | 11532 | yes | 2.44 | 0 |
| dragon | 10000 | yes | 5.38 | 0 |
| dragon2 | 10000 | yes | 2.87 | 0 |
| Surfboard-tg-mixed | 8623 | yes | 2.25 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.6 | 0 |
| barry-far-vless | 6053 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 6028 | yes | 2.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4964 | yes | 1.23 | 0 |
| mahdibland-V2RayAggregator | 4545 | yes | 1.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |
| trojan | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 24 |
| 204 | 6 |
| cn-block | 5 |
| geo | 1 |
