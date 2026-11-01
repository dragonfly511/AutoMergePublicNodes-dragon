# AutoNodes 每日报告

生成时间：2026-11-01 18:04:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/108 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/93 |
| 原始节点数 | 92878 |
| 去重后节点数 | 33661 |
| TCP 可达数 | 3000 |
| 真测通过数 | 62 |
| verified 输出数 | 38 |
| global 输出数 | 136 |
| all 输出数 | 33661 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.5 |
| fetch | 9.0 |
| generate | 17.2 |
| geo | 1.5 |
| probe | 97.8 |
| real_test | 37.9 |
| tcp | 91.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 12 | 10 | 2 | 83.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 42 | 26 | 16 | 61.9% |
| vless | 17 | 14 | 3 | 82.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 14 |
| 204:ProxyError | 5 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 2 |
| geo:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6405 |
| ConnectionRefusedError | 955 |
| OSError | 236 |
| gaierror | 124 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.896 | prefer | 21 | 0.857 | 1751 |
| dragon | 0.775 | prefer | 57 | 0.702 | 10000 |
| mheidari-all | 0.421 | observe | 6 | 0.667 | 15458 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3716 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10659 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5773 |
| barry-far-vless | 0.255 | observe | 0 | None | 5873 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4680 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.134 | observe | 1 | 0.0 | 0 | 171 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 392 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 387 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 212 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 136 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 123 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.667 | 4 | 2 | 6 |
| dragon | 0.702 | 40 | 17 | 57 |
| Au1rxx-base64 | 0.857 | 18 | 3 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15458 | yes | 5.65 | 0 |
| SoliSpirit-all | 10659 | yes | 3.02 | 0 |
| dragon | 10000 | yes | 8.11 | 0 |
| Surfboard-tg-mixed | 8239 | yes | 3.87 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.07 | 0 |
| barry-far-vless | 5873 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5773 | yes | 3.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 4680 | yes | 3.15 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.08 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| real_ok_drop_50pct | real-test ok dropped from 134 to 62 |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 14 |
| 204 | 5 |
| cn-block | 3 |
| speed | 2 |
| geo | 1 |
