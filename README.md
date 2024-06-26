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
|Test 5| (0, 2)| (0, 2)|(0, 2)| |  | (0, 2)|
|Early 1| (0, 1)|(0, 362)|(0. 362)|(0, 512)|(0, 423)| (0, 1603)|
|Early 2| (0, 0)| (0, 144)|(0, 144)|(0, 266)|(0, 318)|(0, 713)|
|Early 3|(0, 49)|(0, 934)|(0, 934)|(0, 1354)|(0, 1068)|(0, 1419)|
|Early 4|(0, 0)|(0, 430)|(0, 430)| -|(0, 556)| (0, 542)|
|Early 6|(0, 607)|(0, 3287)|(0, 3287)| (0, 3957)|(0, 3927)| (0, 5630)|
|Middle 4| (0, 7)|(0, 7)|(0, 7)|(0, 7)|(0, 16)|(0, 7)|
|Late 4|(0, 0)|(0, 0)|(0, 0)|(0, 0)|(0, 0)|(0, 0)|
