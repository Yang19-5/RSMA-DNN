# RSMA-DNN
The source code of RSMA-DNN is the original version. During the execution of other simulations and contents, this code was modified. Currently, the modified code is being sorted out, so the original version of the code is being uploaded first.

# DNN Partitioning and Offloading in Vehicular Networks Based on RSMA.

This is a code package related to the following pape:

Zhijian Lin, Senior Member, IEEE, Shaowei Yang, Celimuge Wu, Senior Member, IEEE, Wenhao Wu, Zhizhao Lu, Jiguang He, Senior Member, IEEE and Linhuang Wu "DNN Partitioning and Offloading in Vehicular Networks Based on RSMA," IEEE TVT.


# Abstract of the Article
The proliferation of intelligent connected vehicles and related applications with deep neural network (DNN) inference tasks has boosted a pivotal requirement for the unprecedented low latency and low energy consumption of the Internet of Vehicles (IoV) networks. However, it is difficult to deploy large-scale and computation-intensive DNN on resource-constrained vehicles. Inspired by the idea of distributed computing, a DNN partitioning and offloading strategy based on RSMA is designed, where various computational auxiliary nodes are introduced in a stochastic geometry approach to alleviate the computation dilemma of the task vehicle. This strategy selects the optimal DNN model partition points based on the computing capability of the auxiliary nodes, and then develops the optimal task offloading strategy to realize the effective distribution and execution of tasks between the edge server and the service vehicle. To minimize the average cost problem, we propose a joint optimization algorithm combining heterogeneous-earliest-finish-time algorithm and successive convex approximation algorithm (HEFT-SCA) to achieve the optimal offloading strategy. Experimental results show that compared to the baselines, the HEFT-SCA can reduce the average cost.

# Content of Code Package
Here is a detailed description of the package:
The code in all packages are implemented in Matlab environment with CVX toolbox assisted.
main.m serves as the main program that implements the SCA-HEFT algorithm.
PCP.m and config.m perform the initial system modeling, including generating vehicle position information, system states, and channel conditions. The generated data are then used by main.m to conduct the simulation.



# Referencing
 If you in any way use this code for research that results in publications, please cite our original article listed above.


