# PrimesResult

The results of the [David Plummer's Primes Drag Race](https://github.com/PlummersSoftwareLLC/Primes).

## Results

Generated at 2021-07-29 on a Ryzen 9 5950X with 32GB RAM.

### Best faithful performers for each language

| Implementation | Slowness   | Position | Index | Solution | Label                                                | Passes | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| -------------- | ---------- | -------- | ----- | -------- | ---------------------------------------------------- | ------ | -------- | ------- | --------- | -------- | ---- | ------------- |
| Cython         | 1.0000     | 1        | 5     | 1        | ssovest-cy                                           | 38791  | 5.00001  | 1       | other     | yes      | 1    | 7758.18448    |
| C              | 1.0686     | 2        | 6     | 3        | fvbakel_Cwords                                       | 36302  | 5.00001  | 1       | other     | yes      | 1    | 7260.38548    |
| CPP            | 1.3112     | 3        | 7     | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-gcc        | 29584  | 5.00007  | 1       | wheel     | yes      | 1    | 5916.71717    |
| Zig            | 1.4690     | 4        | 12    | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030 | 26407  | 5.00018  | 1       | wheel     | yes      | 1    | 5281.20988    |
| Rust           | 1.5360     | 5        | 15    | 1        | mike-barber_bit-storage-striped-blocks               | 25255  | 5.00014  | 1       | base      | yes      | 1    | 5050.86272    |
| Fortran        | 1.9836     | 6        | 26    | 2        | tjol-8bit                                            | 19556  | 5.00012  | 1       | base      | yes      | 8    | 3911.10377    |
| V              | 2.3510     | 7        | 31    | 1        | marghidanu                                           | 16500  | 5.00000  | 1       | base      | yes      |      | 3300.00000    |
| Odin           | 2.7517     | 8        | 39    | 1        | odin_byte_moe                                        | 14097  | 5.00000  | 1       | base      | yes      | 8    | 2819.40000    |
| Go             | 2.7960     | 9        | 40    | 2        | ssovest-go-other                                     | 13876  | 5.00090  | 1       | other     | yes      | 1    | 2774.70015    |
| Assembly       | 2.8592     | 10       | 41    | 1        | rbergen_x64ff_byte                                   | 13567  | 5.00000  | 1       | base      | yes      | 8    | 2713.40000    |
| AssemblyScrip  | 2.8920     | 11       | 42    | 1        | donmahallem                                          | 13413  | 5.00000  | 1       | base      | yes      |      | 2682.60000    |
| Swift          | 3.0599     | 12       | 49    | 1        | yellowcub                                            | 12678  | 5.00031  | 1       | base      | yes      | 8    | 2535.44277    |
| FSharp         | 3.2655     | 13       | 53    | 2        | dmannock_fsharp_port                                 | 11880  | 5.00034  | 1       | base      | yes      |      | 2375.83892    |
| Crystal        | 3.3472     | 14       | 56    | 1        | marghidanu                                           | 11589  | 5.00004  | 1       | base      | yes      | 1    | 2317.78331    |
| Scala          | 3.6081     | 15       | 61    | 2        | scilari                                              | 10751  | 5.00000  | 1       | base      | yes      |      | 2150.20000    |
| NodeJS         | 3.6594     | 16       | 62    | 1        | rogiervandam_memcopy                                 | 10601  | 5.00032  | 1       | other     | yes      | 1    | 2120.06226    |
| Kotlin         | 3.7883     | 17       | 65    | 1        | jvm_kotlin_idiomatic_fast_single                     | 10254  | 5.00700  | 1       | base      | yes      |      | 2047.93289    |
| CSharp         | 3.7917     | 18       | 66    | 1        | kinematics_dbool                                     | 10231  | 5.00019  | 1       | base      | yes      | 8    | 2046.12225    |
| Java           | 4.1001     | 19       | 73    | 1        | MansenC                                              | 9461   | 5.00000  | 1       | base      | yes      |      | 1892.20000    |
| Julia          | 4.1665     | 20       | 75    | 3        | louie-github_port_1of2                               | 9311   | 5.00047  | 1       | base      | yes      | 1    | 1862.02571    |
| Dart           | 4.8460     | 21       | 85    | 1        | eagerestwolf&mmcdon20_8bit                           | 8005   | 5.00019  | 1       | base      | yes      | 8    | 1600.93820    |
| BASIC          | 6.1900     | 22       | 96    | 3        | Nukepayload2_ArrayPool8of30M                         | 6267   | 5.00021  | 1       | wheel     | yes      | 1    | 1253.34678    |
| TypeScript     | 7.4085     | 23       | 106   | 1        | marghidanu                                           | 5236   | 5.00000  | 1       | base      | yes      |      | 1047.20000    |
| Nim            | 13.292     | 24       | 115   | 2        | beef331                                              | 2919   | 5.00119  | 1       | base      | yes      | 1    | 583.66101     |
| D              | 13.353     | 25       | 116   | 1        | eagerestwolf                                         | 2905   | 5.00000  | 1       | base      | yes      | 8    | 581.00000     |
| Python         | 18.604     | 26       | 126   | 2        | ssovest                                              | 2086   | 5.00211  | 1       | base      | yes      | 8    | 417.02424     |
| Pascal         | 32.488     | 27       | 136   | 1        | rbergen                                              | 1194   | 5.00000  | 1       | base      | yes      |      | 238.80000     |
| Pony           | 36.219     | 28       | 138   | 1        | marghidanu                                           | 1071   | 5.00000  | 1       | base      | yes      | 1    | 214.20000     |
| R              | 39.341     | 29       | 140   | 1        | fvbakel_R                                            | 987    | 5.00500  | 1       | base      | yes      | 32   | 197.20280     |
| Haxe           | 54.247     | 30       | 142   | 1        | TayIorRobinson_Haxe_C++                              | 716    | 5.00641  | 1       | base      | yes      |      | 143.01657     |
| Scheme         | 62.294     | 31       | 144   | 1        | William103                                           | 623    | 5.00233  | 1       | base      | yes      | 1    | 124.54202     |
| Octave         | 65.539     | 32       | 145   | 2        | Brandon-Johns_8bit                                   | 592    | 5.00104  | 1       | base      | yes      | 8    | 118.37547     |
| PHP            | 70.409     | 33       | 146   | 1        | DennisdeBest                                         | 552    | 5.00967  | 1       | base      | yes      |      | 110.18685     |
| OCaml          | 70.588     | 34       | 147   | 1        | gkpotter-faithful                                    | 550    | 5.00421  | 1       | base      | yes      |      | 109.90737     |
| Perl           | 103.37     | 35       | 151   | 2        | kjetillll                                            | 376    | 5.00992  | 1       | base      | yes      |      | 75.05116      |
| StandardML     | 188.42     | 36       | 154   | 1        | NotMatthewGriffin_SMLofNJ                            | 206    | 5.00300  | 1       | base      | yes      | 1    | 41.17529      |
| GDScript       | 222.80     | 37       | 155   | 1        | OrigamiDev-Pete                                      | 177    | 5.08300  | 1       | base      | yes      | 8    | 34.82196      |
| Ballerina      | 242.44     | 38       | 156   | 1        | da-strange-boi                                       | 160    | 5.00000  | 1       | base      | yes      | 1    | 32.00000      |
| Ruby           | 257.36     | 39       | 157   | 1        | rbergen                                              | 151    | 5.00900  | 1       | base      | yes      |      | 30.14574      |
| Wren           | 322.61     | 40       | 158   | 1        | marghidanu                                           | 121    | 5.03161  | 1       | base      | yes      |      | 24.04797      |
| REXX           | 390.95     | 41       | 159   | 2        | joss_NetRexx                                         | 100    | 5.03925  | 1       | base      | yes      | 8    | 19.84422      |
| Kos            | 442.61     | 42       | 160   | 1        | cdragan                                              | 88     | 5.02050  | 1       | base      | yes      | 8    | 17.52813      |
| Elixir         | 689.75     | 43       | 163   | 2        | thomas9911                                           | 64     | 5.69000  | 1       | base      | yes      | 1    | 11.24780      |
| Smalltalk      | 724.67     | 44       | 165   | 1        | fvbakel_smalltalk                                    | 54     | 5.04400  | 1       | base      | yes      | 1    | 10.70579      |
| Tcl            | 875.47     | 45       | 166   | 2        | fvbakel_ootcl2                                       | 45     | 5.07800  | 1       | base      | yes      | 32   | 8.86176       |
| Emojicode      | 1337.6     | 46       | 169   | 1        | marghidanu                                           | 29     | 5.00000  | 1       | base      | yes      |      | 5.80000       |
| PowerShell     | 1390.2     | 47       | 171   | 2        | crowbar27_ps2                                        | 28     | 5.01739  | 1       | base      | yes      | 1    | 5.58059       |
| Raku           | 5249.5     | 48       | 175   | 1        | draco1006                                            | 8      | 5.41309  | 1       | base      | yes      |      | 1.47790       |
| Red            | 6089.5     | 49       | 177   | 1        | mmcdon20_red                                         | 7      | 5.49437  | 1       | base      | yes      | 1    | 1.27403       |
| IDL            | 1.2133e+04 | 50       | 182   | 1        | kriztioan_1bit                                       | 4      | 6.25578  | 1       | base      | yes      | 1    | 0.63941       |
| Prolog         | 5.1584e+04 | 51       | 187   | 1        | jimbxb-prolog-basic                                  | 1      | 6.64900  | 1       | base      | yes      | 1    | 0.15040       |

### Single-threaded

| Index | Implementation      | Solution | Label                                                 | Passes  | Duration  | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | ------------------- | -------- | ----------------------------------------------------- | ------- | --------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | PrimeCPP            | 4        | BlackMark-pregenerated-inv_bits<u32>-clang            | 2527236 | 5.00000   | 1       | base      | no       | 1    | 505447.20000  |
| 2     | PrimeCPP            | 4        | BlackMark-pregenerated-inv_bits<u32>-gcc              | 1224713 | 5.00000   | 1       | base      | no       | 1    | 244942.60000  |
| 3     | PrimeRust           | 6        | SycrationSinglethreaded                               | 276890  | 5.00001   | 1       | base      | no       |      | 55377.89416   |
| 4     | PrimeCPP            | 3        | flo80_constexpr                                       | 219458  | 5.00001   | 1       | base      | no       | 1    | 43891.52100   |
| 5     | PrimeCython         | 1        | ssovest-cy                                            | 38791   | 5.00001   | 1       | other     | yes      | 1    | 7758.18448    |
| 6     | PrimeC              | 3        | fvbakel_Cwords                                        | 36302   | 5.00001   | 1       | other     | yes      | 1    | 7260.38548    |
| 7     | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-gcc         | 29584   | 5.00007   | 1       | wheel     | yes      | 1    | 5916.71717    |
| 8     | PrimeMixed          | 1        | ssovest-cgo                                           | 29510   | 5.00082   | 1       | other     | no       | 1    | 5901.02897    |
| 9     | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc           | 29178   | 5.00005   | 1       | wheel     | yes      | 8    | 5835.54164    |
| 10    | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-clang       | 28247   | 5.00012   | 1       | wheel     | yes      | 1    | 5649.26442    |
| 11    | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-clang     | 28057   | 5.00001   | 1       | wheel     | yes      | 1    | 5611.38878    |
| 12    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-5760of30030  | 26407   | 5.00018   | 1       | wheel     | yes      | 1    | 5281.20988    |
| 13    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-5760of30030 | 26288   | 5.00017   | 1       | wheel     | yes      | 1    | 5257.42125    |
| 14    | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-gcc       | 25762   | 5.00012   | 1       | wheel     | yes      | 1    | 5152.27635    |
| 15    | PrimeRust           | 1        | mike-barber_bit-storage-striped-blocks                | 25255   | 5.00014   | 1       | base      | yes      | 1    | 5050.86272    |
| 16    | PrimeRust           | 1        | mike-barber_bit-storage-striped-blocks-small          | 24301   | 5.00021   | 1       | base      | yes      | 1    | 4859.99236    |
| 17    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8-480of2310    | 24195   | 5.00013   | 1       | wheel     | yes      | 1    | 4838.87419    |
| 18    | PrimeC              | 2        | danielspaangberg_48of210                              | 23719   | 5.00005   | 1       | wheel     | yes      | 1    | 4743.74782    |
| 19    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u64-480of2310   | 22664   | 5.00020   | 1       | wheel     | yes      | 1    | 4532.61870    |
| 20    | PrimeRust           | 1        | mike-barber_byte-storage                              | 22537   | 5.00022   | 1       | base      | yes      | 8    | 4507.19755    |
| 21    | PrimeRust           | 1        | mike-barber_bit-storage-striped                       | 21049   | 5.00010   | 1       | base      | yes      | 1    | 4209.71971    |
| 22    | PrimeC              | 2        | danielspaangberg_8of30                                | 20148   | 5.00007   | 1       | wheel     | yes      | 1    | 4029.54117    |
| 23    | PrimeCython         | 1        | rpkak+byte-array                                      | 19885   | 5.00021   | 1       | base      | yes      | 8    | 3976.83437    |
| 24    | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-clang              | 19790   | 5.00018   | 1       | base      | yes      | 8    | 3957.85752    |
| 25    | PrimeCPP            | 4        | BlackMark-1of2-bs-hs-vec<u8>-gcc                      | 19613   | 5.00005   | 1       | base      | yes      | 8    | 3922.56077    |
| 26    | PrimeFortran        | 2        | tjol-8bit                                             | 19556   | 5.00012   | 1       | base      | yes      | 8    | 3911.10377    |
| 27    | PrimeZig            | 2        | ManDeJan&ityonemo-zig-byte-sieve-type-bool            | 19541   | 5.00011   | 1       | base      | no       | 8    | 3908.11402    |
| 28    | PrimeAssembly       | 1        | rbergen_x64uff_byte                                   | 18625   | 5.00000   | 1       | base      | no       | 8    | 3725.00000    |
| 29    | PrimeC              | 2        | danielspaangberg_5760of30030_owrb                     | 17973   | 5.00012   | 1       | wheel     | yes      | 1    | 3594.51373    |
| 30    | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-gcc                | 17879   | 5.00012   | 1       | base      | yes      | 8    | 3575.71418    |
| 31    | PrimeV              | 1        | marghidanu                                            | 16500   | 5.00000   | 1       | base      | yes      |      | 3300.00000    |
| 32    | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-gcc          | 16429   | 5.00018   | 1       | base      | yes      | 1    | 3285.68172    |
| 33    | PrimeC              | 2        | danielspaangberg_480of2310_owrb                       | 15713   | 5.00005   | 1       | wheel     | yes      | 1    | 3142.56795    |
| 34    | PrimeZig            | 1        | devblok                                               | 15589   | 5.00021   | 1       | base      | yes      | 8    | 3117.66906    |
| 35    | PrimeHaskell        | 1        | fatho/vector_unchecked                                | 15391   | 5.00001   | 1       | base      | no       | 8    | 3078.19631    |
| 36    | PrimeAda            | 1        | BoopBeepBoopBeep                                      | 15048   | 5.00020   | 1       | base      | no       |      | 3009.48204    |
| 37    | PrimeCPP            | 1        | davepl_pol                                            | 14489   | 5.00007   | 1       | base      | yes      | 1    | 2897.75885    |
| 38    | PrimeRust           | 1        | mike-barber_bit-storage-rotate                        | 14354   | 5.00019   | 1       | base      | yes      | 1    | 2870.69077    |
| 39    | PrimeOdin           | 1        | odin_byte_moe                                         | 14097   | 5.00000   | 1       | base      | yes      | 8    | 2819.40000    |
| 40    | PrimeGo             | 2        | ssovest-go-other                                      | 13876   | 5.00090   | 1       | other     | yes      | 1    | 2774.70015    |
| 41    | PrimeAssembly       | 1        | rbergen_x64ff_byte                                    | 13567   | 5.00000   | 1       | base      | yes      | 8    | 2713.40000    |
| 42    | PrimeAssemblyScript | 1        | donmahallem                                           | 13413   | 5.00000   | 1       | base      | yes      |      | 2682.60000    |
| 43    | PrimeHaskell        | 1        | fatho/vector                                          | 13332   | 5.00019   | 1       | base      | no       | 8    | 2666.29868    |
| 44    | PrimeFortran        | 1        | johandweber_fortran                                   | 13147   | 5.00000   | 1       | base      | no       | 1    | 2629.40000    |
| 45    | PrimeGo             | 2        | ssovest-go-other-B                                    | 13095   | 5.00099   | 1       | other     | yes      | 1    | 2618.47941    |
| 46    | PrimeC              | 2        | danielspaangberg_48of210_owrb                         | 12895   | 5.00025   | 1       | wheel     | yes      | 1    | 2578.87157    |
| 47    | PrimeFortran        | 2        | tjol-logical                                          | 12849   | 5.00037   | 1       | base      | yes      |      | 2569.60812    |
| 48    | PrimeC              | 1        | mckoss-c830                                           | 12765   | 5.00000   | 1       | wheel     | yes      | 1    | 2553.00000    |
| 49    | PrimeSwift          | 1        | yellowcub                                             | 12678   | 5.00031   | 1       | base      | yes      | 8    | 2535.44277    |
| 50    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-bitSieve-u8              | 12374   | 5.00024   | 1       | base      | yes      | 1    | 2474.68122    |
| 51    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8                 | 12124   | 5.00020   | 1       | base      | yes      | 8    | 2424.70301    |
| 52    | PrimeFortran        | 2        | tjol-bits                                             | 12070   | 5.00025   | 1       | base      | yes      | 1    | 2413.87937    |
| 53    | PrimeFSharp         | 2        | dmannock_fsharp_port                                  | 11880   | 5.00034   | 1       | base      | yes      |      | 2375.83892    |
| 54    | PrimeZig            | 2        | ManDeJan&ityonemo-zig-bit-sieve                       | 11698   | 5.00018   | 1       | base      | no       | 1    | 2339.51578    |
| 55    | PrimeC              | 2        | danielspaangberg_1of2                                 | 11648   | 5.00035   | 1       | base      | yes      | 1    | 2329.43601    |
| 56    | PrimeCrystal        | 1        | marghidanu                                            | 11589   | 5.00004   | 1       | base      | yes      | 1    | 2317.78331    |
| 57    | PrimeD              | 2        | BradleyChatha-Single-SieveCT                          | 11529   | 5.00001   | 1       | base      | no       | 1    | 2305.79539    |
| 58    | PrimeHaskell        | 1        | fatho/bitset                                          | 11318   | 5.00008   | 1       | base      | no       | 1    | 2263.56424    |
| 59    | PrimeFSharp         | 3        | dmannock_fsharp_recursion                             | 11249   | 5.00002   | 1       | base      | yes      |      | 2249.79325    |
| 60    | PrimeRust           | 1        | mike-barber_bit-storage                               | 10987   | 5.00022   | 1       | base      | yes      | 1    | 2197.30172    |
| 61    | PrimeScala          | 2        | scilari                                               | 10751   | 5.00000   | 1       | base      | yes      |      | 2150.20000    |
| 62    | PrimeNodeJS         | 1        | rogiervandam_memcopy                                  | 10601   | 5.00032   | 1       | other     | yes      | 1    | 2120.06226    |
| 63    | PrimeCython         | 1        | rpkak+bit-array                                       | 10308   | 5.00047   | 1       | base      | yes      | 1    | 2061.40597    |
| 64    | PrimeRust           | 2        | Azgrom                                                | 10297   | 5.00047   | 1       | base      | yes      |      | 2059.20767    |
| 65    | PrimeKotlin         | 1        | jvm_kotlin_idiomatic_fast_single                      | 10254   | 5.00700   | 1       | base      | yes      |      | 2047.93289    |
| 66    | PrimeCSharp         | 1        | kinematics_dbool                                      | 10231   | 5.00019   | 1       | base      | yes      | 8    | 2046.12225    |
| 67    | PrimeOdin           | 1        | odin_bit_moe                                          | 10189   | 5.00000   | 1       | base      | yes      | 1    | 2037.80000    |
| 68    | PrimeC              | 2        | danielspaangberg_8of30_owrb                           | 10006   | 5.00024   | 1       | wheel     | yes      | 1    | 2001.10395    |
| 69    | PrimeCSharp         | 1        | kinematics_ibool                                      | 9917    | 5.00025   | 1       | base      | yes      | 8    | 1983.30083    |
| 70    | PrimeKotlin         | 1        | jvm_kotlin_traditional_single                         | 9851    | 5.01600   | 1       | base      | yes      |      | 1963.91547    |
| 71    | PrimeKotlin         | 1        | jvm_kotlin_idiomatic_single                           | 9672    | 5.00300   | 1       | base      | yes      |      | 1933.24006    |
| 72    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-bool               | 9571    | 5.00040   | 1       | base      | yes      | 8    | 1914.04688    |
| 73    | PrimeJava           | 1        | MansenC                                               | 9461    | 5.00000   | 1       | base      | yes      |      | 1892.20000    |
| 74    | PrimeHaskell        | 1        | fatho/bitset_unchecked                                | 9342    | 5.00020   | 1       | base      | no       | 1    | 1868.32527    |
| 75    | PrimeJulia          | 3        | louie-github_port_1of2                                | 9311    | 5.00047   | 1       | base      | yes      | 1    | 1862.02571    |
| 76    | PrimePython         | 3        | emillynge_numpy                                       | 9169    | 5.00033   | 1       | base      | no       | 8    | 1833.67814    |
| 77    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-5760of30030     | 9035    | 5.00051   | 1       | wheel     | yes      | 8    | 1806.81570    |
| 78    | PrimeZig            | 3        | ManDeJan&ityonemo-zig-single-sieve-u8-480of2310       | 8664    | 5.00029   | 1       | wheel     | yes      | 8    | 1732.69950    |
| 79    | PrimeRust           | 4        | joshallen64                                           | 8567    | 5.00055   | 1       | base      | yes      |      | 1713.21223    |
| 80    | PrimeLua            | 2        | ben1jen_luajit1                                       | 8360    | 5.00000   | 1       | base      | no       | 1    | 1672.00000    |
| 81    | PrimeJulia          | 1        | dcbi                                                  | 8347    | 5.00016   | 1       | base      | yes      | 1    | 1669.34619    |
| 82    | PrimeAssembly       | 1        | rbergen_x64uff_bitshift                               | 8109    | 5.00000   | 1       | base      | no       | 1    | 1621.80000    |
| 83    | PrimeJulia          | 2        | epithet-jl                                            | 8052    | 5.00015   | 1       | base      | yes      | 1    | 1610.35040    |
| 84    | PrimeAssembly       | 1        | rbergen_x64ff_bitshift                                | 8014    | 5.00000   | 1       | base      | yes      | 1    | 1602.80000    |
| 85    | PrimeDart           | 1        | eagerestwolf&mmcdon20_8bit                            | 8005    | 5.00019   | 1       | base      | yes      | 8    | 1600.93820    |
| 86    | PrimeCSharp         | 3        | tannergooding                                         | 7954    | 5.00059   | 1       | base      | yes      | 1    | 1590.61368    |
| 87    | PrimeAssembly       | 1        | rbergen_x64uff_bitbtr                                 | 7601    | 5.00000   | 1       | base      | no       | 1    | 1520.20000    |
| 88    | PrimeCSharp         | 1        | kinematics_raw32                                      | 7489    | 5.00003   | 1       | base      | yes      | 1    | 1497.79101    |
| 89    | PrimeAssembly       | 1        | rbergen_x64ff_bitbtr                                  | 7442    | 5.00000   | 1       | base      | yes      | 1    | 1488.40000    |
| 90    | PrimeCSharp         | 1        | kinematics_rawd                                       | 7088    | 5.00067   | 1       | base      | yes      | 1    | 1417.41007    |
| 91    | PrimeCSharp         | 1        | kinematics_raw                                        | 7037    | 5.00038   | 1       | base      | yes      | 1    | 1407.29305    |
| 92    | PrimeScala          | 1        | rom1dep                                               | 7001    | 5.00000   | 1       | base      | yes      |      | 1400.20000    |
| 93    | PrimeCSharp         | 1        | kinematics_bool                                       | 6877    | 5.00034   | 1       | base      | yes      | 8    | 1375.30648    |
| 94    | PrimeCSharp         | 1        | kinematics_raw6                                       | 6819    | 5.00059   | 1       | wheel     | yes      | 1    | 1363.63909    |
| 95    | PrimeNodeJS         | 1        | rogiervandam                                          | 6572    | 5.00007   | 1       | base      | yes      | 1    | 1314.38099    |
| 96    | PrimeBASIC          | 3        | Nukepayload2_ArrayPool8of30M                          | 6267    | 5.00021   | 1       | wheel     | yes      | 1    | 1253.34678    |
| 97    | PrimeGo             | 2        | ssovest-go-uint32                                     | 6223    | 5.00123   | 1       | base      | yes      | 1    | 1244.29413    |
| 98    | PrimeCSharp         | 1        | kinematics_pool30                                     | 6159    | 5.00052   | 1       | wheel     | yes      | 1    | 1231.67191    |
| 99    | PrimeBASIC          | 3        | Nukepayload2_ReDim8of30M                              | 6132    | 5.00073   | 1       | wheel     | yes      | 1    | 1226.22215    |
| 100   | PrimeCPP            | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-clang         | 5997    | 5.00004   | 1       | wheel     | yes      | 8    | 1199.39040    |
| 101   | PrimeGo             | 2        | ssovest-go-uint8-B                                    | 5886    | 5.00152   | 1       | base      | yes      | 1    | 1176.84229    |
| 102   | PrimeCSharp         | 1        | kinematics_pool30m                                    | 5761    | 5.00084   | 1       | wheel     | yes      | 1    | 1152.00646    |
| 103   | PrimeGo             | 2        | ssovest-go-ptr                                        | 5581    | 5.00151   | 1       | base      | yes      | 1    | 1115.86380    |
| 104   | PrimeGo             | 2        | ssovest-go-uint32-B                                   | 5515    | 5.00046   | 1       | base      | yes      | 1    | 1102.89945    |
| 105   | PrimeGo             | 2        | ssovest-go-uint8                                      | 5244    | 5.00135   | 1       | base      | yes      | 1    | 1048.51606    |
| 106   | PrimeTypeScript     | 1        | marghidanu                                            | 5236    | 5.00000   | 1       | base      | yes      |      | 1047.20000    |
| 107   | PrimeGo             | 2        | ssovest-go-ptr-B                                      | 5232    | 5.00147   | 1       | base      | yes      | 1    | 1046.09190    |
| 108   | PrimeCSharp         | 1        | kinematics_pool2of6                                   | 5120    | 5.00061   | 1       | wheel     | yes      | 1    | 1023.87509    |
| 109   | PrimeDart           | 1        | eagerestwolf&mmcdon20_1bit                            | 4629    | 5.00086   | 1       | base      | yes      | 1    | 925.64060     |
| 110   | PrimeJava           | 2        | PratimGhosh86-JavaBitSet                              | 4354    | 5.00000   | 1       | base      | yes      | 1    | 870.80000     |
| 111   | PrimeRust           | 3        | Blui42                                                | 4003    | 5.00007   | 1       | base      | yes      |      | 800.58875     |
| 112   | PrimeJava           | 3        | MansenC-native                                        | 3977    | 5.00100   | 1       | base      | yes      |      | 795.24095     |
| 113   | PrimeKotlin         | 1        | native_kotlin_idiomatic_fast_single                   | 3775    | 5.00100   | 1       | base      | yes      |      | 754.84903     |
| 114   | PrimeCPP            | 4        | BlackMark-1of2-bs-hs-vec<u8>-clang                    | 3031    | 5.00128   | 1       | base      | yes      | 8    | 606.04485     |
| 115   | PrimeNim            | 2        | beef331                                               | 2919    | 5.00119   | 1       | base      | yes      | 1    | 583.66101     |
| 116   | PrimeD              | 1        | eagerestwolf                                          | 2905    | 5.00000   | 1       | base      | yes      | 8    | 581.00000     |
| 117   | PrimeNim            | 1        | marghidanu                                            | 2857    | 5.00094   | 1       | base      | yes      | 8    | 571.29316     |
| 118   | PrimeD              | 2        | BradleyChatha-Single-SieveRT                          | 2843    | 5.00082   | 1       | base      | yes      | 1    | 568.50676     |
| 119   | PrimeCSharp         | 1        | kinematics_pool                                       | 2723    | 5.00036   | 1       | base      | yes      | 1    | 544.56079     |
| 120   | PrimeCSharp         | 1        | kinematics_standard                                   | 2653    | 5.00186   | 1       | base      | yes      | 1    | 530.40269     |
| 121   | PrimeCSharp         | 2        | davepl                                                | 2535    | 5.00169   | 1       | base      | yes      | 1    | 506.82869     |
| 122   | PrimeCSharp         | 1        | kinematics_original                                   | 2499    | 5.00087   | 1       | base      | yes      | 1    | 499.71305     |
| 123   | PrimeBASIC          | 1        | rbergen_8of30                                         | 2404    | 5.00200   | 1       | wheel     | yes      | 1    | 480.60776     |
| 124   | PrimeKotlin         | 1        | native_kotlin_idiomatic_single                        | 2355    | 5.00000   | 1       | base      | yes      |      | 471.00000     |
| 125   | PrimeOctave         | 1        | octave                                                | 2172    | 5.00017   | 1       | base      | no       |      | 434.38523     |
| 126   | PrimePython         | 2        | ssovest                                               | 2086    | 5.00211   | 1       | base      | yes      | 8    | 417.02424     |
| 127   | PrimeKotlin         | 1        | js_kotlin_idiomatic_fast_single                       | 1966    | 5.00300   | 1       | base      | yes      |      | 392.96422     |
| 128   | PrimeKotlin         | 1        | js_kotlin_idiomatic_single                            | 1945    | 5.00300   | 1       | base      | yes      |      | 388.76674     |
| 129   | PrimeKotlin         | 1        | js_kotlin_traditional_single                          | 1897    | 5.01200   | 1       | base      | yes      |      | 378.49162     |
| 130   | PrimeFSharp         | 1        | rbergen                                               | 1813    | 5.00147   | 1       | base      | yes      | 1    | 362.49341     |
| 131   | PrimeCPP            | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-clang        | 1747    | 5.00099   | 1       | base      | yes      | 1    | 349.33083     |
| 132   | PrimeKotlin         | 1        | native_kotlin_traditional_single                      | 1669    | 5.00200   | 1       | base      | yes      |      | 333.66653     |
| 133   | PrimeBASIC          | 2        | rbergen_vb                                            | 1607    | 5.00130   | 1       | base      | yes      | 1    | 321.31650     |
| 134   | PrimeGo             | 1        | bundgaard                                             | 1444    | 5.00222   | 1       | base      | yes      |      | 288.67195     |
| 135   | PrimeCOBOL          | 1        | fvbakel_Cobol                                         | 1259    | 5.00000   | 1       | base      | no       | 8    | 251.80000     |
| 136   | PrimePascal         | 1        | rbergen                                               | 1194    | 5.00000   | 1       | base      | yes      |      | 238.80000     |
| 137   | PrimePascal         | 2        | circular17                                            | 1158    | 5.00000   | 1       | base      | yes      | 1    | 231.60000     |
| 138   | PrimePony           | 1        | marghidanu                                            | 1071    | 5.00000   | 1       | base      | yes      | 1    | 214.20000     |
| 139   | PrimeR              | 2        | nobrien97                                             | 1061    | 5.00100   | 1       | base      | no       | 32   | 212.15757     |
| 140   | PrimeR              | 1        | fvbakel_R                                             | 987     | 5.00500   | 1       | base      | yes      | 32   | 197.20280     |
| 141   | PrimeBASIC          | 1        | rbergen_boolean                                       | 718     | 5.00300   | 1       | base      | yes      |      | 143.51389     |
| 142   | PrimeHaxe           | 1        | TayIorRobinson_Haxe_C++                               | 716     | 5.00641   | 1       | base      | yes      |      | 143.01657     |
| 143   | PrimeOCaml          | 2        | gkpotter-unfaithful                                   | 696     | 5.00618   | 1       | base      | no       |      | 139.02811     |
| 144   | PrimeScheme         | 1        | William103                                            | 623     | 5.00233   | 1       | base      | yes      | 1    | 124.54202     |
| 145   | PrimeOctave         | 2        | Brandon-Johns_8bit                                    | 592     | 5.00104   | 1       | base      | yes      | 8    | 118.37547     |
| 146   | PrimePHP            | 1        | DennisdeBest                                          | 552     | 5.00967   | 1       | base      | yes      |      | 110.18685     |
| 147   | PrimeOCaml          | 1        | gkpotter-faithful                                     | 550     | 5.00421   | 1       | base      | yes      |      | 109.90737     |
| 148   | PrimeForth          | 1        | tjol-8bit                                             | 488     | 5.00528   | 1       | base      | no       | 8    | 97.49697      |
| 149   | PrimeBASIC          | 1        | rbergen_bit32                                         | 477     | 5.00500   | 1       | base      | yes      | 1    | 95.30470      |
| 150   | PrimeBASIC          | 1        | rbergen_bit64                                         | 465     | 5.01000   | 1       | base      | yes      | 1    | 92.81437      |
| 151   | PrimePerl           | 2        | kjetillll                                             | 376     | 5.00992   | 1       | base      | yes      |      | 75.05116      |
| 152   | PrimeForth          | 1        | tjol-1bit                                             | 337     | 5.00586   | 1       | base      | no       | 1    | 67.32106      |
| 153   | PrimePostScript     | 1        | epithet-ps                                            | 249     | 5.01900   | 1       | base      | no       | 8    | 49.61148      |
| 154   | PrimeStandardML     | 1        | NotMatthewGriffin_SMLofNJ                             | 206     | 5.00300   | 1       | base      | yes      | 1    | 41.17529      |
| 155   | PrimeGDScript       | 1        | OrigamiDev-Pete                                       | 177     | 5.08300   | 1       | base      | yes      | 8    | 34.82196      |
| 156   | PrimeBallerina      | 1        | da-strange-boi                                        | 160     | 5.00000   | 1       | base      | yes      | 1    | 32.00000      |
| 157   | PrimeRuby           | 1        | rbergen                                               | 151     | 5.00900   | 1       | base      | yes      |      | 30.14574      |
| 158   | PrimeWren           | 1        | marghidanu                                            | 121     | 5.03161   | 1       | base      | yes      |      | 24.04797      |
| 159   | PrimeREXX           | 2        | joss_NetRexx                                          | 100     | 5.03925   | 1       | base      | yes      | 8    | 19.84422      |
| 160   | PrimeKos            | 1        | cdragan                                               | 88      | 5.02050   | 1       | base      | yes      | 8    | 17.52813      |
| 161   | PrimePerl           | 1        | marghidanu                                            | 58      | 5.04722   | 1       | base      | yes      |      | 11.49147      |
| 162   | PrimeProlog         | 1        | jimbxb-prolog-c                                       | 57      | 5.04100   | 1       | base      | no       | 1    | 11.30728      |
| 163   | PrimeElixir         | 2        | thomas9911                                            | 64      | 5.69000   | 1       | base      | yes      | 1    | 11.24780      |
| 164   | PrimeLisp           | 1        | mikehw                                                | 111     | 10.05001  | 1       | base      | no       | 1    | 11.04477      |
| 165   | PrimeSmalltalk      | 1        | fvbakel_smalltalk                                     | 54      | 5.04400   | 1       | base      | yes      | 1    | 10.70579      |
| 166   | PrimeTcl            | 2        | fvbakel_ootcl2                                        | 45      | 5.07800   | 1       | base      | yes      | 32   | 8.86176       |
| 167   | PrimeMIXAL          | 1        | rbergen                                               | 30      | 3.57000   | 1       | base      | no       | 1    | 8.40336       |
| 168   | PrimeHaxe           | 1        | TayIorRobinson_Haxe_HaxeEval                          | 30      | 5.10854   | 1       | base      | yes      |      | 5.87252       |
| 169   | PrimeEmojicode      | 1        | marghidanu                                            | 29      | 5.00000   | 1       | base      | yes      |      | 5.80000       |
| 170   | PrimeREXX           | 1        | joss_REXX                                             | 29      | 5.01151   | 1       | base      | no       | 8    | 5.78668       |
| 171   | PrimePowerShell     | 2        | crowbar27_ps2                                         | 28      | 5.01739   | 1       | base      | yes      | 1    | 5.58059       |
| 172   | PrimePython         | 1        | davepl                                                | 25      | 5.17420   | 1       | base      | yes      |      | 4.83167       |
| 173   | PrimeSQL            | 2        | fvbakel_MariaDB3                                      | 9       | 5.46900   | 1       | other     | no       | 32   | 1.64564       |
| 174   | PrimeTcl            | 1        | fvbakeltcl                                            | 8       | 5.22900   | 1       | base      | yes      | 1    | 1.52993       |
| 175   | PrimeRaku           | 1        | draco1006                                             | 8       | 5.41309   | 1       | base      | yes      |      | 1.47790       |
| 176   | PrimeSQL            | 1        | fvbakel_sqlite                                        | 7       | 5.14096   | 1       | other     | no       | 8    | 1.36161       |
| 177   | PrimeRed            | 1        | mmcdon20_red                                          | 7       | 5.49437   | 1       | base      | yes      | 1    | 1.27403       |
| 178   | PrimeHaxe           | 1        | TayIorRobinson_Haxe_Python                            | 7       | 5.58547   | 1       | base      | yes      |      | 1.25325       |
| 179   | PrimeTcl            | 2        | fvbakel_ootcl                                         | 7       | 5.78300   | 1       | base      | yes      | 1    | 1.21044       |
| 180   | PrimeSQL            | 2        | fvbakel_MariaDB2                                      | 6       | 5.46800   | 1       | other     | no       | 32   | 1.09729       |
| 181   | PrimeProlog         | 1        | jimbxb-prolog-dynamic                                 | 5       | 5.22800   | 1       | base      | no       |      | 0.95639       |
| 182   | PrimeIDL            | 1        | kriztioan_1bit                                        | 4       | 6.25578   | 1       | base      | yes      | 1    | 0.63941       |
| 183   | PrimeBash           | 1        | bash_inline                                           | 3       | 6.48828   | 1       | base      | no       |      | 0.46237       |
| 184   | PrimeBash           | 1        | bash                                                  | 2       | 7.68162   | 1       | base      | no       |      | 0.26036       |
| 185   | PrimeSQL            | 2        | fvbakel_MariaDB1                                      | 1       | 5.67700   | 1       | base      | no       | 32   | 0.17615       |
| 186   | PrimeLaTeX          | 1        | tjol                                                  | 2       | 13.02654  | 1       | base      | no       | 32   | 0.15353       |
| 187   | PrimeProlog         | 1        | jimbxb-prolog-basic                                   | 1       | 6.64900   | 1       | base      | yes      | 1    | 0.15040       |
| 188   | PrimeBash           | 1        | bash_packed                                           | 1       | 7.28378   | 1       | base      | no       |      | 0.13729       |
| 189   | PrimeElixir         | 1        | cdesch                                                | 1       | 21.48500  | 1       | base      | no       |      | 0.04654       |
| 190   | PrimeLua            | 1        | lua                                                   | 1       | 26.00000  | 1       | base      | no       | 64   | 0.03846       |
| 191   | PrimePowerShell     | 1        | crowbar27_ps1                                         | 1       | 52.29710  | 1       | base      | yes      | 1    | 0.01912       |
| 192   | PrimeOctave         | 2        | Brandon-Johns_1bit                                    | 1       | 130.59115 | 1       | base      | yes      | 1    | 0.00766       |

### Multi-threaded

| Index | Implementation | Solution | Label                                                             | Passes   | Duration | Threads | Algorithm | Faithful | Bits | Passes/Second |
| ----- | -------------- | -------- | ----------------------------------------------------------------- | -------- | -------- | ------- | --------- | -------- | ---- | ------------- |
| 1     | PrimeCPP       | 4        | BlackMark-pregenerated-inv_bits<u32>-clang                        | 32684290 | 5.01323  | 32      | base      | no       | 1    | 203737.72249  |
| 2     | PrimeCPP       | 4        | BlackMark-pregenerated-inv_bits<u32>-gcc                          | 13842329 | 5.00207  | 32      | base      | no       | 1    | 86478.75405   |
| 3     | PrimeRust      | 6        | SycrationMultithreaded                                            | 1964518  | 5.00002  | 8       | base      | no       |      | 49112.75952   |
| 4     | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-gcc                     | 460536   | 5.00105  | 32      | wheel     | yes      | 1    | 2877.74567    |
| 5     | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-gcc                   | 433663   | 5.00381  | 32      | wheel     | yes      | 1    | 2708.33000    |
| 6     | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-5760of30030  | 374572   | 5.00030  | 32      | wheel     | yes      | 1    | 2340.93454    |
| 7     | PrimeCPP       | 3        | flo80_constexpr                                                   | 357024   | 5.00028  | 32      | base      | no       | 1    | 2231.27326    |
| 8     | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_bits<u32>-clang                   | 352089   | 5.00426  | 32      | wheel     | yes      | 1    | 2198.68297    |
| 9     | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8-480of2310    | 349909   | 5.00026  | 32      | wheel     | yes      | 1    | 2186.81754    |
| 10    | PrimeRust      | 1        | mike-barber_bit-storage-striped-blocks-small                      | 333519   | 5.00054  | 32      | base      | yes      | 1    | 2084.27013    |
| 11    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-480of2310   | 332242   | 5.00039  | 32      | wheel     | yes      | 1    | 2076.35054    |
| 12    | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-maskedbits<u32>-clang                 | 331476   | 5.00276  | 32      | wheel     | yes      | 1    | 2070.58204    |
| 13    | PrimeC         | 2        | danielspaangberg_5760of30030_epar                                 | 328962   | 5.00172  | 32      | wheel     | yes      | 1    | 2055.30547    |
| 14    | PrimeRust      | 1        | mike-barber_bit-storage-striped-blocks                            | 325172   | 5.00055  | 32      | base      | yes      | 1    | 2032.10175    |
| 15    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64-5760of30030 | 315599   | 5.00006  | 32      | wheel     | yes      | 1    | 1972.47008    |
| 16    | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-gcc                       | 313982   | 5.00235  | 32      | wheel     | yes      | 8    | 1961.46561    |
| 17    | PrimeRust      | 1        | mike-barber_byte-storage                                          | 287039   | 5.00059  | 32      | base      | yes      | 8    | 1793.78265    |
| 18    | PrimeC         | 2        | danielspaangberg_480of2310_epar                                   | 279167   | 5.01477  | 32      | wheel     | yes      | 1    | 1739.65412    |
| 19    | PrimeRust      | 1        | mike-barber_bit-storage-striped                                   | 277898   | 5.00061  | 32      | base      | yes      | 1    | 1736.65233    |
| 20    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-gcc                            | 263822   | 5.00446  | 32      | base      | yes      | 8    | 1647.41800    |
| 21    | PrimeCPP       | 4        | BlackMark-1of2-bs-hs-vec<u8>-gcc                                  | 260192   | 5.00221  | 32      | base      | yes      | 8    | 1625.48154    |
| 22    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-gcc                      | 249062   | 5.00123  | 32      | base      | yes      | 1    | 1556.25466    |
| 23    | PrimeGo        | 4        | kpym-go-multi                                                     | 30094    | 5.00009  | 4       | base      | yes      |      | 1504.67322    |
| 24    | PrimeC         | 2        | danielspaangberg_48of210_epar                                     | 229467   | 5.00653  | 32      | wheel     | yes      | 1    | 1432.29788    |
| 25    | PrimeCPP       | 2        | davepl_par                                                        | 221937   | 5.00081  | 32      | base      | yes      | 1    | 1386.88158    |
| 26    | PrimeRust      | 1        | mike-barber_bit-storage-rotate                                    | 216360   | 5.00080  | 32      | base      | yes      | 1    | 1352.03364    |
| 27    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_arr<bool>-clang                          | 206902   | 5.02411  | 32      | base      | yes      | 8    | 1286.93191    |
| 28    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-sieve-u8                 | 205282   | 5.00086  | 32      | base      | yes      | 8    | 1282.79186    |
| 29    | PrimeC         | 2        | danielspaangberg_5760of30030_par                                  | 25051    | 5.00010  | 4       | wheel     | yes      | 1    | 1252.52520    |
| 30    | PrimeC         | 2        | danielspaangberg_480of2310_par                                    | 24374    | 5.00013  | 4       | wheel     | yes      | 1    | 1218.66783    |
| 31    | PrimeC         | 2        | danielspaangberg_48of210_par                                      | 23314    | 5.00012  | 4       | wheel     | yes      | 1    | 1165.67202    |
| 32    | PrimeC         | 2        | danielspaangberg_1of2_epar                                        | 184877   | 5.00614  | 32      | base      | yes      | 1    | 1154.06314    |
| 33    | PrimeC         | 2        | danielspaangberg_8of30_par                                        | 22359    | 5.00012  | 4       | wheel     | yes      | 1    | 1117.92295    |
| 34    | PrimeC         | 2        | danielspaangberg_8of30_epar                                       | 172719   | 5.01059  | 32      | wheel     | yes      | 1    | 1077.21178    |
| 35    | PrimeRust      | 1        | mike-barber_bit-storage                                           | 166128   | 5.00100  | 32      | base      | yes      | 1    | 1038.09141    |
| 36    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u8              | 162285   | 5.00011  | 32      | base      | yes      | 1    | 1014.25894    |
| 37    | PrimeOdin      | 1        | odin_bit_threaded_moe                                             | 158055   | 5.02100  | 32      | base      | yes      | 1    | 983.71216     |
| 38    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-gustafson-bitSieve-u64             | 156288   | 5.00017  | 32      | base      | yes      | 1    | 976.76679     |
| 39    | PrimeOdin      | 1        | odin_byte_threaded_moe                                            | 150543   | 5.00200  | 32      | base      | yes      | 8    | 940.51754     |
| 40    | PrimeC         | 2        | danielspaangberg_1of2_par                                         | 18452    | 5.00024  | 4       | base      | yes      | 1    | 922.55627     |
| 41    | PrimeCPP       | 4        | BlackMark-5760of30030-os-hs-inv_vec<u8>-clang                     | 132622   | 5.00730  | 32      | wheel     | yes      | 8    | 827.67909     |
| 42    | PrimeKotlin    | 1        | jvm_kotlin_traditional_multi                                      | 120134   | 5.00000  | 32      | base      | yes      |      | 750.83750     |
| 43    | PrimeKotlin    | 1        | jvm_kotlin_idiomatic_multi                                        | 110881   | 5.00000  | 32      | base      | yes      |      | 693.00625     |
| 44    | PrimeKotlin    | 1        | jvm_kotlin_idiomatic_fast_multi                                   | 108426   | 5.00000  | 32      | base      | yes      |      | 677.66250     |
| 45    | PrimeD         | 2        | BradleyChatha-Multi-SieveCT                                       | 104449   | 5.00059  | 32      | base      | no       | 1    | 652.72923     |
| 46    | PrimeNodeJS    | 1        | rogiervandam                                                      | 99435    | 5.10357  | 32      | base      | yes      | 1    | 608.85722     |
| 47    | PrimeCPP       | 4        | BlackMark-1of2-bs-hs-vec<u8>-clang                                | 71575    | 5.00638  | 32      | base      | yes      | 8    | 446.77367     |
| 48    | PrimeJava      | 2        | PratimGhosh86-JavaBitSetMT                                        | 66718    | 5.00000  | 32      | base      | yes      | 1    | 416.98750     |
| 49    | PrimeDart      | 1        | eagerestwolf&mmcdon20_1bit_par                                    | 62050    | 5.00333  | 32      | base      | yes      | 1    | 387.55439     |
| 50    | PrimeD         | 2        | BradleyChatha-Multi-SieveRT                                       | 41473    | 5.00311  | 32      | base      | yes      | 1    | 259.04512     |
| 51    | PrimeCPP       | 4        | BlackMark-1of2-cs-hs-inv_stridedbits<u8>-clang                    | 37861    | 5.00576  | 32      | base      | yes      | 1    | 236.35896     |
| 52    | PrimeDart      | 1        | eagerestwolf&mmcdon20_8bit_par                                    | 16514    | 5.00163  | 32      | base      | yes      | 8    | 103.17878     |
| 53    | PrimeZig       | 3        | ManDeJan&ityonemo-zig-parallel-amdahl-sieve-u8                    | 10196    | 5.00008  | 32      | base      | yes      | 8    | 63.72398      |
| 54    | PrimeCSharp    | 1        | kinematics_rawp                                                   | 3445     | 5.00013  | 32      | base      | yes      | 1    | 21.53069      |
| 55    | PrimeCSharp    | 1        | kinematics_pool6p                                                 | 3349     | 5.00039  | 32      | wheel     | yes      | 1    | 20.92962      |
| 56    | PrimeIDL       | 1        | kriztioan_idlway                                                  | 517      | 5.00422  | 28      | base      | yes      | 8    | 3.68974       |
