# AutoNodes 每日报告

生成时间：2026-11-26 21:49:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/110 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 98761 |
| 去重后节点数 | 33324 |
| TCP 可达数 | 3000 |
| 真测通过数 | 254 |
| verified 输出数 | 17 |
| global 输出数 | 256 |
| all 输出数 | 33324 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.2 |
| fetch | 6.4 |
| generate | 13.0 |
| geo | 1.5 |
| probe | 80.9 |
| real_test | 45.5 |
| tcp | 84.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 210 | 187 | 23 | 89.0% |
| socks | 8 | 7 | 1 | 87.5% |
| trojan | 60 | 54 | 6 | 90.0% |
| vless | 2 | 2 | 0 | 100.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7087 |
| ConnectionRefusedError | 1030 |
| gaierror | 245 |
| OSError | 241 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | prefer | 251 | 0.9 | 10000 |
| dragon2 | 0.873 | prefer | 27 | 0.815 | 9840 |
| Surfboard-tg-mixed | 0.519 | observe | 5 | 1.0 | 8568 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14669 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 168 |
| ermaozi-get_subscribe | 0.281 | observe | 3 | 0.667 | 314 |
| peasoft-NoMoreWalls | 0.26 | observe | 1 | 1.0 | 133 |
| dragon3 | 0.259 | observe | 1 | 1.0 | 100 |
| tg-proxy_mtm | 0.258 | observe | 1 | 1.0 | 67 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4936 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi | 0.143 | observe | 1 | 0.0 | 0 | 393 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 448 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 443 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 326 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 192 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 179 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| dragon2 | 0.815 | 22 | 5 | 27 |
| dragon | 0.9 | 226 | 25 | 251 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |
| dragon3 | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| tg-proxy_mtm | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| Surfboard-tg-mixed | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14669 | yes | 4.47 | 0 |
| SoliSpirit-all | 11794 | yes | 1.26 | 0 |
| dragon | 10000 | yes | 5.82 | 0 |
| dragon2 | 9840 | yes | 4.05 | 0 |
| Surfboard-tg-mixed | 8568 | yes | 3.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| barry-far-vless | 5607 | yes | 1.82 | 0 |
| Surfboard-tg-vless | 5426 | yes | 2.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 4936 | yes | 0.81 | 0 |
| mahdibland-V2RayAggregator | 4485 | yes | 2.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 7 |
| cn-block | 3 |
| speed | 3 |
