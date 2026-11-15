# AutoNodes 每日报告

生成时间：2026-11-15 06:53:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 103236 |
| 去重后节点数 | 34528 |
| TCP 可达数 | 3000 |
| 真测通过数 | 177 |
| verified 输出数 | 13 |
| global 输出数 | 177 |
| all 输出数 | 34528 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 17.6 |
| fetch | 5.8 |
| generate | 10.6 |
| geo | 1.4 |
| probe | 65.0 |
| real_test | 23.7 |
| tcp | 72.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 1 | 3 | 25.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 114 | 110 | 4 | 96.5% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 55 | 45 | 10 | 81.8% |
| vless | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 10 |
| test_one_timeout:15.0s | 7 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5619 |
| ConnectionRefusedError | 1062 |
| gaierror | 443 |
| OSError | 370 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.991 | prefer | 167 | 0.916 | 10000 |
| mheidari-all | 0.664 | observe | 9 | 1.0 | 13787 |
| dragon2 | 0.557 | observe | 6 | 1.0 | 10000 |
| dragon3 | 0.453 | observe | 7 | 0.857 | 100 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 9013 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4966 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi | 0.127 | observe | 2 | 0.0 | 0 | 576 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 425 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 420 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 169 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 156 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| dragon3 | 0.857 | 6 | 1 | 7 |
| dragon | 0.916 | 153 | 14 | 167 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| dragon2 | 1.0 | 6 | 0 | 6 |
| mheidari-all | 1.0 | 9 | 0 | 9 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13787 | yes | 3.75 | 0 |
| SoliSpirit-all | 11652 | yes | 1.23 | 0 |
| dragon | 10000 | yes | 5.22 | 0 |
| dragon2 | 10000 | yes | 3.96 | 0 |
| Surfboard-tg-mixed | 9013 | yes | 2.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.95 | 0 |
| barry-far-vless | 6500 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 6319 | yes | 2.29 | 0 |
| 10ium-ScrapeCategorize-Vless | 4966 | yes | 0.98 | 0 |
| mahdibland-V2RayAggregator | 4584 | yes | 1.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 11 |
| test_one_timeout | 7 |
