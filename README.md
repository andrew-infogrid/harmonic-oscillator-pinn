# harmonic-oscillator-pinn

Forked from code accompanying this blog post: [So, what is a physics-informed neural network?]
(https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/)

<img src="figures/pinn.gif" width="850">

## This fork adds 2 more examples:

[DiffusionPINN.ipynb](./DiffusionPINN.ipynb):

Example where we have few "sensors" (points we can measure) but know the governing equation of the system well.

<img src="figures/diffusion-pinn.gif" width="850">


[BallisticsPINN.ipynb](./BallisticsPINN.ipynb):

Example where we have multiple observations and don't have a governing equation (artifically) of the system, but resort
to more general physical laws, in this case conservation of energy.

<img src="figures/ballistics-pinn.gif" width="850">

...and explain why this might not be enough, and add another physics constraint - Newton's second law:

<img src="figures/ballistics-pinn2.gif" width="850">
