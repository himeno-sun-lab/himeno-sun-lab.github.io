---
title: Himeno Benchmark
date: 2024/10/22

---

Dr. Ryutaro Himeno, Director of the Advanced Center for Computing and Communication, has developed this benchmark to evaluate performance of incompressible fluid analysis code. This benchmark program takes measurements to proceed major loops in solving the Poisson’s equation solution using the Jacobi iteration method.

Being the code very simple and easy to compile and to execute, users can measure actual speed (in MFLOPS) immediately.
 
We have upgraded the source code from “Himeno benchmark 98” to “himenoBMTxp” with the aim to decrease the difference of calculation time between computers that occurs due to the difference of their performances. As for Fortran versions, results obtained with the previous version can be compared with the one obtained with this version, because we didn’t change the kernel of the code from the old version. But, as for C versions, please be careful that we have changed a method to declare an array. We did so to maintain consistency with that of the Fortran versions. (December, 2001).

The Himeno Benchmark is made available under the LGPL2.0 or later.
