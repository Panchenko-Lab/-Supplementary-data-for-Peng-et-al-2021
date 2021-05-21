# files for calculating tail-DNA binding free energies using MM/GBSA approach

## mmpbsa.in
input configuration file for binding energy calculation using amber mmgbsa tool

## mmpbsa.leap

Sample script to prepare the residue library and force field parameters for use with LEaP progarm.
To execuate the script:
tleap -f gen_nucl

## sub_job.sh

Sample script to run the calculation on CPU

## [example_output](example_output)
Some example outputs

## Installation

Please refer to the instruction at: https://ambermd.org/Installation.php

## running time

10h

## Required Progarms

Amber(https://ambermd.org)

The version of Amber18 was used.
