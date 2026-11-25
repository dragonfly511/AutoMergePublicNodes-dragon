# AutoNodes 每日报告

生成时间：2026-11-25 08:57:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/91 |
| 原始节点数 | 98234 |
| 去重后节点数 | 34174 |
| TCP 可达数 | 3000 |
| 真测通过数 | 219 |
| verified 输出数 | 14 |
| global 输出数 | 224 |
| all 输出数 | 34174 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.5 |
| fetch | 5.3 |
| generate | 11.4 |
| geo | 1.4 |
| probe | 69.9 |
| real_test | 41.8 |
| tcp | 86.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 204 | 183 | 21 | 89.7% |
| socks | 14 | 11 | 3 | 78.6% |
| trojan | 35 | 18 | 17 | 51.4% |
| vless | 13 | 6 | 7 | 46.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 19 |
| test_one_timeout:15.0s | 16 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| speed:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7065 |
| ConnectionRefusedError | 1107 |
| OSError | 262 |
| gaierror | 227 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.926 | prefer | 245 | 0.849 | 10000 |
| ermaozi | 0.584 | observe | 13 | 0.769 | 442 |
| Surfboard-tg-mixed | 0.474 | observe | 10 | 0.6 | 8136 |
| dragon2 | 0.373 | observe | 5 | 0.6 | 9831 |
| ermaozi-get_subscribe | 0.326 | observe | 2 | 1.0 | 376 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11514 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5440 |
| barry-far-vless | 0.255 | observe | 0 | None | 5649 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| dragon3 | 0.164 | observe | 4 | 0.25 | 0 | 100 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 445 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 440 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 323 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 189 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 176 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon3 | 0.25 | 1 | 3 | 4 |
| dragon2 | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.6 | 6 | 4 | 10 |
| ermaozi | 0.769 | 10 | 3 | 13 |
| dragon | 0.849 | 208 | 37 | 245 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14996 | yes | 3.37 | 0 |
| SoliSpirit-all | 11514 | yes | 2.58 | 0 |
| dragon | 10000 | yes | 4.41 | 0 |
| dragon2 | 9831 | yes | 2.82 | 0 |
| Surfboard-tg-mixed | 8136 | yes | 1.79 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.6 | 0 |
| barry-far-vless | 5649 | yes | 1.88 | 0 |
| Surfboard-tg-vless | 5440 | yes | 2.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4463 | yes | 0.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 23 |
| test_one_timeout | 16 |
| cn-block | 6 |
| speed | 2 |
| geo | 2 |
