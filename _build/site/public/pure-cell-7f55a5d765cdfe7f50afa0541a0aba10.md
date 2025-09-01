---
title: PURE Cell
downloads:
  - file: ../protocols/PURE_Cell.pdf
    title: "PURE Cell Protocol"
---

## Overview

PURE liposomes are the basis of a synthetic cell that can perform the fundamental operations of biology: transcription, and translation.

In this protocol, you will make the necessary precursors to creating liposomes, assemble a PURE cell-free reaction that will express Green Fluorescent Protein (GFP), and encapsulate it within a liposome. For the outer solution, you will use the same simple sugar solution that was used in [Buffer-in-Buffer Liposomes](https://www.notion.so/Buffer-in-Buffer-Liposomes-c15ada1e2f19426fa955d73138249eb9?pvs=21).

Successfully built PURE liposomes will start dark and then increase in green fluorescence over time as GFP is produced.

There are four key stages to making PURE liposomes:

:::{table} 
:label: tbl:protocol-timeline
:align: center
| Step | Process | Hands-on Time | Total Time | Notes |
| --- | --- | --- | --- | --- |
| 1 | [**Prepare stock buffers and lipids**](https://www.notion.so/PURE-Cell-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 1 h | 4 h | Buffers and lipids may be prepared in advance and used for experiments on subsequent days. |
| 2 | [**Assemble PURE reactions**](https://www.notion.so/PURE-Cell-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 1 h | 1 h |  |
| 3 | [**Encapsulate liposomes**](https://www.notion.so/PURE-Cell-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 2 h | 2 h |  |
| 4 | [**Measure and image**](https://www.notion.so/PURE-Cell-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 1 h | 6–12 h | Total time depends on the exact experiment and incubation conditions. GFP expression should be seen over the first 6 hours at 37C.
 |

:::

## Materials and Equipment

:::{table}
:label: tbl:materials-and-equipment
:align: center

| **Name** | **Product** | **Manufacturer** | **Part #** | **Price** | **Link** |
| --- | --- | --- | --- | --- | --- |
| ***Buffers*** |  |  |  |  |  |
| **Glucose** | D-(+)-Glucose, 99% | Thermo Scientific | A16828-36 | **$**41.65 | [[link](https://www.thermofisher.com/order/catalog/product/A16828.36)] |
| **Sucrose** | Sucrose, 99% | Thermo Scientific | A15583-36 | $41.65 | [[link](https://www.thermofisher.com/order/catalog/product/A15583.36?SID=srch-srp-A15583.36)] |
|  |  |  |  |  |  |
| ***Lipids*** |  |  |  |  |  |
| **POPC** | 16:0-18:1 PC 25 mg/mL | Avanti Lipids | 850457C-500mg | $435.00 | [[link](https://avantilipids.com/product/850457)] |
| **Liss-Rhod-PE** | 16:0 Liss Rhod PE 1 mg/mL | Avanti Lipids | 810158C-1mg | $281.67 | [[link](https://avantiresearch.com/product/810158)] |
| **Mineral Oil** | Mineral oil, mixed weight | Thermo Scientific | AC415080010 | $53.40 | [[link](https://www.sigmaaldrich.com/US/en/product/sigald/496189)] |
| **Glass Syringe 250 uL** |  | Hamilton | 14-815-238 | $150.15 | [[link](https://www.fishersci.com/shop/products/800-microliter-syringes-rn-termination/14815238)] |
|  |  |  |  |  |  |
| ***PURE*** |  |  |  |  |  |
| **PURE** | PURExpress | NEB | E6800S | $295.00 | [[link](https://www.neb.com/en-us/products/e6800-purexpress-invitro-protein-synthesis-kit)] |
| **RNase Inhibitor** | RNase Inhibitor, Murine | NEB | M0314S | $81.00 | [[link](https://www.neb.com/en-us/products/m0314-rnase-inhibitor-murine)] |
| **DNA** | `pT7-plamGFP PURE` | Nucleus v0.1.0-001 DNA | Well E3 |  | [[link](https://nucleus.bnext.bio/dna-distribution/nucleus-v010-001-distribution-plate)] |

:::

## Step 1: Prepare Stock Buffers and Lipids

Stock buffers may be prepared ahead of time, and stored for months. Lipids may also be prepared in advance and stored at 4C for at least 1 month. If you are making buffers and lipids at the same time, begin with the lipids so that they can evaporate while the buffers are being prepared.

**Prepare lipids in mineral oil**

- [ ]  Clean glass syringes.
    - [ ]  Pour a small amount of 95% ethanol into a glass container ****(e.g. a 10 mL beaker).
    - [ ]  Assemble the glass syringe and prime it by drawing ethanol into the glass syringe, then empty into a waste bottle.
- [ ]  Weight 2.67 g (or pipette 3.25mL) mineral oil into a glass test tube or beaker
- [ ]  Add the lipids to the mineral oil using the appropriate glass syringe:
    - [ ]  Add 480 uL 25 mg/mL POPC.
    - [ ]  *Rinse the syringe with ethanol.*
    - [ ]  Add 15 uL 1 mg/mL Liss Rhod PE.
    - [ ]  *Rinse the syringe with ethanol.*
- [ ]  Evaporate the chloroform from the lipid–oil mixture:
    - [ ]  Place lipid beaker in a 55°C dry bath in a fume hood.
    - [ ]  *(optional)* Shield with aluminum foil to protect from light.
    - [ ]  Evaporate uncovered for 3 h.
- [ ]  Clean syringes and store with plunger removed
- [ ]  Let the sample cool to room temperature in the fume hood.
    - [ ]  If lipids settle towards the bottom, stir them using a pipette tip.
    - [ ]  Aliquot the lipid–oil mixture into 1.5 mL aliquots, in glass jars.
    - [ ]  The lipid–oil mixture can be stored for a week or more at room temperature, or up to one month at 4C.
    - [ ]  Invert gently 3 times before use. Make sure the solution is not cloudy.

**Prepare sugar stock stock solutions**

| Buffer | Target Concentration (M) | MW (kDa) | Weight (g) | Final Volume (mL) |
| --- | --- | --- | --- | --- |
| **3M Glucose Stock** | 3.0 | 180.16 | 5.40 | 10.0 |
| **2M Sucrose Stock** | 2.0 | 342.3 | 10.27 | 15.0 |
- [ ]  Make 3M glucose stock solution:
    - [ ]  Combine 5.40 g glucose and 5.0 mL ddH2O in a 50 mL tube.
    - [ ]  Heat for 15 s in a microwave and mix vigorously to dissolve material completely.
    - [ ]  Add additional ddH2O to achieve a final volume of 10 mL.
    - [ ]  Filter sterilize while warm using a 0.22 um filter and store at -20 C.
- [ ]  Make 2M sucrose stock solution:
    - [ ]  Combine 10.27 g sucrose and 5.0 mL ddH2O in a 50 mL tube.
    - [ ]  Heat for 15 s and mix vigorously to dissolve material completely.
    - [ ]  Add additional ddH2O to achieve a final volume of 15 mL.
    - [ ]  Filter sterilize using a 0.22 um filter and store at -20 C.

**Prepare outer buffer**

- [ ]  Make a 800 mM glucose outer solution:
    - [ ]  Add 0.8 mL 3M glucose stock solution to a 15 mL tube.
    - [ ]  Add ddH2O water to a final volume of 3 mL.
    - [ ]  Vortex vigorously to mix.