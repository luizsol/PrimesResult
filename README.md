# PrimesResult

The results of the [Dave Plummer's Primes Drag Race](https://github.com/PlummersSoftwareLLC/Primes).

## Results

Generated at 2021-07-08 on a Ryzen 9 5950X with 32GB RAM.

### Single-threaded

| Index | Implementation | Solution | Label                                                 | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | cpp            | 3        | flo80_constexpr                                       | 202494 | 5.00002  | 1       | base      | no       | 1    | 40498.64611   |
| 2     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030  | 26631  | 5.00002  | 1       | wheel     | yes      | 1    | 5326.17870    |
| 3     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 26251  | 5.00015  | 1       | wheel     | yes      | 1    | 5250.04250    |
| 4     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-480of2310    | 24753  | 5.00008  | 1       | wheel     | yes      | 1    | 4950.52079    |
| 5     | c              | 2        | danielspaangberg_48of210                              | 24173  | 5.00014  | 1       | wheel     | yes      | 1    | 4834.46077    |
| 6     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-480of2310   | 22730  | 5.00014  | 1       | wheel     | yes      | 1    | 4545.87272    |
| 7     | c              | 2        | danielspaangberg_8of30                                | 20295  | 5.00018  | 1       | wheel     | yes      | 1    | 4058.85469    |
| 8     | rust           | 1        | mike-barber_byte-storage                              | 19771  | 5.00019  | 1       | base      | yes      | 8    | 3954.05294    |
| 9     | zig            | 2        | ManDeJan&ityonemo-zig-byte-sieve-type-bool            | 19610  | 5.00008  | 1       | base      | yes      | 8    | 3921.93725    |
| 10    | assembly       | 1        | rbergen_x64uff_byte                                   | 18452  | 5.00000  | 1       | base      | no       | 8    | 3690.40000    |
| 11    | c              | 2        | danielspaangberg_5760of30030_owrb                     | 18389  | 5.00010  | 1       | wheel     | yes      | 1    | 3677.72350    |
| 12    | v              | 1        | marghidanu                                            | 16567  | 5.00000  | 1       | base      | yes      |      | 3313.40000    |
| 13    | haskell        | 1        | fatho/vector_unchecked                                | 16080  | 5.00029  | 1       | base      | no       | 8    | 3215.81155    |
| 14    | zig            | 1        | devblok                                               | 15966  | 5.00028  | 1       | base      | yes      | 8    | 3193.02119    |
| 15    | c              | 2        | danielspaangberg_480of2310_owrb                       | 15812  | 5.00002  | 1       | wheel     | yes      | 1    | 3162.38798    |
| 16    | assembly       | 1        | rbergen_x64ff_byte                                    | 13431  | 5.00000  | 1       | base      | yes      | 8    | 2686.20000    |
| 17    | haskell        | 1        | fatho/vector                                          | 13374  | 5.00008  | 1       | base      | no       | 8    | 2674.75774    |
| 18    | fortran        | 1        | johandweber_fortran                                   | 13285  | 5.00000  | 1       | base      | no       | 1    | 2657.00000    |
| 19    | c              | 1        | mckoss-c830                                           | 12873  | 5.00000  | 1       | wheel     | yes      | 1    | 2574.60000    |
| 20    | c              | 2        | danielspaangberg_48of210_owrb                         | 12844  | 5.00004  | 1       | wheel     | yes      | 1    | 2568.77996    |
| 21    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8              | 12841  | 5.00019  | 1       | base      | yes      | 1    | 2568.10241    |
| 22    | fsharp         | 3        | dmannock_fsharp_recursion                             | 12030  | 5.00055  | 1       | base      | yes      |      | 2405.73729    |
| 23    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8                 | 11901  | 5.00004  | 1       | base      | yes      | 8    | 2380.18096    |
| 24    | zig            | 2        | ManDeJan&ityonemo-zig-bit-sieve                       | 11615  | 5.00004  | 1       | base      | yes      | 1    | 2322.98142    |
| 25    | crystal        | 1        | marghidanu                                            | 11494  | 5.00040  | 1       | base      | yes      | 1    | 2298.61841    |
| 26    | haskell        | 1        | fatho/bitset                                          | 11226  | 5.00006  | 1       | base      | no       | 1    | 2245.17171    |
| 27    | c              | 2        | danielspaangberg_1of2                                 | 11120  | 5.00029  | 1       | base      | yes      | 1    | 2223.87057    |
| 28    | fsharp         | 2        | dmannock_fsharp_port                                  | 10795  | 5.00032  | 1       | base      | yes      |      | 2158.86097    |
| 29    | rust           | 1        | mike-barber_bit-storage                               | 10746  | 5.00033  | 1       | base      | yes      | 1    | 2149.05858    |
| 30    | rust           | 2        | Azgrom                                                | 10744  | 5.00003  | 1       | base      | yes      |      | 2148.78646    |
| 31    | rust           | 1        | mike-barber_bit-storage-rotate                        | 10092  | 5.00011  | 1       | base      | yes      | 1    | 2018.35727    |
| 32    | csharp         | 1        | kinematics_dbool                                      | 10074  | 5.00011  | 1       | base      | yes      |      | 2014.75568    |
| 33    | cpp            | 1        | davepl                                                | 9701   | 5.00003  | 1       | base      | yes      | 1    | 1940.18875    |
| 34    | c              | 2        | danielspaangberg_8of30_owrb                           | 9626   | 5.00032  | 1       | wheel     | yes      | 1    | 1925.07680    |
| 35    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-bool               | 9477   | 5.00010  | 1       | base      | yes      | 8    | 1895.36209    |
| 36    | java           | 1        | MansenC                                               | 18555  | 10.00000 | 1       | base      | yes      |      | 1855.50000    |
| 37    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-5760of30030     | 9193   | 5.00044  | 1       | wheel     | yes      | 8    | 1838.43822    |
| 38    | haskell        | 1        | fatho/bitset_unchecked                                | 9158   | 5.00021  | 1       | base      | no       | 1    | 1831.52198    |
| 39    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-480of2310       | 8853   | 5.00013  | 1       | wheel     | yes      | 8    | 1770.55397    |
| 40    | rust           | 4        | joshallen64                                           | 8803   | 5.00019  | 1       | base      | yes      |      | 1760.53380    |
| 41    | assembly       | 1        | rbergen_x64ff_bitshift                                | 8528   | 5.00000  | 1       | base      | yes      | 1    | 1705.60000    |
| 42    | assembly       | 1        | rbergen_x64uff_bitshift                               | 8215   | 5.00000  | 1       | base      | no       | 1    | 1643.00000    |
| 43    | csharp         | 3        | tannergooding                                         | 7933   | 5.00011  | 1       | base      | yes      | 1    | 1586.56579    |
| 44    | julia          | 2        | epithet-jl                                            | 7876   | 5.00023  | 1       | base      | yes      | 1    | 1575.12880    |
| 45    | assembly       | 1        | rbergen_x64uff_bitbtr                                 | 7638   | 5.00000  | 1       | base      | no       | 1    | 1527.60000    |
| 46    | assembly       | 1        | rbergen_x64ff_bitbtr                                  | 7481   | 5.00000  | 1       | base      | yes      | 1    | 1496.20000    |
| 47    | csharp         | 1        | kinematics_raw                                        | 6984   | 5.00026  | 1       | base      | yes      | 1    | 1396.72737    |
| 48    | csharp         | 1        | kinematics_rawd                                       | 6970   | 5.00068  | 1       | base      | yes      | 1    | 1393.81044    |
| 49    | csharp         | 1        | kinematics_raw32                                      | 6778   | 5.00003  | 1       | base      | yes      | 1    | 1355.59187    |
| 50    | csharp         | 1        | kinematics_raw6                                       | 6736   | 5.00011  | 1       | wheel     | yes      | 1    | 1347.17036    |
| 51    | nodejs         | 1        | rogiervandam                                          | 6736   | 5.00039  | 1       | base      | yes      | 1    | 1347.09444    |
| 52    | go             | 2        | ssovest-go                                            | 6284   | 5.00048  | 1       | base      | yes      | 1    | 1256.67986    |
| 53    | csharp         | 1        | kinematics_pool30                                     | 5991   | 5.00009  | 1       | wheel     | yes      | 1    | 1198.17843    |
| 54    | lisp           | 2        | mayerrobert-cl                                        | 5754   | 5.00001  | 1       | base      | no       | 1    | 1150.79862    |
| 55    | csharp         | 1        | kinematics_pool30m                                    | 5704   | 5.00005  | 1       | wheel     | yes      | 1    | 1140.78859    |
| 56    | typescript     | 1        | marghidanu                                            | 5575   | 5.00000  | 1       | base      | yes      |      | 1115.00000    |
| 57    | csharp         | 1        | kinematics_pool2of6                                   | 5252   | 5.00093  | 1       | wheel     | yes      | 1    | 1050.20466    |
| 58    | rust           | 3        | Blui42                                                | 4052   | 5.00013  | 1       | base      | yes      |      | 810.37917     |
| 59    | lua            | 2        | ben1jen_luajit1                                       | 3910   | 5.00000  | 1       | base      | no       | 1    | 782.00000     |
| 60    | nim            | 2        | beef331                                               | 2974   | 5.00076  | 1       | base      | yes      | 1    | 594.70908     |
| 61    | d              | 1        | eagerestwolf                                          | 2863   | 5.00000  | 1       | base      | yes      | 8    | 572.60000     |
| 62    | csharp         | 1        | kinematics_ibool                                      | 2830   | 5.00099  | 1       | base      | yes      |      | 565.88795     |
| 63    | csharp         | 1        | kinematics_pool                                       | 2808   | 5.00023  | 1       | base      | yes      | 1    | 561.57417     |
| 64    | nim            | 1        | marghidanu                                            | 2804   | 5.00005  | 1       | base      | yes      | 8    | 560.79492     |
| 65    | go             | 1        | bundgaard                                             | 2606   | 5.00106  | 1       | base      | yes      |      | 521.08984     |
| 66    | cython         | 1        | rpkak                                                 | 2572   | 5.00143  | 1       | base      | yes      | 8    | 514.25322     |
| 67    | csharp         | 1        | kinematics_bool                                       | 2448   | 5.00106  | 1       | base      | yes      |      | 489.49623     |
| 68    | basic          | 1        | rbergen_8of30                                         | 2428   | 5.00000  | 1       | wheel     | yes      | 1    | 485.60000     |
| 69    | assemblyscript | 1        | donmahallem                                           | 4534   | 10.00100 | 1       | base      | yes      |      | 453.35465     |
| 70    | octave         | 1        | octave                                                | 2177   | 5.00043  | 1       | base      | no       |      | 435.36256     |
| 71    | python         | 2        | ssovest                                               | 2083   | 5.00212  | 1       | base      | yes      | 8    | 416.42338     |
| 72    | fsharp         | 1        | rbergen                                               | 1775   | 5.00072  | 1       | base      | yes      | 1    | 354.94899     |
| 73    | csharp         | 1        | kinematics_standard                                   | 1646   | 5.00214  | 1       | base      | yes      | 1    | 329.05916     |
| 74    | basic          | 2        | rbergen_vb                                            | 1632   | 5.00293  | 1       | base      | yes      | 1    | 326.20906     |
| 75    | csharp         | 2        | davepl                                                | 2941   | 10.00240 | 1       | base      | yes      | 1    | 294.02943     |
| 76    | dart           | 1        | eagerestwolf                                          | 1399   | 5.00061  | 1       | base      | yes      |      | 279.76609     |
| 77    | scala          | 1        | rom1dep                                               | 1398   | 5.00200  | 1       | base      | yes      |      | 279.48820     |
| 78    | csharp         | 1        | kinematics_original                                   | 1357   | 5.00114  | 1       | base      | yes      | 1    | 271.33813     |
| 79    | pony           | 1        | marghidanu                                            | 1297   | 5.00000  | 1       | base      | yes      | 1    | 259.40000     |
| 80    | cobol          | 1        | fvbakel_Cobol                                         | 1228   | 5.00000  | 1       | base      | no       | 8    | 245.60000     |
| 81    | pascal         | 1        | rbergen                                               | 1214   | 5.00000  | 1       | base      | yes      |      | 242.80000     |
| 82    | swift          | 1        | j-f1                                                  | 2245   | 10.00072 | 1       | base      | yes      |      | 224.48392     |
| 83    | ada            | 1        | BoopBeepBoopBeep                                      | 751    | 5.00216  | 1       | base      | no       |      | 150.13507     |
| 84    | basic          | 1        | rbergen_boolean                                       | 732    | 5.00400  | 1       | base      | yes      |      | 146.28297     |
| 85    | haxe           | 1        | TayIorRobinson_Haxe_C++                               | 1427   | 10.00641 | 1       | base      | yes      |      | 142.60863     |
| 86    | ocaml          | 2        | gkpotter-unfaithful                                   | 712    | 5.00527  | 1       | base      | no       |      | 142.25004     |
| 87    | ocaml          | 1        | gkpotter-faithful                                     | 553    | 5.00402  | 1       | base      | yes      |      | 110.51122     |
| 88    | julia          | 1        | dcbi                                                  | 541    | 5.00454  | 1       | base      | yes      | 1    | 108.10174     |
| 89    | basic          | 1        | rbergen_bit32                                         | 478    | 5.00100  | 1       | base      | yes      | 1    | 95.58088      |
| 90    | basic          | 1        | rbergen_bit64                                         | 467    | 5.00900  | 1       | base      | yes      | 1    | 93.23218      |
| 91    | postscript     | 1        | epithet-ps                                            | 245    | 5.00100  | 1       | base      | no       | 8    | 48.99020      |
| 92    | ruby           | 1        | rbergen                                               | 148    | 5.00200  | 1       | base      | yes      |      | 29.58816      |
| 93    | wren           | 1        | marghidanu                                            | 120    | 5.00823  | 1       | base      | yes      |      | 23.96057      |
| 94    | php            | 1        | DennisdeBest                                          | 219    | 10.02587 | 1       | base      | yes      |      | 21.84350      |
| 95    | lisp           | 1        | mikehw                                                | 113    | 10.07001 | 1       | base      | no       | 1    | 11.22144      |
| 96    | smalltalk      | 1        | fvbakel_smalltalk                                     | 55     | 5.06900  | 1       | base      | yes      | 1    | 10.85027      |
| 97    | perl           | 1        | marghidanu                                            | 50     | 5.07497  | 1       | base      | yes      |      | 9.85228       |
| 98    | mixal          | 1        | rbergen                                               | 30     | 3.51000  | 1       | base      | no       | 1    | 8.54701       |
| 99    | haxe           | 1        | TayIorRobinson_Haxe_HaxeEval                          | 60     | 10.01609 | 1       | base      | yes      |      | 5.99036       |
| 100   | python         | 1        | davepl                                                | 47     | 10.10644 | 1       | base      | yes      |      | 4.65050       |
| 101   | r              | 1        | fvbakel_R                                             | 10     | 5.50700  | 1       | base      | yes      | 32   | 1.81587       |
| 102   | sql            | 2        | fvbakel_MariaDB3                                      | 9      | 5.38700  | 1       | other     | no       | 32   | 1.67069       |
| 103   | tcl            | 1        | fvbakeltcl                                            | 8      | 5.22400  | 1       | base      | yes      | 1    | 1.53139       |
| 104   | powershell     | 2        | crowbar27_ps2                                         | 8      | 5.67315  | 1       | base      | yes      | 1    | 1.41015       |
| 105   | sql            | 1        | fvbakel_sqlite                                        | 7      | 5.22281  | 1       | other     | no       | 8    | 1.34028       |
| 106   | haxe           | 1        | TayIorRobinson_Haxe_Python                            | 13     | 10.47694 | 1       | base      | yes      |      | 1.24082       |
| 107   | tcl            | 2        | fvbakel_ootcl                                         | 7      | 5.68200  | 1       | base      | yes      | 1    | 1.23196       |
| 108   | sql            | 2        | fvbakel_MariaDB2                                      | 6      | 5.57900  | 1       | other     | no       | 32   | 1.07546       |
| 109   | sql            | 2        | fvbakel_MariaDB1                                      | 1      | 5.91500  | 1       | base      | no       | 32   | 0.16906       |
| 110   | latex          | 1        | tjol                                                  | 2      | 12.82645 | 1       | base      | no       | 32   | 0.15593       |
| 111   | bash           | 1        | bash                                                  | 1      | 7.42022  | 1       | base      | no       |      | 0.13477       |
| 112   | lua            | 1        | lua                                                   | 1      | 26.00000 | 1       | base      | no       | 64   | 0.03846       |
| 113   | powershell     | 1        | crowbar27_ps1                                         | 1      | 52.12820 | 1       | base      | yes      | 1    | 0.01918       |

### Multi-threaded

| Index | Implementation | Solution | Label                                                             | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-5760of30030  | 379918 | 5.00020  | 32      | wheel     | yes      | 1    | 2374.39252    |
| 2     | cpp            | 3        | flo80_constexpr                                                   | 367328 | 5.00010  | 32      | base      | no       | 1    | 2295.75454    |
| 3     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-480of2310    | 349231 | 5.00036  | 32      | wheel     | yes      | 1    | 2182.53661    |
| 4     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-480of2310   | 341622 | 5.00003  | 32      | wheel     | yes      | 1    | 2135.12469    |
| 5     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-5760of30030 | 325192 | 5.00026  | 32      | wheel     | yes      | 1    | 2032.34432    |
| 6     | c              | 2        | danielspaangberg_5760of30030_par                                  | 29870  | 5.00011  | 4       | wheel     | yes      | 1    | 1493.46834    |
| 7     | c              | 2        | danielspaangberg_480of2310_par                                    | 29067  | 5.00012  | 4       | wheel     | yes      | 1    | 1453.31541    |
| 8     | c              | 2        | danielspaangberg_48of210_par                                      | 27570  | 5.00015  | 4       | wheel     | yes      | 1    | 1378.45782    |
| 9     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-sieve-u8                 | 203789 | 5.00033  | 32      | base      | yes      | 8    | 1273.59719    |
| 10    | rust           | 1        | mike-barber_byte-storage                                          | 202672 | 5.00084  | 32      | base      | yes      | 8    | 1266.48827    |
| 11    | c              | 2        | danielspaangberg_8of30_par                                        | 25008  | 5.00012  | 4       | wheel     | yes      | 1    | 1250.36874    |
| 12    | c              | 2        | danielspaangberg_5760of30030_epar                                 | 200042 | 5.00547  | 32      | wheel     | yes      | 1    | 1248.89596    |
| 13    | c              | 2        | danielspaangberg_480of2310_epar                                   | 177743 | 5.00904  | 32      | wheel     | yes      | 1    | 1108.88976    |
| 14    | rust           | 1        | mike-barber_bit-storage-rotate                                    | 167167 | 5.00104  | 32      | base      | yes      | 1    | 1044.57628    |
| 15    | rust           | 1        | mike-barber_bit-storage                                           | 163797 | 5.00095  | 32      | base      | yes      | 1    | 1023.53729    |
| 16    | c              | 2        | danielspaangberg_48of210_epar                                     | 163730 | 5.00656  | 32      | wheel     | yes      | 1    | 1021.97106    |
| 17    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8              | 162733 | 5.00060  | 32      | base      | yes      | 1    | 1016.95921    |
| 18    | c              | 2        | danielspaangberg_1of2_par                                         | 20291  | 5.00015  | 4       | base      | yes      | 1    | 1014.51977    |
| 19    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64             | 156600 | 5.00053  | 32      | base      | yes      | 1    | 978.64626     |
| 20    | c              | 2        | danielspaangberg_1of2_epar                                        | 144596 | 5.01536  | 32      | base      | yes      | 1    | 900.95744     |
| 21    | c              | 2        | danielspaangberg_8of30_epar                                       | 133367 | 5.01430  | 32      | wheel     | yes      | 1    | 831.16661     |
| 22    | cpp            | 2        | davepl_par                                                        | 107296 | 5.00125  | 32      | base      | yes      | 1    | 670.43239     |
| 23    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-amdahl-sieve-u8                    | 10132  | 5.00010  | 32      | base      | yes      | 8    | 63.32373      |
| 24    | csharp         | 1        | kinematics_rawp                                                   | 3365   | 5.00128  | 32      | base      | yes      | 1    | 21.02587      |
| 25    | csharp         | 1        | kinematics_pool6p                                                 | 3308   | 5.00150  | 32      | wheel     | yes      | 1    | 20.66880      |
