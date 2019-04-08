# A branch-and-cut method for the weighted $k$-traveling repairman problem and its application to the maintenance of speed cameras
Private enterprises and governments around the world use speed cameras to control traffic flow and limit speed excess. Cameras may be exposed to difficult weather conditions and typically require frequent maintenance. When deciding the order in which maintenance should be performed, one has to consider both the traveling times between the cameras and the traffic flow that each camera is supposed to monitor. In this paper, we study the problem of routing a set of technicians to repair cameras by minimizing the total weighted latency, that is, the sum of the weighted waiting time for each camera, where the weight is a parameter proportional to the monitored traffic. The resulting problem, called weighted $k$-traveling repairman problem (wkTRP), is a generalization of the well-known traveling repairman problem and can be used to model a variety of  real-world applications. In order to solve the wkTRP, we propose an iterated local search heuristic, as well as an exact branch-and-cut algorithm enriched with a number of valid inequalities. The effectiveness of the two methods is shown by means of extensive computational experiments,
performed both on instances derived from a real-world case study and on benchmark instances from the literature on the wkTRP and related problems.

## Instance files
< number of points N>

< number or vehicles K>

< C_11 ... C_1N

  .
  
    .
    
      .
      
   C_N1 ...  C_NN >
   
   <0> <weight> <repair time> <distance limit> <>
   
   .
   
   .
   
   .
   
   <N -1> <> <> <> <>
   
