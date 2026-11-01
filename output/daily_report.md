# AutoNodes 每日报告

生成时间：2026-11-01 22:17:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/93 |
| 原始节点数 | 92899 |
| 去重后节点数 | 34033 |
| TCP 可达数 | 3000 |
| 真测通过数 | 111 |
| verified 输出数 | 38 |
| global 输出数 | 116 |
| all 输出数 | 34033 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 20.6 |
| fetch | 8.5 |
| generate | 16.6 |
| geo | 1.6 |
| probe | 96.0 |
| real_test | 47.3 |
| tcp | 89.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 16 | 16 | 0 | 100.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 9 | 9 | 0 | 100.0% |
| vless | 101 | 66 | 35 | 65.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 23 |
| cn-block:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| speed:ClientOSError | 2 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6081 |
| ConnectionRefusedError | 974 |
| OSError | 237 |
| gaierror | 203 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.825 | prefer | 49 | 0.755 | 10000 |
| Au1rxx-base64 | 0.781 | prefer | 81 | 0.716 | 1751 |
| Surfboard-tg-mixed | 0.568 | observe | 8 | 0.875 | 8273 |
| mheidari-all | 0.568 | observe | 8 | 0.875 | 15206 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 3716 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10614 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5823 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 393 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 388 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 137 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 124 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.716 | 58 | 23 | 81 |
| dragon | 0.755 | 37 | 12 | 49 |
| mheidari-all | 0.875 | 7 | 1 | 8 |
| Surfboard-tg-mixed | 0.875 | 7 | 1 | 8 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15206 | yes | 5.34 | 0 |
| SoliSpirit-all | 10614 | yes | 2.83 | 0 |
| dragon | 10000 | yes | 7.39 | 0 |
| Surfboard-tg-mixed | 8273 | yes | 3.98 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.01 | 0 |
| barry-far-vless | 5986 | yes | 0.7 | 0 |
| Surfboard-tg-vless | 5823 | yes | 4.16 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 0.51 | 0 |
| mahdibland-V2RayAggregator | 4800 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.84 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 23 |
| cn-block | 6 |
| 204 | 4 |
| geo | 2 |
| speed | 2 |
