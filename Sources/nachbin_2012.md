nachbin, André, and Vanessa da Silva Simões. “Solitary Waves in Open Channels with Abrupt Turns and Branching Points.” Journal of Nonlinear Mathematical Physics, vol. 19, no. Supplement 1, Springer Science and Business Media LLC, 2012, p. 116. Crossref, doi:10.1142/s1402925112400116.

[nachbin_2012_parameters](../Cards/nachbin_2012_parameters.md)
# Sec 1. Introduction

The problem of studying the dynamics of [solitary_waves](../Cards/solitary_waves.md) in complex domains such as open channels with sharp bends and branching points is of great interest due to its wide range of applications, including flood and tidal waves in rivers, channels of an irrigation network, and even [tsunamis_in_norwegian_fjords](../Cards/tsunamis_in_norwegian_fjords.md). The paper aims to address this problem by investigating how nonlinear waves, such as [solitary_waves](../Cards/solitary_waves.md), propagate through sharp bends and branching points in open channels.


**Facts:**

- With the [[jacobian_of_the_schwarz_christoffel_transformation]] we can rationalize the [solitary_waves](solitary_waves.md) characteristic at sharp-beds, both in narrow and wide channel configurations. 

# Sec 2.  Background on the Water Wave  Model

- Provides the background material necessary for understanding the water wave problem and the boundary conditions that must be satisfied.
- **Water Wave Problem:** Describing the motion of an [invisid_fluid](../Cards/invisid_fluid.md), subject to [free_surface_boundary_conditions](../Cards/free_surface_boundary_conditions.md).
- With $\Phi$ velocity potential, $\eta$ free surface wave elevation, and $h_o$ depth of the channel, then the [reduced_potential](../Cards/reduced_potential.md) is equal to $\phi(x,y,t)=\frac{1}{h_o+\eta}\int_{-h_0}^\eta \Phi(x,y,z,t)\ dz$ .
- Using the [reduced_potential](../Cards/reduced_potential.md) Wu obtained the generalized [boussinesq_type_systems](../Cards/boussinesq_type_systems_of_partial_differential_equations.md):
	- $\eta_t + (1+\eta) (\phi_{xx}+\phi_{yy}) + \eta_x\phi_x + \eta_y\phi_y=0$ 
	- $\phi_t + \eta + \frac{(\phi_x)^2+(\phi_y)^2}{2} - \frac{\phi_{xxy}+\phi_{yyt}}{3}=0$  
- With $x$ is a coordinate tangential to the side walls, $y$ is normal to the side walls, $\kappa$ is the curvature, and $L$ is the scale factor $L=1+\kappa y$, due to variable changes the [boussinesq_type_systems](../Cards/boussinesq_type_systems_of_partial_differential_equations.md) becomes:
	- $\eta_t+\frac{1}{L^2} \left[(1+\eta)\phi_y\right]_y + \frac{\kappa}{L} (1+\eta)\phi_y=0$ 
	- $\phi_t+\eta+\frac{1}{2L^2}(\phi_x)^2+(\phi_y)^2 -\frac{1}{3L^2}\phi_{xxt}-\frac{1}{3}\phi_{yyt}-\frac{\kappa}{3L}\phi_{yt}=0$ 
 - Wu made experiments for sharp-corned 90◦-bends as well as smooth. Reported that the reflection and transmission properties of solitary waves going through these bends is mostly controlled by the ratio `width-to-wavelenght`. 
	 - $b=\text{width of the channel}$ and $\lambda_e=\text{solitary wave's effective support}$. When $b/\lambda_e$ is small the channel is narrow; while when $b/\lambda_e$ is not small the channel is wide.


# Sec 3. The Schwarz-Christoffel Transformation of Sharp-Corned Bends

- The authors used the [schwarz_christoffel_transformation](../Cards/schwarz_christoffel_transformation.md) to change the domain of the `L` shaped channel, into a flat strip.
-  Is important to know that [schwarz_christoffel_transformation](../Cards/schwarz_christoffel_transformation.md) is a [conformal_map](../Cards/conformal_map.md) (mainly because of the [riemman_mapping_theorem](../Cards/riemman_mapping_theorem.md)); but it's important in the sense that it keeps the general structure of the original shape.
- [schwarz_christoffel_transformation](../Cards/schwarz_christoffel_transformation.md) helps reformulate the wave model in new coordinate system, allowing for accurate modeling of wave behavior at channel boundaries, even in complex configurations. It improves the efficiency and accuracy of the studying wave dynamics in challenging channel shapes.
- [schwarz_christoffel_transformation](../Cards/schwarz_christoffel_transformation.md) can be applied to branching channels. 
- With $|J|$ the [jacobian_of_the_schwarz_christoffel_transformation](../Cards/jacobian_of_the_schwarz_christoffel_transformation.md), and $z=f(w)$ for $w =\xi + i\zeta$, the generalized [boussinesq_type_systems](../Cards/boussinesq_type_systems_of_partial_differential_equations.md) now reads:
	- $\eta_t + \frac{(1+\eta)(\phi_{\xi\xi})}{|J|} + \frac{\eta_\xi \phi_\xi + \eta_\zeta \phi_\zeta}{|J|}$  
	- $\$phi_t + \eta \frac{\phi^2_\xi + \phi^2)_\zeta}{2|J|} - \frac{1}{3|J|}(\phi_{\xi\xi t} + \phi_{\zeta\zeta t})$ 

# Sec 4. Numerical Methods and Simulations

- Presents the results of the numerical simulations of various channel configurations.
- The experiment is using the trivial [neumman_condition](../Cards/neumman_condition.md): $\frac{d\phi^n}{d\zeta}=0$, it is used to ensure that the wave behaves in a certain way as it encounters the wall of the channel.
- 

# Sec 5.  Conclusion






