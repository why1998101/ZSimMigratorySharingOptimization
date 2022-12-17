## ZSim with Migratory Sharing Optimization

###### by Zhuoyu Ji (zhuoyuj) and Haoyang Wang (haoyang4)

#### We modify the ZSim multicore cache simulator to add a migratory sharing optimization feature. This feature implements an algorithm to detect migratory objects and improve performance when accessing them. Experiment results verify that this optimization is effective.

### Deliverables

#### 1. Modified ZSim source code with the migratory sharing optimization feature added. [here](https://github.com/why1998101/zsim-optimized)
#### 2. Multiple micro-benchmark programs and outputs of running those programs using both default and our modified ZSim. [here](https://github.com/why1998101/zsim-benchmarks)
#### 3. A report with analysis on the optimization and experimental evaluation results. [here](https://github.com/why1998101/ZSimMigratorySharingOptimization/blob/main/Final_Project_Report.pdf)

### Schedule
| Date by  | Tasks |
| ------------- | ------------- |
| 12.2  | ZSim source code modification (DONE)  |
| 12.6  | Haoyang: set up ZSim envrionment in Ubuntu 16.04 VM and test modified code with provided test (DONE)<br />   Zhuoyu: set up ZSim envrionment in AWS and check performance (DONE)  |
| 12.9  | BOTH: write first pair of microbenchmark programs, run using default and modified ZSim to verify improvement and correctness (DONE) |
| 12.12  | BOTH: write additional microbenchmark programs with more migratory access patterns and edge cases (DONE) |
| 12.14  | BOTH: run additional microbenchmark programs using default and modified ZSim and collect results (DONE) |
| 12.17  | BOTH: write reports and prepare for poster session(DONE) |

### References

##### Per Stenström, Mats Brorsson, and Lars Sandberg. 1993. An adaptive cache coherence protocol optimized for migratory sharing. SIGARCH Comput. Archit. News 21, 2 (May 1993), 109–118. https://doi.org/10.1145/173682.165147

##### [ZSim source](https://github.com/s5z/zsim) and [tutorials](http://zsim.csail.mit.edu/tutorial/)
##### Ziqi Wang's [ZSim base](https://github.com/wangziqi2013/zsim-base) and [article](https://wangziqi2013.github.io/article/2019/12/25/understand-zsim-cc-sim.html)

### Additional Documents

[Slides for Poster Session](https://github.com/why1998101/ZSimMigratorySharingOptimization/blob/main/Poster_Slides.pdf)\
[Autolab Submission](https://github.com/why1998101/zsim-submission)\
 \
The Autolab Submission contains a README about how to set up an environment to compile our optimized ZSim and reproduce our tests.

### Legacy Documents

This project was originally targeting other optimizations on ZSim as shown in those legacy documents.\
 \
[Proposal](https://github.com/why1998101/ParallelCacheSimulator/blob/main/Project_Proposal.pdf)\
[Milestone](https://github.com/why1998101/ParallelCacheSimulator/blob/main/Milestone_Report.pdf)
