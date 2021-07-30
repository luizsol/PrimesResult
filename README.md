# PrimesResult

The results of the [David Plummer's Primes Drag Race](https://github.com/PlummersSoftwareLLC/Primes).

## Results

Generated at 2021-07-29 on a Ryzen 9 5950X with 32GB RAM.

### Best faithful performers for each language

| Implementation | Slowness   | Position | Index | Solution | Label                                                 | Passes | Duration | Threads | Algorithm | Bits | Passes/Second |
| -------------- | ---------- | -------- | ----- | -------- | ----------------------------------------------------- | ------ | -------- | ------- | --------- | ---- | ------------- |
| Cython         | 1          | 1        | 5     | 1        | ssovest-cy                                            | 38980  | 5.00005  | 1       | other     | 1    | 7795.92672    |
| C              | 1.0904     | 2        | 6     | 3        | fvbakel_Cwords                                        | 35749  | 5.00012  | 1       | other     | 1    | 7149.62984    |
| CPP            | 1.2505     | 3        | 7     | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc           | 31171  | 5.00006  | 1       | wheel     | 8    | 6234.12519    |
| Zig            | 1.4502     | 4        | 12    | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 26880  | 5.00018  | 1       | wheel     | 1    | 5375.80647    |
| Rust           | 1.5305     | 5        | 15    | 1        | mike-barber_bit-storage-striped-blocks                | 25469  | 5.00018  | 1       | base      | 1    | 5093.61881    |
| Fortran        | 1.9666     | 6        | 23    | 2        | tjol-8bit                                             | 19821  | 5.00013  | 1       | base      | 8    | 3964.09642    |
| V              | 2.3838     | 7        | 32    | 1        | marghidanu                                            | 16352  | 5.00000  | 1       | base      |      | 3270.40000    |
| Odin           | 2.7489     | 8        | 39    | 1        | odin_byte_moe                                         | 14180  | 5.00000  | 1       | base      | 8    | 2836.00000    |
| AssemblyScript | 2.8874     | 9        | 40    | 1        | donmahallem                                           | 13500  | 5.00000  | 1       | base      |      | 2700.00000    |
| Swift          | 2.8994     | 10       | 41    | 1        | yellowcub                                             | 13444  | 5.00004  | 1       | base      | 8    | 2688.77795    |
| Assembly       | 2.9240     | 11       | 43    | 1        | rbergen_x64ff_byte                                    | 13331  | 5.00000  | 1       | base      | 8    | 2666.20000    |
| Go             | 3.0796     | 12       | 48    | 2        | ssovest-go-other                                      | 12660  | 5.00108  | 1       | other     | 1    | 2531.45195    |
| FSharp         | 3.2272     | 13       | 53    | 3        | dmannock_fsharp_recursion                             | 12079  | 5.00026  | 1       | base      |      | 2415.67245    |
| Crystal        | 3.4573     | 14       | 59    | 1        | marghidanu                                            | 11275  | 5.00021  | 1       | base      | 1    | 2254.90484    |
| NodeJS         | 3.6645     | 15       | 61    | 1        | rogiervandam_memcopy                                  | 10638  | 5.00048  | 1       | other     | 1    | 2127.39496    |
| Scala          | 3.7269     | 16       | 64    | 2        | scilari                                               | 10459  | 5.00000  | 1       | base      |      | 2091.80000    |
| CSharp         | 3.8080     | 17       | 65    | 1        | kinematics_dbool                                      | 10237  | 5.00033  | 1       | base      | 8    | 2047.26488    |
| Kotlin         | 3.8212     | 18       | 67    | 1        | jvm_kotlin_idiomatic_fast_single                      | 10213  | 5.00600  | 1       | base      |      | 2040.15182    |
| Java           | 4.1131     | 19       | 72    | 1        | MansenC                                               | 9477   | 5.00000  | 1       | base      |      | 1895.40000    |
| Julia          | 4.3371     | 20       | 76    | 3        | louie-github_port_1of2                                | 8988   | 5.00031  | 1       | base      | 1    | 1797.49003    |
| Dart           | 5.2675     | 21       | 88    | 1        | eagerestwolf&mmcdon20_8bit                            | 7401   | 5.00062  | 1       | base      | 8    | 1480.01677    |
| BASIC          | 6.2204     | 22       | 96    | 3        | Nukepayload2_ArrayPool8of30M                          | 6267   | 5.00048  | 1       | wheel     | 1    | 1253.27964    |
| TypeScript     | 7.1092     | 23       | 101   | 1        | marghidanu                                            | 5483   | 5.00000  | 1       | base      |      | 1096.60000    |
| D              | 13.019     | 24       | 115   | 1        | eagerestwolf                                          | 2994   | 5.00000  | 1       | base      | 8    | 598.80000     |
| Nim            | 13.040     | 25       | 116   | 2        | beef331                                               | 2990   | 5.00128  | 1       | base      | 1    | 597.84637     |
| Python         | 19.042     | 26       | 126   | 2        | ssovest                                               | 2047   | 5.00001  | 1       | base      | 8    | 409.39914     |
| Pony           | 30.429     | 27       | 135   | 1        | marghidanu                                            | 1281   | 5.00000  | 1       | base      | 1    | 256.20000     |
| Pascal         | 31.924     | 28       | 137   | 1        | rbergen                                               | 1221   | 5.00000  | 1       | base      |      | 244.20000     |
| R              | 39.799     | 29       | 140   | 1        | fvbakel_R                                             | 980    | 5.00300  | 1       | base      | 32   | 195.88247     |
| Haxe           | 56.098     | 30       | 142   | 1        | TayIorRobinson_Haxe_C++                               | 695    | 5.00104  | 1       | base      |      | 138.97096     |
| Scheme         | 62.385     | 31       | 144   | 1        | William103                                            | 625    | 5.00139  | 1       | base      | 1    | 124.96514     |
| Octave         | 63.879     | 32       | 145   | 2        | Brandon-Johns_8bit                                    | 611    | 5.00647  | 1       | base      | 8    | 122.04213     |
| PHP            | 71.610     | 33       | 146   | 1        | DennisdeBest                                          | 545    | 5.00610  | 1       | base      |      | 108.86716     |
| OCaml          | 71.918     | 34       | 147   | 1        | gkpotter-faithful                                     | 542    | 5.00001  | 1       | base      |      | 108.39987     |
| Perl           | 99.496     | 35       | 151   | 2        | kjetillll                                             | 392    | 5.00292  | 1       | base      |      | 78.35429      |
| StandardML     | 185.59     | 36       | 154   | 1        | NotMatthewGriffin_SMLofNJ                             | 211    | 5.02300  | 1       | base      | 1    | 42.00677      |
| Ballerina      | 222.74     | 37       | 155   | 1        | da-strange-boi                                        | 175    | 5.00000  | 1       | base      | 1    | 35.00000      |
| GDScript       | 235.60     | 38       | 156   | 1        | OrigamiDev-Pete                                       | 172    | 5.19800  | 1       | base      | 8    | 33.08965      |
| Ruby           | 261.92     | 39       | 157   | 1        | rbergen                                               | 149    | 5.00600  | 1       | base      |      | 29.76428      |
| Wren           | 327.56     | 40       | 158   | 1        | marghidanu                                            | 119    | 5.00005  | 1       | base      |      | 23.79975      |
| REXX           | 412.95     | 41       | 159   | 2        | joss_NetRexx                                          | 95     | 5.03219  | 1       | base      | 8    | 18.87845      |
| Kos            | 435.07     | 42       | 160   | 1        | cdragan                                               | 90     | 5.02265  | 1       | base      | 8    | 17.91883      |
| Elixir         | 695.85     | 43       | 163   | 2        | thomas9911                                            | 58     | 5.17700  | 1       | base      | 1    | 11.20340      |
| Smalltalk      | 739.44     | 44       | 165   | 1        | fvbakel_smalltalk                                     | 53     | 5.02700  | 1       | base      | 1    | 10.54307      |
| Tcl            | 869.85     | 45       | 167   | 2        | fvbakel_ootcl2                                        | 45     | 5.02100  | 1       | base      | 32   | 8.96236       |
| PowerShell     | 1448.1     | 46       | 170   | 2        | crowbar27_ps2                                         | 27     | 5.01531  | 1       | base      | 1    | 5.38352       |
| Emojicode      | 1559.2     | 47       | 172   | 1        | marghidanu                                            | 25     | 5.00000  | 1       | base      |      | 5.00000       |
| Raku           | 5056.4     | 48       | 177   | 1        | draco1006                                             | 8      | 5.18874  | 1       | base      |      | 1.54180       |
| Red            | 6118.8     | 49       | 179   | 1        | mmcdon20_red                                          | 7      | 5.49406  | 1       | base      | 1    | 1.27410       |
| IDL            | 1.2044e+04 | 50       | 184   | 1        | kriztioan_1bit                                        | 4      | 6.17950  | 1       | base      | 1    | 0.64730       |
| Prolog         | 5.0907e+04 | 51       | 189   | 1        | jimbxb-prolog-basic                                   | 1      | 6.53000  | 1       | base      | 1    | 0.15314       |

### Single-threaded

| Index | Implementation      | Solution | Label                                                 | Passes  | Duration  | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | ------------------- | -------- | ----------------------------------------------------- | ------- | --------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | PrimeCPP            | 4        | BlackMark-pregenerated-inv_bits<u32>-clang            | 2545336 | 5.00000   | 1       | base      | no       | 1    | 509067.20000  |
| 2     | PrimeCPP            | 4        | BlackMark-pregenerated-inv_bits<u32>-gcc              | 1213061 | 5.00000   | 1       | base      | no       | 1    | 242612.20000  |
| 3     | PrimeRust           | 6        | SycrationSinglethreaded                               | 286152  | 5.00000   | 1       | base      | no       |      | 57230.34623   |
| 4     | PrimeCPP            | 3        | flo80_constexpr                                       | 234823  | 5.00003   | 1       | base      | no       | 1    | 46964.35579   |
| 5     | PrimeCython         | 1        | ssovest-cy                                            | 38980   | 5.00005   | 1       | other     | yes      | 1    | 7795.92672    |
| 6     | PrimeC              | 3        | fvbakel_Cwords                                        | 35749   | 5.00012   | 1       | other     | yes      | 1    | 7149.62984    |
| 7     | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc           | 31171   | 5.00006   | 1       | wheel     | yes      | 8    | 6234.12519    |
| 8     | PrimeMixed          | 1        | ssovest-cgo                                           | 30069   | 5.00074   | 1       | other     | no       | 1    | 6012.91089    |
| 9     | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-clang       | 29147   | 5.00017   | 1       | wheel     | yes      | 1    | 5829.20181    |
| 10    | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-gcc         | 28990   | 5.00005   | 1       | wheel     | yes      | 1    | 5797.94202    |
| 11    | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-clang     | 28310   | 5.00008   | 1       | wheel     | yes      | 1    | 5661.90941    |
| 12    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 26880   | 5.00018   | 1       | wheel     | yes      | 1    | 5375.80647    |
| 13    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030  | 26660   | 5.00016   | 1       | wheel     | yes      | 1    | 5331.82938    |
| 14    | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-gcc       | 25800   | 5.00013   | 1       | wheel     | yes      | 1    | 5159.86584    |
| 15    | PrimeRust           | 1        | mike-barber_bit-storage-striped-blocks                | 25469   | 5.00018   | 1       | base      | yes      | 1    | 5093.61881    |
| 16    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-480of2310    | 24445   | 5.00001   | 1       | wheel     | yes      | 1    | 4888.99022    |
| 17    | PrimeC              | 2        | danielspaangberg_48of210                              | 24368   | 5.00008   | 1       | wheel     | yes      | 1    | 4873.51910    |
| 18    | PrimeRust           | 1        | mike-barber_bit-storage-striped-blocks-small          | 24240   | 5.00004   | 1       | base      | yes      | 1    | 4847.95978    |
| 19    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-480of2310   | 22831   | 5.00006   | 1       | wheel     | yes      | 1    | 4566.14521    |
| 20    | PrimeRust           | 1        | mike-barber_byte-storage                              | 22797   | 5.00106   | 1       | base      | yes      | 8    | 4558.43317    |
| 21    | PrimeRust           | 1        | mike-barber_bit-storage-striped                       | 21557   | 5.00007   | 1       | base      | yes      | 1    | 4311.33709    |
| 22    | PrimeC              | 2        | danielspaangberg_8of30                                | 19913   | 5.00008   | 1       | wheel     | yes      | 1    | 3982.53947    |
| 23    | PrimeFortran        | 2        | tjol-8bit                                             | 19821   | 5.00013   | 1       | base      | yes      | 8    | 3964.09642    |
| 24    | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-gcc                | 19719   | 5.00003   | 1       | base      | yes      | 8    | 3943.77634    |
| 25    | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-clang              | 19683   | 5.00013   | 1       | base      | yes      | 8    | 3936.49765    |
| 26    | PrimeAssembly       | 1        | rbergen_x64uff_byte                                   | 19631   | 5.00000   | 1       | base      | no       | 8    | 3926.20000    |
| 27    | PrimeCPP            | 4        | BlackMark-1of2-bs-hs-vec<u8>-gcc                      | 19364   | 5.00016   | 1       | base      | yes      | 8    | 3872.67607    |
| 28    | PrimeZig            | 2        | ManDeJan&ityonemo-zig-byte-sieve-type-bool            | 19310   | 5.00019   | 1       | base      | no       | 8    | 3861.85325    |
| 29    | PrimeCython         | 1        | rpkak+byte-array                                      | 18966   | 5.00021   | 1       | base      | yes      | 8    | 3793.04037    |
| 30    | PrimeC              | 2        | danielspaangberg_5760of30030_owrb                     | 18033   | 5.00024   | 1       | wheel     | yes      | 1    | 3606.42833    |
| 31    | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-gcc          | 16911   | 5.00012   | 1       | base      | yes      | 1    | 3382.11883    |
| 32    | PrimeV              | 1        | marghidanu                                            | 16352   | 5.00000   | 1       | base      | yes      |      | 3270.40000    |
| 33    | PrimeHaskell        | 1        | fatho/vector_unchecked                                | 15826   | 5.00011   | 1       | base      | no       | 8    | 3165.13290    |
| 34    | PrimeZig            | 1        | devblok                                               | 15774   | 5.00010   | 1       | base      | yes      | 8    | 3154.73691    |
| 35    | PrimeC              | 2        | danielspaangberg_480of2310_owrb                       | 15723   | 5.00045   | 1       | wheel     | yes      | 1    | 3144.31764    |
| 36    | PrimeAda            | 1        | BoopBeepBoopBeep                                      | 15715   | 5.00018   | 1       | base      | no       |      | 3142.88820    |
| 37    | PrimeCPP            | 1        | davepl_pol                                            | 14691   | 5.00013   | 1       | base      | yes      | 1    | 2938.12243    |
| 38    | PrimeRust           | 1        | mike-barber_bit-storage-rotate                        | 14350   | 5.00022   | 1       | base      | yes      | 1    | 2869.87328    |
| 39    | PrimeOdin           | 1        | odin_byte_moe                                         | 14180   | 5.00000   | 1       | base      | yes      | 8    | 2836.00000    |
| 40    | PrimeAssemblyScript | 1        | donmahallem                                           | 13500   | 5.00000   | 1       | base      | yes      |      | 2700.00000    |
| 41    | PrimeSwift          | 1        | yellowcub                                             | 13444   | 5.00004   | 1       | base      | yes      | 8    | 2688.77795    |
| 42    | PrimeHaskell        | 1        | fatho/vector                                          | 13345   | 5.00030   | 1       | base      | no       | 8    | 2668.83934    |
| 43    | PrimeAssembly       | 1        | rbergen_x64ff_byte                                    | 13331   | 5.00000   | 1       | base      | yes      | 8    | 2666.20000    |
| 44    | PrimeFortran        | 1        | johandweber_fortran                                   | 13291   | 5.00000   | 1       | base      | no       | 1    | 2658.20000    |
| 45    | PrimeC              | 2        | danielspaangberg_48of210_owrb                         | 13101   | 5.00012   | 1       | wheel     | yes      | 1    | 2620.13502    |
| 46    | PrimeFortran        | 2        | tjol-logical                                          | 12842   | 5.00006   | 1       | base      | yes      |      | 2568.36718    |
| 47    | PrimeC              | 1        | mckoss-c830                                           | 12806   | 5.00000   | 1       | wheel     | yes      | 1    | 2561.20000    |
| 48    | PrimeGo             | 2        | ssovest-go-other                                      | 12660   | 5.00108   | 1       | other     | yes      | 1    | 2531.45195    |
| 49    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8              | 12451   | 5.00014   | 1       | base      | yes      | 1    | 2490.13028    |
| 50    | PrimeGo             | 2        | ssovest-go-other-B                                    | 12424   | 5.00080   | 1       | other     | yes      | 1    | 2484.40452    |
| 51    | PrimeFortran        | 2        | tjol-bits                                             | 12312   | 5.00029   | 1       | base      | yes      | 1    | 2462.25512    |
| 52    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8                 | 12121   | 5.00038   | 1       | base      | yes      | 8    | 2424.01577    |
| 53    | PrimeFSharp         | 3        | dmannock_fsharp_recursion                             | 12079   | 5.00026   | 1       | base      | yes      |      | 2415.67245    |
| 54    | PrimeC              | 2        | danielspaangberg_1of2                                 | 11799   | 5.00009   | 1       | base      | yes      | 1    | 2359.75752    |
| 55    | PrimeFSharp         | 2        | dmannock_fsharp_port                                  | 11691   | 5.00013   | 1       | base      | yes      |      | 2338.14061    |
| 56    | PrimeZig            | 2        | ManDeJan&ityonemo-zig-bit-sieve                       | 11604   | 5.00028   | 1       | base      | no       | 1    | 2320.67004    |
| 57    | PrimeD              | 2        | BradleyChatha-Single-SieveCT                          | 11362   | 5.00008   | 1       | base      | no       | 1    | 2272.36364    |
| 58    | PrimeHaskell        | 1        | fatho/bitset                                          | 11342   | 5.00006   | 1       | base      | no       | 1    | 2268.37187    |
| 59    | PrimeCrystal        | 1        | marghidanu                                            | 11275   | 5.00021   | 1       | base      | yes      | 1    | 2254.90484    |
| 60    | PrimeRust           | 1        | mike-barber_bit-storage                               | 10993   | 5.00020   | 1       | base      | yes      | 1    | 2198.51110    |
| 61    | PrimeNodeJS         | 1        | rogiervandam_memcopy                                  | 10638   | 5.00048   | 1       | other     | yes      | 1    | 2127.39496    |
| 62    | PrimeRust           | 2        | Azgrom                                                | 10532   | 5.00034   | 1       | base      | yes      |      | 2106.25593    |
| 63    | PrimeOdin           | 1        | odin_bit_moe                                          | 10470   | 5.00000   | 1       | base      | yes      | 1    | 2094.00000    |
| 64    | PrimeScala          | 2        | scilari                                               | 10459   | 5.00000   | 1       | base      | yes      |      | 2091.80000    |
| 65    | PrimeCSharp         | 1        | kinematics_dbool                                      | 10237   | 5.00033   | 1       | base      | yes      | 8    | 2047.26488    |
| 66    | PrimeCython         | 1        | rpkak+bit-array                                       | 10204   | 5.00021   | 1       | base      | yes      | 1    | 2040.71282    |
| 67    | PrimeKotlin         | 1        | jvm_kotlin_idiomatic_fast_single                      | 10213   | 5.00600   | 1       | base      | yes      |      | 2040.15182    |
| 68    | PrimeKotlin         | 1        | jvm_kotlin_traditional_single                         | 9864    | 5.01600   | 1       | base      | yes      |      | 1966.50718    |
| 69    | PrimeC              | 2        | danielspaangberg_8of30_owrb                           | 9824    | 5.00049   | 1       | wheel     | yes      | 1    | 1964.60550    |
| 70    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-bool               | 9799    | 5.00032   | 1       | base      | yes      | 8    | 1959.67458    |
| 71    | PrimeCSharp         | 1        | kinematics_ibool                                      | 9758    | 5.00003   | 1       | base      | yes      | 8    | 1951.58829    |
| 72    | PrimeJava           | 1        | MansenC                                               | 9477    | 5.00000   | 1       | base      | yes      |      | 1895.40000    |
| 73    | PrimeHaskell        | 1        | fatho/bitset_unchecked                                | 9269    | 5.00038   | 1       | base      | no       | 1    | 1853.65801    |
| 74    | PrimePython         | 3        | emillynge_numpy                                       | 9267    | 5.00035   | 1       | base      | no       | 8    | 1853.27088    |
| 75    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-5760of30030     | 9085    | 5.00025   | 1       | wheel     | yes      | 8    | 1816.90915    |
| 76    | PrimeJulia          | 3        | louie-github_port_1of2                                | 8988    | 5.00031   | 1       | base      | yes      | 1    | 1797.49003    |
| 77    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-480of2310       | 8747    | 5.00023   | 1       | wheel     | yes      | 8    | 1749.31953    |
| 78    | PrimeRust           | 4        | joshallen64                                           | 8629    | 5.00047   | 1       | base      | yes      |      | 1725.63952    |
| 79    | PrimeLua            | 2        | ben1jen_luajit1                                       | 8369    | 5.00000   | 1       | base      | no       | 1    | 1673.80000    |
| 80    | PrimeJulia          | 1        | dcbi                                                  | 8171    | 5.00004   | 1       | base      | yes      | 1    | 1634.18792    |
| 81    | PrimeAssembly       | 1        | rbergen_x64uff_bitshift                               | 8168    | 5.00000   | 1       | base      | no       | 1    | 1633.60000    |
| 82    | PrimeAssembly       | 1        | rbergen_x64ff_bitshift                                | 8106    | 5.00000   | 1       | base      | yes      | 1    | 1621.20000    |
| 83    | PrimeJulia          | 2        | epithet-jl                                            | 7874    | 5.00048   | 1       | base      | yes      | 1    | 1574.64728    |
| 84    | PrimeCSharp         | 3        | tannergooding                                         | 7832    | 5.00055   | 1       | base      | yes      | 1    | 1566.22643    |
| 85    | PrimeCSharp         | 1        | kinematics_raw32                                      | 7618    | 5.00063   | 1       | base      | yes      | 1    | 1523.40805    |
| 86    | PrimeAssembly       | 1        | rbergen_x64ff_bitbtr                                  | 7490    | 5.00000   | 1       | base      | yes      | 1    | 1498.00000    |
| 87    | PrimeAssembly       | 1        | rbergen_x64uff_bitbtr                                 | 7472    | 5.00000   | 1       | base      | no       | 1    | 1494.40000    |
| 88    | PrimeDart           | 1        | eagerestwolf&mmcdon20_8bit                            | 7401    | 5.00062   | 1       | base      | yes      | 8    | 1480.01677    |
| 89    | PrimeCSharp         | 1        | kinematics_rawd                                       | 7189    | 5.00042   | 1       | base      | yes      | 1    | 1437.67923    |
| 90    | PrimeCSharp         | 1        | kinematics_raw                                        | 7170    | 5.00005   | 1       | base      | yes      | 1    | 1433.98566    |
| 91    | PrimeScala          | 1        | rom1dep                                               | 6917    | 5.00000   | 1       | base      | yes      |      | 1383.40000    |
| 92    | PrimeCSharp         | 1        | kinematics_raw6                                       | 6898    | 5.00001   | 1       | wheel     | yes      | 1    | 1379.59724    |
| 93    | PrimeCSharp         | 1        | kinematics_pool30                                     | 6864    | 5.00030   | 1       | wheel     | yes      | 1    | 1372.71764    |
| 94    | PrimeCSharp         | 1        | kinematics_bool                                       | 6830    | 5.00054   | 1       | base      | yes      | 8    | 1365.85249    |
| 95    | PrimeNodeJS         | 1        | rogiervandam                                          | 6789    | 5.00046   | 1       | base      | yes      | 1    | 1357.67586    |
| 96    | PrimeBASIC          | 3        | Nukepayload2_ArrayPool8of30M                          | 6267    | 5.00048   | 1       | wheel     | yes      | 1    | 1253.27964    |
| 97    | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-clang         | 6180    | 5.00000   | 1       | wheel     | yes      | 8    | 1236.00000    |
| 98    | PrimeBASIC          | 3        | Nukepayload2_ReDim8of30M                              | 6127    | 5.00067   | 1       | wheel     | yes      | 1    | 1225.23641    |
| 99    | PrimeCSharp         | 1        | kinematics_pool30m                                    | 5813    | 5.00019   | 1       | wheel     | yes      | 1    | 1162.55582    |
| 100   | PrimeGo             | 2        | ssovest-go-uint8-B                                    | 5695    | 5.00172   | 1       | base      | yes      | 1    | 1138.60735    |
| 101   | PrimeTypeScript     | 1        | marghidanu                                            | 5483    | 5.00000   | 1       | base      | yes      |      | 1096.60000    |
| 102   | PrimeCSharp         | 1        | kinematics_pool2of6                                   | 5243    | 5.00039   | 1       | wheel     | yes      | 1    | 1048.51822    |
| 103   | PrimeGo             | 2        | ssovest-go-uint32                                     | 5143    | 5.00043   | 1       | base      | yes      | 1    | 1028.51105    |
| 104   | PrimeGo             | 2        | ssovest-go-ptr                                        | 5066    | 5.00052   | 1       | base      | yes      | 1    | 1013.09552    |
| 105   | PrimeGo             | 2        | ssovest-go-uint32-B                                   | 5064    | 5.00117   | 1       | base      | yes      | 1    | 1012.56364    |
| 106   | PrimeJava           | 2        | PratimGhosh86-JavaBitSet                              | 4793    | 5.00000   | 1       | base      | yes      | 1    | 958.60000     |
| 107   | PrimeGo             | 2        | ssovest-go-uint8                                      | 4713    | 5.00106   | 1       | base      | yes      | 1    | 942.39960     |
| 108   | PrimeGo             | 2        | ssovest-go-ptr-B                                      | 4703    | 5.00126   | 1       | base      | yes      | 1    | 940.36275     |
| 109   | PrimeDart           | 1        | eagerestwolf&mmcdon20_1bit                            | 4684    | 5.00103   | 1       | base      | yes      | 1    | 936.60800     |
| 110   | PrimeKotlin         | 1        | jvm_kotlin_idiomatic_single                           | 4216    | 5.00300   | 1       | base      | yes      |      | 842.69438     |
| 111   | PrimeRust           | 3        | Blui42                                                | 4023    | 5.00117   | 1       | base      | yes      |      | 804.41250     |
| 112   | PrimeJava           | 3        | MansenC-native                                        | 3886    | 5.00000   | 1       | base      | yes      |      | 777.20000     |
| 113   | PrimeKotlin         | 1        | native_kotlin_idiomatic_fast_single                   | 3854    | 5.00000   | 1       | base      | yes      |      | 770.80000     |
| 114   | PrimeCPP            | 4        | BlackMark-1of2-bs-hs-vec<u8>-clang                    | 3022    | 5.00076   | 1       | base      | yes      | 8    | 604.30815     |
| 115   | PrimeD              | 1        | eagerestwolf                                          | 2994    | 5.00000   | 1       | base      | yes      | 8    | 598.80000     |
| 116   | PrimeNim            | 2        | beef331                                               | 2990    | 5.00128   | 1       | base      | yes      | 1    | 597.84637     |
| 117   | PrimeD              | 2        | BradleyChatha-Single-SieveRT                          | 2908    | 5.00160   | 1       | base      | yes      | 1    | 581.41395     |
| 118   | PrimeCSharp         | 1        | kinematics_pool                                       | 2831    | 5.00157   | 1       | base      | yes      | 1    | 566.02227     |
| 119   | PrimeNim            | 1        | marghidanu                                            | 2808    | 5.00146   | 1       | base      | yes      | 8    | 561.43611     |
| 120   | PrimeCSharp         | 1        | kinematics_standard                                   | 2603    | 5.00049   | 1       | base      | yes      | 1    | 520.54899     |
| 121   | PrimeCSharp         | 2        | davepl                                                | 2544    | 5.00123   | 1       | base      | yes      | 1    | 508.67487     |
| 122   | PrimeCSharp         | 1        | kinematics_original                                   | 2444    | 5.00098   | 1       | base      | yes      | 1    | 488.70421     |
| 123   | PrimeKotlin         | 1        | native_kotlin_idiomatic_single                        | 2435    | 5.00200   | 1       | base      | yes      |      | 486.80528     |
| 124   | PrimeBASIC          | 1        | rbergen_8of30                                         | 2414    | 5.00100   | 1       | wheel     | yes      | 1    | 482.70346     |
| 125   | PrimeOctave         | 1        | octave                                                | 2166    | 5.00191   | 1       | base      | no       |      | 433.03458     |
| 126   | PrimePython         | 2        | ssovest                                               | 2047    | 5.00001   | 1       | base      | yes      | 8    | 409.39914     |
| 127   | PrimeKotlin         | 1        | js_kotlin_idiomatic_fast_single                       | 1961    | 5.00400   | 1       | base      | yes      |      | 391.88649     |
| 128   | PrimeKotlin         | 1        | js_kotlin_idiomatic_single                            | 1960    | 5.00500   | 1       | base      | yes      |      | 391.60839     |
| 129   | PrimeKotlin         | 1        | js_kotlin_traditional_single                          | 1913    | 5.00300   | 1       | base      | yes      |      | 382.37058     |
| 130   | PrimeFSharp         | 1        | rbergen                                               | 1790    | 5.00026   | 1       | base      | yes      | 1    | 357.98168     |
| 131   | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-clang        | 1717    | 5.00269   | 1       | base      | yes      | 1    | 343.21535     |
| 132   | PrimeKotlin         | 1        | native_kotlin_traditional_single                      | 1640    | 5.00300   | 1       | base      | yes      |      | 327.80332     |
| 133   | PrimeBASIC          | 2        | rbergen_vb                                            | 1637    | 5.00081   | 1       | base      | yes      | 1    | 327.34690     |
| 134   | PrimeGo             | 1        | bundgaard                                             | 1290    | 5.00401   | 1       | base      | yes      |      | 257.79320     |
| 135   | PrimePony           | 1        | marghidanu                                            | 1281    | 5.00000   | 1       | base      | yes      | 1    | 256.20000     |
| 136   | PrimeCOBOL          | 1        | fvbakel_Cobol                                         | 1247    | 5.00000   | 1       | base      | no       | 8    | 249.40000     |
| 137   | PrimePascal         | 1        | rbergen                                               | 1221    | 5.00000   | 1       | base      | yes      |      | 244.20000     |
| 138   | PrimePascal         | 2        | circular17                                            | 1196    | 5.00000   | 1       | base      | yes      | 1    | 239.20000     |
| 139   | PrimeR              | 2        | nobrien97                                             | 1054    | 5.00300   | 1       | base      | no       | 32   | 210.67360     |
| 140   | PrimeR              | 1        | fvbakel_R                                             | 980     | 5.00300   | 1       | base      | yes      | 32   | 195.88247     |
| 141   | PrimeBASIC          | 1        | rbergen_boolean                                       | 734     | 5.00200   | 1       | base      | yes      |      | 146.74130     |
| 142   | PrimeHaxe           | 1        | TayIorRobinson_Haxe_C++                               | 695     | 5.00104   | 1       | base      | yes      |      | 138.97096     |
| 143   | PrimeOCaml          | 2        | gkpotter-unfaithful                                   | 690     | 5.00022   | 1       | base      | no       |      | 137.99396     |
| 144   | PrimeScheme         | 1        | William103                                            | 625     | 5.00139   | 1       | base      | yes      | 1    | 124.96514     |
| 145   | PrimeOctave         | 2        | Brandon-Johns_8bit                                    | 611     | 5.00647   | 1       | base      | yes      | 8    | 122.04213     |
| 146   | PrimePHP            | 1        | DennisdeBest                                          | 545     | 5.00610   | 1       | base      | yes      |      | 108.86716     |
| 147   | PrimeOCaml          | 1        | gkpotter-faithful                                     | 542     | 5.00001   | 1       | base      | yes      |      | 108.39987     |
| 148   | PrimeBASIC          | 1        | rbergen_bit32                                         | 487     | 5.00100   | 1       | base      | yes      | 1    | 97.38052      |
| 149   | PrimeForth          | 1        | tjol-8bit                                             | 479     | 5.00591   | 1       | base      | no       | 8    | 95.68688      |
| 150   | PrimeBASIC          | 1        | rbergen_bit64                                         | 470     | 5.00500   | 1       | base      | yes      | 1    | 93.90609      |
| 151   | PrimePerl           | 2        | kjetillll                                             | 392     | 5.00292   | 1       | base      | yes      |      | 78.35429      |
| 152   | PrimeForth          | 1        | tjol-1bit                                             | 338     | 5.01167   | 1       | base      | no       | 1    | 67.44263      |
| 153   | PrimePostScript     | 1        | epithet-ps                                            | 243     | 5.01100   | 1       | base      | no       | 8    | 48.49331      |
| 154   | PrimeStandardML     | 1        | NotMatthewGriffin_SMLofNJ                             | 211     | 5.02300   | 1       | base      | yes      | 1    | 42.00677      |
| 155   | PrimeBallerina      | 1        | da-strange-boi                                        | 175     | 5.00000   | 1       | base      | yes      | 1    | 35.00000      |
| 156   | PrimeGDScript       | 1        | OrigamiDev-Pete                                       | 172     | 5.19800   | 1       | base      | yes      | 8    | 33.08965      |
| 157   | PrimeRuby           | 1        | rbergen                                               | 149     | 5.00600   | 1       | base      | yes      |      | 29.76428      |
| 158   | PrimeWren           | 1        | marghidanu                                            | 119     | 5.00005   | 1       | base      | yes      |      | 23.79975      |
| 159   | PrimeREXX           | 2        | joss_NetRexx                                          | 95      | 5.03219   | 1       | base      | yes      | 8    | 18.87845      |
| 160   | PrimeKos            | 1        | cdragan                                               | 90      | 5.02265   | 1       | base      | yes      | 8    | 17.91883      |
| 161   | PrimePerl           | 1        | marghidanu                                            | 63      | 5.04870   | 1       | base      | yes      |      | 12.47845      |
| 162   | PrimeProlog         | 1        | jimbxb-prolog-c                                       | 59      | 5.07600   | 1       | base      | no       | 1    | 11.62333      |
| 163   | PrimeElixir         | 2        | thomas9911                                            | 58      | 5.17700   | 1       | base      | yes      | 1    | 11.20340      |
| 164   | PrimeLisp           | 1        | mikehw                                                | 112     | 10.06666  | 1       | base      | no       | 1    | 11.12583      |
| 165   | PrimeSmalltalk      | 1        | fvbakel_smalltalk                                     | 53      | 5.02700   | 1       | base      | yes      | 1    | 10.54307      |
| 166   | PrimeTeX            | 2        | jfbu-tex-480of2310                                    | 47      | 5.10362   | 1       | wheel     | no       |      | 9.20915       |
| 167   | PrimeTcl            | 2        | fvbakel_ootcl2                                        | 45      | 5.02100   | 1       | base      | yes      | 32   | 8.96236       |
| 168   | PrimeMIXAL          | 1        | rbergen                                               | 30      | 3.57000   | 1       | base      | no       | 1    | 8.40336       |
| 169   | PrimeHaxe           | 1        | TayIorRobinson_Haxe_HaxeEval                          | 30      | 5.03139   | 1       | base      | yes      |      | 5.96257       |
| 170   | PrimePowerShell     | 2        | crowbar27_ps2                                         | 27      | 5.01531   | 1       | base      | yes      | 1    | 5.38352       |
| 171   | PrimeREXX           | 1        | joss_REXX                                             | 26      | 5.10751   | 1       | base      | no       | 8    | 5.09055       |
| 172   | PrimeEmojicode      | 1        | marghidanu                                            | 25      | 5.00000   | 1       | base      | yes      |      | 5.00000       |
| 173   | PrimePython         | 1        | davepl                                                | 24      | 5.11334   | 1       | base      | yes      |      | 4.69361       |
| 174   | PrimeTeX            | 2        | jfbu-tex                                              | 19      | 5.07965   | 1       | base      | no       |      | 3.74042       |
| 175   | PrimeSQL            | 2        | fvbakel_MariaDB3                                      | 9       | 5.48300   | 1       | other     | no       | 32   | 1.64144       |
| 176   | PrimeTcl            | 1        | fvbakeltcl                                            | 8       | 5.18000   | 1       | base      | yes      | 1    | 1.54440       |
| 177   | PrimeRaku           | 1        | draco1006                                             | 8       | 5.18874   | 1       | base      | yes      |      | 1.54180       |
| 178   | PrimeSQL            | 1        | fvbakel_sqlite                                        | 7       | 5.20583   | 1       | other     | no       | 8    | 1.34465       |
| 179   | PrimeRed            | 1        | mmcdon20_red                                          | 7       | 5.49406   | 1       | base      | yes      | 1    | 1.27410       |
| 180   | PrimeTcl            | 2        | fvbakel_ootcl                                         | 7       | 5.66900   | 1       | base      | yes      | 1    | 1.23479       |
| 181   | PrimeHaxe           | 1        | TayIorRobinson_Haxe_Python                            | 7       | 5.73188   | 1       | base      | yes      |      | 1.22124       |
| 182   | PrimeSQL            | 2        | fvbakel_MariaDB2                                      | 6       | 5.65000   | 1       | other     | no       | 32   | 1.06195       |
| 183   | PrimeProlog         | 1        | jimbxb-prolog-dynamic                                 | 5       | 5.48000   | 1       | base      | no       |      | 0.91241       |
| 184   | PrimeIDL            | 1        | kriztioan_1bit                                        | 4       | 6.17950   | 1       | base      | yes      | 1    | 0.64730       |
| 185   | PrimeBash           | 1        | bash_inline                                           | 3       | 6.92311   | 1       | base      | no       |      | 0.43333       |
| 186   | PrimeBash           | 1        | bash                                                  | 2       | 7.58930   | 1       | base      | no       |      | 0.26353       |
| 187   | PrimeSQL            | 2        | fvbakel_MariaDB1                                      | 1       | 5.89600   | 1       | base      | no       | 32   | 0.16961       |
| 188   | PrimeTeX            | 1        | tjol                                                  | 2       | 12.98244  | 1       | base      | no       | 32   | 0.15405       |
| 189   | PrimeProlog         | 1        | jimbxb-prolog-basic                                   | 1       | 6.53000   | 1       | base      | yes      | 1    | 0.15314       |
| 190   | PrimeBash           | 1        | bash_packed                                           | 1       | 7.33256   | 1       | base      | no       |      | 0.13638       |
| 191   | PrimeElixir         | 1        | cdesch                                                | 1       | 22.32700  | 1       | base      | no       |      | 0.04479       |
| 192   | PrimeLua            | 1        | lua                                                   | 1       | 26.00000  | 1       | base      | no       | 64   | 0.03846       |
| 193   | PrimePowerShell     | 1        | crowbar27_ps1                                         | 1       | 52.74750  | 1       | base      | yes      | 1    | 0.01896       |
| 194   | PrimeOctave         | 2        | Brandon-Johns_1bit                                    | 1       | 129.59967 | 1       | base      | yes      | 1    | 0.00772       |

### Multi-threaded

| Index | Implementation | Solution | Label                                                             | Passes   | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------------------- | -------- | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | PrimeCPP       | 4        | BlackMark-pregenerated-inv_bits<u32>-clang                        | 32755702 | 5.00175  | 32      | base      | no       | 1    | 204651.50947  |
| 2     | PrimeCPP       | 4        | BlackMark-pregenerated-inv_bits<u32>-gcc                          | 14406215 | 5.00124  | 32      | base      | no       | 1    | 90016.51965   |
| 3     | PrimeRust      | 6        | SycrationMultithreaded                                            | 1993137  | 5.00002  | 8       | base      | no       |      | 49828.24535   |
| 4     | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-gcc                     | 468989   | 5.00133  | 32      | wheel     | yes      | 1    | 2930.40176    |
| 5     | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-gcc                   | 444728   | 5.00359  | 32      | wheel     | yes      | 1    | 2777.55571    |
| 6     | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-5760of30030  | 388728   | 5.00027  | 32      | wheel     | yes      | 1    | 2429.41881    |
| 7     | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-clang                   | 361714   | 5.00159  | 32      | wheel     | yes      | 1    | 2259.99382    |
| 8     | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-480of2310    | 359481   | 5.00004  | 32      | wheel     | yes      | 1    | 2246.73828    |
| 9     | PrimeCPP       | 3        | flo80_constexpr                                                   | 358400   | 5.00010  | 32      | base      | no       | 1    | 2239.95430    |
| 10    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-480of2310   | 347408   | 5.00037  | 32      | wheel     | yes      | 1    | 2171.13934    |
| 11    | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-clang                 | 339541   | 5.01197  | 32      | wheel     | yes      | 1    | 2117.06300    |
| 12    | PrimeRust      | 1        | mike-barber_bit-storage-striped-blocks-small                      | 338136   | 5.00070  | 32      | base      | yes      | 1    | 2113.05276    |
| 13    | PrimeC         | 2        | danielspaangberg_5760of30030_epar                                 | 334909   | 5.00111  | 32      | wheel     | yes      | 1    | 2092.71499    |
| 14    | PrimeRust      | 1        | mike-barber_bit-storage-striped-blocks                            | 332038   | 5.00066  | 32      | base      | yes      | 1    | 2074.96185    |
| 15    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-5760of30030 | 329956   | 5.00023  | 32      | wheel     | yes      | 1    | 2062.13014    |
| 16    | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc                       | 314653   | 5.00328  | 32      | wheel     | yes      | 8    | 1965.29202    |
| 17    | PrimeRust      | 1        | mike-barber_byte-storage                                          | 292035   | 5.00091  | 32      | base      | yes      | 8    | 1824.88756    |
| 18    | PrimeC         | 2        | danielspaangberg_480of2310_epar                                   | 285417   | 5.00113  | 32      | wheel     | yes      | 1    | 1783.45426    |
| 19    | PrimeRust      | 1        | mike-barber_bit-storage-striped                                   | 281636   | 5.00056  | 32      | base      | yes      | 1    | 1760.02946    |
| 20    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-gcc                            | 273677   | 5.00511  | 32      | base      | yes      | 8    | 1708.73492    |
| 21    | PrimeCPP       | 4        | BlackMark-1of2-bs-hs-vec<u8>-gcc                                  | 269876   | 5.01000  | 32      | base      | yes      | 8    | 1683.35828    |
| 22    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-gcc                      | 254695   | 5.01140  | 32      | base      | yes      | 1    | 1588.22260    |
| 23    | PrimeC         | 2        | danielspaangberg_48of210_epar                                     | 234820   | 5.00359  | 32      | wheel     | yes      | 1    | 1466.57347    |
| 24    | PrimeCPP       | 2        | davepl_par                                                        | 225940   | 5.00073  | 32      | base      | yes      | 1    | 1411.91886    |
| 25    | PrimeRust      | 1        | mike-barber_bit-storage-rotate                                    | 219335   | 5.00072  | 32      | base      | yes      | 1    | 1370.64559    |
| 26    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-sieve-u8                 | 212364   | 5.00068  | 32      | base      | yes      | 8    | 1327.09452    |
| 27    | PrimeGo        | 4        | kpym-go-multi                                                     | 25516    | 5.00008  | 4       | base      | yes      |      | 1275.77857    |
| 28    | PrimeC         | 2        | danielspaangberg_5760of30030_par                                  | 24893    | 5.00015  | 4       | wheel     | yes      | 1    | 1244.61241    |
| 29    | PrimeC         | 2        | danielspaangberg_480of2310_par                                    | 24725    | 5.00010  | 4       | wheel     | yes      | 1    | 1236.22478    |
| 30    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-clang                          | 195620   | 5.00656  | 32      | base      | yes      | 8    | 1221.02302    |
| 31    | PrimeC         | 2        | danielspaangberg_48of210_par                                      | 23612    | 5.00014  | 4       | wheel     | yes      | 1    | 1180.56647    |
| 32    | PrimeC         | 2        | danielspaangberg_1of2_epar                                        | 188322   | 5.00580  | 32      | base      | yes      | 1    | 1175.64898    |
| 33    | PrimeC         | 2        | danielspaangberg_8of30_par                                        | 22275    | 5.00011  | 4       | wheel     | yes      | 1    | 1113.72572    |
| 34    | PrimeC         | 2        | danielspaangberg_8of30_epar                                       | 176505   | 5.00164  | 32      | wheel     | yes      | 1    | 1102.79542    |
| 35    | PrimeRust      | 1        | mike-barber_bit-storage                                           | 168232   | 5.00091  | 32      | base      | yes      | 1    | 1051.25951    |
| 36    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8              | 164561   | 5.00017  | 32      | base      | yes      | 1    | 1028.47128    |
| 37    | PrimeOdin      | 1        | odin_bit_threaded_moe                                             | 162445   | 5.00200  | 32      | base      | yes      | 1    | 1014.87530    |
| 38    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64             | 158345   | 5.00021  | 32      | base      | yes      | 1    | 989.61469     |
| 39    | PrimeC         | 2        | danielspaangberg_1of2_par                                         | 18550    | 5.00002  | 4       | base      | yes      | 1    | 927.49610     |
| 40    | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-clang                     | 138319   | 5.00325  | 32      | wheel     | yes      | 8    | 863.93219     |
| 41    | PrimeKotlin    | 1        | jvm_kotlin_traditional_multi                                      | 123970   | 5.00000  | 32      | base      | yes      |      | 774.81250     |
| 42    | PrimeD         | 2        | BradleyChatha-Multi-SieveCT                                       | 121697   | 5.00118  | 32      | base      | no       | 1    | 760.42679     |
| 43    | PrimeKotlin    | 1        | jvm_kotlin_idiomatic_fast_multi                                   | 109537   | 5.00000  | 32      | base      | yes      |      | 684.60625     |
| 44    | PrimeNodeJS    | 1        | rogiervandam                                                      | 100758   | 5.09024  | 32      | base      | yes      | 1    | 618.57315     |
| 45    | PrimeKotlin    | 1        | jvm_kotlin_idiomatic_multi                                        | 75791    | 5.00000  | 32      | base      | yes      |      | 473.69375     |
| 46    | PrimeCPP       | 4        | BlackMark-1of2-bs-hs-vec<u8>-clang                                | 73992    | 5.00528  | 32      | base      | yes      | 8    | 461.96217     |
| 47    | PrimeJava      | 2        | PratimGhosh86-JavaBitSetMT                                        | 67593    | 5.00000  | 32      | base      | yes      | 1    | 422.45625     |
| 48    | PrimeDart      | 1        | eagerestwolf&mmcdon20_1bit_par                                    | 63403    | 5.00069  | 32      | base      | yes      | 1    | 396.21431     |
| 49    | PrimeD         | 2        | BradleyChatha-Multi-SieveRT                                       | 47489    | 5.00022  | 32      | base      | yes      | 1    | 296.79319     |
| 50    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-clang                    | 38827    | 5.00446  | 32      | base      | yes      | 1    | 242.45248     |
| 51    | PrimeDart      | 1        | eagerestwolf&mmcdon20_8bit_par                                    | 16547    | 5.00296  | 32      | base      | yes      | 8    | 103.35748     |
| 52    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-amdahl-sieve-u8                    | 10214    | 5.00040  | 32      | base      | yes      | 8    | 63.83239      |
| 53    | PrimeCSharp    | 1        | kinematics_rawp                                                   | 3420     | 5.00050  | 32      | base      | yes      | 1    | 21.37286      |
| 54    | PrimeCSharp    | 1        | kinematics_pool6p                                                 | 3279     | 5.00085  | 32      | wheel     | yes      | 1    | 20.49027      |
| 55    | PrimeIDL       | 1        | kriztioan_idlway                                                  | 532      | 5.00674  | 28      | base      | yes      | 8    | 3.79489       |
