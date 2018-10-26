# A branch-and-cut method for the weighted $k$-traveling repairman problem and its application to the maintenance of speed cameras
Private enterprises and governments around the world use speed cameras to control traffic flow and limit speed excess. Cameras may be exposed to difficult weather conditions and typically require frequent maintenance. When deciding the order in which maintenance should be performed, one has to consider both the traveling times between the cameras, and the traffic flow that each camera is supposed to monitor. In this paper, we study the problem of routing a set of technicians to repair cameras by minimizing the total weighted latency, that is, the sum of weighted waiting time for each camera, where the weight is a parameter proportional to the monitored traffic. The resulting problem, called weighted $k$-traveling repairman problem (wkTRP) is a generalization of the well-known traveling repairmen problem, and models a variety of  applications. To solve the wkTRP, we propose a ILS heuristic and an exact branch-and-cut algorithm enriched with a number of valid inequalities. The effectiveness of the two methods is proved by extensive computational experiments,performed on both instances derived from the real-world study case and on benchmark instances obtained from the literature on similar problems. 

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
   
