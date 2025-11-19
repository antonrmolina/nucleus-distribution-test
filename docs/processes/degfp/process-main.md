---
title: "Reporter: Base Cytosol + deGFP"
---

# Overview

This protocol describes how to set up a Nucleus Cytosol reaction using pOpen-deGFP as a DNA template to express the deGFP reporter protein. 

<!-- The important imformation card begins here -->
<!-- The important imformation card begins here -->
<!-- The important imformation card begins here -->
<!-- The important imformation card begins here -->
<!-- The important imformation card begins here -->

::::::{card}
:header: **Important Information**

Please read this section carefully. It contains important notes, resources, and safety information. Not all information included here is included in the lab-ready protocol.

:::{note} Notes
:class: dropdown

- None

:::

:::::{card}
:header: **Resources**
::::{grid} 1 1 1 3

:::{card}
:header: **Lab-ready Protocol**
:algin: center

{button}`download <protocol-make_template.pdf>`
:::

:::{card}
:header: **Assembly Worksheet**
{button}`download <Nucleus_v0.3.0_AA_worksheet.xlsx>`
:::

:::{card}
:header: **TODO: Bill of Materials**
{button}`download <protocol-Make_tRNAs.pdf>`
:::

::::
:::::

:::::{tip} Composition
:class: dropdown

::::{card}
:header: **Composition of Small Molecule Mix**
:::{table} 
:label: tbl:composition-table
:align: center

- See downloadable platemap

:::
::::
:::::

:::{seealso} Prerequisite Documentation
:class: dropdown
- None

:::

::::{important} Critical Materials
:class: dropdown

:::{table}
:label: tbl:critical-materials
:align: center

| **Name** | **Product** | **Manufacturer** | **Storage Conditions** |
| --- | --- | --- | --- |
| Energy Solution | SMix | b.next | -85C to -75C |
| PURE Protein Mix | PMix | b.next | -85C to -75C |
| *E. coli* Ribosomes | Ribosomes | b.next | -85C to -75C |
| *E. coli* tRNAs | tRNAs | b.next | -85C to -75C |
| Magnesium acetate | Magnesium acetate | b.next | -85C to -15C |
| DNA template | `pOpen-deGFP` | b.next | -85C to -15C |
| Nuclease-free water | Nuclease-free water | ThermoFisher Scientific (AM9916) | 4C to 30C |
| PCR tubes | Thin-walled, RNase-free PCR tubes | ThermoFisher Scientific (AM12225) | 4C to 30C |
| Optical Adhesive Film | MicroAmp Optical Adhesive Film | ThermoFisher Scientific (4311971) | 15C to 30C |
| 384-well plate | 384 SV NoBind | Greiner Bio-One (784900) | 15C to 30C |

::::

::::{important} Genetically Encoded Components
:class: dropdown

:::{table}
:label: tbl:critical-materials
:align: center

| **Name** | **Product** | **Manufacturer** | **Storage Conditions** |
| --- | --- | --- | --- |
| DNA template | `pOpen-deGFP` | b.next | -85C to -15C |
::::

::::{danger} Hazardous Materials
:class: dropdown

- None

::::

::::{note} References
:class: dropdown

- None

::::

::::::

<!-- The important imformation card ends here -->
<!-- The important imformation card ends here -->


# Protocol

- [ ]  Remove all components listed in the table below from the -80°C freezer and thaw them on ice.
- [ ]  Load the GFP fluorescence measurement protocol in the plate reader and preheat it to 37°C to measure protein expression kinetics.
- [ ]  Plan your reaction setup using the template below. This prepares a 35 µL reaction mastermix in a PCR tube on ice or a cold block.
  
:::{hint} Note: prepare reaction on ice.
:class: dropdown
Prepare the reaction on ice or a cold block to prevent protein expression from starting during assembly. This ensures the plate reader captures the complete fluorescence kinetics for deGFP expression.
:::

:::{table}
:label: tbl:rxn-setup

| **Component** | **Stock Concentration** | **Unit** | **Final concentration** | **Unit** | **Volume for mastermix [µL]** |
| --- | --- | --- | --- | --- | --- |
| SMix | 3.33 | × | 1 | × | 10.5 |
| PMix | 15 | mg/mL | 1.80 | mg/mL | 4.2 |
| Ribosomes | 10 | µM | 1.8 | µM | 6.3 |
| Nucleus tRNA | 35 | mg/ml | 3.5 | mg/ml | 3.5 |
| `pOpen-deGFP` DNA template | 124 | nM | 3 | nM | 0.85 |
| Magnesium acetate | 200 | mM | 8 | mM | 1.4 |
| Water |  |  |  |  | 8.25 |
| **Total mastermix volume [µL]** |  |  |  |  | **35** |

:::

- [ ]  Mix the mastermix thoroughly by pipetting up and down 10–15 times until it appears homogeneous and clear.
- [ ]  Aliquot 10 µL of the mastermix in triplicate into a 384-well plate for fluorescence measurement. Space the reactions with at least one empty well between them, and dispense the mastermix at the bottom of each well.

:::{hint} Note: prepare reaction on ice.
:class: dropdown
Set the P20 pipette to 10.1 µL to draw the mastermix, then dispense into the plate well by pushing the plunger to the first stop only—this prevents bubble generation in the reaction.
:::

- [ ]  Once all reactions are dispensed and the plate is ready for fluorescence measurement, seal it with an optical film to prevent evaporation.
- [ ]  Measure deGFP fluorescence in the plate reader while incubating at 37°C.


