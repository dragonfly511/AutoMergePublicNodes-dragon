# AutoNodes 每日报告

生成时间：2026-11-16 22:25:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 103358 |
| 去重后节点数 | 35002 |
| TCP 可达数 | 3000 |
| 真测通过数 | 229 |
| verified 输出数 | 19 |
| global 输出数 | 230 |
| all 输出数 | 35002 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.9 |
| fetch | 5.8 |
| generate | 11.1 |
| geo | 1.4 |
| probe | 76.4 |
| real_test | 31.9 |
| tcp | 71.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 192 | 181 | 11 | 94.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 1 | 1 | 0 | 100.0% |
| vless | 41 | 34 | 7 | 82.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 14 |
| 204:TimeoutError | 3 |
| 204:ProxyError | 1 |
| 204:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5421 |
| ConnectionRefusedError | 1081 |
| gaierror | 469 |
| OSError | 376 |
| SSRFBlocked | 5 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.995 | prefer | 232 | 0.918 | 10000 |
| mheidari-all | 0.557 | observe | 6 | 1.0 | 14735 |
| dragon3 | 0.404 | observe | 4 | 1.0 | 100 |
| dragon2 | 0.391 | observe | 2 | 1.0 | 10000 |
| Surfboard-tg-vless | 0.335 | observe | 1 | 1.0 | 6010 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi | 0.333 | observe | 2 | 1.0 | 548 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 170 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4964 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2915 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 428 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 423 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 306 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 172 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 159 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| dragon | 0.918 | 213 | 19 | 232 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-vless | 1.0 | 1 | 0 | 1 |
| dragon2 | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 2 | 0 | 2 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| dragon3 | 1.0 | 4 | 0 | 4 |
| mheidari-all | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14735 | yes | 3.98 | 0 |
| SoliSpirit-all | 11743 | yes | 3.26 | 0 |
| dragon | 10000 | yes | 5.34 | 0 |
| dragon2 | 10000 | yes | 3.39 | 0 |
| Surfboard-tg-mixed | 8691 | yes | 2.05 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.23 | 0 |
| barry-far-vless | 6209 | yes | 1.39 | 0 |
| Surfboard-tg-vless | 6010 | yes | 2.23 | 0 |
| 10ium-ScrapeCategorize-Vless | 4964 | yes | 2.06 | 0 |
| mahdibland-V2RayAggregator | 4545 | yes | 0.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 14 |
| 204 | 5 |
| cn-block | 1 |
