# AutoNodes 每日报告

生成时间：2026-10-31 17:22:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 1/94 |
| 原始节点数 | 91402 |
| 去重后节点数 | 33519 |
| TCP 可达数 | 3000 |
| 真测通过数 | 171 |
| verified 输出数 | 52 |
| global 输出数 | 171 |
| all 输出数 | 33519 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.0 |
| fetch | 9.0 |
| generate | 17.8 |
| geo | 1.5 |
| probe | 98.5 |
| real_test | 56.2 |
| tcp | 95.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 115 | 99 | 16 | 86.1% |
| trojan | 89 | 56 | 33 | 62.9% |
| vless | 30 | 6 | 24 | 20.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 53 |
| geo:ClientOSError | 12 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6252 |
| ConnectionRefusedError | 980 |
| OSError | 248 |
| gaierror | 151 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.902 | prefer | 172 | 0.826 | 10000 |
| Au1rxx-base64 | 0.493 | observe | 24 | 0.417 | 1751 |
| mheidari-all | 0.373 | observe | 5 | 0.6 | 14848 |
| peasoft-NoMoreWalls | 0.365 | observe | 26 | 0.346 | 206 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 6752 |
| tg-Farah_VPN | 0.319 | observe | 2 | 1.0 | 200 |
| Surfboard-tg-mixed | 0.281 | observe | 14 | 0.214 | 7984 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2848 |
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
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 178 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 498 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 389 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 384 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 133 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.214 | 3 | 11 | 14 |
| peasoft-NoMoreWalls | 0.346 | 9 | 17 | 26 |
| Au1rxx-base64 | 0.417 | 10 | 14 | 24 |
| mheidari-all | 0.6 | 3 | 2 | 5 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| dragon | 0.826 | 142 | 30 | 172 |
| tg-Farah_VPN | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14848 | yes | 5.07 | 0 |
| SoliSpirit-all | 10813 | yes | 3.27 | 0 |
| dragon | 10000 | yes | 8.09 | 0 |
| Surfboard-tg-mixed | 7984 | yes | 3.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.01 | 0 |
| barry-far-vless | 5990 | yes | 1.98 | 0 |
| Surfboard-tg-vless | 5777 | yes | 3.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 2.22 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 2.34 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.32 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 53 |
| geo | 12 |
| 204 | 9 |
| cn-block | 2 |
