# PrimesResult

The results of the [David Plummer's Primes Drag Race](https://github.com/PlummersSoftwareLLC/Primes).

## Results

Generated at 2021-09-12 on a Ryzen 9 5950X with 32GB RAM.

### Best faithful performers for each language

| Implementation | Slowness   | Position | Index | Solution | Label                                                 | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| -------------- | ---------- | -------- | ----- | -------- | ----------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| rust           | 1          | 1        | 6     | 1        | mike-barber_bit-unrolled-hybrid                       | 65997  | 5.00004  | 1       | base      | yes      | 1    | 13199.29552   |
| nim            | 1.0672     | 2        | 7     | 3        | GordonBGood_extreme_hybrid                            | 61844  | 5.00003  | 1       | base      | yes      | 1    | 12368.72956   |
| crystal        | 1.2782     | 3        | 8     | 2        | GordonBGood_extreme-hybrid                            | 51633  | 5.00007  | 1       | base      | yes      | 1    | 10326.46576   |
| chapel         | 1.4356     | 4        | 9     | 1        | GordonBGood_unrolled_hybrid                           | 45971  | 5.00003  | 1       | base      | yes      | 1    | 9194.14484    |
| v              | 1.4646     | 5        | 10    | 2        | GordonBGood_extreme-hybrid                            | 45062  | 5.00005  | 1       | base      | yes      | 1    | 9012.31168    |
| c              | 1.4905     | 6        | 11    | 3        | fvbakel_Cwords                                        | 44279  | 5.00000  | 1       | other     | yes      | 1    | 8855.79292    |
| cython         | 1.5865     | 7        | 12    | 1        | ssovest-cy                                            | 41598  | 5.00006  | 1       | other     | yes      | 1    | 8319.50849    |
| cpp            | 2.1590     | 8        | 14    | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc           | 30569  | 5.00010  | 1       | wheel     | yes      | 8    | 6113.67773    |
| zig            | 2.4313     | 9        | 20    | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 27145  | 5.00011  | 1       | wheel     | yes      | 1    | 5428.88056    |
| go             | 2.6729     | 10       | 30    | 2        | ssovest-go-other-u64                                  | 24697  | 5.00124  | 1       | other     | yes      | 1    | 4938.17250    |
| julia          | 2.8110     | 11       | 33    | 4        | GordonBGood_unpeeled                                  | 23479  | 5.00018  | 1       | base      | yes      | 1    | 4695.62647    |
| csharp         | 2.8550     | 12       | 36    | 4        | italytoast-stride8-blocks32k                          | 23117  | 5.00012  | 1       | base      | yes      | 1    | 4623.28904    |
| amd64          | 3.2689     | 13       | 47    | 1        | dacvs8                                                | 20189  | 5.00000  | 1       | base      | yes      | 8    | 4037.79919    |
| lisp           | 3.3109     | 14       | 51    | 2        | mayerrobert-cl-words                                  | 19933  | 5.00001  | 1       | other     | yes      | 1    | 3986.59043    |
| fortran        | 3.4027     | 15       | 54    | 2        | tjol-8bit                                             | 19396  | 5.00012  | 1       | base      | yes      | 8    | 3879.10789    |
| haskell        | 3.4281     | 16       | 56    | 2        | GordonBGood_unpeeled_block                            | 19252  | 5.00007  | 1       | base      | yes      | 1    | 3850.34538    |
| fsharp         | 3.7003     | 17       | 58    | 4        | GordonBGood_unpeeled                                  | 17836  | 5.00014  | 1       | base      | yes      | 1    | 3567.10155    |
| java           | 3.7997     | 18       | 63    | 4        | chrvanorleStrided32Blocks16k                          | 17369  | 5.00000  | 1       | base      | yes      | 1    | 3473.80000    |
| swift          | 3.8746     | 19       | 65    | 1        | yellowcub_striped_UInt8                               | 17034  | 5.00026  | 1       | base      | yes      | 1    | 3406.62148    |
| assemblyscript | 3.9396     | 20       | 66    | 2        | maxgraey_unrolled                                     | 16752  | 5.00000  | 1       | base      | yes      | 1    | 3350.40000    |
| assembly       | 4.6641     | 21       | 81    | 1        | rbergen_x64ff_byte                                    | 14150  | 5.00000  | 1       | base      | yes      | 8    | 2830.00000    |
| odin           | 4.7432     | 22       | 82    | 1        | odin_byte_moe                                         | 13914  | 5.00000  | 1       | base      | yes      | 8    | 2782.80000    |
| nodejs         | 6.1245     | 23       | 108   | 1        | rogiervandam_memcopy                                  | 10776  | 5.00007  | 1       | other     | yes      | 1    | 2155.17003    |
| clojure        | 6.1381     | 24       | 109   | 2        | axvr_clj-sln-2_8-bit                                  | 10753  | 5.00052  | 1       | base      | yes      | 8    | 2150.37711    |
| scala          | 6.2196     | 25       | 111   | 2        | scilari                                               | 10611  | 5.00000  | 1       | base      | yes      |      | 2122.20000    |
| kotlin         | 6.5558     | 26       | 117   | 1        | jvm_kotlin_idiomatic_fast_single                      | 10081  | 5.00700  | 1       | base      | yes      |      | 2013.38127    |
| rexx           | 7.1042     | 27       | 126   | 2        | joss_NetRexx                                          | 9290   | 5.00012  | 1       | base      | yes      | 8    | 1857.95467    |
| dart           | 9.1110     | 28       | 141   | 1        | eagerestwolf&mmcdon20_8bit                            | 7244   | 5.00025  | 1       | base      | yes      | 8    | 1448.72640    |
| typescript     | 9.8078     | 29       | 148   | 2        | mikevdbokke_8bit-array                                | 6729   | 5.00000  | 1       | base      | yes      | 1    | 1345.80000    |
| basic          | 10.525     | 30       | 150   | 3        | Nukepayload2_ArrayPool8of30M                          | 6271   | 5.00028  | 1       | wheel     | yes      | 1    | 1254.12879    |
| umple          | 15.199     | 31       | 168   | 1        | mmcdon20_umple                                        | 4343   | 5.00100  | 1       | base      | yes      | 1    | 868.42631     |
| d              | 20.471     | 32       | 172   | 2        | BradleyChatha-Single-SieveRTB1_32                     | 3224   | 5.00008  | 1       | base      | yes      | 1    | 644.78968     |
| pascal         | 21.455     | 33       | 176   | 3        | olivierbrun-1-threads                                 | 3076   | 5.00000  | 1       | base      | yes      | 1    | 615.20000     |
| python         | 26.546     | 34       | 188   | 2        | ssovest                                               | 2487   | 5.00183  | 1       | base      | yes      | 8    | 497.21805     |
| standardml     | 37.035     | 35       | 197   | 1        | NotMatthewGriffin_SML                                 | 1782   | 5.00000  | 1       | base      | yes      | 1    | 356.40000     |
| lean4          | 48.556     | 36       | 202   | 1        | badly-drawn-wizards                                   | 1360   | 5.00300  | 1       | base      | yes      | 8    | 271.83690     |
| pony           | 60.381     | 37       | 208   | 1        | marghidanu                                            | 1093   | 5.00000  | 1       | base      | yes      | 1    | 218.60000     |
| r              | 66.301     | 38       | 209   | 1        | fvbakel_R                                             | 996    | 5.00300  | 1       | base      | yes      | 32   | 199.08055     |
| haxe           | 93.080     | 39       | 211   | 1        | TayIorRobinson_Haxe_C++                               | 710    | 5.00686  | 1       | base      | yes      |      | 141.80550     |
| scheme         | 103.00     | 40       | 214   | 1        | William103                                            | 641    | 5.00194  | 1       | base      | yes      | 1    | 128.15031     |
| octave         | 108.52     | 41       | 215   | 2        | Brandon-Johns_8bit                                    | 609    | 5.00680  | 1       | base      | yes      | 8    | 121.63465     |
| ocaml          | 115.08     | 42       | 216   | 1        | gkpotter-faithful                                     | 574    | 5.00436  | 1       | base      | yes      |      | 114.70005     |
| php            | 158.45     | 43       | 220   | 1        | DennisdeBest                                          | 418    | 5.01788  | 1       | base      | yes      |      | 83.30206      |
| perl           | 171.31     | 44       | 221   | 2        | kjetillll                                             | 386    | 5.00992  | 1       | base      | yes      |      | 77.04715      |
| groovy         | 189.80     | 45       | 222   | 1        | mmcdon20_groovy                                       | 348    | 5.00400  | 1       | base      | yes      | 1    | 69.54436      |
| ballerina      | 366.65     | 46       | 228   | 1        | da-strange-boi                                        | 180    | 5.00000  | 1       | base      | yes      | 1    | 36.00000      |
| gdscript       | 387.70     | 47       | 229   | 1        | OrigamiDev-Pete                                       | 177    | 5.19900  | 1       | base      | yes      | 8    | 34.04501      |
| ruby           | 425.68     | 48       | 230   | 1        | rbergen                                               | 156    | 5.03100  | 1       | base      | yes      |      | 31.00775      |
| wren           | 549.01     | 49       | 231   | 1        | marghidanu                                            | 121    | 5.03282  | 1       | base      | yes      |      | 24.04220      |
| hack           | 646.77     | 50       | 233   | 1        | da-strange-boi                                        | 103    | 5.04700  | 1       | base      | yes      |      | 20.40816      |
| kos            | 734.94     | 51       | 234   | 1        | cdragan                                               | 90     | 5.01123  | 1       | base      | yes      | 8    | 17.95966      |
| lua            | 970.54     | 52       | 236   | 1        | lua                                                   | 68     | 5.00000  | 1       | base      | yes      | 64   | 13.60000      |
| elixir         | 1108.3     | 53       | 238   | 2        | thomas9911                                            | 62     | 5.20600  | 1       | base      | yes      | 1    | 11.90934      |
| smalltalk      | 1257.9     | 54       | 241   | 1        | fvbakel_smalltalk                                     | 53     | 5.05100  | 1       | base      | yes      | 1    | 10.49297      |
| tcl            | 1461.1     | 55       | 242   | 2        | fvbakel_ootcl2                                        | 46     | 5.09200  | 1       | base      | yes      | 32   | 9.03378       |
| powershell     | 1625.3     | 56       | 244   | 3        | RobCannon_ps3                                         | 41     | 5.04849  | 1       | base      | yes      | 1    | 8.12124       |
| emojicode      | 2639.9     | 57       | 248   | 1        | marghidanu                                            | 25     | 5.00000  | 1       | base      | yes      |      | 5.00000       |
| raku           | 8276.3     | 58       | 251   | 1        | draco1006                                             | 8      | 5.01616  | 1       | base      | yes      |      | 1.59484       |
| red            | 1.0518e+04 | 59       | 255   | 1        | mmcdon20_red                                          | 7      | 5.57829  | 1       | base      | yes      | 1    | 1.25487       |
| idl            | 2.0184e+04 | 60       | 261   | 1        | kriztioan_1bit                                        | 4      | 6.11656  | 1       | base      | yes      | 1    | 0.65396       |
| yoix           | 6.3409e+04 | 61       | 264   | 1        | mmcdon20_yoix                                         | 2      | 9.60800  | 1       | base      | yes      | 1    | 0.20816       |
| prolog         | 8.3382e+04 | 62       | 266   | 1        | jimbxb-prolog-basic                                   | 1      | 6.31700  | 1       | base      | yes      | 1    | 0.15830       |

### Single-threaded

| Index | Implementation | Solution | Label                                                 | Passes    | Duration  | Threads | Algorithm | Faithful | Bits | Passes/Second  |
| ----- | -------------- | -------- | ----------------------------------------------------- | --------- | --------- | ------- | --------- | -------- | ---- | -------------- |
| 1     | lisp           | 2        | mayerrobert-cl-hashdot                                | 453691544 | 5.00001   | 1       | base      | no       | 1    | 90738091.02858 |
| 2     | cpp            | 3        | flo80_pol_constexpr                                   | 233001419 | 5.00001   | 1       | base      | no       | 1    | 46600227.87973 |
| 3     | cpp            | 4        | BlackMark-pregenerated-inv_bits<u32>-clang            | 2464201   | 5.00000   | 1       | base      | no       | 1    | 492840.20000   |
| 4     | cpp            | 4        | BlackMark-pregenerated-inv_bits<u32>-gcc              | 1302899   | 5.00000   | 1       | base      | no       | 1    | 260579.80000   |
| 5     | rust           | 6        | SycrationSinglethreaded                               | 287912    | 5.00000   | 1       | base      | no       |      | 57582.34731    |
| 6     | rust           | 1        | mike-barber_bit-unrolled-hybrid                       | 65997     | 5.00004   | 1       | base      | yes      | 1    | 13199.29552    |
| 7     | nim            | 3        | GordonBGood_extreme_hybrid                            | 61844     | 5.00003   | 1       | base      | yes      | 1    | 12368.72956    |
| 8     | crystal        | 2        | GordonBGood_extreme-hybrid                            | 51633     | 5.00007   | 1       | base      | yes      | 1    | 10326.46576    |
| 9     | chapel         | 1        | GordonBGood_unrolled_hybrid                           | 45971     | 5.00003   | 1       | base      | yes      | 1    | 9194.14484     |
| 10    | v              | 2        | GordonBGood_extreme-hybrid                            | 45062     | 5.00005   | 1       | base      | yes      | 1    | 9012.31168     |
| 11    | c              | 3        | fvbakel_Cwords                                        | 44279     | 5.00000   | 1       | other     | yes      | 1    | 8855.79292     |
| 12    | cython         | 1        | ssovest-cy                                            | 41598     | 5.00006   | 1       | other     | yes      | 1    | 8319.50849     |
| 13    | rust           | 1        | mike-barber_bit-striped-hybrid-blocks16k              | 31363     | 5.00012   | 1       | base      | yes      | 1    | 6272.44985     |
| 14    | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc           | 30569     | 5.00010   | 1       | wheel     | yes      | 8    | 6113.67773     |
| 15    | mixed          | 1        | ssovest-cgo                                           | 29620     | 5.00034   | 1       | other     | no       | 1    | 5923.59897     |
| 16    | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-gcc         | 29377     | 5.00014   | 1       | wheel     | yes      | 1    | 5875.23549     |
| 17    | rust           | 1        | mike-barber_bit-striped-hybrid-blocks4k               | 29232     | 5.00005   | 1       | base      | yes      | 1    | 5846.33978     |
| 18    | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-clang       | 28441     | 5.00010   | 1       | wheel     | yes      | 1    | 5688.08624     |
| 19    | cpp            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-clang     | 28202     | 5.00000   | 1       | wheel     | yes      | 1    | 5640.40000     |
| 20    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 27145     | 5.00011   | 1       | wheel     | yes      | 1    | 5428.88056     |
| 21    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030  | 26543     | 5.00006   | 1       | wheel     | yes      | 1    | 5308.53630     |
| 22    | crystal        | 2        | GordonBGood_extreme                                   | 26335     | 5.00014   | 1       | base      | yes      | 1    | 5266.85253     |
| 23    | c              | 2        | danielspaangberg_48of210                              | 26003     | 5.00009   | 1       | wheel     | yes      | 1    | 5200.50743     |
| 24    | rust           | 1        | mike-barber_bit-striped-blocks16k                     | 25844     | 5.00002   | 1       | base      | yes      | 1    | 5168.78176     |
| 25    | cpp            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-gcc       | 25831     | 5.00000   | 1       | wheel     | yes      | 1    | 5166.20000     |
| 26    | v              | 2        | GordonBGood_extreme                                   | 25812     | 5.00012   | 1       | base      | yes      | 1    | 5162.27404     |
| 27    | rust           | 1        | mike-barber_bit-striped-blocks4k                      | 25033     | 5.00002   | 1       | base      | yes      | 1    | 5006.57804     |
| 28    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-480of2310    | 24917     | 5.00004   | 1       | wheel     | yes      | 1    | 4983.36013     |
| 29    | c              | 4        | merriam                                               | 24889     | 5.00000   | 1       | wheel     | yes      | 1    | 4977.80000     |
| 30    | go             | 2        | ssovest-go-other-u64                                  | 24697     | 5.00124   | 1       | other     | yes      | 1    | 4938.17250     |
| 31    | chapel         | 1        | GordonBGood_unrolled                                  | 24444     | 5.00019   | 1       | base      | yes      | 1    | 4888.61423     |
| 32    | crystal        | 2        | GordonBGood_stride8-rblock16K                         | 24188     | 5.00009   | 1       | base      | yes      | 1    | 4837.51776     |
| 33    | julia          | 4        | GordonBGood_unpeeled                                  | 23479     | 5.00018   | 1       | base      | yes      | 1    | 4695.62647     |
| 34    | go             | 2        | ssovest-go-other-u32-seg-16k                          | 23475     | 5.00132   | 1       | other     | yes      | 1    | 4693.76319     |
| 35    | rust           | 1        | mike-barber_byte                                      | 23402     | 5.00019   | 1       | base      | yes      | 8    | 4680.22414     |
| 36    | csharp         | 4        | italytoast-stride8-blocks32k                          | 23117     | 5.00012   | 1       | base      | yes      | 1    | 4623.28904     |
| 37    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-480of2310   | 22833     | 5.00021   | 1       | wheel     | yes      | 1    | 4566.40821     |
| 38    | v              | 2        | GordonBGood_stride8-block16K                          | 22828     | 5.00009   | 1       | base      | yes      | 1    | 4565.51326     |
| 39    | csharp         | 4        | italytoast-stride8-blocks16k                          | 22546     | 5.00015   | 1       | base      | yes      | 1    | 4509.06473     |
| 40    | c              | 3        | fvbakel_Cstriped-block                                | 22314     | 5.00013   | 1       | base      | yes      | 1    | 4462.68219     |
| 41    | go             | 2        | ssovest-go-other-u32-rblock-16k                       | 21807     | 5.00118   | 1       | other     | yes      | 1    | 4360.37241     |
| 42    | c              | 2        | danielspaangberg_8of30                                | 21798     | 5.00008   | 1       | wheel     | yes      | 1    | 4359.53374     |
| 43    | rust           | 7        | sergiocks                                             | 21643     | 5.00028   | 1       | wheel     | yes      | 8    | 4328.35764     |
| 44    | rust           | 1        | mike-barber_bit-striped                               | 21566     | 5.00006   | 1       | base      | yes      | 1    | 4313.15023     |
| 45    | csharp         | 4        | italytoast-stride8-blocks64k                          | 20698     | 5.00012   | 1       | base      | yes      | 1    | 4139.50065     |
| 46    | zig            | 2        | ManDeJan&ityonemo-zig-byte-sieve-type-bool            | 20402     | 5.00007   | 1       | base      | no       | 8    | 4080.34288     |
| 47    | amd64          | 1        | dacvs8                                                | 20189     | 5.00000   | 1       | base      | yes      | 8    | 4037.79919     |
| 48    | c              | 2        | danielspaangberg_5760of30030_owrb                     | 20074     | 5.00002   | 1       | wheel     | yes      | 1    | 4014.78474     |
| 49    | cpp            | 4        | BlackMark-1of2-bs-hs-vec<u8>-gcc                      | 20037     | 5.00012   | 1       | base      | yes      | 8    | 4007.30382     |
| 50    | cpp            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-gcc                | 19997     | 5.00001   | 1       | base      | yes      | 8    | 3999.39200     |
| 51    | lisp           | 2        | mayerrobert-cl-words                                  | 19933     | 5.00001   | 1       | other     | yes      | 1    | 3986.59043     |
| 52    | go             | 2        | ssovest-go-other-u32-block-16k                        | 19807     | 5.00187   | 1       | other     | yes      | 1    | 3959.92282     |
| 53    | cpp            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-clang              | 19403     | 5.00010   | 1       | base      | yes      | 8    | 3880.52239     |
| 54    | fortran        | 2        | tjol-8bit                                             | 19396     | 5.00012   | 1       | base      | yes      | 8    | 3879.10789     |
| 55    | cython         | 1        | rpkak+byte-array                                      | 19352     | 5.00024   | 1       | base      | yes      | 8    | 3870.21801     |
| 56    | haskell        | 2        | GordonBGood_unpeeled_block                            | 19252     | 5.00007   | 1       | base      | yes      | 1    | 3850.34538     |
| 57    | assembly       | 1        | rbergen_x64uff_byte                                   | 19133     | 5.00000   | 1       | base      | no       | 8    | 3826.60000     |
| 58    | fsharp         | 4        | GordonBGood_unpeeled                                  | 17836     | 5.00014   | 1       | base      | yes      | 1    | 3567.10155     |
| 59    | lisp           | 2        | mayerrobert-cl-wheel-opt                              | 17830     | 5.00001   | 1       | wheel     | yes      | 1    | 3565.99144     |
| 60    | chapel         | 1        | GordonBGood_unpeeled_block                            | 17744     | 5.00016   | 1       | base      | yes      | 1    | 3548.68644     |
| 61    | lisp           | 2        | mayerrobert-cl-wheel                                  | 17408     | 5.00001   | 1       | wheel     | yes      | 1    | 3481.59234     |
| 62    | csharp         | 4        | italytoast-stride8                                    | 17407     | 5.00023   | 1       | base      | yes      | 1    | 3481.23986     |
| 63    | java           | 4        | chrvanorleStrided32Blocks16k                          | 17369     | 5.00000   | 1       | base      | yes      | 1    | 3473.80000     |
| 64    | haskell        | 2        | GordonBGood_unpeeled                                  | 17294     | 5.00021   | 1       | base      | yes      | 1    | 3458.65470     |
| 65    | swift          | 1        | yellowcub_striped_UInt8                               | 17034     | 5.00026   | 1       | base      | yes      | 1    | 3406.62148     |
| 66    | assemblyscript | 2        | maxgraey_unrolled                                     | 16752     | 5.00000   | 1       | base      | yes      | 1    | 3350.40000     |
| 67    | cpp            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-gcc          | 16697     | 5.00009   | 1       | base      | yes      | 1    | 3339.33989     |
| 68    | lisp           | 2        | mayerrobert-cl-wheel-bitvector                        | 16605     | 5.00001   | 1       | wheel     | yes      | 1    | 3320.99203     |
| 69    | crystal        | 2        | GordonBGood_stride8                                   | 16574     | 5.00026   | 1       | base      | yes      | 1    | 3314.62963     |
| 70    | c              | 2        | danielspaangberg_480of2310_owrb                       | 16572     | 5.00019   | 1       | wheel     | yes      | 1    | 3314.27339     |
| 71    | chapel         | 1        | GordonBGood_unpeeled                                  | 16523     | 5.00017   | 1       | base      | yes      | 1    | 3304.48765     |
| 72    | v              | 2        | GordonBGood_stride8                                   | 16477     | 5.00019   | 1       | base      | yes      | 1    | 3295.27807     |
| 73    | haskell        | 1        | fatho/vector_unchecked                                | 16077     | 5.00017   | 1       | base      | no       | 8    | 3215.29068     |
| 74    | zig            | 1        | devblok                                               | 16040     | 5.00001   | 1       | base      | yes      | 8    | 3207.99358     |
| 75    | v              | 1        | marghidanu                                            | 15770     | 5.00000   | 1       | base      | yes      |      | 3154.00000     |
| 76    | cpp            | 1        | davepl_pol                                            | 15200     | 5.00026   | 1       | base      | yes      | 1    | 3039.84497     |
| 77    | ada            | 1        | BoopBeepBoopBeep                                      | 14988     | 5.00004   | 1       | base      | no       |      | 2997.57529     |
| 78    | go             | 2        | ssovest-go-stride-u32-rblock-16k                      | 14898     | 5.00125   | 1       | base      | yes      | 1    | 2978.85549     |
| 79    | d              | 2        | BradleyChatha-Single-SieveCT                          | 14669     | 5.00014   | 1       | base      | no       | 1    | 2933.71786     |
| 80    | assemblyscript | 1        | donmahallem                                           | 14318     | 5.00000   | 1       | base      | yes      |      | 2863.60000     |
| 81    | assembly       | 1        | rbergen_x64ff_byte                                    | 14150     | 5.00000   | 1       | base      | yes      | 8    | 2830.00000     |
| 82    | odin           | 1        | odin_byte_moe                                         | 13914     | 5.00000   | 1       | base      | yes      | 8    | 2782.80000     |
| 83    | rust           | 1        | mike-barber_bit-rotate                                | 13912     | 5.00024   | 1       | base      | yes      | 1    | 2782.26919     |
| 84    | c              | 2        | danielspaangberg_48of210_owrb                         | 13827     | 5.00001   | 1       | wheel     | yes      | 1    | 2765.39668     |
| 85    | csharp         | 4        | italytoast-dense-and-sparse                           | 13817     | 5.00004   | 1       | base      | yes      | 1    | 2763.37789     |
| 86    | haskell        | 1        | fatho/vector                                          | 13532     | 5.00035   | 1       | base      | no       | 8    | 2706.21111     |
| 87    | go             | 2        | ssovest-go-stride-u32-block-16k                       | 13408     | 5.00151   | 1       | base      | yes      | 1    | 2680.79141     |
| 88    | fortran        | 1        | johandweber_fortran                                   | 13306     | 5.00000   | 1       | base      | no       | 1    | 2661.20000     |
| 89    | fortran        | 2        | tjol-logical                                          | 13182     | 5.00011   | 1       | base      | yes      |      | 2636.34394     |
| 90    | c              | 1        | mckoss-c830                                           | 12998     | 5.00000   | 1       | wheel     | yes      | 1    | 2599.60000     |
| 91    | assembly       | 1        | rbergen_x64uff_bitshift                               | 12569     | 5.00000   | 1       | base      | no       | 1    | 2513.80000     |
| 92    | zig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8              | 12320     | 5.00011   | 1       | base      | yes      | 1    | 2463.94579     |
| 93    | fortran        | 2        | tjol-bits                                             | 12168     | 5.00040   | 1       | base      | yes      | 1    | 2433.40692     |
| 94    | zig            | 2        | ManDeJan&ityonemo-zig-bit-sieve                       | 12109     | 5.00028   | 1       | base      | no       | 1    | 2421.66439     |
| 95    | assembly       | 1        | rbergen_x64ff_bitshift                                | 12066     | 5.00000   | 1       | base      | yes      | 1    | 2413.20000     |
| 96    | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8                 | 12037     | 5.00008   | 1       | base      | yes      | 8    | 2407.36148     |
| 97    | chapel         | 1        | GordonBGood_bittwiddle                                | 11674     | 5.00032   | 1       | base      | yes      | 1    | 2334.65058     |
| 98    | c              | 2        | danielspaangberg_1of2                                 | 11669     | 5.00027   | 1       | base      | yes      | 1    | 2333.67538     |
| 99    | java           | 4        | chrvanorleI32CUnroll                                  | 11594     | 5.00000   | 1       | base      | yes      | 1    | 2318.80000     |
| 100   | crystal        | 1        | marghidanu                                            | 11472     | 5.00012   | 1       | base      | yes      | 1    | 2294.34264     |
| 101   | haskell        | 1        | fatho/bitset                                          | 11440     | 5.00038   | 1       | base      | no       | 1    | 2287.82567     |
| 102   | fsharp         | 2        | dmannock_fsharp_port                                  | 11241     | 5.00037   | 1       | base      | yes      |      | 2248.03410     |
| 103   | rust           | 1        | mike-barber_bit                                       | 11161     | 5.00037   | 1       | base      | yes      | 1    | 2232.03482     |
| 104   | swift          | 1        | yellowcub_1bit_UInt8                                  | 10940     | 5.00041   | 1       | base      | yes      | 1    | 2187.81884     |
| 105   | crystal        | 2        | GordonBGood_bittwiddle                                | 10912     | 5.00018   | 1       | base      | yes      | 1    | 2182.32100     |
| 106   | fsharp         | 3        | dmannock_fsharp_recursion                             | 10815     | 5.00001   | 1       | base      | yes      |      | 2162.99567     |
| 107   | go             | 2        | ssovest-go-stride-u32                                 | 10797     | 5.00133   | 1       | base      | yes      | 1    | 2158.82730     |
| 108   | nodejs         | 1        | rogiervandam_memcopy                                  | 10776     | 5.00007   | 1       | other     | yes      | 1    | 2155.17003     |
| 109   | clojure        | 2        | axvr_clj-sln-2_8-bit                                  | 10753     | 5.00052   | 1       | base      | yes      | 8    | 2150.37711     |
| 110   | rust           | 2        | Azgrom                                                | 10739     | 5.00005   | 1       | base      | yes      |      | 2147.77852     |
| 111   | scala          | 2        | scilari                                               | 10611     | 5.00000   | 1       | base      | yes      |      | 2122.20000     |
| 112   | c              | 2        | danielspaangberg_8of30_owrb                           | 10499     | 5.00029   | 1       | wheel     | yes      | 1    | 2099.67780     |
| 113   | amd64          | 1        | dacvs1                                                | 10418     | 5.00037   | 1       | base      | yes      | 1    | 2083.44791     |
| 114   | cython         | 1        | rpkak+bit-array                                       | 10389     | 5.00002   | 1       | base      | yes      | 1    | 2077.79238     |
| 115   | csharp         | 1        | kinematics_dbool                                      | 10304     | 5.00028   | 1       | base      | yes      | 8    | 2060.68460     |
| 116   | julia          | 3        | louie-github_port_1of2                                | 10113     | 5.00041   | 1       | base      | yes      | 1    | 2022.43500     |
| 117   | kotlin         | 1        | jvm_kotlin_idiomatic_fast_single                      | 10081     | 5.00700   | 1       | base      | yes      |      | 2013.38127     |
| 118   | csharp         | 1        | kinematics_ibool                                      | 10052     | 5.00043   | 1       | base      | yes      | 8    | 2010.22712     |
| 119   | odin           | 1        | odin_bit_moe                                          | 9950      | 5.00000   | 1       | base      | yes      | 1    | 1990.00000     |
| 120   | java           | 1        | MansenC                                               | 9646      | 5.00000   | 1       | base      | yes      |      | 1929.20000     |
| 121   | kotlin         | 1        | jvm_kotlin_traditional_single                         | 9662      | 5.01900   | 1       | base      | yes      |      | 1925.08468     |
| 122   | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-bool               | 9597      | 5.00026   | 1       | base      | yes      | 8    | 1919.30020     |
| 123   | kotlin         | 1        | jvm_kotlin_idiomatic_single                           | 9577      | 5.00200   | 1       | base      | yes      |      | 1914.63415     |
| 124   | haskell        | 1        | fatho/bitset_unchecked                                | 9439      | 5.00012   | 1       | base      | no       | 1    | 1887.75620     |
| 125   | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-5760of30030     | 9298      | 5.00035   | 1       | wheel     | yes      | 8    | 1859.46984     |
| 126   | rexx           | 2        | joss_NetRexx                                          | 9290      | 5.00012   | 1       | base      | yes      | 8    | 1857.95467     |
| 127   | python         | 3        | emillynge_numpy                                       | 9240      | 5.00016   | 1       | base      | no       | 8    | 1847.94028     |
| 128   | assemblyscript | 2        | maxgraey                                              | 9002      | 5.00000   | 1       | base      | yes      | 1    | 1800.40000     |
| 129   | zig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-480of2310       | 8901      | 5.00053   | 1       | wheel     | yes      | 8    | 1780.01132     |
| 130   | rust           | 4        | joshallen64                                           | 8629      | 5.00029   | 1       | base      | yes      |      | 1725.69912     |
| 131   | julia          | 1        | dcbi                                                  | 8535      | 5.00011   | 1       | base      | yes      | 1    | 1706.96142     |
| 132   | v              | 2        | GordonBGood_bittwiddle                                | 8507      | 5.00030   | 1       | base      | yes      | 1    | 1701.29792     |
| 133   | lua            | 2        | ben1jen_luajit1                                       | 8328      | 5.00000   | 1       | base      | no       | 1    | 1665.60000     |
| 134   | julia          | 2        | epithet-jl                                            | 8057      | 5.00055   | 1       | base      | yes      | 1    | 1611.22276     |
| 135   | csharp         | 3        | tannergooding                                         | 7924      | 5.00020   | 1       | base      | yes      | 1    | 1584.73645     |
| 136   | java           | 4        | chrvanorleI64PatternCalc                              | 7893      | 5.00000   | 1       | other     | yes      | 1    | 1578.60000     |
| 137   | assembly       | 1        | rbergen_x64uff_bitbtr                                 | 7860      | 5.00000   | 1       | base      | no       | 1    | 1572.00000     |
| 138   | mixed          | 2        | RobCannon_ps2                                         | 7793      | 5.00064   | 1       | base      | no       | 1    | 1558.40052     |
| 139   | csharp         | 1        | kinematics_raw32                                      | 7616      | 5.00013   | 1       | base      | yes      | 1    | 1523.16040     |
| 140   | assembly       | 1        | rbergen_x64ff_bitbtr                                  | 7554      | 5.00000   | 1       | base      | yes      | 1    | 1510.80000     |
| 141   | dart           | 1        | eagerestwolf&mmcdon20_8bit                            | 7244      | 5.00025   | 1       | base      | yes      | 8    | 1448.72640     |
| 142   | csharp         | 1        | kinematics_rawd                                       | 7176      | 5.00039   | 1       | base      | yes      | 1    | 1435.08806     |
| 143   | csharp         | 1        | kinematics_raw                                        | 7169      | 5.00048   | 1       | base      | yes      | 1    | 1433.66237     |
| 144   | scala          | 1        | rom1dep                                               | 7107      | 5.00000   | 1       | base      | yes      |      | 1421.40000     |
| 145   | lisp           | 2        | mayerrobert-cl                                        | 7052      | 5.00001   | 1       | base      | yes      | 1    | 1410.39690     |
| 146   | csharp         | 1        | kinematics_bool                                       | 6925      | 5.00024   | 1       | base      | yes      | 8    | 1384.93352     |
| 147   | csharp         | 1        | kinematics_raw6                                       | 6888      | 5.00043   | 1       | wheel     | yes      | 1    | 1377.48154     |
| 148   | typescript     | 2        | mikevdbokke_8bit-array                                | 6729      | 5.00000   | 1       | base      | yes      | 1    | 1345.80000     |
| 149   | nodejs         | 1        | rogiervandam                                          | 6608      | 5.00011   | 1       | base      | yes      | 1    | 1321.57133     |
| 150   | basic          | 3        | Nukepayload2_ArrayPool8of30M                          | 6271      | 5.00028   | 1       | wheel     | yes      | 1    | 1254.12879     |
| 151   | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-clang         | 6182      | 5.00026   | 1       | wheel     | yes      | 8    | 1236.33571     |
| 152   | csharp         | 1        | kinematics_pool30                                     | 6164      | 5.00026   | 1       | wheel     | yes      | 1    | 1232.73590     |
| 153   | basic          | 3        | Nukepayload2_ReDim8of30M                              | 6128      | 5.00027   | 1       | wheel     | yes      | 1    | 1225.53500     |
| 154   | dart           | 1        | eagerestwolf&mmcdon20_1bit                            | 5972      | 5.00075   | 1       | base      | yes      | 1    | 1194.22087     |
| 155   | csharp         | 1        | kinematics_pool30m                                    | 5798      | 5.00012   | 1       | wheel     | yes      | 1    | 1159.57217     |
| 156   | typescript     | 1        | marghidanu                                            | 5677      | 5.00000   | 1       | base      | yes      |      | 1135.40000     |
| 157   | go             | 2        | ssovest-go-simple-u32                                 | 5648      | 5.00152   | 1       | base      | yes      | 1    | 1129.25691     |
| 158   | lisp           | 2        | mayerrobert-clb                                       | 5644      | 5.00001   | 1       | base      | yes      | 1    | 1128.79729     |
| 159   | typescript     | 2        | mikevdbokke_byte-array                                | 5622      | 5.00000   | 1       | base      | yes      | 8    | 1124.40000     |
| 160   | typescript     | 2        | mikevdbokke_32bit-array                               | 5167      | 5.00000   | 1       | base      | yes      | 1    | 1033.40000     |
| 161   | csharp         | 1        | kinematics_pool2of6                                   | 5167      | 5.00060   | 1       | wheel     | yes      | 1    | 1033.27601     |
| 162   | java           | 2        | PratimGhosh86-JavaBitSet                              | 4951      | 5.00000   | 1       | base      | yes      | 1    | 990.20000      |
| 163   | java           | 4        | chrvanorleI64                                         | 4942      | 5.00000   | 1       | base      | yes      | 1    | 988.40000      |
| 164   | java           | 4        | chrvanorleI64C                                        | 4936      | 5.00000   | 1       | base      | yes      | 1    | 987.20000      |
| 165   | java           | 4        | chrvanorleI8                                          | 4933      | 5.00000   | 1       | base      | yes      | 1    | 986.60000      |
| 166   | java           | 4        | chrvanorleI32C                                        | 4843      | 5.00000   | 1       | base      | yes      | 1    | 968.60000      |
| 167   | java           | 4        | chrvanorleI32                                         | 4833      | 5.00000   | 1       | base      | yes      | 1    | 966.60000      |
| 168   | umple          | 1        | mmcdon20_umple                                        | 4343      | 5.00100   | 1       | base      | yes      | 1    | 868.42631      |
| 169   | rust           | 3        | Blui42                                                | 4150      | 5.00098   | 1       | base      | yes      |      | 829.83661      |
| 170   | java           | 3        | MansenC-native                                        | 4023      | 5.00000   | 1       | base      | yes      |      | 804.60000      |
| 171   | kotlin         | 1        | native_kotlin_idiomatic_fast_single                   | 3766      | 5.00100   | 1       | base      | yes      |      | 753.04939      |
| 172   | d              | 2        | BradleyChatha-Single-SieveRTB1_32                     | 3224      | 5.00008   | 1       | base      | yes      | 1    | 644.78968      |
| 173   | d              | 2        | BradleyChatha-Single-SieveRTB1_64                     | 3221      | 5.00047   | 1       | base      | yes      | 1    | 644.13945      |
| 174   | swift          | 1        | j-f1_yellowcub_bool                                   | 3090      | 5.00026   | 1       | base      | yes      | 8    | 617.96775      |
| 175   | cpp            | 4        | BlackMark-1of2-bs-hs-vec<u8>-clang                    | 3087      | 5.00031   | 1       | base      | yes      | 8    | 617.36172      |
| 176   | pascal         | 3        | olivierbrun-1-threads                                 | 3076      | 5.00000   | 1       | base      | yes      | 1    | 615.20000      |
| 177   | d              | 2        | BradleyChatha-Single-SieveRTB1_16                     | 3066      | 5.00161   | 1       | base      | yes      | 1    | 613.00261      |
| 178   | d              | 2        | BradleyChatha-Single-SieveRT                          | 3033      | 5.00026   | 1       | base      | yes      | 1    | 606.56846      |
| 179   | nim            | 2        | beef331                                               | 3026      | 5.00142   | 1       | base      | yes      | 1    | 605.02759      |
| 180   | d              | 2        | BradleyChatha-Single-SieveRTBX                        | 2954      | 5.00048   | 1       | base      | yes      | 8    | 590.74329      |
| 181   | d              | 1        | eagerestwolf                                          | 2908      | 5.00000   | 1       | base      | yes      | 8    | 581.60000      |
| 182   | nim            | 1        | marghidanu                                            | 2886      | 5.00134   | 1       | base      | yes      | 8    | 577.04533      |
| 183   | mixed          | 3        | 1mikegrn/CPython                                      | 2818      | 5.00001   | 1       | base      | no       | 32   | 563.59836      |
| 184   | csharp         | 1        | kinematics_pool                                       | 2804      | 5.00036   | 1       | base      | yes      | 1    | 560.75963      |
| 185   | clojure        | 2        | axvr_clj-sln-2_1-bit                                  | 2655      | 5.00186   | 1       | base      | yes      | 1    | 530.80260      |
| 186   | csharp         | 1        | kinematics_standard                                   | 2638      | 5.00049   | 1       | base      | yes      | 1    | 527.54830      |
| 187   | csharp         | 2        | davepl                                                | 2527      | 5.00063   | 1       | base      | yes      | 1    | 505.33633      |
| 188   | python         | 2        | ssovest                                               | 2487      | 5.00183   | 1       | base      | yes      | 8    | 497.21805      |
| 189   | csharp         | 1        | kinematics_original                                   | 2477      | 5.00170   | 1       | base      | yes      | 1    | 495.23162      |
| 190   | basic          | 1        | rbergen_8of30                                         | 2462      | 5.00000   | 1       | wheel     | yes      | 1    | 492.40000      |
| 191   | kotlin         | 1        | native_kotlin_idiomatic_single                        | 2403      | 5.00100   | 1       | base      | yes      |      | 480.50390      |
| 192   | octave         | 1        | octave                                                | 2212      | 5.00073   | 1       | base      | no       |      | 442.33542      |
| 193   | kotlin         | 1        | js_kotlin_idiomatic_fast_single                       | 2003      | 5.00400   | 1       | base      | yes      |      | 400.27978      |
| 194   | kotlin         | 1        | js_kotlin_idiomatic_single                            | 1986      | 5.00400   | 1       | base      | yes      |      | 396.88249      |
| 195   | kotlin         | 1        | js_kotlin_traditional_single                          | 1953      | 5.00400   | 1       | base      | yes      |      | 390.28777      |
| 196   | d              | 2        | BradleyChatha-Single-SieveRTBX                        | 1842      | 5.00088   | 1       | base      | yes      | 64   | 368.33517      |
| 197   | standardml     | 1        | NotMatthewGriffin_SML                                 | 1782      | 5.00000   | 1       | base      | yes      | 1    | 356.40000      |
| 198   | fsharp         | 1        | rbergen                                               | 1781      | 5.00161   | 1       | base      | yes      | 1    | 356.08538      |
| 199   | cpp            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-clang        | 1695      | 5.00061   | 1       | base      | yes      | 1    | 338.95865      |
| 200   | kotlin         | 1        | native_kotlin_traditional_single                      | 1604      | 5.00200   | 1       | base      | yes      |      | 320.67173      |
| 201   | basic          | 2        | rbergen_vb                                            | 1600      | 5.00096   | 1       | base      | yes      | 1    | 319.93826      |
| 202   | lean4          | 1        | badly-drawn-wizards                                   | 1360      | 5.00300   | 1       | base      | yes      | 8    | 271.83690      |
| 203   | go             | 1        | bundgaard                                             | 1264      | 5.00080   | 1       | base      | yes      |      | 252.75956      |
| 204   | cobol          | 1        | fvbakel_Cobol                                         | 1246      | 5.00000   | 1       | base      | no       | 8    | 249.20000      |
| 205   | pascal         | 1        | rbergen                                               | 1245      | 5.00000   | 1       | base      | yes      |      | 249.00000      |
| 206   | pascal         | 2        | circular17                                            | 1170      | 5.00000   | 1       | base      | yes      | 1    | 234.00000      |
| 207   | r              | 2        | nobrien97                                             | 1106      | 5.00200   | 1       | base      | no       | 32   | 221.11156      |
| 208   | pony           | 1        | marghidanu                                            | 1093      | 5.00000   | 1       | base      | yes      | 1    | 218.60000      |
| 209   | r              | 1        | fvbakel_R                                             | 996       | 5.00300   | 1       | base      | yes      | 32   | 199.08055      |
| 210   | basic          | 1        | rbergen_boolean                                       | 734       | 5.00500   | 1       | base      | yes      |      | 146.65335      |
| 211   | haxe           | 1        | TayIorRobinson_Haxe_C++                               | 710       | 5.00686   | 1       | base      | yes      |      | 141.80550      |
| 212   | ocaml          | 2        | gkpotter-unfaithful                                   | 701       | 5.00981   | 1       | base      | no       |      | 139.92533      |
| 213   | scala          | 3        | mmcdon20_scala                                        | 664       | 5.00000   | 1       | base      | yes      | 1    | 132.80000      |
| 214   | scheme         | 1        | William103                                            | 641       | 5.00194   | 1       | base      | yes      | 1    | 128.15031      |
| 215   | octave         | 2        | Brandon-Johns_8bit                                    | 609       | 5.00680   | 1       | base      | yes      | 8    | 121.63465      |
| 216   | ocaml          | 1        | gkpotter-faithful                                     | 574       | 5.00436   | 1       | base      | yes      |      | 114.70005      |
| 217   | forth          | 1        | tjol-8bit                                             | 499       | 5.00198   | 1       | base      | no       | 8    | 99.76044       |
| 218   | basic          | 1        | rbergen_bit32                                         | 483       | 5.00200   | 1       | base      | yes      | 1    | 96.56138       |
| 219   | basic          | 1        | rbergen_bit64                                         | 457       | 5.00900   | 1       | base      | yes      | 1    | 91.23578       |
| 220   | php            | 1        | DennisdeBest                                          | 418       | 5.01788   | 1       | base      | yes      |      | 83.30206       |
| 221   | perl           | 2        | kjetillll                                             | 386       | 5.00992   | 1       | base      | yes      |      | 77.04715       |
| 222   | groovy         | 1        | mmcdon20_groovy                                       | 348       | 5.00400   | 1       | base      | yes      | 1    | 69.54436       |
| 223   | forth          | 1        | tjol-1bit                                             | 337       | 5.00454   | 1       | base      | no       | 1    | 67.33886       |
| 224   | typescript     | 2        | mikevdbokke_number-array                              | 300       | 5.01300   | 1       | base      | yes      |      | 59.84440       |
| 225   | postscript     | 1        | epithet-ps                                            | 246       | 5.00700   | 1       | base      | no       | 8    | 49.13122       |
| 226   | tex            | 2        | jfbu-tex-48of210                                      | 192       | 5.02481   | 1       | wheel     | no       | 32   | 38.21040       |
| 227   | tex            | 2        | jfbu-tex-8of30                                        | 182       | 5.02449   | 1       | wheel     | no       | 32   | 36.22258       |
| 228   | ballerina      | 1        | da-strange-boi                                        | 180       | 5.00000   | 1       | base      | yes      | 1    | 36.00000       |
| 229   | gdscript       | 1        | OrigamiDev-Pete                                       | 177       | 5.19900   | 1       | base      | yes      | 8    | 34.04501       |
| 230   | ruby           | 1        | rbergen                                               | 156       | 5.03100   | 1       | base      | yes      |      | 31.00775       |
| 231   | wren           | 1        | marghidanu                                            | 121       | 5.03282   | 1       | base      | yes      |      | 24.04220       |
| 232   | tex            | 2        | jfbu-tex-480of2310                                    | 110       | 5.02590   | 1       | wheel     | no       | 32   | 21.88663       |
| 233   | hack           | 1        | da-strange-boi                                        | 103       | 5.04700   | 1       | base      | yes      |      | 20.40816       |
| 234   | kos            | 1        | cdragan                                               | 90        | 5.01123   | 1       | base      | yes      | 8    | 17.95966       |
| 235   | tex            | 2        | jfbu-tex                                              | 70        | 5.02098   | 1       | base      | no       | 32   | 13.94150       |
| 236   | lua            | 1        | lua                                                   | 68        | 5.00000   | 1       | base      | yes      | 64   | 13.60000       |
| 237   | perl           | 1        | marghidanu                                            | 60        | 5.01152   | 1       | base      | yes      |      | 11.97242       |
| 238   | elixir         | 2        | thomas9911                                            | 62        | 5.20600   | 1       | base      | yes      | 1    | 11.90934       |
| 239   | lisp           | 1        | mikehw                                                | 114       | 10.00336  | 1       | base      | no       | 1    | 11.39617       |
| 240   | prolog         | 1        | jimbxb-prolog-c                                       | 57        | 5.00800   | 1       | base      | no       | 1    | 11.38179       |
| 241   | smalltalk      | 1        | fvbakel_smalltalk                                     | 53        | 5.05100   | 1       | base      | yes      | 1    | 10.49297       |
| 242   | tcl            | 2        | fvbakel_ootcl2                                        | 46        | 5.09200   | 1       | base      | yes      | 32   | 9.03378        |
| 243   | mixal          | 1        | rbergen                                               | 30        | 3.63000   | 1       | base      | no       | 1    | 8.26446        |
| 244   | powershell     | 3        | RobCannon_ps3                                         | 41        | 5.04849   | 1       | base      | yes      | 1    | 8.12124        |
| 245   | rexx           | 1        | joss_REXX                                             | 31        | 5.03635   | 1       | base      | no       | 8    | 6.15525        |
| 246   | haxe           | 1        | TayIorRobinson_Haxe_HaxeEval                          | 30        | 5.10925   | 1       | base      | yes      |      | 5.87170        |
| 247   | powershell     | 2        | crowbar27_ps2                                         | 28        | 5.14513   | 1       | base      | yes      | 1    | 5.44204        |
| 248   | emojicode      | 1        | marghidanu                                            | 25        | 5.00000   | 1       | base      | yes      |      | 5.00000        |
| 249   | python         | 1        | davepl                                                | 24        | 5.01127   | 1       | base      | yes      |      | 4.78921        |
| 250   | sql            | 2        | fvbakel_MariaDB3                                      | 9         | 5.40700   | 1       | other     | no       | 32   | 1.66451        |
| 251   | raku           | 1        | draco1006                                             | 8         | 5.01616   | 1       | base      | yes      |      | 1.59484        |
| 252   | tcl            | 1        | fvbakeltcl                                            | 8         | 5.06500   | 1       | base      | yes      | 1    | 1.57947        |
| 253   | sql            | 1        | fvbakel_sqlite                                        | 7         | 5.10247   | 1       | other     | no       | 8    | 1.37188        |
| 254   | befunge        | 1        | tjol-bf98                                             | 7         | 5.20545   | 1       | base      | no       | 1    | 1.34474        |
| 255   | red            | 1        | mmcdon20_red                                          | 7         | 5.57829   | 1       | base      | yes      | 1    | 1.25487        |
| 256   | haxe           | 1        | TayIorRobinson_Haxe_Python                            | 7         | 5.71463   | 1       | base      | yes      |      | 1.22493        |
| 257   | tcl            | 2        | fvbakel_ootcl                                         | 7         | 5.78900   | 1       | base      | yes      | 1    | 1.20919        |
| 258   | sql            | 2        | fvbakel_MariaDB2                                      | 6         | 5.65700   | 1       | other     | no       | 32   | 1.06063        |
| 259   | clojure        | 1        | mmcdon20_clojure                                      | 5         | 5.12800   | 1       | base      | yes      | 1    | 0.97504        |
| 260   | prolog         | 1        | jimbxb-prolog-dynamic                                 | 5         | 5.46400   | 1       | base      | no       |      | 0.91508        |
| 261   | idl            | 1        | kriztioan_1bit                                        | 4         | 6.11656   | 1       | base      | yes      | 1    | 0.65396        |
| 262   | bash           | 1        | bash_inline                                           | 3         | 6.63242   | 1       | base      | no       |      | 0.45232        |
| 263   | bash           | 1        | bash                                                  | 2         | 7.58028   | 1       | base      | no       |      | 0.26384        |
| 264   | yoix           | 1        | mmcdon20_yoix                                         | 2         | 9.60800   | 1       | base      | yes      | 1    | 0.20816        |
| 265   | sql            | 2        | fvbakel_MariaDB1                                      | 1         | 5.96400   | 1       | base      | no       | 32   | 0.16767        |
| 266   | prolog         | 1        | jimbxb-prolog-basic                                   | 1         | 6.31700   | 1       | base      | yes      | 1    | 0.15830        |
| 267   | tex            | 1        | tjol                                                  | 2         | 13.05067  | 1       | base      | no       | 32   | 0.15325        |
| 268   | bash           | 1        | bash_packed                                           | 1         | 7.47044   | 1       | base      | no       |      | 0.13386        |
| 269   | elixir         | 1        | cdesch                                                | 1         | 22.08000  | 1       | base      | no       |      | 0.04529        |
| 270   | powershell     | 1        | crowbar27_ps1                                         | 1         | 50.82070  | 1       | base      | yes      | 1    | 0.01968        |
| 271   | brainfuck      | 1        | aquarel                                               | 1         | 101.21107 | 1       | base      | no       | 32   | 0.00988        |
| 272   | octave         | 2        | Brandon-Johns_1bit                                    | 1         | 126.81154 | 1       | base      | yes      | 1    | 0.00789        |

### Multi-threaded

| Index | Implementation | Solution | Label                                                             | Passes     | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second  |
| ----- | -------------- | -------- | ----------------------------------------------------------------- | ---------- | -------- | ------- | --------- | -------- | ---- | -------------- |
| 1     | d              | 2        | BradleyChatha-MultistaticThreads-SieveRTCT_Cheatiness             | 3096613368 | 5.00001  | 32      | other     | no       | 1    | 19353794.84241 |
| 2     | cpp            | 3        | flo80_pol_constexpr                                               | 1095313694 | 5.00052  | 32      | base      | no       | 1    | 6845001.44535  |
| 3     | cpp            | 4        | BlackMark-pregenerated-inv_bits<u32>-clang                        | 32968570   | 5.00129  | 32      | base      | no       | 1    | 206000.41439   |
| 4     | cpp            | 4        | BlackMark-pregenerated-inv_bits<u32>-gcc                          | 13699797   | 5.00129  | 32      | base      | no       | 1    | 85601.64603    |
| 5     | rust           | 6        | SycrationMultithreaded                                            | 1991833    | 5.00002  | 8       | base      | no       |      | 49795.67117    |
| 6     | rust           | 1        | mike-barber_bit-unrolled-hybrid                                   | 882062     | 5.00043  | 32      | base      | yes      | 1    | 5512.41121     |
| 7     | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-gcc                     | 459571     | 5.00152  | 32      | wheel     | yes      | 1    | 2871.44583     |
| 8     | cpp            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-gcc                   | 434244     | 5.02001  | 32      | wheel     | yes      | 1    | 2703.20677     |
| 9     | rust           | 1        | mike-barber_bit-striped-hybrid-blocks4k                           | 410477     | 5.00048  | 32      | base      | yes      | 1    | 2565.23270     |
| 10    | rust           | 1        | mike-barber_bit-striped-hybrid-blocks16k                          | 400728     | 5.00055  | 32      | base      | yes      | 1    | 2504.27225     |
| 11    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-5760of30030  | 379252     | 5.00008  | 32      | wheel     | yes      | 1    | 2370.28708     |
| 12    | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-clang                   | 353957     | 5.00131  | 32      | wheel     | yes      | 1    | 2211.65180     |
| 13    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-480of2310    | 350820     | 5.00022  | 32      | wheel     | yes      | 1    | 2192.52853     |
| 14    | c              | 2        | danielspaangberg_5760of30030_epar                                 | 343336     | 5.00110  | 32      | wheel     | yes      | 1    | 2145.37973     |
| 15    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-480of2310   | 342006     | 5.00013  | 32      | wheel     | yes      | 1    | 2137.48193     |
| 16    | rust           | 1        | mike-barber_bit-striped-blocks4k                                  | 333693     | 5.00049  | 32      | base      | yes      | 1    | 2085.37680     |
| 17    | cpp            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-clang                 | 333435     | 5.00253  | 32      | wheel     | yes      | 1    | 2082.91480     |
| 18    | rust           | 1        | mike-barber_bit-striped-blocks16k                                 | 330536     | 5.00057  | 32      | base      | yes      | 1    | 2065.61656     |
| 19    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-5760of30030 | 324478     | 5.00006  | 32      | wheel     | yes      | 1    | 2027.96316     |
| 20    | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc                       | 305390     | 5.00324  | 32      | wheel     | yes      | 8    | 1907.45147     |
| 21    | rust           | 1        | mike-barber_byte                                                  | 297851     | 5.00062  | 32      | base      | yes      | 8    | 1861.33870     |
| 22    | c              | 2        | danielspaangberg_480of2310_epar                                   | 291472     | 5.00126  | 32      | wheel     | yes      | 1    | 1821.24214     |
| 23    | rust           | 1        | mike-barber_bit-striped                                           | 282235     | 5.00057  | 32      | base      | yes      | 1    | 1763.76606     |
| 24    | cpp            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-gcc                            | 264943     | 5.00386  | 32      | base      | yes      | 8    | 1654.61639     |
| 25    | cpp            | 4        | BlackMark-1of2-bs-hs-vec<u8>-gcc                                  | 261815     | 5.00285  | 32      | base      | yes      | 8    | 1635.41157     |
| 26    | cpp            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-gcc                      | 253040     | 5.00129  | 32      | base      | yes      | 1    | 1581.09208     |
| 27    | c              | 2        | danielspaangberg_5760of30030_par                                  | 30348      | 5.00004  | 4       | wheel     | yes      | 1    | 1517.38847     |
| 28    | c              | 2        | danielspaangberg_48of210_epar                                     | 240580     | 5.00138  | 32      | wheel     | yes      | 1    | 1503.21162     |
| 29    | java           | 4        | chrvanorleStrided32Blocks16k                                      | 232509     | 5.00500  | 32      | base      | yes      | 1    | 1451.72952     |
| 30    | c              | 2        | danielspaangberg_480of2310_par                                    | 28782      | 5.00014  | 4       | wheel     | yes      | 1    | 1439.06086     |
| 31    | d              | 2        | BradleyChatha-MultistaticThreads-SieveCT                          | 222940     | 5.00056  | 32      | base      | no       | 1    | 1393.21896     |
| 32    | cpp            | 2        | davepl_par                                                        | 221302     | 5.00082  | 32      | base      | yes      | 1    | 1382.91070     |
| 33    | c              | 2        | danielspaangberg_48of210_par                                      | 27656      | 5.00006  | 4       | wheel     | yes      | 1    | 1382.78258     |
| 34    | rust           | 1        | mike-barber_bit-rotate                                            | 219586     | 5.00068  | 32      | base      | yes      | 1    | 1372.22523     |
| 35    | c              | 2        | danielspaangberg_8of30_par                                        | 26478      | 5.00011  | 4       | wheel     | yes      | 1    | 1323.87087     |
| 36    | rust           | 7        | sergiocks                                                         | 208810     | 5.00069  | 32      | wheel     | yes      | 8    | 1304.88232     |
| 37    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-sieve-u8                 | 199158     | 5.00049  | 32      | base      | yes      | 8    | 1244.61553     |
| 38    | go             | 4        | kpym-go-multi                                                     | 24237      | 5.00021  | 4       | base      | yes      |      | 1211.79910     |
| 39    | c              | 2        | danielspaangberg_1of2_epar                                        | 193609     | 5.00169  | 32      | base      | yes      | 1    | 1209.64739     |
| 40    | cpp            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-clang                          | 191519     | 5.00292  | 32      | base      | yes      | 8    | 1196.29511     |
| 41    | c              | 2        | danielspaangberg_8of30_epar                                       | 179352     | 5.00157  | 32      | wheel     | yes      | 1    | 1120.59768     |
| 42    | java           | 4        | chrvanorleI64PatternCalc                                          | 178428     | 5.00700  | 32      | other     | yes      | 1    | 1113.61594     |
| 43    | java           | 4        | chrvanorleI32CUnroll                                              | 174979     | 5.00700  | 32      | base      | yes      | 1    | 1092.08982     |
| 44    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8              | 163946     | 5.00047  | 32      | base      | yes      | 1    | 1024.56619     |
| 45    | rust           | 1        | mike-barber_bit                                                   | 163847     | 5.00079  | 32      | base      | yes      | 1    | 1023.88244     |
| 46    | c              | 2        | danielspaangberg_1of2_par                                         | 20466      | 5.00018  | 4       | base      | yes      | 1    | 1023.26255     |
| 47    | odin           | 1        | odin_bit_threaded_moe                                             | 160118     | 5.00400  | 32      | base      | yes      | 1    | 999.93755      |
| 48    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64             | 157946     | 5.00065  | 32      | base      | yes      | 1    | 987.03419      |
| 49    | odin           | 1        | odin_byte_threaded_moe                                            | 143748     | 5.00200  | 32      | base      | yes      | 8    | 898.06577      |
| 50    | cpp            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-clang                     | 136862     | 5.00342  | 32      | wheel     | yes      | 8    | 854.80281      |
| 51    | kotlin         | 1        | jvm_kotlin_idiomatic_fast_multi                                   | 127610     | 5.00000  | 32      | base      | yes      |      | 797.56250      |
| 52    | kotlin         | 1        | jvm_kotlin_traditional_multi                                      | 124419     | 5.00000  | 32      | base      | yes      |      | 777.61875      |
| 53    | java           | 4        | chrvanorleI32                                                     | 118551     | 5.00500  | 32      | base      | yes      | 1    | 740.20355      |
| 54    | java           | 4        | chrvanorleI32C                                                    | 116472     | 5.00600  | 32      | base      | yes      | 1    | 727.07751      |
| 55    | java           | 4        | chrvanorleI64                                                     | 114944     | 5.01300  | 32      | base      | yes      | 1    | 716.53700      |
| 56    | java           | 4        | chrvanorleI64C                                                    | 112942     | 5.00600  | 32      | base      | yes      | 1    | 705.04145      |
| 57    | rust           | 5        | kulasko-rust-tile-stripe-u8192                                    | 106277     | 5.00003  | 31      | base      | yes      | 1    | 685.65359      |
| 58    | kotlin         | 1        | jvm_kotlin_idiomatic_multi                                        | 108606     | 5.00000  | 32      | base      | yes      |      | 678.78750      |
| 59    | rust           | 5        | kulasko-rust-tile-rotate-u8                                       | 106244     | 5.00003  | 32      | base      | yes      | 1    | 664.02076      |
| 60    | java           | 4        | chrvanorleI8                                                      | 104398     | 5.01800  | 32      | base      | yes      | 1    | 650.14697      |
| 61    | rust           | 5        | kulasko-rust-tile-rotate-u32                                      | 101338     | 5.00005  | 32      | base      | yes      | 1    | 633.35680      |
| 62    | nodejs         | 1        | rogiervandam                                                      | 100209     | 5.07981  | 32      | base      | yes      | 1    | 616.46622      |
| 63    | rust           | 5        | kulasko-rust-tile-bit-u8                                          | 97756      | 5.00000  | 32      | base      | yes      | 1    | 610.97455      |
| 64    | rust           | 5        | kulasko-rust-tile-bit-u32                                         | 95429      | 5.00005  | 32      | base      | yes      | 1    | 596.42552      |
| 65    | dart           | 1        | eagerestwolf&mmcdon20_1bit_par                                    | 86275      | 5.00055  | 32      | base      | yes      | 1    | 539.15955      |
| 66    | d              | 2        | BradleyChatha-MultistaticThreads-SieveRTB1_32                     | 77027      | 5.00182  | 32      | base      | yes      | 1    | 481.24358      |
| 67    | java           | 2        | PratimGhosh86-JavaBitSetMT                                        | 75134      | 5.00000  | 32      | base      | yes      | 1    | 469.58750      |
| 68    | cpp            | 4        | BlackMark-1of2-bs-hs-vec<u8>-clang                                | 73292      | 5.00299  | 32      | base      | yes      | 8    | 457.80123      |
| 69    | pascal         | 3        | olivierbrun-32-threads                                            | 73153      | 5.00200  | 32      | base      | yes      | 1    | 457.02344      |
| 70    | d              | 2        | BradleyChatha-MultistaticThreads-SieveRT                          | 71424      | 5.00207  | 32      | base      | yes      | 1    | 446.21527      |
| 71    | cpp            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-clang                    | 38283      | 5.00488  | 32      | base      | yes      | 1    | 239.03545      |
| 72    | rust           | 5        | kulasko-rust-tile-bool-u8                                         | 32957      | 5.00011  | 32      | base      | yes      | 8    | 205.97672      |
| 73    | dart           | 1        | eagerestwolf&mmcdon20_8bit_par                                    | 15914      | 5.00144  | 32      | base      | yes      | 8    | 99.43388       |
| 74    | zig            | 3        | ManDeJan&ityonemo-zig-parallel-amdahl-sieve-u8                    | 9365       | 5.00057  | 32      | base      | yes      | 8    | 58.52458       |
| 75    | csharp         | 1        | kinematics_rawp                                                   | 3420       | 5.00149  | 32      | base      | yes      | 1    | 21.36863       |
| 76    | csharp         | 1        | kinematics_pool6p                                                 | 3282       | 5.00119  | 32      | wheel     | yes      | 1    | 20.50762       |
| 77    | rust           | 5        | kulasko-rust-stream-rotate-u8                                     | 1840       | 5.00120  | 32      | base      | yes      | 1    | 11.49724       |
| 78    | rust           | 5        | kulasko-rust-stream-bit-u8                                        | 1839       | 5.00024  | 32      | base      | yes      | 1    | 11.49319       |
| 79    | rust           | 5        | kulasko-rust-stream-rotate-u32                                    | 1810       | 5.00042  | 32      | base      | yes      | 1    | 11.31155       |
| 80    | rust           | 5        | kulasko-rust-stream-bit-u32                                       | 1806       | 5.00105  | 32      | base      | yes      | 1    | 11.28514       |
| 81    | rust           | 5        | kulasko-rust-stream-bool-u8                                       | 1646       | 5.00161  | 32      | base      | yes      | 8    | 10.28418       |
| 82    | rust           | 5        | kulasko-rust-stream-stripe-u8192                                  | 1551       | 5.00056  | 31      | base      | yes      | 1    | 10.00533       |
| 83    | idl            | 1        | kriztioan_idlway                                                  | 541        | 5.00060  | 28      | base      | yes      | 8    | 3.86382        |
