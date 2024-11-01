## Expected Runtime Analysis:
singleThd : O(n)

naive: O(n^2)

recurseDb: O(log(n))

## Raw Data Collection

| Test Data | singleThd time (ns) | naive time (ns) | recurseDb time (ns) |
|-----------|---------------------|-----------------|---------------------|
| Array of ints, size 128 | 953.674316 | 397920.608521 | 269174.575806 |
| Array of floats, size 128 | 953.674316 | 502109.5276 | 282049.1791 |
| Array of ints, size 256 | 953.674316 | 762939.453125 | 276803.970337 |
| Array of floats, size 256 | 953.674316 | 1199960.709 | 227928.1616 |
| Array of ints, size 512 | 1907.348633 | 2007007.598877 | 297069.549561 |
| Array of floats, size 512 | 1192.09289 | 3854036.331 | 277042.3889 |

## Data Chart

![ScalingDataChart.png](https://github.com/SmithCollege/a3-scan-prefix-sum-rakurosawa/blob/5a8c2e84f30de1b6655ead1445f193200f22ec99/ScalingDataChart.png)
