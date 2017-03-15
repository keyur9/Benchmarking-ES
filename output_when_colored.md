|                          Metric |             Operation |   Baseline |   Contender |                Diff |   Unit |
|--------------------------------:|----------------------:|-----------:|------------:|--------------------:|-------:|
|                   Indexing time |                       | -0.0489833 |     1.44825 |     [31;1m+1.49723[0m |    min |
|                      Merge time |                       | -0.0783167 |    0.840617 |     [31;1m+0.91893[0m |    min |
|                    Refresh time |                       |  0.0427833 |    0.750083 |     [31;1m+0.70730[0m |    min |
|                      Flush time |                       |          0 |   0.0149333 |     [31;1m+0.01493[0m |    min |
|             Merge throttle time |                       |          0 |           0 |      [39;1m0.00000[0m |    min |
|              Total Young Gen GC |                       |     25.486 |      41.068 |    [31;1m+15.58200[0m |      s |
|                Total Old Gen GC |                       |      8.478 |      11.363 |     [31;1m+2.88500[0m |      s |
|          Heap used for segments |                       |    9.20783 |     9.47482 |     [31;1m+0.26699[0m |     MB |
|        Heap used for doc values |                       |    1.68724 |     1.78688 |     [31;1m+0.09964[0m |     MB |
|             Heap used for terms |                       |    6.65354 |     6.80069 |     [31;1m+0.14716[0m |     MB |
|             Heap used for norms |                       |   0.209473 |    0.221436 |     [31;1m+0.01196[0m |     MB |
|            Heap used for points |                       |   0.281197 |    0.282434 |     [31;1m+0.00124[0m |     MB |
|     Heap used for stored fields |                       |   0.376381 |    0.383377 |     [31;1m+0.00700[0m |     MB |
|                   Segment count |                       |        419 |         448 |    [31;1m+29.00000[0m |        |
|                  Min Throughput |                 index |     527.51 |     162.714 |   [31;1m-364.79553[0m | docs/s |
|               Median Throughput |                 index |    1855.06 |      967.71 |   [31;1m-887.35223[0m | docs/s |
|                  Max Throughput |                 index |    2551.67 |     1407.17 |  [31;1m-1144.49902[0m | docs/s |
|       50.0th percentile latency |                 index |    10641.9 |     19820.9 |  [31;1m+9178.93115[0m |     ms |
|       90.0th percentile latency |                 index |    46041.2 |     94415.3 | [31;1m+48374.02148[0m |     ms |
|      100.0th percentile latency |                 index |    77439.3 |      168107 | [31;1m+90668.00781[0m |     ms |
|  50.0th percentile service time |                 index |    10641.9 |     19820.9 |  [31;1m+9178.93115[0m |     ms |
|  90.0th percentile service time |                 index |    46041.2 |     94415.3 | [31;1m+48374.02148[0m |     ms |
| 100.0th percentile service time |                 index |    77439.3 |      168107 | [31;1m+90668.00781[0m |     ms |
|                      error rate |                 index |          0 |     1.13636 |     [31;1m+1.13636[0m |      % |
|                  Min Throughput |           force-merge |   0.256027 |    0.224791 |     [31;1m-0.03124[0m |  ops/s |
|               Median Throughput |           force-merge |   0.988183 |     5.73445 |     [32;1m+4.74627[0m |  ops/s |
|                  Max Throughput |           force-merge |    8.58311 |     10.1443 |     [32;1m+1.56117[0m |  ops/s |
|       50.0th percentile latency |           force-merge |    8.64068 |     15.1276 |     [31;1m+6.48692[0m |     ms |
|       90.0th percentile latency |           force-merge |    44.6694 |     69.7526 |    [31;1m+25.08319[0m |     ms |
|       99.0th percentile latency |           force-merge |    293.753 |     533.995 |   [31;1m+240.24251[0m |     ms |
|      100.0th percentile latency |           force-merge |    3905.78 |     4448.51 |   [31;1m+542.72827[0m |     ms |
|  50.0th percentile service time |           force-merge |    8.64068 |     15.1276 |     [31;1m+6.48692[0m |     ms |
|  90.0th percentile service time |           force-merge |    44.6694 |     69.7526 |    [31;1m+25.08319[0m |     ms |
|  99.0th percentile service time |           force-merge |    293.753 |     533.995 |   [31;1m+240.24251[0m |     ms |
| 100.0th percentile service time |           force-merge |    3905.78 |     4448.51 |   [31;1m+542.72827[0m |     ms |
|                      error rate |           force-merge |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput |           index-stats |    6.67009 |     1.55554 |     [31;1m-5.11455[0m |  ops/s |
|               Median Throughput |           index-stats |    13.7778 |     11.4685 |     [31;1m-2.30924[0m |  ops/s |
|                  Max Throughput |           index-stats |    15.8681 |     13.3272 |     [31;1m-2.54084[0m |  ops/s |
|       50.0th percentile latency |           index-stats |       3239 |      3528.7 |   [31;1m+289.70264[0m |     ms |
|       90.0th percentile latency |           index-stats |    5610.18 |     7068.07 |  [31;1m+1457.89712[0m |     ms |
|       99.0th percentile latency |           index-stats |    6054.55 |     7602.68 |  [31;1m+1548.12222[0m |     ms |
|      100.0th percentile latency |           index-stats |    6180.81 |     7652.04 |  [31;1m+1471.22852[0m |     ms |
|  50.0th percentile service time |           index-stats |    59.4539 |     73.9479 |    [31;1m+14.49407[0m |     ms |
|  90.0th percentile service time |           index-stats |    115.924 |     127.256 |    [31;1m+11.33247[0m |     ms |
|  99.0th percentile service time |           index-stats |    253.341 |     193.498 |    [32;1m-59.84248[0m |     ms |
| 100.0th percentile service time |           index-stats |    529.076 |     642.751 |   [31;1m+113.67566[0m |     ms |
|                      error rate |           index-stats |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput |            node-stats |    7.13157 |     1.52891 |     [31;1m-5.60266[0m |  ops/s |
|               Median Throughput |            node-stats |    15.1907 |     12.5328 |     [31;1m-2.65792[0m |  ops/s |
|                  Max Throughput |            node-stats |     16.769 |     13.7414 |     [31;1m-3.02757[0m |  ops/s |
|       50.0th percentile latency |            node-stats |    3090.75 |     3279.11 |   [31;1m+188.36023[0m |     ms |
|       90.0th percentile latency |            node-stats |    4692.72 |     6481.53 |  [31;1m+1788.80947[0m |     ms |
|       99.0th percentile latency |            node-stats |    5206.15 |     7103.22 |  [31;1m+1897.07288[0m |     ms |
|      100.0th percentile latency |            node-stats |    5253.49 |     7221.54 |  [31;1m+1968.04834[0m |     ms |
|  50.0th percentile service time |            node-stats |    53.2459 |     62.7355 |     [31;1m+9.48964[0m |     ms |
|  90.0th percentile service time |            node-stats |    112.719 |     131.445 |    [31;1m+18.72583[0m |     ms |
|  99.0th percentile service time |            node-stats |     182.56 |     277.641 |    [31;1m+95.08152[0m |     ms |
| 100.0th percentile service time |            node-stats |    191.043 |     654.051 |   [31;1m+463.00854[0m |     ms |
|                      error rate |            node-stats |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput |       query-match-all |   0.347642 |    0.245894 |     [31;1m-0.10175[0m |  ops/s |
|               Median Throughput |       query-match-all |    2.98341 |      2.6374 |     [31;1m-0.34602[0m |  ops/s |
|                  Max Throughput |       query-match-all |    3.61507 |     3.41067 |     [31;1m-0.20441[0m |  ops/s |
|       50.0th percentile latency |       query-match-all |    15627.5 |     17822.3 |  [31;1m+2194.86230[0m |     ms |
|       90.0th percentile latency |       query-match-all |      24463 |     26457.4 |  [31;1m+1994.37871[0m |     ms |
|       99.0th percentile latency |       query-match-all |    26270.4 |     28031.7 |  [31;1m+1761.25430[0m |     ms |
|      100.0th percentile latency |       query-match-all |    26502.3 |     28339.7 |  [31;1m+1837.47656[0m |     ms |
|  50.0th percentile service time |       query-match-all |    454.136 |     460.855 |     [31;1m+6.71860[0m |     ms |
|  90.0th percentile service time |       query-match-all |     669.39 |      707.55 |    [31;1m+38.15985[0m |     ms |
|  99.0th percentile service time |       query-match-all |    2876.72 |      4066.9 |  [31;1m+1190.17491[0m |     ms |
| 100.0th percentile service time |       query-match-all |    2897.85 |     4077.95 |  [31;1m+1180.10620[0m |     ms |
|                      error rate |       query-match-all |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput |            query-gary |   0.346682 |     0.24609 |     [31;1m-0.10059[0m |  ops/s |
|               Median Throughput |            query-gary |    1.48668 |     1.41304 |     [31;1m-0.07364[0m |  ops/s |
|                  Max Throughput |            query-gary |    3.09956 |     3.08953 |     [31;1m-0.01003[0m |  ops/s |
|       50.0th percentile latency |            query-gary |      27735 |       28966 |  [31;1m+1231.04199[0m |     ms |
|       90.0th percentile latency |            query-gary |    29016.5 |     30732.3 |  [31;1m+1715.78301[0m |     ms |
|       99.0th percentile latency |            query-gary |      29209 |     31064.7 |  [31;1m+1855.73055[0m |     ms |
|      100.0th percentile latency |            query-gary |    29238.1 |     31092.1 |  [31;1m+1853.99805[0m |     ms |
|  50.0th percentile service time |            query-gary |    80.4059 |     213.493 |   [31;1m+133.08733[0m |     ms |
|  90.0th percentile service time |            query-gary |     630.34 |     536.606 |    [32;1m-93.73397[0m |     ms |
|  99.0th percentile service time |            query-gary |    1463.18 |     1524.99 |    [31;1m+61.80900[0m |     ms |
| 100.0th percentile service time |            query-gary |    2884.47 |     4063.54 |  [31;1m+1179.06787[0m |     ms |
|                      error rate |            query-gary |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput |           query-educ* |   0.349431 |    0.266924 |     [31;1m-0.08251[0m |  ops/s |
|               Median Throughput |           query-educ* |    2.98959 |     2.76291 |     [31;1m-0.22669[0m |  ops/s |
|                  Max Throughput |           query-educ* |    3.57068 |     3.46311 |     [31;1m-0.10756[0m |  ops/s |
|       50.0th percentile latency |           query-educ* |    15650.4 |     17042.4 |  [31;1m+1392.01270[0m |     ms |
|       90.0th percentile latency |           query-educ* |    24824.8 |     25574.3 |   [31;1m+749.46563[0m |     ms |
|       99.0th percentile latency |           query-educ* |    26645.1 |     27418.4 |   [31;1m+773.21855[0m |     ms |
|      100.0th percentile latency |           query-educ* |    26835.9 |     27694.4 |   [31;1m+858.47070[0m |     ms |
|  50.0th percentile service time |           query-educ* |    466.559 |     451.797 |    [32;1m-14.76199[0m |     ms |
|  90.0th percentile service time |           query-educ* |    688.668 |     643.183 |    [32;1m-45.48484[0m |     ms |
|  99.0th percentile service time |           query-educ* |    2862.12 |     3750.08 |   [31;1m+887.96487[0m |     ms |
| 100.0th percentile service time |           query-educ* |    2895.49 |      4117.7 |  [31;1m+1222.21338[0m |     ms |
|                      error rate |           query-educ* |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput | query-match-all-educ* |    0.34907 |    0.268176 |     [31;1m-0.08089[0m |  ops/s |
|               Median Throughput | query-match-all-educ* |    3.01528 |     2.76655 |     [31;1m-0.24874[0m |  ops/s |
|                  Max Throughput | query-match-all-educ* |    3.64859 |     3.50845 |     [31;1m-0.14014[0m |  ops/s |
|       50.0th percentile latency | query-match-all-educ* |    15616.5 |     17076.7 |  [31;1m+1460.20459[0m |     ms |
|       90.0th percentile latency | query-match-all-educ* |    24098.7 |     25123.3 |  [31;1m+1024.54805[0m |     ms |
|       99.0th percentile latency | query-match-all-educ* |    26177.1 |     27260.8 |  [31;1m+1083.78551[0m |     ms |
|      100.0th percentile latency | query-match-all-educ* |    26430.1 |     27513.1 |  [31;1m+1083.04688[0m |     ms |
|  50.0th percentile service time | query-match-all-educ* |    457.603 |     430.854 |    [32;1m-26.74919[0m |     ms |
|  90.0th percentile service time | query-match-all-educ* |    664.032 |      702.52 |    [31;1m+38.48847[0m |     ms |
|  99.0th percentile service time | query-match-all-educ* |    2864.89 |      3732.3 |   [31;1m+867.41871[0m |     ms |
| 100.0th percentile service time | query-match-all-educ* |    2885.15 |     4078.23 |  [31;1m+1193.08472[0m |     ms |
|                      error rate | query-match-all-educ* |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput |           query-JohnD |   0.348352 |    0.217049 |     [31;1m-0.13130[0m |  ops/s |
|               Median Throughput |           query-JohnD |    2.78659 |     2.48464 |     [31;1m-0.30195[0m |  ops/s |
|                  Max Throughput |           query-JohnD |    3.49964 |     3.20609 |     [31;1m-0.29355[0m |  ops/s |
|       50.0th percentile latency |           query-JohnD |      16987 |     18489.4 |  [31;1m+1502.45215[0m |     ms |
|       90.0th percentile latency |           query-JohnD |    26030.7 |     27786.2 |  [31;1m+1755.49492[0m |     ms |
|       99.0th percentile latency |           query-JohnD |    27105.7 |     28702.5 |  [31;1m+1596.80756[0m |     ms |
|      100.0th percentile latency |           query-JohnD |    27201.9 |     28793.2 |  [31;1m+1591.29102[0m |     ms |
|  50.0th percentile service time |           query-JohnD |    484.193 |     474.254 |     [32;1m-9.93819[0m |     ms |
|  90.0th percentile service time |           query-JohnD |    660.981 |     740.877 |    [31;1m+79.89637[0m |     ms |
|  99.0th percentile service time |           query-JohnD |     2872.9 |        4608 |  [31;1m+1735.09813[0m |     ms |
| 100.0th percentile service time |           query-JohnD |    3100.36 |     4683.94 |  [31;1m+1583.57593[0m |     ms |
|                      error rate |           query-JohnD |          0 |           0 |      [39;1m0.00000[0m |      % |
|                  Min Throughput | query-match-all-JohnD |   0.320708 |    0.245474 |     [31;1m-0.07523[0m |  ops/s |
|               Median Throughput | query-match-all-JohnD |    2.78797 |     2.48417 |     [31;1m-0.30379[0m |  ops/s |
|                  Max Throughput | query-match-all-JohnD |    3.41543 |     3.23304 |     [31;1m-0.18239[0m |  ops/s |
|       50.0th percentile latency | query-match-all-JohnD |    16625.3 |     18497.8 |  [31;1m+1872.47070[0m |     ms |
|       90.0th percentile latency | query-match-all-JohnD |    25630.2 |     27760.1 |  [31;1m+2129.84414[0m |     ms |
|       99.0th percentile latency | query-match-all-JohnD |    26974.9 |     28696.9 |  [31;1m+1721.98492[0m |     ms |
|      100.0th percentile latency | query-match-all-JohnD |    26983.7 |     28715.6 |  [31;1m+1731.90039[0m |     ms |
|  50.0th percentile service time | query-match-all-JohnD |    478.305 |     479.513 |     [31;1m+1.20769[0m |     ms |
|  90.0th percentile service time | query-match-all-JohnD |    655.061 |     775.497 |   [31;1m+120.43540[0m |     ms |
|  99.0th percentile service time | query-match-all-JohnD |    3118.55 |     4073.93 |   [31;1m+955.37223[0m |     ms |
| 100.0th percentile service time | query-match-all-JohnD |    3167.58 |     4098.34 |   [31;1m+930.75928[0m |     ms |
|                      error rate | query-match-all-JohnD |          0 |           0 |      [39;1m0.00000[0m |      % |
