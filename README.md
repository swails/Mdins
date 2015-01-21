Input files for MD simulations with Amber
=========================================

The names contain abbreviations for certain aspects:

- ES == Explicit Solvent (with periodic boundary conditions and PME)
- IS == Implicit Solvent (Generalized Born model)
- CpH/constpH == Constant pH MD
- NPT == isobaric-isothermal ensemble
- TI == thermodynamic integration

Current templates
-----------------

- `ES_CpH_md.mdin`: Explicit solvent constant pH MD input file
- `ES_equil.mdin`: Standard NpT equilibration input
- `ES_heat.mdin`: Standard heating (with restraints)
- `ES_md.mdin`: Standard production MD in explicit solvent
- `ES_NPT_Equilibrate.mdin`: Standard NpT equilibration w/ restraints
- `ES_relax_min.mdin`: Explicit solvent minimization
- `ES_relax_restrained_CpH_min.mdin`: explicit solvent constant pH minimization
        file with cartesian restraints
- `ES_slow_heat_CpH_restrained.mdin`: explicit solvent constant pH heating with
        cartesian restraints and linearly scaling the target temperature to
        effect slow heating
- `ES_slow_heat.mdin`: standard heating input file scaling the target
        temperature to effect slow heating
- `ES_TI_prod.mdin`: Standard TI production input file
- `IS_constpH_heat.mdin`: Implicit solvent heating for constant pH MD
- `IS_constpH_md.mdin`: Implicit solvent production for constant pH MD
- `IS_constpH_slow_heat.mdin`: Implicit solvent heating for constant pH MD
        linearly scaling the target temperature to effect slow heating
- `IS_constpH_slow_heat_restrained.mdin`: Same as above, but with cartesian
        positional restraints
- `IS_heat.mdin`: Standard implicit solvent heating input
- `IS_jar.mdin`: Implicit solvent steered MD input file
- `IS_md.mdin`: Standard implicit solvent production input
- `IS_relax_constpH_min.mdin`: Implicit solvent constant pH minimization
- `IS_relax_min.mdin`: Standard implicit solvent minimization
- `IS_slow_heat.mdin`: Standard implicit solvent heating input
        linearly scaling the target temperature to effect slow heating
