# Beyond relativistic Lagrangian perturbation theory: A numerical example.
*_This research was funded by National Science Centre (NCN, Poland) under the Sonata-15 research grant UMO-2019/35/D/ST9/00342_*

This notebook contains the code used to generate the figures shown in *Section Numerical Example* of the paper *Delgado Gaspar, Buchert and Ostrowski (2022)* [arXiv:2210.04004]. It intends to provide a pedagogical introduction to GRZA as a generalization of Szekeres models.

This notebook is organized as follows.

- **Section 1: Quasi-spherical Szekeres models in Hellaby's parametrization.** In this section, we introduced the Szekeres 'seed model' in Hellaby's parametrization setting up its free functions. This LTB-like parametrization is the most popular representation of the quasi-spherical models of class I. And our intuition (at least mine) works better here.

- **Section 2: GW parametrization.** The seed model is rewritten in the GW language.

- **Section 3: GRZA solutions.** We use the functions of the rescaled Szekeres model and perturb the initial data. The new solution can be interpreted as a generalization of the quasi-spherical Szekeres models, where the surfaces of $t,r=\hbox{const.}$ are 2-spheres but arranged in a more general way than in Szekeres.

- **Section 4: Estimation of the error via the Ham. constraint.** We exploit the relationship between the present models and the exact solutions to work out a closed-form expression for $\mathbb{H}:= \left(G_{\mu\nu}-8\pi T_{\mu\nu}\right) u^\mu u^\nu=  G_{00}-8\pi T_{00}$. Here, we evaluate the final expression.
