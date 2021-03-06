# Benchmark result

## Local machine

### Machine #1

- MacBook Air (M1, 2020)
- 8GB RAM

### commit hash `06513349873fe2a37fdc669f9ac206253b3bcbfc`

(time sharing worker)

`./kash -mode client -command benchmark -n 1000 -parallel 50 -key-size 5`

```
-> Benchmark result
# Worker 0
    sum: 1.009950591s
    avg: 1.00995ms
    p50: 829.75µs
    p90: 2.0675ms
    p99: 4.005958ms
# Worker 1
    sum: 962.906068ms
    avg: 962.906µs
    p50: 759.375µs
    p90: 2.031333ms
    p99: 3.815416ms
# Worker 2
    sum: 1.003774223s
    avg: 1.003774ms
    p50: 837.167µs
    p90: 2.077167ms
    p99: 3.669208ms
# Worker 3
    sum: 1.014555651s
    avg: 1.014555ms
    p50: 818.583µs
    p90: 2.153208ms
    p99: 4.065458ms
# Worker 4
    sum: 1.001279727s
    avg: 1.001279ms
    p50: 787.75µs
    p90: 2.0835ms
    p99: 4.022666ms
# Worker 5
    sum: 1.013679585s
    avg: 1.013679ms
    p50: 846.834µs
    p90: 2.053167ms
    p99: 3.593667ms
# Worker 6
    sum: 1.009297129s
    avg: 1.009297ms
    p50: 827.125µs
    p90: 2.081959ms
    p99: 3.748542ms
# Worker 7
    sum: 974.805319ms
    avg: 974.805µs
    p50: 820.5µs
    p90: 1.983792ms
    p99: 3.599958ms
# Worker 8
    sum: 998.931739ms
    avg: 998.931µs
    p50: 765.583µs
    p90: 2.116333ms
    p99: 3.652167ms
# Worker 9
    sum: 994.45079ms
    avg: 994.45µs
    p50: 817.834µs
    p90: 2.039125ms
    p99: 3.861375ms
# Worker 10
    sum: 980.910448ms
    avg: 980.91µs
    p50: 800.417µs
    p90: 2.004375ms
    p99: 3.507875ms
# Worker 11
    sum: 995.328475ms
    avg: 995.328µs
    p50: 800.458µs
    p90: 2.059959ms
    p99: 3.389208ms
# Worker 12
    sum: 1.011414696s
    avg: 1.011414ms
    p50: 806.125µs
    p90: 2.067459ms
    p99: 4.044875ms
# Worker 13
    sum: 1.012539378s
    avg: 1.012539ms
    p50: 818.333µs
    p90: 2.127875ms
    p99: 3.640458ms
# Worker 14
    sum: 1.001220843s
    avg: 1.00122ms
    p50: 829.125µs
    p90: 2.018833ms
    p99: 3.463958ms
# Worker 15
    sum: 1.020405672s
    avg: 1.020405ms
    p50: 827.917µs
    p90: 2.151291ms
    p99: 4.169166ms
# Worker 16
    sum: 972.015164ms
    avg: 972.015µs
    p50: 772.708µs
    p90: 2.042083ms
    p99: 3.375959ms
# Worker 17
    sum: 1.009574679s
    avg: 1.009574ms
    p50: 796.833µs
    p90: 2.08725ms
    p99: 3.66875ms
# Worker 18
    sum: 1.0114183s
    avg: 1.011418ms
    p50: 821.5µs
    p90: 2.088583ms
    p99: 3.895083ms
# Worker 19
    sum: 1.008968893s
    avg: 1.008968ms
    p50: 815.959µs
    p90: 2.115875ms
    p99: 3.837375ms
# Worker 20
    sum: 1.011241192s
    avg: 1.011241ms
    p50: 822µs
    p90: 2.097458ms
    p99: 3.610042ms
# Worker 21
    sum: 992.059464ms
    avg: 992.059µs
    p50: 812.292µs
    p90: 1.958625ms
    p99: 3.65525ms
# Worker 22
    sum: 972.013628ms
    avg: 972.013µs
    p50: 823.25µs
    p90: 1.964625ms
    p99: 3.422208ms
# Worker 23
    sum: 1.014770372s
    avg: 1.01477ms
    p50: 786.833µs
    p90: 2.116833ms
    p99: 3.985792ms
# Worker 24
    sum: 1.003313743s
    avg: 1.003313ms
    p50: 833.458µs
    p90: 2.067625ms
    p99: 3.823167ms
# Worker 25
    sum: 1.00803901s
    avg: 1.008039ms
    p50: 829.75µs
    p90: 2.106042ms
    p99: 3.611833ms
# Worker 26
    sum: 1.017567786s
    avg: 1.017567ms
    p50: 827.875µs
    p90: 2.196834ms
    p99: 3.5715ms
# Worker 27
    sum: 973.657507ms
    avg: 973.657µs
    p50: 813.75µs
    p90: 1.931041ms
    p99: 3.587792ms
# Worker 28
    sum: 1.007376427s
    avg: 1.007376ms
    p50: 834.417µs
    p90: 2.132917ms
    p99: 3.846292ms
# Worker 29
    sum: 962.165749ms
    avg: 962.165µs
    p50: 800.125µs
    p90: 1.941125ms
    p99: 3.589834ms
# Worker 30
    sum: 972.506726ms
    avg: 972.506µs
    p50: 790.25µs
    p90: 2.030375ms
    p99: 3.788417ms
# Worker 31
    sum: 1.004170165s
    avg: 1.00417ms
    p50: 811.125µs
    p90: 2.109542ms
    p99: 3.754208ms
# Worker 32
    sum: 1.004343004s
    avg: 1.004343ms
    p50: 827.292µs
    p90: 2.083792ms
    p99: 3.796208ms
# Worker 33
    sum: 975.790552ms
    avg: 975.79µs
    p50: 805.042µs
    p90: 2.019209ms
    p99: 3.423542ms
# Worker 34
    sum: 1.018014663s
    avg: 1.018014ms
    p50: 810.709µs
    p90: 2.162833ms
    p99: 3.866417ms
# Worker 35
    sum: 1.005591791s
    avg: 1.005591ms
    p50: 780.958µs
    p90: 2.111625ms
    p99: 4.130084ms
# Worker 36
    sum: 1.01397928s
    avg: 1.013979ms
    p50: 785.375µs
    p90: 2.050583ms
    p99: 3.685375ms
# Worker 37
    sum: 997.433538ms
    avg: 997.433µs
    p50: 833.792µs
    p90: 1.972709ms
    p99: 3.884792ms
# Worker 38
    sum: 1.004703174s
    avg: 1.004703ms
    p50: 837.167µs
    p90: 2.070917ms
    p99: 3.904417ms
# Worker 39
    sum: 1.003982755s
    avg: 1.003982ms
    p50: 821.625µs
    p90: 2.049666ms
    p99: 3.3885ms
# Worker 40
    sum: 993.793095ms
    avg: 993.793µs
    p50: 815.583µs
    p90: 2.053333ms
    p99: 3.428416ms
# Worker 41
    sum: 1.016305541s
    avg: 1.016305ms
    p50: 847.542µs
    p90: 2.097084ms
    p99: 3.819042ms
# Worker 42
    sum: 1.003284583s
    avg: 1.003284ms
    p50: 803.917µs
    p90: 2.129875ms
    p99: 3.890375ms
# Worker 43
    sum: 1.013726989s
    avg: 1.013726ms
    p50: 825.75µs
    p90: 2.072542ms
    p99: 3.754708ms
# Worker 44
    sum: 1.018156279s
    avg: 1.018156ms
    p50: 826.625µs
    p90: 2.121375ms
    p99: 3.656917ms
# Worker 45
    sum: 1.002678815s
    avg: 1.002678ms
    p50: 821.458µs
    p90: 2.100833ms
    p99: 3.834209ms
# Worker 46
    sum: 1.000676544s
    avg: 1.000676ms
    p50: 841.209µs
    p90: 2.035166ms
    p99: 3.703625ms
# Worker 47
    sum: 1.018503681s
    avg: 1.018503ms
    p50: 796.25µs
    p90: 2.091916ms
    p99: 3.862041ms
# Worker 48
    sum: 986.978606ms
    avg: 986.978µs
    p50: 802.958µs
    p90: 2.082959ms
    p99: 3.629541ms
# Worker 49
    sum: 1.011583988s
    avg: 1.011583ms
    p50: 815.416µs
    p90: 2.106292ms
    p99: 3.340417ms
```

### commit hash `f1250d4bb68643ac5bdb69e855b4ebdeedf12731`

(mutex based)

```
-> Benchmark result
# Worker 0
    sum: 1.031920238s
    avg: 1.03192ms
    p50: 662.459µs
    p90: 2.538042ms
    p99: 4.573958ms
# Worker 1
    sum: 1.006793851s
    avg: 1.006793ms
    p50: 624.167µs
    p90: 2.358833ms
    p99: 4.532875ms
# Worker 2
    sum: 1.051398119s
    avg: 1.051398ms
    p50: 650.625µs
    p90: 2.581ms
    p99: 5.057625ms
# Worker 3
    sum: 1.051532401s
    avg: 1.051532ms
    p50: 630.916µs
    p90: 2.560375ms
    p99: 4.8165ms
# Worker 4
    sum: 992.525263ms
    avg: 992.525µs
    p50: 587.25µs
    p90: 2.446541ms
    p99: 4.774417ms
# Worker 5
    sum: 1.049632131s
    avg: 1.049632ms
    p50: 631.958µs
    p90: 2.601917ms
    p99: 4.986667ms
# Worker 6
    sum: 1.028685292s
    avg: 1.028685ms
    p50: 656.916µs
    p90: 2.602084ms
    p99: 4.606042ms
# Worker 7
    sum: 1.036979424s
    avg: 1.036979ms
    p50: 674.958µs
    p90: 2.491209ms
    p99: 4.519042ms
# Worker 8
    sum: 1.049590667s
    avg: 1.04959ms
    p50: 636.458µs
    p90: 2.541792ms
    p99: 4.664208ms
# Worker 9
    sum: 1.031445871s
    avg: 1.031445ms
    p50: 669.917µs
    p90: 2.431292ms
    p99: 4.354208ms
# Worker 10
    sum: 1.04741454s
    avg: 1.047414ms
    p50: 644.292µs
    p90: 2.581959ms
    p99: 4.9865ms
# Worker 11
    sum: 1.049110477s
    avg: 1.04911ms
    p50: 710.958µs
    p90: 2.506ms
    p99: 4.63525ms
# Worker 12
    sum: 1.025588197s
    avg: 1.025588ms
    p50: 607.458µs
    p90: 2.465042ms
    p99: 4.956083ms
# Worker 13
    sum: 981.826106ms
    avg: 981.826µs
    p50: 521.916µs
    p90: 2.608709ms
    p99: 4.463167ms
# Worker 14
    sum: 1.049329252s
    avg: 1.049329ms
    p50: 665.167µs
    p90: 2.578833ms
    p99: 4.610416ms
# Worker 15
    sum: 1.045940579s
    avg: 1.04594ms
    p50: 604.958µs
    p90: 2.59925ms
    p99: 4.8435ms
# Worker 16
    sum: 1.04378184s
    avg: 1.043781ms
    p50: 672.125µs
    p90: 2.554791ms
    p99: 4.681959ms
# Worker 17
    sum: 1.020753791s
    avg: 1.020753ms
    p50: 611.5µs
    p90: 2.450875ms
    p99: 4.605084ms
# Worker 18
    sum: 1.042946844s
    avg: 1.042946ms
    p50: 652.208µs
    p90: 2.561208ms
    p99: 4.508333ms
# Worker 19
    sum: 1.045395608s
    avg: 1.045395ms
    p50: 634.792µs
    p90: 2.656958ms
    p99: 4.596167ms
# Worker 20
    sum: 1.002919574s
    avg: 1.002919ms
    p50: 628.833µs
    p90: 2.536041ms
    p99: 4.428208ms
# Worker 21
    sum: 1.018354183s
    avg: 1.018354ms
    p50: 642.083µs
    p90: 2.373417ms
    p99: 4.874334ms
# Worker 22
    sum: 1.037422036s
    avg: 1.037422ms
    p50: 662.292µs
    p90: 2.639042ms
    p99: 3.853875ms
# Worker 23
    sum: 1.051309305s
    avg: 1.051309ms
    p50: 608.458µs
    p90: 2.641667ms
    p99: 4.840042ms
# Worker 24
    sum: 1.013578579s
    avg: 1.013578ms
    p50: 585.084µs
    p90: 2.58125ms
    p99: 4.696625ms
# Worker 25
    sum: 1.04336709s
    avg: 1.043367ms
    p50: 634.166µs
    p90: 2.56875ms
    p99: 4.563917ms
# Worker 26
    sum: 1.016870902s
    avg: 1.01687ms
    p50: 627.417µs
    p90: 2.505084ms
    p99: 4.528708ms
# Worker 27
    sum: 1.037763869s
    avg: 1.037763ms
    p50: 627.416µs
    p90: 2.669167ms
    p99: 4.697542ms
# Worker 28
    sum: 1.039134545s
    avg: 1.039134ms
    p50: 657.583µs
    p90: 2.499084ms
    p99: 4.914167ms
# Worker 29
    sum: 1.035603083s
    avg: 1.035603ms
    p50: 635.375µs
    p90: 2.489417ms
    p99: 5.342417ms
# Worker 30
    sum: 1.040808022s
    avg: 1.040808ms
    p50: 611.792µs
    p90: 2.654625ms
    p99: 4.470458ms
# Worker 31
    sum: 1.029910459s
    avg: 1.02991ms
    p50: 653.375µs
    p90: 2.561792ms
    p99: 4.754125ms
# Worker 32
    sum: 1.036134142s
    avg: 1.036134ms
    p50: 645.584µs
    p90: 2.565125ms
    p99: 4.556375ms
# Worker 33
    sum: 1.04051781s
    avg: 1.040517ms
    p50: 639.167µs
    p90: 2.486375ms
    p99: 4.572125ms
# Worker 34
    sum: 1.046246997s
    avg: 1.046246ms
    p50: 598.125µs
    p90: 2.68275ms
    p99: 4.675458ms
# Worker 35
    sum: 1.053320576s
    avg: 1.05332ms
    p50: 657.167µs
    p90: 2.573459ms
    p99: 4.681ms
# Worker 36
    sum: 1.045275757s
    avg: 1.045275ms
    p50: 658.958µs
    p90: 2.575417ms
    p99: 4.417166ms
# Worker 37
    sum: 1.049474322s
    avg: 1.049474ms
    p50: 637.125µs
    p90: 2.572083ms
    p99: 4.962084ms
# Worker 38
    sum: 1.041249366s
    avg: 1.041249ms
    p50: 642µs
    p90: 2.569708ms
    p99: 4.410833ms
# Worker 39
    sum: 1.037485711s
    avg: 1.037485ms
    p50: 605µs
    p90: 2.685959ms
    p99: 4.469292ms
# Worker 40
    sum: 1.050138131s
    avg: 1.050138ms
    p50: 647.833µs
    p90: 2.487375ms
    p99: 4.862083ms
# Worker 41
    sum: 963.638335ms
    avg: 963.638µs
    p50: 627.709µs
    p90: 2.338625ms
    p99: 3.9815ms
# Worker 42
    sum: 984.638289ms
    avg: 984.638µs
    p50: 616.084µs
    p90: 2.317792ms
    p99: 4.576ms
# Worker 43
    sum: 1.04715646s
    avg: 1.047156ms
    p50: 622.875µs
    p90: 2.678459ms
    p99: 4.740042ms
# Worker 44
    sum: 981.22035ms
    avg: 981.22µs
    p50: 596.167µs
    p90: 2.388333ms
    p99: 4.3755ms
# Worker 45
    sum: 1.03715538s
    avg: 1.037155ms
    p50: 633.834µs
    p90: 2.56125ms
    p99: 4.588542ms
# Worker 46
    sum: 1.044385715s
    avg: 1.044385ms
    p50: 641.75µs
    p90: 2.533959ms
    p99: 4.704333ms
# Worker 47
    sum: 1.048796731s
    avg: 1.048796ms
    p50: 626.541µs
    p90: 2.637875ms
    p99: 4.616917ms
# Worker 48
    sum: 946.242713ms
    avg: 946.242µs
    p50: 527.25µs
    p90: 2.389708ms
    p99: 4.570208ms
# Worker 49
    sum: 1.019070823s
    avg: 1.01907ms
    p50: 613.292µs
    p90: 2.627333ms
    p99: 4.338584ms
```

### commit hash `beb5c1c81e53ec18ed348a384e209ed271697288`

(remove encoding/gob)

```
-> Benchmark result
# Worker 0
    sum: 364.003665ms
    avg: 364.003µs
    p50: 223.792µs
    p90: 880.459µs
    p99: 2.267958ms
# Worker 1
    sum: 371.940169ms
    avg: 371.94µs
    p50: 221.125µs
    p90: 882.75µs
    p99: 2.286875ms
# Worker 2
    sum: 378.54505ms
    avg: 378.545µs
    p50: 231.459µs
    p90: 917.334µs
    p99: 2.391833ms
# Worker 3
    sum: 376.88841ms
    avg: 376.888µs
    p50: 237.667µs
    p90: 863.667µs
    p99: 2.398292ms
# Worker 4
    sum: 370.599248ms
    avg: 370.599µs
    p50: 230.583µs
    p90: 828.083µs
    p99: 2.289042ms
# Worker 5
    sum: 377.723296ms
    avg: 377.723µs
    p50: 248.5µs
    p90: 878.708µs
    p99: 2.387292ms
# Worker 6
    sum: 350.922079ms
    avg: 350.922µs
    p50: 218.292µs
    p90: 822µs
    p99: 2.21075ms
# Worker 7
    sum: 377.406372ms
    avg: 377.406µs
    p50: 233.167µs
    p90: 909.667µs
    p99: 2.344208ms
# Worker 8
    sum: 371.217605ms
    avg: 371.217µs
    p50: 229.708µs
    p90: 847.583µs
    p99: 2.275167ms
# Worker 9
    sum: 366.364969ms
    avg: 366.364µs
    p50: 231µs
    p90: 858.958µs
    p99: 2.392458ms
# Worker 10
    sum: 380.710581ms
    avg: 380.71µs
    p50: 221.625µs
    p90: 932.792µs
    p99: 2.292958ms
# Worker 11
    sum: 375.167608ms
    avg: 375.167µs
    p50: 228.916µs
    p90: 869.167µs
    p99: 2.282ms
# Worker 12
    sum: 374.272355ms
    avg: 374.272µs
    p50: 235.792µs
    p90: 859.916µs
    p99: 2.129542ms
# Worker 13
    sum: 375.297327ms
    avg: 375.297µs
    p50: 226.917µs
    p90: 880.041µs
    p99: 2.241042ms
# Worker 14
    sum: 377.973837ms
    avg: 377.973µs
    p50: 224.416µs
    p90: 904.792µs
    p99: 2.285458ms
# Worker 15
    sum: 377.906845ms
    avg: 377.906µs
    p50: 232.541µs
    p90: 904.75µs
    p99: 2.27075ms
# Worker 16
    sum: 378.294924ms
    avg: 378.294µs
    p50: 227.458µs
    p90: 872.959µs
    p99: 2.286917ms
# Worker 17
    sum: 372.296347ms
    avg: 372.296µs
    p50: 234µs
    p90: 886.333µs
    p99: 2.357083ms
# Worker 18
    sum: 367.51239ms
    avg: 367.512µs
    p50: 224.167µs
    p90: 894.792µs
    p99: 2.352292ms
# Worker 19
    sum: 381.994554ms
    avg: 381.994µs
    p50: 230.583µs
    p90: 905.917µs
    p99: 2.395125ms
# Worker 20
    sum: 377.318585ms
    avg: 377.318µs
    p50: 232.958µs
    p90: 861.041µs
    p99: 2.365833ms
# Worker 21
    sum: 379.534271ms
    avg: 379.534µs
    p50: 234.25µs
    p90: 910.333µs
    p99: 2.179459ms
# Worker 22
    sum: 366.02666ms
    avg: 366.026µs
    p50: 223.041µs
    p90: 853.167µs
    p99: 2.297375ms
# Worker 23
    sum: 358.915567ms
    avg: 358.915µs
    p50: 236.583µs
    p90: 838.916µs
    p99: 1.810333ms
# Worker 24
    sum: 380.849105ms
    avg: 380.849µs
    p50: 225.709µs
    p90: 859.583µs
    p99: 2.377208ms
# Worker 25
    sum: 365.786998ms
    avg: 365.786µs
    p50: 226.291µs
    p90: 875.333µs
    p99: 2.267708ms
# Worker 26
    sum: 373.547591ms
    avg: 373.547µs
    p50: 245.041µs
    p90: 848.792µs
    p99: 2.277708ms
# Worker 27
    sum: 363.554293ms
    avg: 363.554µs
    p50: 223.542µs
    p90: 852.708µs
    p99: 2.359917ms
# Worker 28
    sum: 379.434283ms
    avg: 379.434µs
    p50: 235.834µs
    p90: 910.583µs
    p99: 2.214ms
# Worker 29
    sum: 379.633965ms
    avg: 379.633µs
    p50: 227.083µs
    p90: 922.667µs
    p99: 2.360917ms
# Worker 30
    sum: 370.499138ms
    avg: 370.499µs
    p50: 219.666µs
    p90: 892.458µs
    p99: 2.341334ms
# Worker 31
    sum: 380.548038ms
    avg: 380.548µs
    p50: 230.125µs
    p90: 903.042µs
    p99: 2.313209ms
# Worker 32
    sum: 375.916444ms
    avg: 375.916µs
    p50: 234.042µs
    p90: 911.667µs
    p99: 2.3655ms
# Worker 33
    sum: 368.601206ms
    avg: 368.601µs
    p50: 229.458µs
    p90: 847.208µs
    p99: 2.384125ms
# Worker 34
    sum: 379.028187ms
    avg: 379.028µs
    p50: 228.583µs
    p90: 877µs
    p99: 2.376541ms
# Worker 35
    sum: 360.392132ms
    avg: 360.392µs
    p50: 219.125µs
    p90: 819.583µs
    p99: 2.355417ms
# Worker 36
    sum: 380.857943ms
    avg: 380.857µs
    p50: 228.291µs
    p90: 889.75µs
    p99: 2.401833ms
# Worker 37
    sum: 373.029921ms
    avg: 373.029µs
    p50: 237.209µs
    p90: 854.375µs
    p99: 2.306125ms
# Worker 38
    sum: 370.67398ms
    avg: 370.673µs
    p50: 228.583µs
    p90: 912.209µs
    p99: 2.013833ms
# Worker 39
    sum: 369.106036ms
    avg: 369.106µs
    p50: 228.709µs
    p90: 904.791µs
    p99: 2.142959ms
# Worker 40
    sum: 374.468074ms
    avg: 374.468µs
    p50: 227.208µs
    p90: 858.875µs
    p99: 2.373083ms
# Worker 41
    sum: 375.76554ms
    avg: 375.765µs
    p50: 228.25µs
    p90: 868.541µs
    p99: 2.258583ms
# Worker 42
    sum: 376.997091ms
    avg: 376.997µs
    p50: 229.125µs
    p90: 889µs
    p99: 2.272625ms
# Worker 43
    sum: 380.849239ms
    avg: 380.849µs
    p50: 226.083µs
    p90: 904.542µs
    p99: 2.27075ms
# Worker 44
    sum: 374.310025ms
    avg: 374.31µs
    p50: 234.292µs
    p90: 853.542µs
    p99: 2.25675ms
# Worker 45
    sum: 372.887641ms
    avg: 372.887µs
    p50: 241.542µs
    p90: 889.792µs
    p99: 2.0125ms
# Worker 46
    sum: 376.388393ms
    avg: 376.388µs
    p50: 232.958µs
    p90: 854.792µs
    p99: 2.284875ms
# Worker 47
    sum: 376.423077ms
    avg: 376.423µs
    p50: 232.125µs
    p90: 881.459µs
    p99: 2.362417ms
# Worker 48
    sum: 375.852504ms
    avg: 375.852µs
    p50: 224.25µs
    p90: 911µs
    p99: 2.447083ms
# Worker 49
    sum: 380.164149ms
    avg: 380.164µs
    p50: 234.709µs
    p90: 868.75µs
    p99: 2.385333ms
```
