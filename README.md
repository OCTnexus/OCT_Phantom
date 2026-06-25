<img width="1389" height="1190" alt="Long Term Track" src="https://github.com/user-attachments/assets/3c191a9b-4fe9-4d99-9bc2-4f3fab92734c" />
# TiO2 OCT Phantom Protocol

This repository contains documentation and fabrication support files for titanium dioxide (TiO2) optical scattering phantoms used as physical reference objects for optical coherence tomography (OCT) imaging and attenuation measurement validation.

The main protocol describes cartridge-format TiO2-doped PDMS phantoms assembled with a cover glass, sealed sample chamber, buffer chamber, inlet port, epoxy sealing channel, and protective 3D-printed enclosure. The phantoms are intended for OCT system performance assessment, repeatability testing, and comparison of quantitative attenuation measurement methods.

## Repository Contents

| Path | Description |
| --- | --- |
| [`TiO2_OCT_Phantom_Protocol_V3.pdf`](TiO2_OCT_Phantom_Protocol_V3.pdf) | Current protocol PDF, including fabrication workflow, optical characterization methods, handling guidance, safety notes, storage, and shipping instructions. |
| [`3D Printed Components/`](3D%20Printed%20Components/) | CAD and STL files for the phantom cartridge, trap, enclosure/case parts, and related printed components. |
| [`SDS_Files/`](SDS_Files/) | Safety data sheets currently included with the repository. |

## Protocol Summary

The protocol covers:

- Fabrication of TiO2-PDMS optical scattering phantoms.
- Preparation of the 3D-printed cartridge and cover-glass seal.
- Mixing, dispersion, filling, vacuum degassing, and curing of the scattering PDMS sample.
- Final assembly of the protective cartridge enclosure.
- Optical property measurements using integrating-sphere measurements, inverse adding-doubling analysis, and low-coherence interferometry.
- Labeling, handling, storage, shipping, and safety requirements.

The protocol reports example phantom sets with TiO2 concentrations from 1 mg/g to 20 mg/g and measured reduced scattering, absorption, scattering, and anisotropy values. See the PDF for the measurement tables, serial-number format, figures, and references.

## 3D Printed Components

The [`3D Printed Components/`](3D%20Printed%20Components/) folder includes:

- [`Phantom_Hill.stl`](3D%20Printed%20Components/Phantom_Hill.stl) - STL model for the imaging hill.
- [`Phantom_trap.stl`](3D%20Printed%20Components/Phantom_trap.stl) - STL model for the phantom trap component.
- [`Phantom_trap_case_part1.stl`](3D%20Printed%20Components/Phantom_trap_case_part1.stl) and [`Phantom_trap_case_part2.stl`](3D%20Printed%20Components/Phantom_trap_case_part2.stl) - STL models for the protective case/enclosure parts.

Review the printed parts against the dimensions and assembly steps in the protocol before fabrication.

## Safety Data Sheets

The [`SDS_Files/`](SDS_Files/) folder currently includes:

- [`Gorilla-Epoxy-Syringe-Resin.pdf`](SDS_Files/Gorilla-Epoxy-Syringe-Resin.pdf)
- [`Sylgard_184_base.pdf`](SDS_Files/Sylgard_184_base.pdf)
- [`Sylgard_184_CuringAgent.pdf`](SDS_Files/Sylgard_184_CuringAgent.pdf)

Before fabrication, confirm that all current SDS documents required by the protocol are available to personnel, including the SDS for the specific TiO2 powder used in the lab.

## Basic Workflow

1. Read the current protocol PDF completely before fabrication.
2. Print and inspect the cartridge and enclosure components.
3. Prepare the cartridge, cover glass, and epoxy seal as described in the protocol.
4. Prepare the TiO2-PDMS mixture using the target concentration and the specified base-to-curing-agent ratio.
5. Fill, degas, and cure the phantom cartridge.
6. Assemble the protective enclosure.
7. Inspect, label, measure, and store the phantom according to the protocol.

## Shelf Time Track

<p align="center">
  <img src="./Long%20Term%20Track/Long%20Term%20Track.png" width="450" height="300" alt="Shelf Time Track">
</p>

## Use Limitations

These phantoms are research and validation tools for optical imaging systems. They are not clinical diagnostic devices, are not intended for sterile use, and are not intended for direct patient contact.

## Acknowledgment

This work is supported by NIBIB R21EB03393 for the National Medical Phantom Library (NMPL).
