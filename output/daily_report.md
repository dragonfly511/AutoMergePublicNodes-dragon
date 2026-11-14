# AutoNodes 每日报告

生成时间：2026-11-14 06:49:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 103939 |
| 去重后节点数 | 34517 |
| TCP 可达数 | 3000 |
| 真测通过数 | 82 |
| verified 输出数 | 15 |
| global 输出数 | 246 |
| all 输出数 | 34517 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 54.0 |
| fetch | 5.1 |
| generate | 10.7 |
| geo | 1.4 |
| probe | 67.8 |
| real_test | 39.9 |
| tcp | 92.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| hysteria2 | 15 | 12 | 3 | 80.0% |
| shadowsocks | 53 | 49 | 4 | 92.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 3 | 2 | 1 | 66.7% |
| vless | 38 | 17 | 21 | 44.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 14 |
| speed:ClientOSError | 8 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| 204:ProxyError | 1 |
| cn-block:TimeoutError | 1 |
| 204:TimeoutError | 1 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6824 |
| ConnectionRefusedError | 961 |
| OSError | 235 |
| gaierror | 185 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon2 | 0.958 | prefer | 39 | 0.897 | 10000 |
| dragon | 0.734 | prefer | 50 | 0.66 | 10000 |
| dragon3 | 0.536 | observe | 16 | 0.625 | 100 |
| ermaozi | 0.335 | observe | 2 | 1.0 | 597 |
| mheidari-all | 0.287 | observe | 2 | 0.5 | 14251 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 471 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4900 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 422 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 417 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 166 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 153 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.5 | 1 | 1 | 2 |
| dragon3 | 0.625 | 10 | 6 | 16 |
| dragon | 0.66 | 33 | 17 | 50 |
| dragon2 | 0.897 | 35 | 4 | 39 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14251 | yes | 3.09 | 0 |
| SoliSpirit-all | 11507 | yes | 2.34 | 0 |
| dragon | 10000 | yes | 4.85 | 0 |
| dragon2 | 10000 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 8942 | yes | 2.66 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.34 | 0 |
| barry-far-vless | 6640 | yes | 1.59 | 0 |
| Surfboard-tg-vless | 6457 | yes | 1.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 4900 | yes | 0.87 | 0 |
| mahdibland-V2RayAggregator | 4551 | yes | 1.24 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| real_ok_drop_50pct | real-test ok dropped from 245 to 82 |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 14 |
| speed | 8 |
| 204 | 3 |
| cn-block | 3 |
| geo | 2 |
