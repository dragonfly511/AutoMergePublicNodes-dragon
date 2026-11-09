# AutoNodes 每日报告

生成时间：2026-11-09 22:37:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 101701 |
| 去重后节点数 | 34165 |
| TCP 可达数 | 3000 |
| 真测通过数 | 162 |
| verified 输出数 | 10 |
| global 输出数 | 163 |
| all 输出数 | 34165 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.1 |
| fetch | 9.1 |
| generate | 18.2 |
| geo | 1.6 |
| probe | 91.6 |
| real_test | 40.8 |
| tcp | 92.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 153 | 139 | 14 | 90.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 14 | 11 | 3 | 78.6% |
| vless | 5 | 1 | 4 | 20.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 15 |
| speed:ClientOSError | 2 |
| cn-block:TimeoutError | 2 |
| cn-block:ClientOSError | 1 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6619 |
| ConnectionRefusedError | 1024 |
| OSError | 238 |
| gaierror | 127 |
| ConnectionResetError | 2 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.993 | prefer | 136 | 0.919 | 10000 |
| dragon2 | 0.896 | prefer | 36 | 0.833 | 10000 |
| mheidari-all | 0.465 | observe | 7 | 0.714 | 14061 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| dragon3 | 0.259 | observe | 1 | 1.0 | 100 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2754 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11213 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6133 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Surfboard-tg-mixed | 0.16 | observe | 4 | 0.0 | 0 | 8250 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 413 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 408 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 157 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 144 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.714 | 5 | 2 | 7 |
| dragon2 | 0.833 | 30 | 6 | 36 |
| dragon | 0.919 | 125 | 11 | 136 |
| dragon3 | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14061 | yes | 5.99 | 0 |
| SoliSpirit-all | 11213 | yes | 4.24 | 0 |
| dragon | 10000 | yes | 8.4 | 0 |
| dragon2 | 10000 | yes | 4.49 | 0 |
| Surfboard-tg-mixed | 8250 | yes | 4.75 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.44 | 0 |
| Surfboard-tg-vless | 6133 | yes | 3.53 | 0 |
| barry-far-vless | 6103 | yes | 1.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.77 | 0 |
| mahdibland-V2RayAggregator | 4583 | yes | 2.3 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 15 |
| cn-block | 3 |
| 204 | 2 |
| speed | 2 |
| geo | 1 |
