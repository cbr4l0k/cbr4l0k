
# Parameters

| name               | definition                                                                                                      |
| ------------------ | --------------------------------------------------------------------------------------------------------------- |
| $(x,y)$            | Original coordinates                                                                                            |
| $(\xi,\zeta)$      | Coordinates after mapping                                                                                       |
| $\Phi(x,y,z,t)$    | Velocity potential                                                                                              |
| $\eta(x,y,z)$      | Wave elevation                                                                                                  |
| $h_o$              | Channel depth                                                                                                   |
| $\phi(x,y,t)$      | [Reduced potential](reduced_potential.md)                                                                       |
| $L$                | Scale factor                                                                                                    |
| $b$                | Width of the channel                                                                                            |
| $\lambda_e$        | Solitary wave's effective wavelength                                                                            |
| $b/\lambda_e$      | *width-to-wavelength*                                                                                           |
| $f$                | [Schwarz-Christoffel Mapping](schwarz_christoffel_transformation.md) (S.C.M)                                    |
| $\left\|J\right\|$ | [Jacobian of the S.C.M.](jacobian_of_the_schwarz_christoffel_transformation.md)                                 |
| $\phi^n(i,j)$      | $\phi(\xi_i,\zeta_j,t^n)$                                                                                       |
| $(\xi_i,\zeta_j)$  | Mesh points                                                                                                     |
| $E^n(i,j)$         | $-\frac{1}{\|J\|}\left[(1+\eta)(\phi_{\xi\xi}+\phi_{\zeta\zeta})(\eta_\xi\phi_\xi+\eta_\zeta\phi_\zeta)\right]$ |
| $G^n(i,j)$         | $-\eta - \frac{(\phi_\xi)^2+(\phi_\zeta)^2}{2\|J\|}$                                                            |
| $F$                | Auxiliary function                                                                                              |
| $\mu$              | Number of iterations/corrections made                                                                                                                |
| $\alpha$           | [solitary wave](solitary_waves.md) amplitud                                                                     |
| $\beta(\alpha)$    | influences the shape and width of the [solitary wave](solitary_waves.md)                                        |
| $c(\alpha)$        | Wave speed                                                                                                      |
| $\theta$           | Angle between branching channel                                                                                 |
| $a$                | Node at the inner corner                                                                                        |
| $b$                | Node North of $a$                                                                                               |
| $c$                | Node East of $a$                                                                                                |
| $C_1,C_2$          | Constants                                                                                                       |
