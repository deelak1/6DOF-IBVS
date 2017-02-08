# 6DOF-IBVS
## Dynamics
  M(q)𝑞 ̈+N(q,𝑞 ̇)= 𝜏    	Eqn 1
  
  M=inertia matrix
  
  N=Coriolis matrix+gravity vector+coefficient of friction
  
  Tau=applied torque which is also the control input

## Closed loop error dynamics
  M(𝑒 ̈+kv𝑒 ̇+kpe)=0 	Eqn 2

## Design of computed torque control
  With control objective e=q-qd
  
### And from eqn 1 and 2
  
  𝜏=N-M𝑞 ̈d - M (kv𝑒 ̇+kpe)  Eqn 3



