# RSMA-DNN
The RSMA-DNN source code is the original version of the code. Subsequently, it was modified when running other simulations and contents.
Currently, GitHub is still being improved.

# RSMA-Assisted Edge Collaborative Inference for Internet of Vehicles.

This is a code package related to the following pape:

Zhijian Lin, Senior Member, IEEE, Shaowei Yang, Xiaopei Chen, Student Member, IEEE, Daxin Tian, Fellow, IEEE, Jiguang He, Senior Member, IEEE, Yi Fang, Senior Member, IEEE, and Wenhao Wu, "RSMA-Assisted Edge Collaborative Inference for Internet of Vehicles," IEEE TVT.


# Abstract of the Article
With the growing deployment of intelligent applications in the Internet of Vehicles (IoV), collaborative deep neural network (DNN) inference across edge nodes has become essential for satisfying real-time processing and service demands. As a key enabler for 6G networks, rate-splitting multiple access (RSMA) offers improved transmission performance to meet the diverse requirements of multi-user communications. In this work, we propose an RSMA-assisted edge co-inference framework for distributed DNN task offloading in the IoV, where DNN inference tasks are partitioned and offloaded across roadside unit (RSU) and vehicles in a collaborative manner. The objective is to minimize the total task completion time for all vehicles by jointly optimizing the DNN partitioning and offloading strategy, RSMA power allocation, and computing resource allocation. The problem is inherently non-convex due to the strong coupling among communication, computation, and model partitioning variables. To address this, we develop a unified optimization framework and decompose it into three coordinated sub-problems. A triple-iteration joint optimization algorithm is formulated, combining successive convex approximation (SCA) based RSMA power control, genetic algorithm based DNN task scheduling, and Lagrange multiplier method based computing resource allocation at RSU. \textcolor{blue}{Simulation results demonstrate that, compared with baseline schemes, the proposed framework can reduce inference latency by up to $20\%$ and improve inference accuracy by up to $18\%$.


# License and Referencing
This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.


