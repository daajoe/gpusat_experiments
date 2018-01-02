# gpusat_experiments

The used Benchmark sets are form the following Sources:

* **ApproxMC**(165 Instances): [https://www.cs.rice.edu/CS/Verification/Projects/ApproxMC/](https://www.cs.rice.edu/CS/Verification/Projects/ApproxMC/)
* **C2D**(14 Instances): [http://reasoning.cs.ucla.edu/c2d/results.html](http://reasoning.cs.ucla.edu/c2d/results.html)
* **Cachet**(1090 Instances): [https://www.cs.rochester.edu/u/kautz/Cachet/Model_Counting_Benchmarks/index.html](https://www.cs.rochester.edu/u/kautz/Cachet/Model_Counting_Benchmarks/index.html)
* **counting-benchmarks**(1451 Instances): [https://github.com/dfremont/counting-benchmarks](https://github.com/dfremont/counting-benchmarks)
* **dynasp_all**(1367 Instances): [https://github.com/daajoe/dynasp_experiments](https://github.com/daajoe/dynasp_experiments)
* **SATCOMP (2005/2007/2009/2011/2015/2016/2017)**(4153 Instances): [http://www.satcompetition.org/](http://www.satcompetition.org/)
* **SATLIB**(9389 Instances): [http://www.cs.ubc.ca/~hoos/SATLIB/benchm.html](http://www.cs.ubc.ca/~hoos/SATLIB/benchm.html)

## Overview

### Incidence Tree-Width

Number of instances for each width range:

| Set | Width 0-10 | Width 11-20 | Width 21-30 | Width 31-40 | Width 41-50 | Width 51-60 | Width 61-70 | Width 71-80 | Width 81-100 | Width 101-150 | Width 151-300 | Width 301-500 | Width >500 | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ApproxMC | 0 | 1 | 71 | 26 | 14 | 15 | 16 | 9 | 11 | 0 | 0 | 2 | 0 |
| counting-benchmarks | 15 | 151 | 547 | 222 | 158 | 26 | 25 | 10 | 20 | 31 | 105 | 43 | 95 |
| dynasp_all | 1367 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| SATCOMP | 6 | 83 | 44 | 64 | 84 | 89 | 126 | 143 | 224 | 338 | 707 | 667 | 1130 |
| C2D | 0 | 1 | 1 | 1 | 3 | 2 | 1 | 0 | 0 | 0 | 0 | 4 | 1 |
| all_sets | 1420 | 1308 | 719 | 2399 | 1240 | 747 | 2710 | 226 | 671 | 1186 | 1402 | 795 | 1267 |
| Cachet | 0 | 126 | 538 | 216 | 153 | 15 | 17 | 9 | 12 | 0 | 0 | 4 | 0 |
| SATLIB | 32 | 1023 | 114 | 2114 | 993 | 628 | 2557 | 73 | 427 | 815 | 572 | 18 | 21 |


### Primal Tree-Width

Number of instances for each width range:

| Set | Width 0-10 | Width 11-20 | Width 21-30 | Width 31-40 | Width 41-50 | Width 51-60 | Width 61-70 | Width 71-80 | Width 81-100 | Width 101-150 | Width 151-300 | Width 301-500 | Width >500 | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ApproxMC  | 0 | 1 | 71 | 25 | 15 | 15 | 15 | 12 | 9 | 0 | 0 | 2 | 0 |
| counting-benchmarks | 16 | 151 | 552 | 216 | 158 | 27 | 22 | 12 | 16 | 15 | 114 | 61 | 91 |
| dynasp_all | 1367 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| SATCOMP | 3 | 60 | 33 | 44 | 82 | 87 | 120 | 138 | 234 | 340 | 712 | 667 | 1139 |
| C2D | 0 | 1 | 1 | 2 | 2 | 1 | 2 | 0 | 0 | 0 | 0 | 4 | 1 |
| all_sets | 1414 | 1283 | 715 | 2384 | 1225 | 743 | 2699 | 230 | 676 | 1163 | 1434 | 819 | 1275 |
| Cachet | 0 | 127 | 543 | 210 | 153 | 16 | 15 | 12 | 10 | 0 | 0 | 4 | 0 |
| SATLIB | 28 | 1022 | 115 | 2124 | 981 | 626 | 2554 | 80 | 426 | 807 | 585 | 17 | 23 |


