## ZSim with Migratory Sharing Optimization

###### by Zhuoyu Ji (zhuoyuj) and Haoyang Wang (haoyang4)

#### We modify the ZSim cache simulator to add a migratory sharing optimization feature. This feature implements an algorithm to detect migratory objects. When migratory objects are detected, it improves performance by reducing the number of invalidation workflows in the cache system.

### Deliverables

#### 1. Modified ZSim source code with the migratory sharing optimization feature added.
#### 2. Multiple microbenmark programs and outputs of running those programs using ZSim.
#### 3. A report with analysis on the optimization and experimental evaluation results.

### Schedule
| Date by  | Tasks |
| ------------- | ------------- |
| 12.2  | ZSim source code modification (DONE)  |
| 12.6  | Haoyang: set up ZSim envrionments in Ubuntu 16.04 VM;    Zhuoyu: attempt to set up ZSim envrionments in AWS  |
| 12.11  | Haoyang & Zhuoyu: each write two to three microbenchmark programs, complie and run in the ZSim environments |
| 12.14  | Haoyang & Zhuoyu: prepare ZSim config files and use ZSim to collect results of running microbenmark programs  |
| 12.17  | Haoyang & Zhuoyu: write reports and prepare for poster session |

### References

##### Per Stenström, Mats Brorsson, and Lars Sandberg. 1993. An adaptive cache coherence protocol optimized for migratory sharing. SIGARCH Comput. Archit. News 21, 2 (May 1993), 109–118. https://doi.org/10.1145/173682.165147

##### [ZSim source](https://github.com/s5z/zsim) and [tutorials](http://zsim.csail.mit.edu/tutorial/)
##### [Ziqi Wang's base ZSim](https://github.com/wangziqi2013/zsim-base) and [article](https://wangziqi2013.github.io/article/2019/12/25/understand-zsim-cc-sim.html)

### Legacy Documents

###### This project was originally targeting on other optimization directions on ZSim as shown in those legacy documents.

##### [Proposal](https://github.com/why1998101/ParallelCacheSimulator/blob/main/Project_Proposal.pdf)
##### [Milestone](https://github.com/why1998101/ParallelCacheSimulator/blob/main/Milestone_Report.pdf)
