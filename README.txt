# Particle-swarm-optimization-pseudo-code
for each particle
{
initialize particle
END
}
Do 
{
  for each particle
  calculate fitness value
  if the fitness value is better than the pBest in history
  
  set current value as the pBest 
  END
  
choose the particle with the best fitness value of all particle
}

for  each particle 

  calculate particle velocity
  update prticle position
     
     
     v[]=v[]   +   c1    *   rand()*   (pBest[]-present[])   +  c2*rand()* (gBest[]-present[])     
     Present[]=Present[]+v[]
     while max iteration or min error criteria is attained
     
