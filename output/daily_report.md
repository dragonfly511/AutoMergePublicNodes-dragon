# AutoNodes 每日报告

生成时间：2026-11-02 06:34:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/93 |
| 原始节点数 | 92989 |
| 去重后节点数 | 34103 |
| TCP 可达数 | 3000 |
| 真测通过数 | 217 |
| verified 输出数 | 38 |
| global 输出数 | 219 |
| all 输出数 | 34103 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 50.7 |
| fetch | 9.1 |
| generate | 17.9 |
| geo | 1.5 |
| probe | 93.2 |
| real_test | 38.2 |
| tcp | 91.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 126 | 114 | 12 | 90.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 74 | 68 | 6 | 91.9% |
| vless | 27 | 18 | 9 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| geo:ClientOSError | 4 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| 204:TimeoutError | 2 |
| cn-block:ClientOSError | 2 |
| speed:ClientOSError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6297 |
| ConnectionRefusedError | 963 |
| OSError | 233 |
| gaierror | 122 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | prefer | 201 | 0.9 | 10000 |
| Au1rxx-base64 | 0.919 | prefer | 31 | 0.871 | 1751 |
| mheidari-all | 0.557 | observe | 6 | 1.0 | 15216 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| Surfboard-tg-mixed | 0.284 | observe | 6 | 0.333 | 8273 |
| ermaozi-get_subscribe | 0.277 | observe | 1 | 1.0 | 547 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3716 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10657 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 394 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 389 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 219 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 138 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 125 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.333 | 2 | 4 | 6 |
| Au1rxx-base64 | 0.871 | 27 | 4 | 31 |
| dragon | 0.9 | 181 | 20 | 201 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15216 | yes | 6.16 | 0 |
| SoliSpirit-all | 10657 | yes | 2.55 | 0 |
| dragon | 10000 | yes | 8.26 | 0 |
| Surfboard-tg-mixed | 8273 | yes | 4.58 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.37 | 0 |
| barry-far-vless | 6036 | yes | 1.65 | 0 |
| Surfboard-tg-vless | 5823 | yes | 3.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.94 | 0 |
| mahdibland-V2RayAggregator | 4726 | yes | 0.52 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.64 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| geo | 7 |
| 204 | 5 |
| cn-block | 4 |
| speed | 1 |
