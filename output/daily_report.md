# AutoNodes 每日报告

生成时间：2026-11-09 06:58:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 101134 |
| 去重后节点数 | 34075 |
| TCP 可达数 | 3000 |
| 真测通过数 | 170 |
| verified 输出数 | 13 |
| global 输出数 | 170 |
| all 输出数 | 34075 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.8 |
| fetch | 5.0 |
| generate | 10.2 |
| geo | 1.4 |
| probe | 65.1 |
| real_test | 23.4 |
| tcp | 91.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 137 | 130 | 7 | 94.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 31 | 28 | 3 | 90.3% |
| vless | 1 | 1 | 0 | 100.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6543 |
| ConnectionRefusedError | 1000 |
| OSError | 238 |
| gaierror | 173 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 152 | 0.961 | 10000 |
| dragon2 | 0.734 | prefer | 18 | 0.722 | 10000 |
| mheidari-all | 0.48 | observe | 4 | 1.0 | 13820 |
| dragon3 | 0.443 | observe | 5 | 1.0 | 100 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5035 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10927 |

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
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 412 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 407 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 156 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 143 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| dragon2 | 0.722 | 13 | 5 | 18 |
| dragon | 0.961 | 146 | 6 | 152 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 4 | 0 | 4 |
| dragon3 | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 13820 | yes | 2.09 | 0 |
| SoliSpirit-all | 10927 | yes | 1.04 | 0 |
| dragon | 10000 | yes | 3.77 | 0 |
| dragon2 | 10000 | yes | 2.24 | 0 |
| Surfboard-tg-mixed | 8133 | yes | 1.82 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.86 | 0 |
| barry-far-vless | 6048 | yes | 1.16 | 0 |
| Surfboard-tg-vless | 5838 | yes | 1.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 5035 | yes | 1.39 | 0 |
| mahdibland-V2RayAggregator | 4583 | yes | 1.48 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 27 to 13 |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 2 |
