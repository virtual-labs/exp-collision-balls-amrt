## Theory 

The abrupt change to the path of a moving body (or bodies) due to its interaction with other body (or bodies) is called collision. The magnitude and direction of the velocity of the colliding bodies may change in a collision. The force involved in collision may be large, but it acts only for a very short time. We come across many examples of collision daily. The coins of a carom game colliding with one another or collision between two automobiles in a road accident etc. are examples of collision. The Conservation Laws applied here are:

1. **Law of conservation of linear momentum:** Total linear momentum of a system of particle is conserved if no external force acts on the system. i.e., total linear momentum before collision is equal to total linear momentum after collision, if no external force acts on the system.
2. **Law of conservation of energy:** Energy can neither be created nor destroyed. But can be converted from one form to other.
 

### Types of collision:
 
1. **Elastic collision**: Collisions in which both momentum and kinetic energy of the system are conserved are called elastic collisions. The collision between subatomic particles is generally elastic. The collision between two steel or glass balls is nearly elastic. In elastic collisions, the forces involved during interaction are of conservative in nature.
2. **Inelastic collision**: Collisions in which momentum of the system is conserved but not the kinetic energy are called inelastic collisions. Most collision in everyday life is inelastic.
 

**Centre of mass of a system of particles**: Every physical system has associated with a certain point whose motion characterises that of the system as a whole. When the system moves under an external force then this point moves in the same way as a single particle would move under the same external force. This point is called centre of mass of the system. The motion of the system can be described in terms of the motion of its centre of mass.
 

### Formulas used:
 

#### Elastic and Inelastic Collision in Two Dimensions:

Here for the determination of the 'impact angle', the hard sphere model which obviously would only be an approximation for charged particles (strictly speaking the Rutherford scattering formula would have to be used for this). Apart from this, the solution below is a completely general and exact description of a 2D collision event (and in any case it provides exact conservation of momentum and energy). The relationship between the velocities of masses m1 and m2 before the collision (unprimed) and after the collision (primed) is given by the conservation equations for momentum and energy:

$$m_{1}v_{x,1}=m_{1}v_{x,1'}+m_{2}\Delta v_{x,2'}..............(1)$$
$$m_{1}v_{y,1}=m_{1}v_{y,1'}+m_{2}\Delta v_{x,2'}\tan (\theta)............(2)$$
$$\frac{m_{1}}{2}(v_{x,12}+v_{y,12})=\frac{m_{1}}{2}(v_{x,1'2})+\frac{m_{2}}{2}\Delta v_{x,2'2}(1+\tan (2\theta)).....(3)$$

For the sake of simplicity it has been assumed here that mass 2 is initially resting i.e. vx,2=0, vy,2=0 and $v_{x,2'}=\Delta v_{x,2'}$ (this does not affect the general validity of the final result as the assumption will be dropped again later by referring the velocities to mass 2 explicitly). The angle $\theta$¸ in Eq.(2) (and (3)) is the angle of the final velocity vector of ball 2 with the x-axis. This will be determined separately later from the geometry of the collision (alternatively, one can also treat $\theta$¸ as a free parameter). Solving now Eq.(1) for $v_{x,1'}$ and Eq.(2) for $v_{y,1'}$ yields

$$v_{x,1'}=v_{x,1}-\frac{m_{2}}{m_{1}}\Delta v_{x,2'}........(4)$$
$$v_{y,1'}=v_{y,1}-\frac{m_{2}}{m_{1}}\Delta v_{x,2'}\tan (\theta)............(5)$$

Inserting (4) and (5) into Eq.(3) results in a quadratic equation for $\Delta v_{x,2'}$ which (after some lengthy but straightforward algebraic manipulations) yields the solution:

$$\Delta v_{x,2'}=\frac{2[v_{x,1}+\tan (\theta)v_{y,1}]}{[(1+\tan 2\theta])(1+\frac{m_{2}}{m_{1}})]}........(6)$$

Refering now the initial velocities explicitly to ball 2 and noting that the angle $\theta$¸ is the sum of the relative velocity angle between ball 1 and 2

$$Yv=\arctan \left[ \frac{(v_{y,1}-v_{y,2})}{(v_{x,1}-v_{x,2})} \right]..........(7)$$

and the impact angle $\theta$ (see below); one can finally write

$$\Delta v_{x,2'}=\frac{2[v_{x,1}-v_{y,2}+a.(v_{y,1}-v_{y,2})]}{[(1+a2)(1+\frac{m_{2}}{m_{1}})]}......(8)$$

where

$$a=\tan (\theta)=\tan (Yv+\alpha)..................(9)$$

The 'impact angle' $\theta$ can vary between $-90^{0}$ and $+90^{0}$ (or $\frac{-\pi}{2}$ and $\frac{\pi}{2}$ when using radians) ($0^{0}$ corresponds to a head-on- and the extreme values to a grazing collision). (in most treatments of collision problems, the center-of -mass scattering angle $\theta$ is used, which relates to $\theta$ through $\theta=(\pi-\theta)/2; however, as $\theta$ is independent of the reference frame, it is a much better choice here). The actual value of$\theta$ depends on the exact coordinates of the particles, so if the latter are not known, one has to treat $\theta$ as a free parameter and generate it for instance through a random number generator. (otherwise see below for the determination of $\theta$). From Eqs.(2),(4),(5),(8),and (9) the velocity components after the collision are therefore:

$$v_{x,2'}=v_{x,2}+\Delta v_{x,2'}...............(10)$$
$$v_{y,2'}=v_{y,2}+a.\Delta v_{x,2'}...............(11)$$
$$v_{x,1'}=v_{x,1}-\frac{m_{2}}{m_{1}}\Delta v_{x,2'}...............(12)$$
$$v_{y,1'}=v_{y,1}-a.\frac{m_{2}}{m_{1}}\Delta v_{x,2'}...............(13)$$

The 'impact angle' $\alpha$ in Eq.(9) can be determined from the collision geometry as shown in the illustration below:




