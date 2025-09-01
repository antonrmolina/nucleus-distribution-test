---
title: "Specification: plamGFP"
site:
    hide-toc: true
    numbered_references: false
---

## Overview

Mitochondria consectetur adipiscing phylum, sed do ribosomes tempor incididunt ut chlorophyll et dolore magna cytoplasm. Ut enim ad minim chromosome, quis nostrud photosynthesis ullamco laboris nisi ut enzyme aliquip ex ea commodo peptide. Duis aute nucleotide in reprehenderit in voluptate vesicle esse cillum genome fugiat nulla pariatur.

### Schematic

::::{aside}
:::{dropdown} TODO

What are good guidelines for a schematic representations of different modules? For a protein output I think it might be useful to include a table of properties, there properties might correspond to parameters that we would put into the CDK can start with molecular weight and isoelectric point for proteins, small molecules might include MW, membrane permeability? Although some of this might be split into a particular instance as well - particularly if it involves interaction with membrane...
:::
::::

:::{figure} gfp-schematic.png
:width: 50%

This is a schematic of the module.
:::

### Designs

::::{aside}
:::{dropdown} TODO

What should belong in this table?
:::
::::

| **Name** | **Length (bp)** | **File** |
| --- | --- | --- |
| `pOpen-pT7-plamGFP-PURE` | 2946 | [design](https://github.com/bnext-bio/nucleus/blob/main/dna-distribution/v0.1.0-001/plamGFP-PURE.gb) |
| `pOpen-??-plamGFP-TXTL` | 2958 | [design](https://github.com/bnext-bio/nucleus/blob/main/dna-distribution/v0.1.0-001/plamGFP-TXTL.gb) |
| `pOpen-??-plamGFP-Chimeric` | 2958 | [design](https://github.com/bnext-bio/nucleus/blob/main/dna-distribution/v0.1.0-001/plamGFP-Chimeric.gb) |

### Compatible processes

- [PURE](./docs/02-collections/cytosols.md)

### Usage

**Collections**

- [Collection-1](/docs/collections/cytosols/instance-template/instance)

**DevNotes**

- [DevNote-3](https://doi.org/10.63765/djnv7772)

**Literature**

- [Wang *et al.* 2019](https://doi.org/10.1021/acssynbio.9b00456)

::::{aside}
:::{dropdown} TODO

I want to figure out how to hide the list of references from being auto generated at the bottom.
:::
::::
