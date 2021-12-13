# Travelling-Salesman-Problem-of-Space-Trajectory-Design
 A conituous mapping technique is used to reformulate the mixed intger
% TSP into a continuous optimization probelm. A set of continuous
% paramteres, expected value and variance  of position to be traveled to the
% nex node are used to instead of the integer ID of node to be optimized.
% The program select the node to visit using prior of expected value and
% varaiance, togther with the variance progagated from the previous node.
% Variance of the distance are then predicted using the updated variance at
% the current node and the previous node. After the continuous mapping reformulation,
% a gradient-based optimizer is used to search the optimal solution. Three
% bencmarks of TSPLIB, burma14,bays29 and korA100 with 14, 29 and 100 nodes respectively are used to test the
% algorithm.
%

% Benchmarks are from:http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/tsp/ 
% Author: 
%  Liqiang-Hou, School of Aeronautics and Astronautics, Shanghai Jiaotong University
% For any questions about the program, please email houliqiang@sjtu.edu.cn
% All right revserved
