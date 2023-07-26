+++
date = "2023-07-01"
description = ""
external_link = ""
image = ""
project_id = ""
picture = "ideal_stability_alpha3.0_unsaturated_figure_3.png"
short_description = ""
sort_position= 1
title = "Minimal Models of Moist Convection"
[[participants]]
    name = "Jeff Oishi"
    id = "jsoishi"
    is_member = true
+++

## Motivation

When water vapor condenses in the atmosphere, it releases latent heat and changes the buoyancy of the surrounding air.
This phase transition is a fundamentally non-linear process that dramatically shapes the evolution of convection, making it fundamentally different than ``dry'' convection without moisture.
Convective activity plays a key role in the climate system, including the radiation inhibition driven by clouds and the formation of severe weather.
Today's most advanced global climate models do not reliably resolve the formation of clouds, and thus they include significant model-dependent details that drive disagreements in the results.
Given that one of the key questions facing climate science is the effect warming will have on the cloud feedback, it is crucial to understand the essential physics of moist convection.
We are interested in the important question of how the release of latent heat by condensation affects the surrounding area: what **patterns** are driven by moist convection?


## Methods
We are using the "Rainy-Benard" model of moist convection, in which the effect of humidity is added to the standard *Rayleigh*-Benard model of convection in a viscous, conductive fluid.
The Rayleigh-Benard model is an excellent framework for studying pattern formation, but it is far too simple to be useful for Earth's atmosphere.
Rainy-Benard combines the simplicity and reproducibility of Rayleigh-Benard convection with the essential non-linear thermodynamics of condensation by coupling a moisture field to the buoyancy.
Using Dedalus's multidimensional non-linear boundary value solver, we are probing the highly non-linear equilibrium states of Rainy-Benard and investigating their stability.
Building on this, the group is pursuing a large-scale, three-dimensional study of the patterns formed in the system, seeking to understand the inhibiting effects of a given convective plume on its surroundings.


## Project Repository

[Github](https://github.com/jsoishi/rainy_benard_aggregation)


## External Collaborators

* Ben Brown (Colorado)
* Whitney Powers (Colorado)
* Steve Tobias (Leeds)
* Geoff Vallis (Exeter)

