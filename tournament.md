                          Metric |       Operation |   Baseline |   Contender |               Diff |   Unit |
|--------------------------------:|----------------:|-----------:|------------:|-------------------:|-------:|
|                   Indexing time |                 |  0.0522667 |      0.0112 |    -0.04107 |    min |
|                      Merge time |                 |   0.172733 |    0.799367 |    +0.62663 |    min |
|                    Refresh time |                 |  0.0706167 |    0.108083 |    +0.03747 |    min |
|                      Flush time |                 |          0 |           0 |     0.00000 |    min |
|             Merge throttle time |                 |          0 |     0.00045 |    +0.00045 |    min |
|              Total Young Gen GC |                 |     14.336 |      14.867 |    +0.53100 |      s |
|                Total Old Gen GC |                 |      1.649 |       1.614 |    -0.03500 |      s |
|          Heap used for segments |                 |    6.87584 |     6.75315 |    -0.12269 |     MB |
|        Heap used for doc values |                 |    1.42245 |     1.32712 |    -0.09534 |     MB |
|             Heap used for terms |                 |    4.75538 |     4.70088 |    -0.05450 |     MB |
|             Heap used for norms |                 |   0.147522 |    0.146912 |    -0.00061 |     MB |
|            Heap used for points |                 |   0.253709 |    0.254189 |    +0.00048 |     MB |
|            Heap used for points |                 |   0.297775 |    0.301247 |    +0.00347 |     MB |
|                   Segment count |                 |        320 |         314 |    -6.00000 |        |
|                  Min Throughput |           index |    1552.37 |     1660.73 |  +108.36804 | docs/s |
|               Median Throughput |           index |    1677.54 |     1699.01 |   +21.47589 | docs/s |
|                  Max Throughput |           index |    1873.74 |     1726.32 |  -147.42407 | docs/s |
|       50.0th percentile latency |           index |    17351.7 |     16534.1 |  -817.59961 |     ms |
|      100.0th percentile latency |           index |    21042.9 |       20006 | -1036.97461 |     ms |
|  50.0th percentile service time |           index |    17351.7 |     16534.1 |  -817.59961 |     ms |
| 100.0th percentile service time |           index |    21042.9 |       20006 | -1036.97461 |     ms |
|                  Min Throughput |     force-merge |    1.67537 |     2.06841 |    +0.39304 |  ops/s |
|               Median Throughput |     force-merge |    1.91348 |     2.18762 |    +0.27414 |  ops/s |
|                  Max Throughput |     force-merge |    2.79385 |     2.76959 |    -0.02427 |  ops/s |
|       50.0th percentile latency |     force-merge |    522.599 |      457.11 |   -65.48907 |     ms |
|      100.0th percentile latency |     force-merge |    596.873 |     483.451 |  -113.42194 |     ms |
|  50.0th percentile service time |     force-merge |    522.599 |      457.11 |   -65.48907 |     ms |
| 100.0th percentile service time |     force-merge |    596.873 |     483.451 |  -113.42194 |     ms |
|                  Min Throughput |     index-stats |     60.812 |     49.4823 |   -11.32969 |  ops/s |
|               Median Throughput |     index-stats |    63.6633 |     61.1113 |    -2.55200 |  ops/s |
|                  Max Throughput |     index-stats |    64.6051 |     64.1932 |    -0.41190 |  ops/s |
|       50.0th percentile latency |     index-stats |    5742.58 |     6809.36 | +1066.77665 |     ms |
|       90.0th percentile latency |     index-stats |     8214.4 |     12259.2 | +4044.75080 |     ms |
|       99.0th percentile latency |     index-stats |    9052.36 |     14613.3 | +5560.96978 |     ms |
|       99.9th percentile latency |     index-stats |    9177.89 |     14885.6 | +5707.72744 |     ms |
|      100.0th percentile latency |     index-stats |    9201.68 |     14908.1 | +5706.37598 |     ms |
|  50.0th percentile service time |     index-stats |    14.4028 |      15.123 |    +0.72018 |     ms |
|  90.0th percentile service time |     index-stats |    18.2337 |     22.0342 |    +3.80052 |     ms |
|  99.0th percentile service time |     index-stats |    42.1432 |     48.5215 |    +6.37829 |     ms |
|  99.9th percentile service time |     index-stats |    99.4275 |     110.677 |   +11.24964 |     ms |
| 100.0th percentile service time |     index-stats |    140.221 |     239.695 |   +99.47441 |     ms |
|                  Min Throughput |      node-stats |     70.389 |     63.4415 |    -6.94748 |  ops/s |
|               Median Throughput |      node-stats |    74.4991 |     76.3615 |    +1.86233 |  ops/s |
|                  Max Throughput |      node-stats |    78.9274 |     80.1314 |    +1.20401 |  ops/s |
|       50.0th percentile latency |      node-stats |    2128.61 |     2064.46 |   -64.14292 |     ms |
|       90.0th percentile latency |      node-stats |    3527.52 |     3315.58 |  -211.93968 |     ms |
|       99.0th percentile latency |      node-stats |    3952.58 |     4590.05 |  +637.46552 |     ms |
|       99.9th percentile latency |      node-stats |    4031.13 |     4690.96 |  +659.82826 |     ms |
|      100.0th percentile latency |      node-stats |    4041.19 |     4699.05 |  +657.86377 |     ms |
|  50.0th percentile service time |      node-stats |    12.3378 |     12.4163 |    +0.07848 |     ms |
|  90.0th percentile service time |      node-stats |    15.5411 |     15.4179 |    -0.12325 |     ms |
|  99.0th percentile service time |      node-stats |    31.4009 |     27.3277 |    -4.07322 |     ms |
|  99.9th percentile service time |      node-stats |    57.9381 |     44.5717 |   -13.36640 |     ms |
| 100.0th percentile service time |      node-stats |    73.1888 |      62.608 |   -10.58080 |     ms |
|                  Min Throughput | query-match-all |     105.26 |     104.668 |    -0.59253 |  ops/s |
|               Median Throughput | query-match-all |     105.31 |     105.408 |    +0.09805 |  ops/s |
|                  Max Throughput | query-match-all |    105.332 |     105.625 |    +0.29318 |  ops/s |
|       50.0th percentile latency | query-match-all |    22.6184 |     22.3914 |    -0.22694 |     ms |
|       90.0th percentile latency | query-match-all |     28.321 |     29.4253 |    +1.10434 |     ms |
|       99.0th percentile latency | query-match-all |    35.6207 |     40.7305 |    +5.10985 |     ms |
|      100.0th percentile latency | query-match-all |    41.1029 |     47.3379 |    +6.23499 |     ms |
|  50.0th percentile service time | query-match-all |     19.003 |     18.4503 |    -0.55267 |     ms |
|  90.0th percentile service time | query-match-all |    25.0022 |     25.6538 |    +0.65164 |     ms |
|  99.0th percentile service time | query-match-all |    31.1712 |     36.5285 |    +5.35729 |     ms |
| 100.0th percentile service time | query-match-all |     37.304 |     42.6747 |    +5.37073 |     ms |
|                  Min Throughput |      query-gary |    96.7361 |     102.954 |    +6.21811 |  ops/s |
|               Median Throughput |      query-gary |    105.499 |     105.231 |    -0.26840 |  ops/s |
|                  Max Throughput |      query-gary |    105.554 |     105.332 |    -0.22137 |  ops/s |
|       50.0th percentile latency |      query-gary |    25.7871 |     26.1446 |    +0.35747 |     ms |
|       90.0th percentile latency |      query-gary |    39.1572 |     39.1929 |    +0.03566 |     ms |
|       99.0th percentile latency |      query-gary |    50.5077 |     65.7265 |   +15.21882 |     ms |
|      100.0th percentile latency |      query-gary |    54.2874 |     69.2602 |   +14.97276 |     ms |
|  50.0th percentile service time |      query-gary |    22.0365 |     22.5468 |    +0.51030 |     ms |
|  90.0th percentile service time |      query-gary |    35.1811 |     35.0575 |    -0.12360 |     ms |
|  99.0th percentile service time |      query-gary |    47.2291 |     62.0939 |   +14.86476 |     ms |
| 100.0th percentile service time |      query-gary |    51.5827 |     64.6806 |   +13.09795 |     ms |