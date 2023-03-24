# Cache-replacement-policies-using-gem-5
Comparison Of Cache Replacement Policies using Gem-5 Simulator

For memory-intensive programs, a good cache replacement policy
can exploit high performance. It is hard to decide on a particular algorithm that is
highly efficient for a specific cache configuration, as trade-offs exist on every part.
In this project, we carried out a detailed comparative analysis among some of the
common and efficient cache replacement policies with an aim to study their
individual effectiveness for different cache configurations, which will be performed
by using the gem5 simulator. The evaluation is carried out by using benchmarks with
varying workloads to determine the performance metrics individually. In this current
study, we evaluated the performance of Random Replacement (RR), Least Recently
Used (LRU), and First in First Out (FIFO) replacement policies with benchmark
Nqueens and BFS. In addition, this project also intends to find out the impacts of the
above-mentioned replacement policies on time-driven cache side-channel attacks’
performance in terms of success rate. However, we have not been able to run such
attack for different gem5 instances. So far, we have been able to write the source
code to produce AES side-channel timing attack and have been able to verify the
success rate of such attack on the local PC, not on the gem5 simulation environment.
However, as we know that in the full-system mode, GEM5 runs a real operating
system on it and allows users to interact with the OS. Hence, users can run any
applications on GEM5 as running on real-world hardware and we can exploit this
feature to launch the side-channel attack for different gem5 simulation instances to
understand the impacts of different replacement policies on the success rate
