# AutoNodes 每日报告

生成时间：2026-10-30 02:19:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 3/91 |
| 原始节点数 | 109310 |
| 去重后节点数 | 35026 |
| TCP 可达数 | 3000 |
| 真测通过数 | 232 |
| verified 输出数 | 49 |
| global 输出数 | 235 |
| all 输出数 | 35026 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.1 |
| fetch | 7.9 |
| generate | 15.3 |
| geo | 1.6 |
| probe | 88.1 |
| real_test | 43.6 |
| tcp | 101.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 21 | 20 | 1 | 95.2% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 151 | 141 | 10 | 93.4% |
| trojan | 41 | 37 | 4 | 90.2% |
| vless | 32 | 16 | 16 | 50.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 18 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 3 |
| geo:ClientOSError | 3 |
| 204:ClientOSError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7435 |
| ConnectionRefusedError | 1126 |
| OSError | 238 |
| gaierror | 166 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 193 | 0.927 | 10000 |
| ermaozi | 0.934 | prefer | 21 | 0.952 | 515 |
| Au1rxx-base64 | 0.735 | prefer | 28 | 0.679 | 1706 |
| mheidari-all | 0.57 | observe | 11 | 0.727 | 33573 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 6752 |
| Surfboard-tg-mixed | 0.352 | observe | 6 | 0.5 | 7758 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 497 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 388 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 383 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 132 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.5 | 3 | 3 | 6 |
| Au1rxx-base64 | 0.679 | 19 | 9 | 28 |
| mheidari-all | 0.727 | 8 | 3 | 11 |
| dragon | 0.927 | 179 | 14 | 193 |
| ermaozi | 0.952 | 20 | 1 | 21 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 33573 | yes | 5.72 | 0 |
| SoliSpirit-all | 10432 | yes | 2.26 | 0 |
| dragon | 10000 | yes | 7.44 | 0 |
| Surfboard-tg-mixed | 7758 | yes | 3.16 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 6001 | yes | 0.48 | 0 |
| Surfboard-tg-vless | 5789 | yes | 3.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 2.56 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.97 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 131 to 49 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 18 |
| cn-block | 5 |
| 204 | 4 |
| geo | 3 |
| speed | 1 |
