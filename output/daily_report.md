# AutoNodes 每日报告

生成时间：2026-11-20 20:39:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/110 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 3/89 |
| 原始节点数 | 102672 |
| 去重后节点数 | 35842 |
| TCP 可达数 | 3000 |
| 真测通过数 | 184 |
| verified 输出数 | 11 |
| global 输出数 | 185 |
| all 输出数 | 35842 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.5 |
| fetch | 8.9 |
| generate | 18.5 |
| geo | 1.6 |
| probe | 97.6 |
| real_test | 34.2 |
| tcp | 92.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 168 | 149 | 19 | 88.7% |
| socks | 15 | 12 | 3 | 80.0% |
| trojan | 32 | 10 | 22 | 31.2% |
| vless | 12 | 11 | 1 | 91.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 22 |
| test_one_timeout:15.0s | 12 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 2 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6576 |
| ConnectionRefusedError | 1047 |
| gaierror | 343 |
| OSError | 241 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.899 | prefer | 169 | 0.822 | 10000 |
| dragon3 | 0.897 | prefer | 26 | 0.923 | 100 |
| Surfboard-tg-mixed | 0.757 | prefer | 16 | 0.812 | 8704 |
| dragon2 | 0.689 | observe | 21 | 0.619 | 10000 |
| mheidari-all | 0.438 | observe | 3 | 1.0 | 14341 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5045 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.142 | observe | 1 | 0.0 | 0 | 369 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 436 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 431 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 314 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 180 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 167 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.333 | 1 | 2 | 3 |
| dragon2 | 0.619 | 13 | 8 | 21 |
| Surfboard-tg-mixed | 0.812 | 13 | 3 | 16 |
| dragon | 0.822 | 139 | 30 | 169 |
| dragon3 | 0.923 | 24 | 2 | 26 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| mheidari-all | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14341 | yes | 6.39 | 0 |
| SoliSpirit-all | 11804 | yes | 3.74 | 0 |
| dragon | 10000 | yes | 8.41 | 0 |
| dragon2 | 10000 | yes | 5.44 | 0 |
| Surfboard-tg-mixed | 8704 | yes | 3.55 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.45 | 0 |
| barry-far-vless | 5776 | yes | 2.02 | 0 |
| Surfboard-tg-vless | 5734 | yes | 4.34 | 0 |
| 10ium-ScrapeCategorize-Vless | 5045 | yes | 1.78 | 0 |
| mahdibland-V2RayAggregator | 4518 | yes | 2.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 28 |
| test_one_timeout | 12 |
| cn-block | 6 |
