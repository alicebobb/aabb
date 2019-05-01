A-SearchVerificationCube

Search and verification of the 33-dimension cube of Xoodyak satisfying the rules in first two rounds:

1. search：1.XoodyakCubeSearch.py (gurobi)

2. verification: 2.XoodyakConditionalCubeVerification.py (sagemath)




B-Experiments_Attack

(1) key recovery of 5-round Ketje JR v1: Attackon5rKetjeJrV1.cpp;

The program is run in Visual Studio 2012 with x64 platform Release. The time is about 8 seconds for one recovery of 6 key bits using one CPU core (Intel i7 3.6GHz), and parallelism can reduce time.

(2) key recovery of 5-round Ketje JR v2: Attackon5rKetjeJrV2.cpp;

The program is run in Visual Studio 2012 with x64 platform Release. The time is about 17 seconds for one recovery of 7 key bits using one CPU core (Intel i7 3.6GHz), and parallelism can reduce time.

(3) key recovery of 6-round Xoodoo-AE: Attackon6rXoodoo.cpp;

The program is run in Visual Studio 2012 with x64 platform Release. The time is about 1.75 hours for one recovery of 1 key bits using one CPU core (Intel i7 3.6GHz), and parallelism can reduce time.

(4) key recovery of 6-round Xoodyak: Attackon6rXoodyak.cpp;

The program is run in Visual Studio 2012 with x64 platform Release. The time is about 130 hours for one recovery of 6 key bits using one CPU core (Intel i7 3.6GHz), and parallelism can reduce time. The code only test one correct key and two wrong keys for saving verification time.

