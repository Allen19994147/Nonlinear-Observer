# Nonlinear-Observer

The tasks are to design nonlinear observers by using contraction analysis to estimate velocity of a nonlinear system. Note that the three files share the same dynamic equation and it is infinitely differentiable. 

In this task, the measurable position is assumed to be x,and it's used to estimate velocity,x_dot, called x_hat_dot.

The result shows that it accurately estimates velocity and a controller design based on the measureable position and estimated velocity is able to stablize the system.

In Nonlinear_Observer_v1.slx and Nonlinear_Observer_v2.slx files, it's shown that an nonlinear observer can be built to accurately estimate the velocity given the position and equation of the dynamic. While in Nonlinear_Observer_v3.slx file, the simulation is extended to track a time-varing, yet continuous command and the differentiation of the measurable position and the estimation of the velocity from the observer is compared.

The result shows that though differentiation of the measurable position gives satisfactory estimation, it has a slight time delay to the actual velocity. However, the designed observer gives nearly identical estimation of velocity.
