# CP-PSO

CP-PSO is a hybrid algorithm developed by Athanasios N. Kranidiotis for the purpose of a Master Sc. Thesis with the title "Effective Solution of the Sports Timetabling Problem Using Computational Intelligence Particle Swarm Optimization (PSO) Algorithms". CP-PSO combines the power of PSO with the flexibility and effectiveness of Google OR-Tools, CP-SAT. 

### Thesis
A copy of the thesis can be found here [link will be added in the future].

### Repository
The purpose of this repository is to publish the results of testing CP-PSO on ITC2021 problem instances. Those instances are listed into four dinstict categories:
- Test instances (Benchmarks)
- Early instances
- Middle instances
- Late instances

### Benchmarks
CP-PSO algorithm passed successfully the benchmark tests shown in the table below:

| Instance | Best LB | Best UB | Best known ITC2021 solution | CP-PSO Result |
|:----------:|:---------:|:--------------:|:-----------------:|:-------------------:|
| Test 1 | (0, 1066) | (0, 1066) | (0, 1066) | (0, 1066)|
| Test 2 | (0, 176) | (0, 176) | (0, 176) |  (0, 176) |
| Test 3| (0, 1253) | (0, 1253) | (0, 1253) | (0, 1253) |
| Test 4 |(0, 4535) | (0, 4535) | (0, 4535) |  (0, 4535)|
| Test 5| (0, 2)| (0, 2)|(0, 2)| (0, 2)|


This means that CP-PSO algorithm is working properly and efficiently. 

### Experimental Results
The objectives derived after executing CP-PSO algorithm on ITC2021 instances are shown below:

| Instance | Best LB | Best UB | Best known ITC2021 solution | Dimitsas et al. (2022) objective | Rosati et al. (2022) objective|CP-PSO objective |
|:----------:|:---------:|:--------------:|:-----------------:|:-------------------:|:---------------:|:---------------:|
| Early 1| (0, 1)|(0, 362)|(0. 362)|(0, 512)|(0, 423)| (0, 1603)|
| Early 2| (0, 0)| (0, 144)|(0, 144)|(0, 266)|(0, 318)|(0, 713)|
| Early 3|(0, 49)|(0, 934)|(0, 934)|(0, 1354)|(0, 1068)|(0, 1419)|
| Early 4|(0, 0)|(0, 430)|(0, 430)| (6,-)|(0, 556)| (9, -) |
| Early 5|(0, 270)|(0, 3127)|(0, 3127)| (5, -)|(0, 4117)| (36, -) |
| Early 6|(0, 607)|(0, 3287)|(0, 3287)| (0, 3957)|(0, 3927)| (0, 5630)|
| Early 7|(0, 1296)|(0, 4744)|(0, 4744)| (0, 9644)|(0, 5205)| (0, 10818)|
| Early 8|(0, 213)|(0, 1051)|(0, 1051)| (0, 1614)|(0, 1051)| (0, 1994)|
| Early 9|(0, 0)|(0, 56)|(0, 56)| (0, 448)|(0, 132)| (0, 1613)|
| Early 10|(0, 331)|(0, 3400)|(0, 3400)| (32, -)|(0, 4986)| (34,-) |
| Early 11|(0, 348)|(0, 4381)|(0, 4381)| (0, 8189)|(0, 4526)| (0, 11989)|
| Early 12|(0, 0)|(0, 315)|(0, 315)| (0, 1025)|(0, 1010)| (0, 1445)|
| Early 13|(0, 2)|(0, 121)|(0, 121)| (0, 380)|(0, 173)| (0, 730)|
| Early 14|(0, 1)|(0, 4)|(0, 4)| (0, 63)|(0, 63)| (0, 1392)|
| Early 15|(0, 485)|(0, 2955)|(0, 2955)| (0, 4470)|(0, 3556)| (0, 6681)|
| Middle 1| (0, 2955)|(0, 5177)|(0, 5177)|(17, -)|(0, 5657)|(12, -)|
| Middle 2| (0, 2984)|(0, 7381)|(0, 7381)|(48, -)|(5, -)|(35, -)|
| Middle 3| (0, 3378)|(0, 9315)|(0, 9315)|(0, 12170)|(0, 9542)|(0, 11809)|
| Middle 4| (0, 7)|(0, 7)|(0, 7)|(0, 7)|(0, 16)|(0, 7)|
| Middle 5| (0, 47)|(0, 279)|(0, 279)|(0, 732)|(0, 510)|(0, 1029)|
| Middle 6| (0, 24)|(0, 1090)|(0, 1090)|(0, 1900)|(0, 1701)|(0, 1920)|
| Middle 7| (0, 27)|(0, 1780)|(0, 1780)|(0, 2792)|(0, 2203)|(0, 2672)|
| Middle 8| (0, 2)|(0, 129)|(0, 129)|(0, 301)|(0, 136)|(0, 447)|
| Middle 9| (0, 0)|(0, 415)|(0, 415)|(0, 1015)|(0, 640)|(0, 2185)|
| Middle 10| (0, 4)|(0, 1228)|(0, 1228)|(1, -)|(0, 1357)|(0, 2211)|
| Middle 11| (0, 345)|(0, 2177)|(0, 2177)|(0, 2956)|(0, 2696)|(0, 3638)|
| Middle 12| (0, 1)|(0, 597)|(0, 597)|(0, 1596)|(0, 950)|(0, 3291)|
| Middle 13| (0, 0)|(0, 211)|(0, 211)|(0, 780)|(0, 362)|(0, 4715)|
| Middle 14| (0, 0)|(0, 1140)|(0, 1140)|(0, 1619)|(0, 1172)|(0, 2889)|
| Middle 15| (0, 1)|(0, 462)|(0, 462)|(0, 1833)|(0, 985)|(0, 6290)|
| Late 1|(0, 1103)|(0, 1919)|(0, 1919)|(0, 2234)|(0, 2021)|(0, 3115)|
| Late 2|(0, 2818)|(0, 5379)|(0, 5379)|(0, 5680)|(0, 5715)|(0, 6434)|
| Late 3|(0, 416)|(0, 2369)|(0, 2369)|(0, 3004)|(0, 2457)|(0, 2833)|
| Late 4|(0, 0)|(0, 0)|(0, 0)|(0, 0)|(0, 0)|(0, 0)|
| Late 5|(0, 398)|(0, 1849)|(0, 1849)|(39,-)|(0, 2341)|(29, -)|
| Late 6|(0, 6)|(0, 872)|(0, 872)|(0, 1440)|(0, 930)|(0, 1648)|
| Late 7|(0, 5)|(0, 1558)|(0, 1558)|(0, 3009)|(0, 1765)|(0, 7082)|
| Late 8|(0, 78)|(0, 934)|(0, 934)|(0, 1375)|(0, 997)|(0, 1971)|
| Late 9|(0, 3)|(0, 498)|(0, 498)|(0, 1108)|(0, 715)|(0, 2426)|
| Late 10|(0, 1)|(0, 1786)|(0, 1786)|(6, -)|(0, 2571)|(21, -)|
| Late 11|(0, 0)|(0, 201)|(0, 201)|(0, 511)|(0, 207)|(0, 796)|
| Late 12|(0, 203)|(0, 3226)|(0, 3226)|(0, 7218)|(0, 3944)|(0, 11271)|
| Late 13|(0, 7)|(0, 1813)|(0, 1813)|(0, 3576)|(0, 1862)|(0, 7810)|
| Late 14|(0, 7)|(0, 1140)|(0, 1140)|(0, 1650)|(0, 1202)|(0, 1966)|
| Late 15|(0, 0)|(0, 0)|(0, 0)|(0, 80)|(0, 60)|(0, 1280)|


Objectives were produced by running CP-PSO algorithm at slow machines (max 8 vCPU) at limited wall time. Compared to other researchers' available computational power (64 vCPU), our solutions can certainly be improved on a faster machine. 
