# Instance configuration for the AMRs

This repo is part of the *Configuration Manager*. See here for an intro to configuration manager: https://tresor.it/p#0038mrbjmiq6fycy8q8wu3yd/Office_IT/AMR_Navigation_internal_DFM_meeting/12.13/Tony%20Configuration.pptx

# How to configure
Each branch of this repository contains configuration specific to an AMR. Branches must be named `amrXX` where XX is the AMR's id. 

Inside the branches, the directory structure is the same as in the `config` subfolder of `amr_bringup`.

Any configured value will override the values from more general configurations.

# Conventions

Only put here the values that are overriden. Do *not*  copy the whole config subfolder.

This way, if we improve / rename / remove default parameters, no changes need to be done here for unmodified parameters.
