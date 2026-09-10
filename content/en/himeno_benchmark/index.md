---
title: Himeno Benchmark
showReadingTime: false
showPagination: false
showDate: false
authors:
  - himeno
---
## Introduction to Himeno Benchmark
Prof. Ryutaro Himeno, former Director of the Advanced Center for Computing and Communication of RIKEN, has developed this benchmark to evaluate performance of incompressible fluid analysis code. This benchmark program takes measurements to proceed major loops in solving the Poisson’s equation solution using the Jacobi iteration method.

Being the code very simple and easy to compile and to execute, users can measure actual speed (in MFLOPS) immediately.
 
We have upgraded the source code from “Himeno benchmark 98” to “himenoBMTxp” with the aim to decrease the difference of calculation time between computers that occurs due to the difference of their performances. As for Fortran versions, results obtained with the previous version can be compared with the one obtained with this version, because we didn’t change the kernel of the code from the old version. But, as for C versions, please be careful that we have changed a method to declare an array. We did so to maintain consistency with that of the Fortran versions. (December, 2001).

The Himeno Benchmark is made available under the LGPL2.0 or later.

## Download
More information can be found [here](https://i.riken.jp/en/supercom/documents/himenobmt/).

You can also download source code [here](https://i.riken.jp/en/supercom/documents/himenobmt/download/).

If you have any questions for need for further assistance, please feel free to contact us.

### Source code & Executables(Win/Mac)
#### FORTRAN77
|Size|FORTRAN77|
|---|---|
|XL *(1024 x 512 x 512)*|[himenobmtxp_xl.f](win-mac/himenobmtxp_xl.zip)|
|L *(512 x 256 x 256)*|[himenobmtxp_l.f](win-mac/himenobmtxp_l.zip)|
|M *(256 x 128 x 128)*|[himenobmtxp_m.f](win-mac/himenobmtxp_m.zip)|
|S *(128 x 64 x 64)*|[himenobmtxp_s.f](win-mac/himenobmtxp_s.zip)|

#### FORTRAN90
|Size|FORTRAN90|
|---|---|
|All Size|[himenobmtxp.f90](win-mac/f90_xp.zip)|

#### C(Static Allocation Version)
|Size|C *(SA version)*|
|---|---|
|XL *(1024 x 512 x 512)*|[cc_himenobmtxp_xl.lzh](win-mac/cc_himenobmtxp_xl.zip)|
|L *(512 x 256 x 256)*|[cc_himenobmtxp_l.lzh](win-mac/cc_himenobmtxp_l.zip)|
|M *(256 x 128 x 128)*|[cc_himenobmtxp_m.lzh](win-mac/cc_himenobmtxp_m.zip)|
|S *(128 x 64 x 64)*|[cc_himenobmtxp_s.lzh](win-mac/cc_himenobmtxp_s.zip)|

#### C(Dynamic Allocation Version)
|Size|C *(DA version)*|
|---|---|
|All Size|[himenobmtxpa.c](win-mac/himenobmtxpa.zip)|

#### Executable
|Size|Windows|Mac|
|---|---|---|
|L *(512 x 256 x 256)*|[himenobmtxp_l.exe](win-mac/himenobmtxp_l_exe.zip)|-|
|M *(256 x 128 x 128)*|[himenobmtxp_m.exe](win-mac/himenobmtxp_m_exe.zip)|[himenobmtxp_m_mac](win-mac/himenobmtxp_m_mac.zip)|
|S *(128 x 64 x 64)*|[himenobmtxp_s.exe](win-mac/himenobmtxp_s_exe.zip)|[himenobmtxp_l_mac](win-mac/himenobmtxp_s_mac.zip)|
|XS|-|[himenobmtxp_ss_mac](win-mac/himenobmtxp_ss_mac.zip)|
<br>

<div style="text-align: center">
{{< button href="mailto:himeno.sun@juntendo.ac.jp" target="_self" >}}
Contact us!
{{< /button >}}
</div>
