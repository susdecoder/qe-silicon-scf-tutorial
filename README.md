# qe-silicon-scf-tutorial
My first Quantum Espresso DFT calculation: SCF calculation of crystalline silicon using PBE pseudopotentials.
# Quantum ESPRESSO: First SCF Calculation of Crystalline Silicon

This repository documents my first hands-on Density Functional Theory (DFT) simulation using Quantum ESPRESSO.

## Objective

Perform a self-consistent field (SCF) calculation of crystalline silicon and analyze the resulting total energy and electronic properties.

## Workflow

* Set up Quantum Mobile virtual machine
* Activated Quantum ESPRESSO environment
* Downloaded silicon crystal structure (`9008566.cif`)
* Converted CIF to QE input using `cif2cell`
* Prepared and edited `basic.in`
* Selected silicon pseudopotential (`Si.pbe-n-kjpaw_psl.1.0.0.UPF`)
* Ran SCF calculation using `pw.x`

## Input Parameters

* Exchange-correlation functional: PBE
* Plane-wave cutoff energy (`ecutwfc`): 50 Ry
* Charge density cutoff (`ecutrho`): 200 Ry
* K-point mesh: 7 × 7 × 7
* Calculation type: SCF

## Results

* Total Energy: **−93.45256277 Ry**
* Fermi Energy: **6.5160 eV**
* SCF Convergence: **5 iterations**

## Skills Demonstrated

* Basic Density Functional Theory (DFT) workflow
* Quantum ESPRESSO input preparation
* CIF crystal structure handling
* Pseudopotential selection (UPF / SSSP)
* SCF output interpretation

## Tools Used

* Quantum ESPRESSO
* Quantum Mobile VM
* cif2cell
* GitHub
