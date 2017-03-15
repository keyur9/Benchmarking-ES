|                          Metric |             Operation |   Baseline |   Contender |     Diff |   Unit |
|--------------------------------:|----------------------:|-----------:|------------:|---------:|-------:|
|                   Indexing time |                       | -0.0489833 |     1.44825 |  1.49723 |    min |
|                      Merge time |                       | -0.0783167 |    0.840617 |  0.91893 |    min |
|                    Refresh time |                       |  0.0427833 |    0.750083 |   0.7073 |    min |
|                      Flush time |                       |          0 |   0.0149333 |  0.01493 |    min |
|             Merge throttle time |                       |          0 |           0 |        0 |    min |
|              Total Young Gen GC |                       |     25.486 |      41.068 |   15.582 |      s |
|                Total Old Gen GC |                       |      8.478 |      11.363 |    2.885 |      s |
|          Heap used for segments |                       |    9.20783 |     9.47482 |  0.26699 |     MB |
|        Heap used for doc values |                       |    1.68724 |     1.78688 |  0.09964 |     MB |
|             Heap used for terms |                       |    6.65354 |     6.80069 |  0.14716 |     MB |
|             Heap used for norms |                       |   0.209473 |    0.221436 |  0.01196 |     MB |
|            Heap used for points |                       |   0.281197 |    0.282434 |  0.00124 |     MB |
|     Heap used for stored fields |                       |   0.376381 |    0.383377 |    0.007 |     MB |
|                   Segment count |                       |        419 |         448 |       29 |        |
|                  Min Throughput |                 index |     527.51 |     162.714 | -364.796 | docs/s |
|               Median Throughput |                 index |    1855.06 |      967.71 | -887.352 | docs/s |
|                  Max Throughput |                 index |    2551.67 |     1407.17 |  -1144.5 | docs/s |
|       50.0th percentile latency |                 index |    10641.9 |     19820.9 |  9178.93 |     ms |
|       90.0th percentile latency |                 index |    46041.2 |     94415.3 |    48374 |     ms |
|      100.0th percentile latency |                 index |    77439.3 |      168107 |    90668 |     ms |
|  50.0th percentile service time |                 index |    10641.9 |     19820.9 |  9178.93 |     ms |
|  90.0th percentile service time |                 index |    46041.2 |     94415.3 |    48374 |     ms |
| 100.0th percentile service time |                 index |    77439.3 |      168107 |    90668 |     ms |
|                      error rate |                 index |          0 |     1.13636 |  1.13636 |      % |
|                  Min Throughput |           force-merge |   0.256027 |    0.224791 | -0.03124 |  ops/s |
|               Median Throughput |           force-merge |   0.988183 |     5.73445 |  4.74627 |  ops/s |
|                  Max Throughput |           force-merge |    8.58311 |     10.1443 |  1.56117 |  ops/s |
|       50.0th percentile latency |           force-merge |    8.64068 |     15.1276 |  6.48692 |     ms |
|       90.0th percentile latency |           force-merge |    44.6694 |     69.7526 |  25.0832 |     ms |
|       99.0th percentile latency |           force-merge |    293.753 |     533.995 |  240.243 |     ms |
|      100.0th percentile latency |           force-merge |    3905.78 |     4448.51 |  542.728 |     ms |
|  50.0th percentile service time |           force-merge |    8.64068 |     15.1276 |  6.48692 |     ms |
|  90.0th percentile service time |           force-merge |    44.6694 |     69.7526 |  25.0832 |     ms |
|  99.0th percentile service time |           force-merge |    293.753 |     533.995 |  240.243 |     ms |
| 100.0th percentile service time |           force-merge |    3905.78 |     4448.51 |  542.728 |     ms |
|                      error rate |           force-merge |          0 |           0 |        0 |      % |
|                  Min Throughput |           index-stats |    6.67009 |     1.55554 | -5.11455 |  ops/s |
|               Median Throughput |           index-stats |    13.7778 |     11.4685 | -2.30924 |  ops/s |
|                  Max Throughput |           index-stats |    15.8681 |     13.3272 | -2.54084 |  ops/s |
|       50.0th percentile latency |           index-stats |       3239 |      3528.7 |  289.703 |     ms |
|       90.0th percentile latency |           index-stats |    5610.18 |     7068.07 |   1457.9 |     ms |
|       99.0th percentile latency |           index-stats |    6054.55 |     7602.68 |  1548.12 |     ms |
|      100.0th percentile latency |           index-stats |    6180.81 |     7652.04 |  1471.23 |     ms |
|  50.0th percentile service time |           index-stats |    59.4539 |     73.9479 |  14.4941 |     ms |
|  90.0th percentile service time |           index-stats |    115.924 |     127.256 |  11.3325 |     ms |
|  99.0th percentile service time |           index-stats |    253.341 |     193.498 | -59.8425 |     ms |
| 100.0th percentile service time |           index-stats |    529.076 |     642.751 |  113.676 |     ms |
|                      error rate |           index-stats |          0 |           0 |        0 |      % |
|                  Min Throughput |            node-stats |    7.13157 |     1.52891 | -5.60266 |  ops/s |
|               Median Throughput |            node-stats |    15.1907 |     12.5328 | -2.65792 |  ops/s |
|                  Max Throughput |            node-stats |     16.769 |     13.7414 | -3.02757 |  ops/s |
|       50.0th percentile latency |            node-stats |    3090.75 |     3279.11 |   188.36 |     ms |
|       90.0th percentile latency |            node-stats |    4692.72 |     6481.53 |  1788.81 |     ms |
|       99.0th percentile latency |            node-stats |    5206.15 |     7103.22 |  1897.07 |     ms |
|      100.0th percentile latency |            node-stats |    5253.49 |     7221.54 |  1968.05 |     ms |
|  50.0th percentile service time |            node-stats |    53.2459 |     62.7355 |  9.48964 |     ms |
|  90.0th percentile service time |            node-stats |    112.719 |     131.445 |  18.7258 |     ms |
|  99.0th percentile service time |            node-stats |     182.56 |     277.641 |  95.0815 |     ms |
| 100.0th percentile service time |            node-stats |    191.043 |     654.051 |  463.009 |     ms |
|                      error rate |            node-stats |          0 |           0 |        0 |      % |
|                  Min Throughput |       query-match-all |   0.347642 |    0.245894 | -0.10175 |  ops/s |
|               Median Throughput |       query-match-all |    2.98341 |      2.6374 | -0.34602 |  ops/s |
|                  Max Throughput |       query-match-all |    3.61507 |     3.41067 | -0.20441 |  ops/s |
|       50.0th percentile latency |       query-match-all |    15627.5 |     17822.3 |  2194.86 |     ms |
|       90.0th percentile latency |       query-match-all |      24463 |     26457.4 |  1994.38 |     ms |
|       99.0th percentile latency |       query-match-all |    26270.4 |     28031.7 |  1761.25 |     ms |
|      100.0th percentile latency |       query-match-all |    26502.3 |     28339.7 |  1837.48 |     ms |
|  50.0th percentile service time |       query-match-all |    454.136 |     460.855 |   6.7186 |     ms |
|  90.0th percentile service time |       query-match-all |     669.39 |      707.55 |  38.1598 |     ms |
|  99.0th percentile service time |       query-match-all |    2876.72 |      4066.9 |  1190.17 |     ms |
| 100.0th percentile service time |       query-match-all |    2897.85 |     4077.95 |  1180.11 |     ms |
|                      error rate |       query-match-all |          0 |           0 |        0 |      % |
|                  Min Throughput |            query-gary |   0.346682 |     0.24609 | -0.10059 |  ops/s |
|               Median Throughput |            query-gary |    1.48668 |     1.41304 | -0.07364 |  ops/s |
|                  Max Throughput |            query-gary |    3.09956 |     3.08953 | -0.01003 |  ops/s |
|       50.0th percentile latency |            query-gary |      27735 |       28966 |  1231.04 |     ms |
|       90.0th percentile latency |            query-gary |    29016.5 |     30732.3 |  1715.78 |     ms |
|       99.0th percentile latency |            query-gary |      29209 |     31064.7 |  1855.73 |     ms |
|      100.0th percentile latency |            query-gary |    29238.1 |     31092.1 |     1854 |     ms |
|  50.0th percentile service time |            query-gary |    80.4059 |     213.493 |  133.087 |     ms |
|  90.0th percentile service time |            query-gary |     630.34 |     536.606 |  -93.734 |     ms |
|  99.0th percentile service time |            query-gary |    1463.18 |     1524.99 |   61.809 |     ms |
| 100.0th percentile service time |            query-gary |    2884.47 |     4063.54 |  1179.07 |     ms |
|                      error rate |            query-gary |          0 |           0 |        0 |      % |
|                  Min Throughput |           query-educ* |   0.349431 |    0.266924 | -0.08251 |  ops/s |
|               Median Throughput |           query-educ* |    2.98959 |     2.76291 | -0.22669 |  ops/s |
|                  Max Throughput |           query-educ* |    3.57068 |     3.46311 | -0.10756 |  ops/s |
|       50.0th percentile latency |           query-educ* |    15650.4 |     17042.4 |  1392.01 |     ms |
|       90.0th percentile latency |           query-educ* |    24824.8 |     25574.3 |  749.466 |     ms |
|       99.0th percentile latency |           query-educ* |    26645.1 |     27418.4 |  773.219 |     ms |
|      100.0th percentile latency |           query-educ* |    26835.9 |     27694.4 |  858.471 |     ms |
|  50.0th percentile service time |           query-educ* |    466.559 |     451.797 |  -14.762 |     ms |
|  90.0th percentile service time |           query-educ* |    688.668 |     643.183 | -45.4848 |     ms |
|  99.0th percentile service time |           query-educ* |    2862.12 |     3750.08 |  887.965 |     ms |
| 100.0th percentile service time |           query-educ* |    2895.49 |      4117.7 |  1222.21 |     ms |
|                      error rate |           query-educ* |          0 |           0 |        0 |      % |
|                  Min Throughput | query-match-all-educ* |    0.34907 |    0.268176 | -0.08089 |  ops/s |
|               Median Throughput | query-match-all-educ* |    3.01528 |     2.76655 | -0.24874 |  ops/s |
|                  Max Throughput | query-match-all-educ* |    3.64859 |     3.50845 | -0.14014 |  ops/s |
|       50.0th percentile latency | query-match-all-educ* |    15616.5 |     17076.7 |   1460.2 |     ms |
|       90.0th percentile latency | query-match-all-educ* |    24098.7 |     25123.3 |  1024.55 |     ms |
|       99.0th percentile latency | query-match-all-educ* |    26177.1 |     27260.8 |  1083.79 |     ms |
|      100.0th percentile latency | query-match-all-educ* |    26430.1 |     27513.1 |  1083.05 |     ms |
|  50.0th percentile service time | query-match-all-educ* |    457.603 |     430.854 | -26.7492 |     ms |
|  90.0th percentile service time | query-match-all-educ* |    664.032 |      702.52 |  38.4885 |     ms |
|  99.0th percentile service time | query-match-all-educ* |    2864.89 |      3732.3 |  867.419 |     ms |
| 100.0th percentile service time | query-match-all-educ* |    2885.15 |     4078.23 |  1193.08 |     ms |
|                      error rate | query-match-all-educ* |          0 |           0 |        0 |      % |
|                  Min Throughput |           query-JohnD |   0.348352 |    0.217049 |  -0.1313 |  ops/s |
|               Median Throughput |           query-JohnD |    2.78659 |     2.48464 | -0.30195 |  ops/s |
|                  Max Throughput |           query-JohnD |    3.49964 |     3.20609 | -0.29355 |  ops/s |
|       50.0th percentile latency |           query-JohnD |      16987 |     18489.4 |  1502.45 |     ms |
|       90.0th percentile latency |           query-JohnD |    26030.7 |     27786.2 |  1755.49 |     ms |
|       99.0th percentile latency |           query-JohnD |    27105.7 |     28702.5 |  1596.81 |     ms |
|      100.0th percentile latency |           query-JohnD |    27201.9 |     28793.2 |  1591.29 |     ms |
|  50.0th percentile service time |           query-JohnD |    484.193 |     474.254 | -9.93819 |     ms |
|  90.0th percentile service time |           query-JohnD |    660.981 |     740.877 |  79.8964 |     ms |
|  99.0th percentile service time |           query-JohnD |     2872.9 |        4608 |   1735.1 |     ms |
| 100.0th percentile service time |           query-JohnD |    3100.36 |     4683.94 |  1583.58 |     ms |
|                      error rate |           query-JohnD |          0 |           0 |        0 |      % |
|                  Min Throughput | query-match-all-JohnD |   0.320708 |    0.245474 | -0.07523 |  ops/s |
|               Median Throughput | query-match-all-JohnD |    2.78797 |     2.48417 | -0.30379 |  ops/s |
|                  Max Throughput | query-match-all-JohnD |    3.41543 |     3.23304 | -0.18239 |  ops/s |
|       50.0th percentile latency | query-match-all-JohnD |    16625.3 |     18497.8 |  1872.47 |     ms |
|       90.0th percentile latency | query-match-all-JohnD |    25630.2 |     27760.1 |  2129.84 |     ms |
|       99.0th percentile latency | query-match-all-JohnD |    26974.9 |     28696.9 |  1721.98 |     ms |
|      100.0th percentile latency | query-match-all-JohnD |    26983.7 |     28715.6 |   1731.9 |     ms |
|  50.0th percentile service time | query-match-all-JohnD |    478.305 |     479.513 |  1.20769 |     ms |
|  90.0th percentile service time | query-match-all-JohnD |    655.061 |     775.497 |  120.435 |     ms |
|  99.0th percentile service time | query-match-all-JohnD |    3118.55 |     4073.93 |  955.372 |     ms |
| 100.0th percentile service time | query-match-all-JohnD |    3167.58 |     4098.34 |  930.759 |     ms |
|                      error rate | query-match-all-JohnD |          0 |           0 |        0 |      % |
