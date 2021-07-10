# PrimesResult

The results of the [David Plummer's Primes Drag Race](https://github.com/PlummersSoftwareLLC/Primes).

## Results

Generated at 2021-07-10 on a Ryzen 9 5950X with 32GB RAM.

### Best faithful performers for each language

| Implementation | "Slowness" | Position | Index | Solution | Label                                                | Passes | Duration | Threads | Algorithm | Bits | Passes/Second |
| -------------- | ---------- | -------- | ----- | -------- | ---------------------------------------------------- | ------ | -------- | ------- | --------- | ---- | ------------- |
| zig            | 1          | 1        | 2     | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030 | 26992  | 5.00004  | 1       | wheel     | 1    | 5398.35681    |
| c              | 1.1123     | 2        | 5     | 2        | danielspaangberg_48of210                             | 24267  | 5.00011  | 1       | wheel     | 1    | 4853.29129    |
| rust           | 1.3590     | 3        | 8     | 1        | mike-barber_byte-storage                             | 19862  | 5.00029  | 1       | base      | 8    | 3972.17347    |
| v              | 1.6341     | 4        | 12    | 1        | marghidanu                                           | 16518  | 5.00000  | 1       | base      |      | 3303.60000    |
| assembly       | 2.0101     | 5        | 17    | 1        | rbergen_x64ff_byte                                   | 13428  | 5.00000  | 1       | base      | 8    | 2685.60000    |
| crystal        | 2.3392     | 6        | 25    | 1        | marghidanu                                           | 11539  | 5.00003  | 1       | base      | 1    | 2307.78523    |
| fsharp         | 2.3581     | 7        | 26    | 2        | dmannock_fsharp_port                                 | 11447  | 5.00018  | 1       | base      |      | 2289.31575    |
| csharp         | 2.6607     | 8        | 32    | 1        | kinematics_dbool                                     | 10145  | 5.00013  | 1       | base      |      | 2028.94725    |
| cpp            | 2.7623     | 9        | 34    | 1        | davepl                                               | 9772   | 5.00034  | 1       | base      | 1    | 1954.26828    |
| java           | 2.8441     | 10       | 36    | 1        | MansenC                                              | 18981  | 10.00000 | 1       | base      |      | 1898.10000    |
| julia          | 3.4850     | 11       | 45    | 2        | epithet-jl                                           | 7746   | 5.00059  | 1       | base      | 1    | 1549.01719    |
| dart           | 3.8213     | 12       | 48    | 1        | eagerestwolf&mmcdon20                                | 7064   | 5.00035  | 1       | base      | 8    | 1412.70196    |
| nodejs         | 4.0418     | 13       | 53    | 1        | rogiervandam                                         | 6679   | 5.00065  | 1       | base      | 1    | 1335.62686    |
| d              | 4.1664     | 14       | 54    | 2        | BradleyChatha                                        | 6479   | 5.00042  | 1       | base      | 1    | 1295.69116    |
| typescript     | 4.5479     | 15       | 56    | 1        | marghidanu                                           | 5935   | 5.00000  | 1       | base      |      | 1187.00000    |
| go             | 5.7284     | 16       | 60    | 2        | ssovest-go                                           | 4713   | 5.00112  | 1       | base      | 1    | 942.38909     |
| nim            | 9.0551     | 17       | 63    | 2        | beef331                                              | 2981   | 5.00029  | 1       | base      | 1    | 596.16583     |
| cython         | 10.188     | 18       | 68    | 1        | rpkak                                                | 2650   | 5.00111  | 1       | base      | 8    | 529.88184     |
| basic          | 11.080     | 19       | 71    | 1        | rbergen_8of30                                        | 2437   | 5.00200  | 1       | wheel     | 1    | 487.20512     |
| assemblyscript | 11.660     | 20       | 72    | 1        | donmahallem                                          | 4630   | 10.00000 | 1       | base      |      | 463.00000     |
| python         | 13.274     | 21       | 74    | 2        | ssovest                                              | 2034   | 5.00129  | 1       | base      | 8    | 406.69468     |
| scala          | 19.381     | 22       | 79    | 1        | rom1dep                                              | 1393   | 5.00100  | 1       | base      |      | 278.54429     |
| pony           | 21.439     | 23       | 81    | 1        | marghidanu                                           | 1259   | 5.00000  | 1       | base      | 1    | 251.80000     |
| pascal         | 21.945     | 24       | 83    | 1        | rbergen                                              | 1230   | 5.00000  | 1       | base      |      | 246.00000     |
| swift          | 24.430     | 25       | 84    | 1        | j-f1                                                 | 2210   | 10.00122 | 1       | base      |      | 220.97313     |
| r              | 31.905     | 26       | 85    | 1        | fvbakel_R                                            | 846    | 5.00000  | 1       | base      | 32   | 169.20000     |
| haxe           | 37.483     | 27       | 87    | 1        | TayIorRobinson_Haxe_C++                              | 1441   | 10.00532 | 1       | base      |      | 144.02334     |
| ocaml          | 49.639     | 28       | 89    | 1        | gkpotter-faithful                                    | 544    | 5.00219  | 1       | base      |      | 108.75230     |
| ruby           | 179.83     | 29       | 94    | 1        | rbergen                                              | 151    | 5.03000  | 1       | base      |      | 30.01988      |
| wren           | 232.10     | 31       | 95    | 1        | marghidanu                                           | 117    | 5.03027  | 1       | base      |      | 23.25919      |
| php            | 254.91     | 32       | 96    | 1        | DennisdeBest                                         | 212    | 10.01061 | 1       | base      |      | 21.17752      |
| smalltalk      | 501.65     | 33       | 98    | 1        | fvbakel_smalltalk                                    | 54     | 5.01800  | 1       | base      | 1    | 10.76126      |
| perl           | 563.41     | 34       | 99    | 1        | marghidanu                                           | 48     | 5.00965  | 1       | base      |      | 9.58150       |
| tcl            | 3443.5     | 35       | 104   | 1        | fvbakeltcl                                           | 8      | 5.10300  | 1       | base      | 1    | 1.56771       |
| powershell     | 4021.5     | 36       | 106   | 2        | crowbar27_ps2                                        | 7      | 5.21470  | 1       | base      | 1    | 1.34236       |
| prolog         | 3.3416e+04 | 37       | 111   | 1        | jimbxb_prolog                                        | 1      | 6.19000  | 1       | base      | 1    | 0.16155       |

### Single-threaded

| Index | Implementation | Solution | Label                                                 | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | cpp            | 3        | flo80_constexpr                                       | 219511 | 5.00003  | 1       | base      | no       | 1    | 43901.94537   |
| 2     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030  | 26992  | 5.00004  | 1       | wheel     | yes      | 1    | 5398.35681    |
| 3     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 26937  | 5.00016  | 1       | wheel     | yes      | 1    | 5387.22761    |
| 4     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-480of2310    | 24724  | 5.00002  | 1       | wheel     | yes      | 1    | 4944.78022    |
| 5     | c              | 2        | danielspaangberg_48of210                              | 24267  | 5.00011  | 1       | wheel     | yes      | 1    | 4853.29129    |
| 6     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-480of2310   | 23157  | 5.00009  | 1       | wheel     | yes      | 1    | 4631.31664    |
| 7     | c              | 2        | danielspaangberg_8of30                                | 20248  | 5.00012  | 1       | wheel     | yes      | 1    | 4049.50038    |
| 8     | rust           | 1        | mike-barber_byte-storage                              | 19862  | 5.00029  | 1       | base      | yes      | 8    | 3972.17347    |
| 9     | zig            | 2        | ManDeJan&ityonemo-zig-byte-sieve-type-bool            | 19452  | 5.00007  | 1       | base      | yes      | 8    | 3890.34554    |
| 10    | assembly       | 1        | rbergen_x64uff_byte                                   | 18472  | 5.00000  | 1       | base      | no       | 8    | 3694.40000    |
| 11    | c              | 2        | danielspaangberg_5760of30030_owrb                     | 18379  | 5.00025  | 1       | wheel     | yes      | 1    | 3675.61916    |
| 12    | v              | 1        | marghidanu                                            | 16518  | 5.00000  | 1       | base      | yes      |      | 3303.60000    |
| 13    | haskell        | 1        | fatho/vector_unchecked                                | 16089  | 5.00024  | 1       | base      | no       | 8    | 3217.64813    |
| 14    | ada            | 1        | BoopBeepBoopBeep                                      | 15942  | 5.00027  | 1       | base      | no       |      | 3188.22801    |
| 15    | zig            | 1        | devblok                                               | 15887  | 5.00004  | 1       | base      | yes      | 8    | 3177.37458    |
| 16    | c              | 2        | danielspaangberg_480of2310_owrb                       | 15881  | 5.00030  | 1       | wheel     | yes      | 1    | 3176.00880    |
| 17    | assembly       | 1        | rbergen_x64ff_byte                                    | 13428  | 5.00000  | 1       | base      | yes      | 8    | 2685.60000    |
| 18    | haskell        | 1        | fatho/vector                                          | 13425  | 5.00027  | 1       | base      | no       | 8    | 2684.85502    |
| 19    | fortran        | 1        | johandweber_fortran                                   | 13171  | 5.00000  | 1       | base      | no       | 1    | 2634.20000    |
| 20    | c              | 1        | mckoss-c830                                           | 13101  | 5.00000  | 1       | wheel     | yes      | 1    | 2620.20000    |
| 21    | c              | 2        | danielspaangberg_48of210_owrb                         | 12718  | 5.00007  | 1       | wheel     | yes      | 1    | 2543.56388    |
| 22    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8              | 12584  | 5.00005  | 1       | base      | yes      | 1    | 2516.77483    |
| 23    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8                 | 11991  | 5.00032  | 1       | base      | yes      | 8    | 2398.04653    |
| 24    | zig            | 2        | ManDeJan&ityonemo-zig-bit-sieve                       | 11729  | 5.00034  | 1       | base      | yes      | 1    | 2345.64050    |
| 25    | crystal        | 1        | marghidanu                                            | 11539  | 5.00003  | 1       | base      | yes      | 1    | 2307.78523    |
| 26    | fsharp         | 2        | dmannock_fsharp_port                                  | 11447  | 5.00018  | 1       | base      | yes      |      | 2289.31575    |
| 27    | c              | 2        | danielspaangberg_1of2                                 | 11286  | 5.00015  | 1       | base      | yes      | 1    | 2257.13138    |
| 28    | haskell        | 1        | fatho/bitset                                          | 11272  | 5.00019  | 1       | base      | no       | 1    | 2254.31208    |
| 29    | fsharp         | 3        | dmannock_fsharp_recursion                             | 10839  | 5.00011  | 1       | base      | yes      |      | 2167.75404    |
| 30    | rust           | 2        | Azgrom                                                | 10740  | 5.00042  | 1       | base      | yes      |      | 2147.82173    |
| 31    | rust           | 1        | mike-barber_bit-storage                               | 10670  | 5.00043  | 1       | base      | yes      | 1    | 2133.81543    |
| 32    | csharp         | 1        | kinematics_dbool                                      | 10145  | 5.00013  | 1       | base      | yes      |      | 2028.94725    |
| 33    | rust           | 1        | mike-barber_bit-storage-rotate                        | 10094  | 5.00061  | 1       | base      | yes      | 1    | 2018.55494    |
| 34    | cpp            | 1        | davepl                                                | 9772   | 5.00034  | 1       | base      | yes      | 1    | 1954.26828    |
| 35    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-bool               | 9555   | 5.00047  | 1       | base      | yes      | 8    | 1910.82038    |
| 36    | java           | 1        | MansenC                                               | 18981  | 10.00000 | 1       | base      | yes      |      | 1898.10000    |
| 37    | c              | 2        | danielspaangberg_8of30_owrb                           | 9411   | 5.00004  | 1       | wheel     | yes      | 1    | 1882.18645    |
| 38    | haskell        | 1        | fatho/bitset_unchecked                                | 9357   | 5.00039  | 1       | base      | no       | 1    | 1871.25292    |
| 39    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-5760of30030     | 9190   | 5.00031  | 1       | wheel     | yes      | 8    | 1837.88605    |
| 40    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-480of2310       | 8859   | 5.00051  | 1       | wheel     | yes      | 8    | 1771.61929    |
| 41    | rust           | 4        | joshallen64                                           | 8691   | 5.00047  | 1       | base      | yes      |      | 1738.03767    |
| 42    | assembly       | 1        | rbergen_x64ff_bitshift                                | 8585   | 5.00000  | 1       | base      | yes      | 1    | 1717.00000    |
| 43    | assembly       | 1        | rbergen_x64uff_bitshift                               | 8242   | 5.00000  | 1       | base      | no       | 1    | 1648.40000    |
| 44    | assembly       | 1        | rbergen_x64uff_bitbtr                                 | 7765   | 5.00000  | 1       | base      | no       | 1    | 1553.00000    |
| 45    | julia          | 2        | epithet-jl                                            | 7746   | 5.00059  | 1       | base      | yes      | 1    | 1549.01719    |
| 46    | csharp         | 3        | tannergooding                                         | 7706   | 5.00060  | 1       | base      | yes      | 1    | 1541.01449    |
| 47    | assembly       | 1        | rbergen_x64ff_bitbtr                                  | 7501   | 5.00000  | 1       | base      | yes      | 1    | 1500.20000    |
| 48    | dart           | 1        | eagerestwolf&mmcdon20                                 | 7064   | 5.00035  | 1       | base      | yes      | 8    | 1412.70196    |
| 49    | csharp         | 1        | kinematics_rawd                                       | 6915   | 5.00082  | 1       | base      | yes      | 1    | 1382.77323    |
| 50    | csharp         | 1        | kinematics_raw                                        | 6891   | 5.00058  | 1       | base      | yes      | 1    | 1378.04015    |
| 51    | csharp         | 1        | kinematics_raw32                                      | 6799   | 5.00038  | 1       | base      | yes      | 1    | 1359.69666    |
| 52    | csharp         | 1        | kinematics_raw6                                       | 6791   | 5.00043  | 1       | wheel     | yes      | 1    | 1358.08320    |
| 53    | nodejs         | 1        | rogiervandam                                          | 6679   | 5.00065  | 1       | base      | yes      | 1    | 1335.62686    |
| 54    | d              | 2        | BradleyChatha                                         | 6479   | 5.00042  | 1       | base      | yes      | 1    | 1295.69116    |
| 55    | csharp         | 1        | kinematics_pool30                                     | 6082   | 5.00019  | 1       | wheel     | yes      | 1    | 1216.35378    |
| 56    | typescript     | 1        | marghidanu                                            | 5935   | 5.00000  | 1       | base      | yes      |      | 1187.00000    |
| 57    | lisp           | 2        | mayerrobert-cl                                        | 5815   | 5.00333  | 1       | base      | no       | 1    | 1162.22596    |
| 58    | csharp         | 1        | kinematics_pool30m                                    | 5787   | 5.00053  | 1       | wheel     | yes      | 1    | 1157.27733    |
| 59    | csharp         | 1        | kinematics_pool2of6                                   | 5100   | 5.00016  | 1       | wheel     | yes      | 1    | 1019.96736    |
| 60    | go             | 2        | ssovest-go                                            | 4713   | 5.00112  | 1       | base      | yes      | 1    | 942.38909     |
| 61    | rust           | 3        | Blui42                                                | 4062   | 5.00099  | 1       | base      | yes      |      | 812.23974     |
| 62    | lua            | 2        | ben1jen_luajit1                                       | 3932   | 5.00000  | 1       | base      | no       | 1    | 786.40000     |
| 63    | nim            | 2        | beef331                                               | 2981   | 5.00029  | 1       | base      | yes      | 1    | 596.16583     |
| 64    | d              | 1        | eagerestwolf                                          | 2908   | 5.00000  | 1       | base      | yes      | 8    | 581.60000     |
| 65    | nim            | 1        | marghidanu                                            | 2794   | 5.00075  | 1       | base      | yes      | 8    | 558.71571     |
| 66    | csharp         | 1        | kinematics_ibool                                      | 2728   | 5.00132  | 1       | base      | yes      |      | 545.45600     |
| 67    | csharp         | 1        | kinematics_pool                                       | 2700   | 5.00016  | 1       | base      | yes      | 1    | 539.98272     |
| 68    | cython         | 1        | rpkak                                                 | 2650   | 5.00111  | 1       | base      | yes      | 8    | 529.88184     |
| 69    | go             | 1        | bundgaard                                             | 2639   | 5.00080  | 1       | base      | yes      |      | 527.71567     |
| 70    | csharp         | 1        | kinematics_bool                                       | 2491   | 5.00185  | 1       | base      | yes      |      | 498.01573     |
| 71    | basic          | 1        | rbergen_8of30                                         | 2437   | 5.00200  | 1       | wheel     | yes      | 1    | 487.20512     |
| 72    | assemblyscript | 1        | donmahallem                                           | 4630   | 10.00000 | 1       | base      | yes      |      | 463.00000     |
| 73    | octave         | 1        | octave                                                | 2188   | 5.00120  | 1       | base      | no       |      | 437.49500     |
| 74    | python         | 2        | ssovest                                               | 2034   | 5.00129  | 1       | base      | yes      | 8    | 406.69468     |
| 75    | fsharp         | 1        | rbergen                                               | 1789   | 5.00219  | 1       | base      | yes      | 1    | 357.64309     |
| 76    | csharp         | 1        | kinematics_standard                                   | 1686   | 5.00087  | 1       | base      | yes      | 1    | 337.14134     |
| 77    | basic          | 2        | rbergen_vb                                            | 1619   | 5.00065  | 1       | base      | yes      | 1    | 323.75818     |
| 78    | csharp         | 2        | davepl                                                | 2968   | 10.00160 | 1       | base      | yes      | 1    | 296.75252     |
| 79    | scala          | 1        | rom1dep                                               | 1393   | 5.00100  | 1       | base      | yes      |      | 278.54429     |
| 80    | csharp         | 1        | kinematics_original                                   | 1362   | 5.00034  | 1       | base      | yes      | 1    | 272.38148     |
| 81    | pony           | 1        | marghidanu                                            | 1259   | 5.00000  | 1       | base      | yes      | 1    | 251.80000     |
| 82    | cobol          | 1        | fvbakel_Cobol                                         | 1239   | 5.00000  | 1       | base      | no       | 8    | 247.80000     |
| 83    | pascal         | 1        | rbergen                                               | 1230   | 5.00000  | 1       | base      | yes      |      | 246.00000     |
| 84    | swift          | 1        | j-f1                                                  | 2210   | 10.00122 | 1       | base      | yes      |      | 220.97313     |
| 85    | r              | 1        | fvbakel_R                                             | 846    | 5.00000  | 1       | base      | yes      | 32   | 169.20000     |
| 86    | basic          | 1        | rbergen_boolean                                       | 741    | 5.00400  | 1       | base      | yes      |      | 148.08153     |
| 87    | haxe           | 1        | TayIorRobinson_Haxe_C++                               | 1441   | 10.00532 | 1       | base      | yes      |      | 144.02334     |
| 88    | ocaml          | 2        | gkpotter-unfaithful                                   | 700    | 5.00261  | 1       | base      | no       |      | 139.92699     |
| 89    | ocaml          | 1        | gkpotter-faithful                                     | 544    | 5.00219  | 1       | base      | yes      |      | 108.75230     |
| 90    | julia          | 1        | dcbi                                                  | 530    | 5.00380  | 1       | base      | yes      | 1    | 105.91950     |
| 91    | basic          | 1        | rbergen_bit32                                         | 486    | 5.00600  | 1       | base      | yes      | 1    | 97.08350      |
| 92    | basic          | 1        | rbergen_bit64                                         | 466    | 5.00500  | 1       | base      | yes      | 1    | 93.10689      |
| 93    | postscript     | 1        | epithet-ps                                            | 238    | 5.01300  | 1       | base      | no       | 8    | 47.47656      |
| 94    | ruby           | 1        | rbergen                                               | 151    | 5.03000  | 1       | base      | yes      |      | 30.01988      |
| 95    | wren           | 1        | marghidanu                                            | 117    | 5.03027  | 1       | base      | yes      |      | 23.25919      |
| 96    | php            | 1        | DennisdeBest                                          | 212    | 10.01061 | 1       | base      | yes      |      | 21.17752      |
| 97    | lisp           | 1        | mikehw                                                | 114    | 10.05666 | 1       | base      | no       | 1    | 11.33577      |
| 98    | smalltalk      | 1        | fvbakel_smalltalk                                     | 54     | 5.01800  | 1       | base      | yes      | 1    | 10.76126      |
| 99    | perl           | 1        | marghidanu                                            | 48     | 5.00965  | 1       | base      | yes      |      | 9.58150       |
| 100   | mixal          | 1        | rbergen                                               | 30     | 3.52000  | 1       | base      | no       | 1    | 8.52273       |
| 101   | haxe           | 1        | TayIorRobinson_Haxe_HaxeEval                          | 59     | 10.08438 | 1       | base      | yes      |      | 5.85063       |
| 102   | python         | 1        | davepl                                                | 47     | 10.15263 | 1       | base      | yes      |      | 4.62934       |
| 103   | sql            | 2        | fvbakel_MariaDB3                                      | 9      | 5.49200  | 1       | other     | no       | 32   | 1.63875       |
| 104   | tcl            | 1        | fvbakeltcl                                            | 8      | 5.10300  | 1       | base      | yes      | 1    | 1.56771       |
| 105   | sql            | 1        | fvbakel_sqlite                                        | 7      | 5.12606  | 1       | other     | no       | 8    | 1.36557       |
| 106   | powershell     | 2        | crowbar27_ps2                                         | 7      | 5.21470  | 1       | base      | yes      | 1    | 1.34236       |
| 107   | haxe           | 1        | TayIorRobinson_Haxe_Python                            | 13     | 10.54138 | 1       | base      | yes      |      | 1.23323       |
| 108   | tcl            | 2        | fvbakel_ootcl                                         | 7      | 5.76700  | 1       | base      | yes      | 1    | 1.21380       |
| 109   | sql            | 2        | fvbakel_MariaDB2                                      | 6      | 5.63600  | 1       | other     | no       | 32   | 1.06458       |
| 110   | sql            | 2        | fvbakel_MariaDB1                                      | 1      | 5.79400  | 1       | base      | no       | 32   | 0.17259       |
| 111   | prolog         | 1        | jimbxb_prolog                                         | 1      | 6.19000  | 1       | base      | yes      | 1    | 0.16155       |
| 112   | latex          | 1        | tjol                                                  | 2      | 13.18956 | 1       | base      | no       | 32   | 0.15164       |
| 113   | bash           | 1        | bash                                                  | 1      | 7.19842  | 1       | base      | no       |      | 0.13892       |
| 114   | elixir         | 1        | cdesch                                                | 1      | 22.90000 | 1       | base      | no       |      | 0.04367       |
| 115   | lua            | 1        | lua                                                   | 1      | 26.00000 | 1       | base      | no       | 64   | 0.03846       |
| 116   | powershell     | 1        | crowbar27_ps1                                         | 1      | 52.67450 | 1       | base      | yes      | 1    | 0.01898       |

### Multi-threaded

| Index | Implementation | Solution | Label                                                             | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-5760of30030  | 379772 | 5.00006  | 32      | wheel     | yes      | 1    | 2373.54652    |
| 2     | cpp            | 3        | flo80_constexpr                                                   | 376192 | 5.00044  | 32      | base      | no       | 1    | 2350.99405    |
| 3     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-480of2310    | 351716 | 5.00034  | 32      | wheel     | yes      | 1    | 2198.07553    |
| 4     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-480of2310   | 340473 | 5.00042  | 32      | wheel     | yes      | 1    | 2127.77752    |
| 5     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-5760of30030 | 321699 | 5.00011  | 32      | wheel     | yes      | 1    | 2010.57452    |
| 6     | c              | 2        | danielspaangberg_5760of30030_par                                  | 29357  | 5.00005  | 4       | wheel     | yes      | 1    | 1467.83620    |
| 7     | c              | 2        | danielspaangberg_480of2310_par                                    | 29104  | 5.00014  | 4       | wheel     | yes      | 1    | 1455.15780    |
| 8     | c              | 2        | danielspaangberg_48of210_par                                      | 26918  | 5.00013  | 4       | wheel     | yes      | 1    | 1345.86393    |
| 9     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-sieve-u8                 | 205103 | 5.00096  | 32      | base      | yes      | 8    | 1281.64767    |
| 10    | c              | 2        | danielspaangberg_8of30_par                                        | 25460  | 5.00020  | 4       | wheel     | yes      | 1    | 1272.94985    |
| 11    | rust           | 1        | mike-barber_byte-storage                                          | 202238 | 5.00082  | 32      | base      | yes      | 8    | 1263.78020    |
| 12    | c              | 2        | danielspaangberg_5760of30030_epar                                 | 199404 | 5.00285  | 32      | wheel     | yes      | 1    | 1245.56577    |
| 13    | c              | 2        | danielspaangberg_480of2310_epar                                   | 181435 | 5.01124  | 32      | wheel     | yes      | 1    | 1131.42440    |
| 14    | rust           | 1        | mike-barber_bit-storage-rotate                                    | 166293 | 5.00101  | 32      | base      | yes      | 1    | 1039.12086    |
| 15    | rust           | 1        | mike-barber_bit-storage                                           | 162684 | 5.00104  | 32      | base      | yes      | 1    | 1016.56385    |
| 16    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8              | 162022 | 5.00045  | 32      | base      | yes      | 1    | 1012.54637    |
| 17    | c              | 2        | danielspaangberg_1of2_par                                         | 19946  | 5.00002  | 4       | base      | yes      | 1    | 997.29541     |
| 18    | c              | 2        | danielspaangberg_48of210_epar                                     | 156359 | 5.01128  | 32      | wheel     | yes      | 1    | 975.04425     |
| 19    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64             | 156006 | 5.00003  | 32      | base      | yes      | 1    | 975.03165     |
| 20    | c              | 2        | danielspaangberg_1of2_epar                                        | 140170 | 5.01243  | 32      | base      | yes      | 1    | 873.88949     |
| 21    | c              | 2        | danielspaangberg_8of30_epar                                       | 133161 | 5.01130  | 32      | wheel     | yes      | 1    | 830.37992     |
| 22    | cpp            | 2        | davepl_par                                                        | 96256  | 5.00075  | 32      | base      | yes      | 1    | 601.50977     |
| 23    | d              | 2        | BradleyChatha-Multi                                               | 96097  | 5.00145  | 32      | base      | yes      | 1    | 600.43212     |
| 24    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-amdahl-sieve-u8                    | 9989   | 5.00045  | 32      | base      | yes      | 8    | 62.42563      |
| 25    | csharp         | 1        | kinematics_rawp                                                   | 3498   | 5.00099  | 32      | base      | yes      | 1    | 21.85817      |
| 26    | csharp         | 1        | kinematics_pool6p                                                 | 3348   | 5.00144  | 32      | wheel     | yes      | 1    | 20.91898      |
