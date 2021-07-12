# PrimesResult

The results of the [David Plummer's Primes Drag Race](https://github.com/PlummersSoftwareLLC/Primes).

## Results

Generated at 2021-07-12 on a Ryzen 9 5950X with 32GB RAM.

### Best faithful performers for each language

| Implementation | Slowness   | Position | Index | Solution | Label                                                 | Passes | Duration | Threads | Algorithm | Bits | Passes/Second |
| -------------- | ---------- | -------- | ----- | -------- | ----------------------------------------------------- | ------ | -------- | ------- | --------- | ---- | ------------- |
| zig            | 1.0000     | 1        | 2     | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 27181  | 5.00016  | 1       | wheel     | 1    | 5436.02605    |
| c              | 1.0748     | 2        | 4     | 2        | danielspaangberg_48of210                              | 25289  | 5.00011  | 1       | wheel     | 1    | 5057.68873    |
| rust           | 1.3958     | 3        | 8     | 1        | mike-barber_byte-storage                              | 19474  | 5.00016  | 1       | base      | 8    | 3894.67594    |
| v              | 1.6278     | 5        | 12    | 1        | marghidanu                                            | 16697  | 5.00000  | 1       | base      |      | 3339.40000    |
| assembly       | 1.9905     | 6        | 17    | 1        | rbergen_x64ff_byte                                    | 13655  | 5.00000  | 1       | base      | 8    | 2731.00000    |
| crystal        | 2.3139     | 7        | 24    | 1        | marghidanu                                            | 11747  | 5.00016  | 1       | base      | 1    | 2349.32529    |
| fsharp         | 2.3290     | 8        | 25    | 3        | dmannock_fsharp_recursion                             | 11671  | 5.00030  | 1       | base      |      | 2334.05996    |
| csharp         | 2.7257     | 9        | 32    | 1        | kinematics_dbool                                      | 9972   | 5.00017  | 1       | base      |      | 1994.33219    |
| cpp            | 2.7690     | 10       | 35    | 1        | davepl                                                | 9816   | 5.00007  | 1       | base      | 1    | 1963.17330    |
| java           | 2.8627     | 11       | 37    | 1        | MansenC                                               | 18989  | 10.00000 | 1       | base      |      | 1898.90000    |
| julia          | 3.4456     | 12       | 45    | 2        | epithet-jl                                            | 7889   | 5.00039  | 1       | base      | 1    | 1577.67632    |
| dart           | 3.9191     | 13       | 50    | 1        | eagerestwolf&mmcdon20                                 | 6936   | 5.00053  | 1       | base      | 8    | 1387.05408    |
| d              | 3.9973     | 15       | 51    | 2        | BradleyChatha                                         | 6800   | 5.00034  | 1       | base      | 1    | 1359.90753    |
| nodejs         | 4.0447     | 16       | 55    | 1        | rogiervandam                                          | 6720   | 5.00007  | 1       | base      | 1    | 1343.98038    |
| typescript     | 4.7221     | 17       | 58    | 1        | marghidanu                                            | 5756   | 5.00000  | 1       | base      |      | 1151.20000    |
| go             | 5.8861     | 18       | 60    | 2        | ssovest-go                                            | 4618   | 5.00037  | 1       | base      | 1    | 923.53199     |
| nim            | 8.9986     | 19       | 64    | 2        | beef331                                               | 3021   | 5.00083  | 1       | base      | 1    | 604.10013     |
| cython         | 10.376     | 20       | 69    | 1        | rpkak                                                 | 2620   | 5.00078  | 1       | base      | 8    | 523.91810     |
| basic          | 11.094     | 21       | 71    | 1        | rbergen_8of30                                         | 2451   | 5.00200  | 1       | wheel     | 1    | 490.00400     |
| assemblyscript | 11.802     | 22       | 73    | 1        | donmahallem                                           | 4606   | 10.00000 | 1       | base      |      | 460.60000     |
| python         | 12.967     | 23       | 75    | 2        | ssovest                                               | 2097   | 5.00223  | 1       | base      | 8    | 419.21323     |
| scala          | 19.422     | 25       | 80    | 1        | rom1dep                                               | 1400   | 5.00200  | 1       | base      |      | 279.88804     |
| pony           | 21.503     | 26       | 82    | 1        | marghidanu                                            | 1264   | 5.00000  | 1       | base      | 1    | 252.80000     |
| pascal         | 22.352     | 27       | 84    | 1        | rbergen                                               | 1216   | 5.00000  | 1       | base      |      | 243.20000     |
| swift          | 24.768     | 28       | 86    | 1        | j-f1                                                  | 2195   | 10.00107 | 1       | base      |      | 219.47643     |
| r              | 27.985     | 29       | 87    | 1        | fvbakel_R                                             | 972    | 5.00400  | 1       | base      | 32   | 194.24460     |
| haxe           | 38.015     | 30       | 89    | 1        | TayIorRobinson_Haxe_C++                               | 1430   | 10.00013 | 1       | base      |      | 142.99814     |
| ocaml          | 47.535     | 31       | 91    | 1        | gkpotter-faithful                                     | 572    | 5.00187  | 1       | base      |      | 114.35732     |
| ballerina      | 168.82     | 32       | 98    | 1        | da-strange-boi                                        | 161    | 5.00000  | 1       | base      | 1    | 32.20000      |
| ruby           | 178.36     | 33       | 99    | 1        | rbergen                                               | 153    | 5.02000  | 1       | base      |      | 30.47809      |
| wren           | 231.57     | 35       | 100   | 1        | marghidanu                                            | 118    | 5.02670  | 1       | base      |      | 23.47463      |
| php            | 253.25     | 36       | 101   | 1        | DennisdeBest                                          | 215    | 10.01646 | 1       | base      |      | 21.46468      |
| smalltalk      | 509.38     | 37       | 103   | 1        | fvbakel_smalltalk                                     | 54     | 5.06000  | 1       | base      | 1    | 10.67194      |
| tcl            | 595.48     | 38       | 104   | 2        | fvbakel_ootcl2                                        | 46     | 5.03900  | 1       | base      | 32   | 9.12880       |
| perl           | 598.41     | 39       | 105   | 1        | marghidanu                                            | 46     | 5.06377  | 1       | base      |      | 9.08413       |
| powershell     | 3898.1     | 40       | 111   | 2        | crowbar27_ps2                                         | 7      | 5.01966  | 1       | base      | 1    | 1.39452       |
| prolog         | 3.3508e+04 | 41       | 117   | 1        | jimbxb_prolog                                         | 1      | 6.16400  | 1       | base      | 1    | 0.16223       |

### Single-threaded

| Index | Implementation | Solution | Label                                                 | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | cpp            | 3        | flo80_constexpr                                       | 186501 | 5.00001  | 1       | base      | no       | 1    | 37300.12540   |
| 2     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 27181  | 5.00016  | 1       | wheel     | yes      | 1    | 5436.02605    |
| 3     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030  | 27163  | 5.00001  | 1       | wheel     | yes      | 1    | 5432.58913    |
| 4     | c              | 2        | danielspaangberg_48of210                              | 25289  | 5.00011  | 1       | wheel     | yes      | 1    | 5057.68873    |
| 5     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-480of2310    | 24997  | 5.00005  | 1       | wheel     | yes      | 1    | 4999.35001    |
| 6     | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-480of2310   | 23315  | 5.00002  | 1       | wheel     | yes      | 1    | 4662.98135    |
| 7     | c              | 2        | danielspaangberg_8of30                                | 20650  | 5.00021  | 1       | wheel     | yes      | 1    | 4129.82655    |
| 8     | rust           | 1        | mike-barber_byte-storage                              | 19474  | 5.00016  | 1       | base      | yes      | 8    | 3894.67594    |
| 9     | zig            | 2        | ManDeJan&ityonemo-zig-byte-sieve-type-bool            | 19343  | 5.00023  | 1       | base      | yes      | 8    | 3868.42205    |
| 10    | assembly       | 1        | rbergen_x64uff_byte                                   | 18918  | 5.00000  | 1       | base      | no       | 8    | 3783.60000    |
| 11    | c              | 2        | danielspaangberg_5760of30030_owrb                     | 18902  | 5.00016  | 1       | wheel     | yes      | 1    | 3780.27828    |
| 12    | v              | 1        | marghidanu                                            | 16697  | 5.00000  | 1       | base      | yes      |      | 3339.40000    |
| 13    | haskell        | 1        | fatho/vector_unchecked                                | 16173  | 5.00014  | 1       | base      | no       | 8    | 3234.51202    |
| 14    | c              | 2        | danielspaangberg_480of2310_owrb                       | 16100  | 5.00020  | 1       | wheel     | yes      | 1    | 3219.87056    |
| 15    | zig            | 1        | devblok                                               | 16018  | 5.00011  | 1       | base      | yes      | 8    | 3203.52952    |
| 16    | ada            | 1        | BoopBeepBoopBeep                                      | 15823  | 5.00005  | 1       | base      | no       |      | 3164.56853    |
| 17    | assembly       | 1        | rbergen_x64ff_byte                                    | 13655  | 5.00000  | 1       | base      | yes      | 8    | 2731.00000    |
| 18    | haskell        | 1        | fatho/vector                                          | 13635  | 5.00009  | 1       | base      | no       | 8    | 2726.94982    |
| 19    | fortran        | 1        | johandweber_fortran                                   | 13365  | 5.00000  | 1       | base      | no       | 1    | 2673.00000    |
| 20    | c              | 1        | mckoss-c830                                           | 13002  | 5.00000  | 1       | wheel     | yes      | 1    | 2600.40000    |
| 21    | c              | 2        | danielspaangberg_48of210_owrb                         | 12844  | 5.00036  | 1       | wheel     | yes      | 1    | 2568.61711    |
| 22    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8              | 12658  | 5.00038  | 1       | base      | yes      | 1    | 2531.40761    |
| 23    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8                 | 12221  | 5.00014  | 1       | base      | yes      | 8    | 2444.13156    |
| 24    | crystal        | 1        | marghidanu                                            | 11747  | 5.00016  | 1       | base      | yes      | 1    | 2349.32529    |
| 25    | fsharp         | 3        | dmannock_fsharp_recursion                             | 11671  | 5.00030  | 1       | base      | yes      |      | 2334.05996    |
| 26    | fsharp         | 2        | dmannock_fsharp_port                                  | 11663  | 5.00037  | 1       | base      | yes      |      | 2332.42600    |
| 27    | zig            | 2        | ManDeJan&ityonemo-zig-bit-sieve                       | 11550  | 5.00024  | 1       | base      | yes      | 1    | 2309.88913    |
| 28    | c              | 2        | danielspaangberg_1of2                                 | 11528  | 5.00004  | 1       | base      | yes      | 1    | 2305.58248    |
| 29    | haskell        | 1        | fatho/bitset                                          | 11419  | 5.00039  | 1       | base      | no       | 1    | 2283.62279    |
| 30    | rust           | 2        | Azgrom                                                | 10717  | 5.00024  | 1       | base      | yes      |      | 2143.29781    |
| 31    | rust           | 1        | mike-barber_bit-storage                               | 10539  | 5.00006  | 1       | base      | yes      | 1    | 2107.77528    |
| 32    | csharp         | 1        | kinematics_dbool                                      | 9972   | 5.00017  | 1       | base      | yes      |      | 1994.33219    |
| 33    | c              | 2        | danielspaangberg_8of30_owrb                           | 9897   | 5.00013  | 1       | wheel     | yes      | 1    | 1979.34775    |
| 34    | rust           | 1        | mike-barber_bit-storage-rotate                        | 9835   | 5.00028  | 1       | base      | yes      | 1    | 1966.88802    |
| 35    | cpp            | 1        | davepl                                                | 9816   | 5.00007  | 1       | base      | yes      | 1    | 1963.17330    |
| 36    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-bool               | 9714   | 5.00015  | 1       | base      | yes      | 8    | 1942.74172    |
| 37    | java           | 1        | MansenC                                               | 18989  | 10.00000 | 1       | base      | yes      |      | 1898.90000    |
| 38    | haskell        | 1        | fatho/bitset_unchecked                                | 9401   | 5.00049  | 1       | base      | no       | 1    | 1880.01501    |
| 39    | python         | 3        | emillynge_numpy                                       | 9378   | 5.00052  | 1       | base      | no       | 8    | 1875.40487    |
| 40    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-5760of30030     | 9229   | 5.00040  | 1       | wheel     | yes      | 8    | 1845.65235    |
| 41    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-480of2310       | 8902   | 5.00001  | 1       | wheel     | yes      | 8    | 1780.39644    |
| 42    | rust           | 4        | joshallen64                                           | 8775   | 5.00031  | 1       | base      | yes      |      | 1754.88944    |
| 43    | assembly       | 1        | rbergen_x64ff_bitshift                                | 8503   | 5.00000  | 1       | base      | yes      | 1    | 1700.60000    |
| 44    | assembly       | 1        | rbergen_x64uff_bitshift                               | 7954   | 5.00000  | 1       | base      | no       | 1    | 1590.80000    |
| 45    | julia          | 2        | epithet-jl                                            | 7889   | 5.00039  | 1       | base      | yes      | 1    | 1577.67632    |
| 46    | csharp         | 3        | tannergooding                                         | 7849   | 5.00051  | 1       | base      | yes      | 1    | 1569.63955    |
| 47    | assembly       | 1        | rbergen_x64uff_bitbtr                                 | 7577   | 5.00000  | 1       | base      | no       | 1    | 1515.40000    |
| 48    | assembly       | 1        | rbergen_x64ff_bitbtr                                  | 7309   | 5.00000  | 1       | base      | yes      | 1    | 1461.80000    |
| 49    | csharp         | 1        | kinematics_rawd                                       | 6981   | 5.00045  | 1       | base      | yes      | 1    | 1396.07435    |
| 50    | dart           | 1        | eagerestwolf&mmcdon20                                 | 6936   | 5.00053  | 1       | base      | yes      | 8    | 1387.05408    |
| 51    | d              | 2        | BradleyChatha                                         | 6800   | 5.00034  | 1       | base      | yes      | 1    | 1359.90753    |
| 52    | csharp         | 1        | kinematics_raw32                                      | 6764   | 5.00026  | 1       | base      | yes      | 1    | 1352.72966    |
| 53    | csharp         | 1        | kinematics_raw6                                       | 6759   | 5.00027  | 1       | wheel     | yes      | 1    | 1351.72701    |
| 54    | csharp         | 1        | kinematics_raw                                        | 6750   | 5.00069  | 1       | base      | yes      | 1    | 1349.81373    |
| 55    | nodejs         | 1        | rogiervandam                                          | 6720   | 5.00007  | 1       | base      | yes      | 1    | 1343.98038    |
| 56    | csharp         | 1        | kinematics_pool30                                     | 6187   | 5.00031  | 1       | wheel     | yes      | 1    | 1237.32329    |
| 57    | csharp         | 1        | kinematics_pool30m                                    | 5811   | 5.00020  | 1       | wheel     | yes      | 1    | 1162.15351    |
| 58    | typescript     | 1        | marghidanu                                            | 5756   | 5.00000  | 1       | base      | yes      |      | 1151.20000    |
| 59    | csharp         | 1        | kinematics_pool2of6                                   | 5057   | 5.00009  | 1       | wheel     | yes      | 1    | 1011.38180    |
| 60    | go             | 2        | ssovest-go                                            | 4618   | 5.00037  | 1       | base      | yes      | 1    | 923.53199     |
| 61    | java           | 2        | PratimGhosh86                                         | 4157   | 5.00000  | 1       | base      | yes      | 1    | 831.40000     |
| 62    | lua            | 2        | ben1jen_luajit1                                       | 4057   | 5.00000  | 1       | base      | no       | 1    | 811.40000     |
| 63    | rust           | 3        | Blui42                                                | 3982   | 5.00035  | 1       | base      | yes      |      | 796.34475     |
| 64    | nim            | 2        | beef331                                               | 3021   | 5.00083  | 1       | base      | yes      | 1    | 604.10013     |
| 65    | nim            | 1        | marghidanu                                            | 2848   | 5.00054  | 1       | base      | yes      | 8    | 569.53892     |
| 66    | csharp         | 1        | kinematics_ibool                                      | 2815   | 5.00011  | 1       | base      | yes      |      | 562.98761     |
| 67    | d              | 1        | eagerestwolf                                          | 2795   | 5.00000  | 1       | base      | yes      | 8    | 559.00000     |
| 68    | csharp         | 1        | kinematics_pool                                       | 2753   | 5.00015  | 1       | base      | yes      | 1    | 550.58348     |
| 69    | cython         | 1        | rpkak                                                 | 2620   | 5.00078  | 1       | base      | yes      | 8    | 523.91810     |
| 70    | go             | 1        | bundgaard                                             | 2591   | 5.00113  | 1       | base      | yes      |      | 518.08343     |
| 71    | basic          | 1        | rbergen_8of30                                         | 2451   | 5.00200  | 1       | wheel     | yes      | 1    | 490.00400     |
| 72    | csharp         | 1        | kinematics_bool                                       | 2444   | 5.00024  | 1       | base      | yes      |      | 488.77654     |
| 73    | assemblyscript | 1        | donmahallem                                           | 4606   | 10.00000 | 1       | base      | yes      |      | 460.60000     |
| 74    | octave         | 1        | octave                                                | 2209   | 5.00141  | 1       | base      | no       |      | 441.67545     |
| 75    | python         | 2        | ssovest                                               | 2097   | 5.00223  | 1       | base      | yes      | 8    | 419.21323     |
| 76    | fsharp         | 1        | rbergen                                               | 1810   | 5.00213  | 1       | base      | yes      | 1    | 361.84561     |
| 77    | csharp         | 1        | kinematics_standard                                   | 1644   | 5.00198  | 1       | base      | yes      | 1    | 328.66985     |
| 78    | basic          | 2        | rbergen_vb                                            | 1636   | 5.00181  | 1       | base      | yes      | 1    | 327.08130     |
| 79    | csharp         | 2        | davepl                                                | 3034   | 10.00050 | 1       | base      | yes      | 1    | 303.38483     |
| 80    | scala          | 1        | rom1dep                                               | 1400   | 5.00200  | 1       | base      | yes      |      | 279.88804     |
| 81    | csharp         | 1        | kinematics_original                                   | 1321   | 5.00365  | 1       | base      | yes      | 1    | 264.00727     |
| 82    | pony           | 1        | marghidanu                                            | 1264   | 5.00000  | 1       | base      | yes      | 1    | 252.80000     |
| 83    | cobol          | 1        | fvbakel_Cobol                                         | 1233   | 5.00000  | 1       | base      | no       | 8    | 246.60000     |
| 84    | pascal         | 1        | rbergen                                               | 1216   | 5.00000  | 1       | base      | yes      |      | 243.20000     |
| 85    | pascal         | 2        | circular17                                            | 1186   | 5.00000  | 1       | base      | yes      | 1    | 237.20000     |
| 86    | swift          | 1        | j-f1                                                  | 2195   | 10.00107 | 1       | base      | yes      |      | 219.47643     |
| 87    | r              | 1        | fvbakel_R                                             | 972    | 5.00400  | 1       | base      | yes      | 32   | 194.24460     |
| 88    | basic          | 1        | rbergen_boolean                                       | 751    | 5.00600  | 1       | base      | yes      |      | 150.01998     |
| 89    | haxe           | 1        | TayIorRobinson_Haxe_C++                               | 1430   | 10.00013 | 1       | base      | yes      |      | 142.99814     |
| 90    | ocaml          | 2        | gkpotter-unfaithful                                   | 712    | 5.00373  | 1       | base      | no       |      | 142.29379     |
| 91    | ocaml          | 1        | gkpotter-faithful                                     | 572    | 5.00187  | 1       | base      | yes      |      | 114.35732     |
| 92    | julia          | 1        | dcbi                                                  | 547    | 5.00869  | 1       | base      | yes      | 1    | 109.21028     |
| 93    | forth          | 1        | tjol-8bit                                             | 479    | 5.00903  | 1       | base      | no       | 8    | 95.62735      |
| 94    | basic          | 1        | rbergen_bit32                                         | 477    | 5.00800  | 1       | base      | yes      | 1    | 95.24760      |
| 95    | basic          | 1        | rbergen_bit64                                         | 474    | 5.00700  | 1       | base      | yes      | 1    | 94.66747      |
| 96    | forth          | 1        | tjol-1bit                                             | 342    | 5.00074  | 1       | base      | no       | 1    | 68.38984      |
| 97    | postscript     | 1        | epithet-ps                                            | 250    | 5.00700  | 1       | base      | no       | 8    | 49.93010      |
| 98    | ballerina      | 1        | da-strange-boi                                        | 161    | 5.00000  | 1       | base      | yes      | 1    | 32.20000      |
| 99    | ruby           | 1        | rbergen                                               | 153    | 5.02000  | 1       | base      | yes      |      | 30.47809      |
| 100   | wren           | 1        | marghidanu                                            | 118    | 5.02670  | 1       | base      | yes      |      | 23.47463      |
| 101   | php            | 1        | DennisdeBest                                          | 215    | 10.01646 | 1       | base      | yes      |      | 21.46468      |
| 102   | lisp           | 1        | mikehw                                                | 113    | 10.04003 | 1       | base      | no       | 1    | 11.25494      |
| 103   | smalltalk      | 1        | fvbakel_smalltalk                                     | 54     | 5.06000  | 1       | base      | yes      | 1    | 10.67194      |
| 104   | tcl            | 2        | fvbakel_ootcl2                                        | 46     | 5.03900  | 1       | base      | yes      | 32   | 9.12880       |
| 105   | perl           | 1        | marghidanu                                            | 46     | 5.06377  | 1       | base      | yes      |      | 9.08413       |
| 106   | mixal          | 1        | rbergen                                               | 30     | 3.59000  | 1       | base      | no       | 1    | 8.35655       |
| 107   | haxe           | 1        | TayIorRobinson_Haxe_HaxeEval                          | 61     | 10.14118 | 1       | base      | yes      |      | 6.01508       |
| 108   | python         | 1        | davepl                                                | 48     | 10.14735 | 1       | base      | yes      |      | 4.73030       |
| 109   | sql            | 2        | fvbakel_MariaDB3                                      | 9      | 5.35700  | 1       | other     | no       | 32   | 1.68004       |
| 110   | tcl            | 1        | fvbakeltcl                                            | 8      | 5.17200  | 1       | base      | yes      | 1    | 1.54679       |
| 111   | powershell     | 2        | crowbar27_ps2                                         | 7      | 5.01966  | 1       | base      | yes      | 1    | 1.39452       |
| 112   | sql            | 1        | fvbakel_sqlite                                        | 7      | 5.08857  | 1       | other     | no       | 8    | 1.37563       |
| 113   | haxe           | 1        | TayIorRobinson_Haxe_Python                            | 13     | 10.31061 | 1       | base      | yes      |      | 1.26084       |
| 114   | tcl            | 2        | fvbakel_ootcl                                         | 7      | 5.72300  | 1       | base      | yes      | 1    | 1.22313       |
| 115   | sql            | 2        | fvbakel_MariaDB2                                      | 6      | 5.51900  | 1       | other     | no       | 32   | 1.08715       |
| 116   | sql            | 2        | fvbakel_MariaDB1                                      | 1      | 5.70300  | 1       | base      | no       | 32   | 0.17535       |
| 117   | prolog         | 1        | jimbxb_prolog                                         | 1      | 6.16400  | 1       | base      | yes      | 1    | 0.16223       |
| 118   | latex          | 1        | tjol                                                  | 2      | 12.98419 | 1       | base      | no       | 32   | 0.15403       |
| 119   | bash           | 1        | bash                                                  | 1      | 7.54277  | 1       | base      | no       |      | 0.13258       |
| 120   | elixir         | 1        | cdesch                                                | 1      | 24.54900 | 1       | base      | no       |      | 0.04073       |
| 121   | lua            | 1        | lua                                                   | 1      | 25.00000 | 1       | base      | no       | 64   | 0.04000       |
| 122   | powershell     | 1        | crowbar27_ps1                                         | 1      | 52.70770 | 1       | base      | yes      | 1    | 0.01897       |

### Multi-threaded

| Index | Implementation | Solution | Label                                                             | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-5760of30030  | 384599 | 5.00011  | 32      | wheel     | yes      | 1    | 2403.69087    |
| 2     | cpp            | 3        | flo80_constexpr                                                   | 364352 | 5.00028  | 32      | base      | no       | 1    | 2277.07112    |
| 3     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-480of2310    | 356576 | 5.00042  | 32      | wheel     | yes      | 1    | 2228.41281    |
| 4     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-480of2310   | 345147 | 5.00022  | 32      | wheel     | yes      | 1    | 2157.07384    |
| 5     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-5760of30030 | 327391 | 5.00015  | 32      | wheel     | yes      | 1    | 2046.13237    |
| 6     | c              | 2        | danielspaangberg_5760of30030_par                                  | 30434  | 5.00001  | 4       | wheel     | yes      | 1    | 1521.69696    |
| 7     | c              | 2        | danielspaangberg_480of2310_par                                    | 28080  | 5.00013  | 4       | wheel     | yes      | 1    | 1403.96322    |
| 8     | c              | 2        | danielspaangberg_48of210_par                                      | 26615  | 5.00015  | 4       | wheel     | yes      | 1    | 1330.70955    |
| 9     | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-sieve-u8                 | 204816 | 5.00031  | 32      | base      | yes      | 8    | 1280.02064    |
| 10    | rust           | 1        | mike-barber_byte-storage                                          | 202186 | 5.00092  | 32      | base      | yes      | 8    | 1263.43032    |
| 11    | c              | 2        | danielspaangberg_5760of30030_epar                                 | 201962 | 5.00842  | 32      | wheel     | yes      | 1    | 1260.13942    |
| 12    | c              | 2        | danielspaangberg_8of30_par                                        | 25160  | 5.00004  | 4       | wheel     | yes      | 1    | 1257.99069    |
| 13    | c              | 2        | danielspaangberg_480of2310_epar                                   | 183833 | 5.00600  | 32      | wheel     | yes      | 1    | 1147.57984    |
| 14    | c              | 2        | danielspaangberg_48of210_epar                                     | 169200 | 5.00556  | 32      | wheel     | yes      | 1    | 1056.32431    |
| 15    | rust           | 1        | mike-barber_bit-storage-rotate                                    | 168624 | 5.00095  | 32      | base      | yes      | 1    | 1053.69973    |
| 16    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8              | 165244 | 5.00074  | 32      | base      | yes      | 1    | 1032.62217    |
| 17    | rust           | 1        | mike-barber_bit-storage                                           | 165131 | 5.00097  | 32      | base      | yes      | 1    | 1031.86790    |
| 18    | c              | 2        | danielspaangberg_1of2_par                                         | 19755  | 5.00010  | 4       | base      | yes      | 1    | 987.72946     |
| 19    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64             | 157663 | 5.00015  | 32      | base      | yes      | 1    | 985.36419     |
| 20    | c              | 2        | danielspaangberg_1of2_epar                                        | 148160 | 5.00587  | 32      | base      | yes      | 1    | 924.91434     |
| 21    | c              | 2        | danielspaangberg_8of30_epar                                       | 138141 | 5.00678  | 32      | wheel     | yes      | 1    | 862.21140     |
| 22    | d              | 2        | BradleyChatha-Multi                                               | 101089 | 5.00016  | 32      | base      | yes      | 1    | 631.78603     |
| 23    | nodejs         | 1        | rogiervandam                                                      | 100999 | 5.09187  | 32      | base      | yes      | 1    | 619.85467     |
| 24    | cpp            | 2        | davepl_par                                                        | 94464  | 5.00061  | 32      | base      | yes      | 1    | 590.32798     |
| 25    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-amdahl-sieve-u8                    | 10399  | 5.00026  | 32      | base      | yes      | 8    | 64.99037      |
| 26    | csharp         | 1        | kinematics_rawp                                                   | 3467   | 5.00011  | 32      | base      | yes      | 1    | 21.66827      |
| 27    | csharp         | 1        | kinematics_pool6p                                                 | 3372   | 5.00099  | 32      | wheel     | yes      | 1    | 21.07083      |
