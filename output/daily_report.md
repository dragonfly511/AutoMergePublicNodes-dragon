# AutoNodes 每日报告

生成时间：2026-11-08 13:46:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 3/89 |
| 原始节点数 | 101940 |
| 去重后节点数 | 34837 |
| TCP 可达数 | 3000 |
| 真测通过数 | 252 |
| verified 输出数 | 14 |
| global 输出数 | 253 |
| all 输出数 | 34837 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.2 |
| fetch | 9.0 |
| generate | 17.6 |
| geo | 1.5 |
| probe | 91.1 |
| real_test | 46.4 |
| tcp | 87.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 15 | 11 | 4 | 73.3% |
| shadowsocks | 211 | 190 | 21 | 90.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 68 | 47 | 21 | 69.1% |
| vless | 3 | 3 | 0 | 100.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 22 |
| 204:ProxyError | 8 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6601 |
| ConnectionRefusedError | 1052 |
| OSError | 238 |
| gaierror | 181 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon3 | 0.978 | prefer | 37 | 1.0 | 100 |
| dragon2 | 0.94 | prefer | 177 | 0.864 | 10000 |
| dragon | 0.804 | prefer | 74 | 0.73 | 10000 |
| mheidari-all | 0.547 | observe | 9 | 0.778 | 14420 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5035 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10990 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5786 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 410 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 405 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 154 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 141 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 2 | 2 |
| dragon | 0.73 | 54 | 20 | 74 |
| mheidari-all | 0.778 | 7 | 2 | 9 |
| dragon2 | 0.864 | 153 | 24 | 177 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| dragon3 | 1.0 | 37 | 0 | 37 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14420 | yes | 6.38 | 0 |
| SoliSpirit-all | 10990 | yes | 2.61 | 0 |
| dragon | 10000 | yes | 8.24 | 0 |
| dragon2 | 10000 | yes | 4.1 | 0 |
| Surfboard-tg-mixed | 8136 | yes | 3.74 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.32 | 0 |
| barry-far-vless | 5999 | yes | 1.76 | 0 |
| Surfboard-tg-vless | 5786 | yes | 3.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5035 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 2.67 | 0 |

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
| test_one_timeout | 22 |
| 204 | 17 |
| cn-block | 4 |
| geo | 3 |
| speed | 2 |
