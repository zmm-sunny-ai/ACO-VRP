# ACO-VRP
  目的：在车辆路径规划问题上应用蚁群算法进行解决
### 路径规划问题（Vehicle Routing Problems，VRP）
路径规划根据是否有时间要求有很多种类型，有的包含投递要求的时间窗，较为复杂，添加一些限制条件也能够实现。

此处的是关于单台车，运载一定量的货物递送各个目的地，可以一趟跑多个点，也可以只跑一个点。

#### 旅行推销员问题（最短路径问题）（英语：Travelling salesman problem, TSP）
旅行推销员问题给定一系列城市和每对城市之间的距离，求解访问每一座城市一次并回到起始城市的最短回路。它是组合优化中的一个NP困难问题，在运筹学和理论计算机科学中非常重要。

## 路径规划问题和旅行推销员问题
两个存在极大的相似性，不同之处在于，旅行商通常没有货物运载量的限制，不需回会到仓库装载货物。因此旅行商问题可以看做是车辆路径规划问题的特殊形式。本算法从这个思路出发，将现有的aco-tsp算法进行修改成为aco-vrp。
