# python-2DFlow-LBM
2D flow around a cylinder using Lattice Boltzmann Method(LBM)

The Lattice Boltzmann Method (LBM) is a modern numerical technique, very efficient, 
flexible to simulate different flows within complex and varying geometries.

maxIter = 200000 (Total number of time iterations)          
Re      = 220.0  (Reynolds number)     
nx = 520; ny = 180; ly=ny-1.0; q = 9 (Lattice dimensions and populations.)     
cx = nx/4; cy=ny/2; r=ny/9  (Coordinates of the cylinder.)     
uLB     = 0.04  (Velocity in lattice units.)         
nulb    = uLB*r/Re; omega = 1.0 / (3.*nulb+0.5) (Relaxation parameter.)  

you can easy to change parameter or color and number of cylinder
also can add more different position/size cylinder.

Example1 : 1-cylinder with red color in Velocity field
![image](https://github.com/weisting-sinica/python-2DFlow-LBM/blob/master/FlowAroundCylinder.gif)


Example2: 2-different-size-cylinder with nomarl color in Velocity field
![image](https://github.com/weisting-sinica/python-2DFlow-LBM/blob/master/twocylinder.gif)
