# CP-PSO

CP-PSO is a hybrid algorithm developed by Athanasios N. Kranidiotis for the purpose of a Master Sc. Thesis with title "Effective Solution of the Sports Timetabling Problem Using Computational Intelligence Particle Swarm Optimization (PSO) Algorithms". CP-PSO combines the power of PSO with the flexibility and effectiveness of Google OR-Tools, CP-SAT. 

### Thesis
A copy of the thesis can be found here [link will be added in the future].

### Repository
The purpose of this repository is to publish the results of testing CP-PSO on ITC2021 instances. Those instances are listed into four dinstict categories:
- Test instances
- Early instances
- Middle instances
- Late instances

### Results
Currently, CP-PSO have been tested successfully on the following instances:

| Instance | Best LB | Best UB | Best known ITC2021 | Dimitsas et al. (2022) | Rosati et al. (2022) |CP-PSO Result |
|:----------:|:---------:|:--------------:|:-----------------:|:-------------------:|:---------------:|:---------------:|
| Test 1 | (0, 1066) | (0, 1066) | (0, 1066) |  |  | (0, 1066)|
| Test 2 | (0, 176) | (0, 176) | (0, 176) | |  | (0, 176) |
| Test 3| (0, 1253) | (0, 1253) | (0, 1253) | |  | (0, 1253) |
| Test 4 |(0, 4535) | (0, 4535) | (0, 4535) | |  | (0, 4535)|
| Test 5| (0, 2)| (0, 2)|(0, 2)| |  | (0, 2)|
| Early 1| (0, 1)|(0, 362)|(0. 362)|(0, 512)|(0, 423)| (0, 1603)|
| Early 2| (0, 0)| (0, 144)|(0, 144)|(0, 266)|(0, 318)|(0, 713)|
| Early 3|(0, 49)|(0, 934)|(0, 934)|(0, 1354)|(0, 1068)|(0, 1419)|
| Early 4|(0, 0)|(0, 430)|(0, 430)| -|(0, 556)| (0, 542)|
| Early 6|(0, 607)|(0, 3287)|(0, 3287)| (0, 3957)|(0, 3927)| (0, 5630)|
| Early 8|(0, 213)|(0, 1051)|(0, 1051)| (0, 1614)|(0, 1051)| (0, 2165)|
| Early 9|(0, 0)|(0, 56)|(0, 56)| (0, 448)|(0, 132)| (0, 1613)|
| Early 12|(0, 0)|(0, 315)|(0, 315)| (0, 1025)|(0, 1010)| (0, 1445)|
| Early 15|(0, 485)|(0, 2955)|(0, 2955)| (0, 4470)|(0, 3556)| (0, 6681)|
| Middle 4| (0, 7)|(0, 7)|(0, 7)|(0, 7)|(0, 16)|(0, 7)|
| Middle 5| (0, 47)|(0, 279)|(0, 279)|(0, 732)|(0, 510)|(0, 1029)|
| Middle 6| (0, 24)|(0, 1090)|(0, 1090)|(0, 1900)|(0, 1701)|(0, 1920)|
| Middle 7| (0, 27)|(0, 1780)|(0, 1780)|(0, 2792)|(0, 2203)|(0, 2672)|
| Middle 8| (0, 2)|(0, 129)|(0, 129)|(0, 301)|(0, 136)|(0, 703)|
| Middle 9| (0, 0)|(0, 415)|(0, 415)|(0, 1015)|(0, 640)|(0, 2185)|
| Middle 11| (0, 345)|(0, 2177)|(0, 2177)|(0, 2956)|(0, 2696)|(0, 3638)|
| Middle 14| (0, 0)|(0, 1140)|(0, 1140)|(0, 1619)|(0, 1172)|(0, 2889)|
| Late 3|(0, 416)|(0, 2369)|(0, 2369)|(0, 3004)|(0, 2457)|(0, 2833)|
| Late 4|(0, 0)|(0, 0)|(0, 0)|(0, 0)|(0, 0)|(0, 0)|
| Late 5|(0, 398)|(0, 1849)|(0, 1849)|-|(0, 2341)|(0, 1933)|
| Late 6|(0, 6)|(0, 872)|(0, 872)|(0, 1440)|(0, 930)|(0, 1648)|
| Late 7|(0, 5)|(0, 1558)|(0, 1558)|(0, 3009)|(0, 1765)|(0, 7082)|
| Late 8|(0, 78)|(0, 934)|(0, 934)|(0, 1375)|(0, 997)|(0, 1971)|
| Late 9|(0, 3)|(0, 498)|(0, 498)|(0, 1108)|(0, 715)|(0, 2426)|
| Late 11|(0, 0)|(0, 201)|(0, 201)|(0, 511)|(0, 207)|(0, 796)|
| Late 14|(0, 7)|(0, 1140)|(0, 1140)|(0, 1650)|(0, 1202)|(0, 2514)|
