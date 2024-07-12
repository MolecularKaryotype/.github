## Introduction
This is a collection of tools that can be used for the Molecular Karyotype file format.

## What is Molecular Karyotype?
It is a file format that describes a karyotype as a collection of lists, each consists of ordered, large chromosomal segments. This file format carries the full information of a karyotype, to the basepair resolution.

It offers the advange of being able to easily convert to a full karyotype, such as abstraction to a banded visualization. It can also be used to efficiently introduce rearrangements such as during simulation, and perform comparison between two karyotypes.

Molecular karyotype is the output file format of **OMKar**, an algorithm that takes in the CNV and SV information and output a virtual karyotype.

## Included Tools
- ### [KarSimulator](https://github.com/MolecularKaryotype/KarSimulator)
Simulates a karyotype by introducing random SVs based on parameter file.

- ### [KarComparator](https://github.com/MolecularKaryotype/KarComparator)
Given two Molecular Karyotype files, compare the unphased similarity between the two karyotypes, with the option of allowing a small distance of mismatching between paired SV edges.

- ### [KarReporter](https://github.com/MolecularKaryotype/KarReporter)
Given a Molecular Karyotype file, produce the ISCN interpretation of the rearragements on the Karyotype, alongside with banded karyotype visualization and table of genes of interest.
