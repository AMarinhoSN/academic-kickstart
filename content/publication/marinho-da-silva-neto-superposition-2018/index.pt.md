+++
title = "A superposition free method for protein conformational ensemble analyses and local clustering based on a differential geometry representation of backbone"
date = 2018-12-01
authors = ["Antonio Marinho da Silva Neto", "Samuel Reghim Silva", "Michele Vendruscolo", "Carlo Camilloni", "Rinaldo Wander Montalvao"]
publication_types = ["2"]
abstract = ""
selected = true
publication = "*Proteins: Structure, Function, and Bioinformatics*"
url_pdf = "http://doi.wiley.com/10.1002/prot.25652"
doi = "10.1002/prot.25652"
+++

---

## In a nutshell
In this paper we propose a method for protein conformational analyses based on differential geometry(DG) representation of protein backbone. This representation presents the main advantages of atomic coordinates, $\phi- \psi$ angles and collective variables, while avoiding the main bottlenecks of these popular representations. The main DG advantages are:

  1. avoiding the superposition problem
    * the necessity of structural superposition is the main drawback of the usage of atomic coordinates
  2. avoiding non-flat space topologies
    * the periodic nature of $\phi-\psi$ angles impose a non-flat topology that impose some difficulties to the analyses, especially for conformational clustering.
  3. be intuitive and general mathematical representation
    * the notion of changes in curvature and torsion are intuitive to humans, such as some collective variables, but still applicable to every protein, unlike the more intuitive collective variables.

Based on this DG representation we propose:

  * A new metric of protein flexibility, $d_{max}$
  * A new method of global clustering based on residues local features
  * A new method to compare protein conformations.

By comparing to other standard techniques and applying to two extreme scenarios of the protein flexibility spectrum (a rigid and an intrinsically unstructured protein conformational ensemble), we demonstrate how such methods presents superior or equally good results than the standard techniques and can substitute and/or complement such methods on flexibility analyses.

---

## Implications ##
This findings are interesting for:
  * Intrinsically unstructured proteins analyses
    * In this extreme flexibility scenario a good superposition solution is hard or not even possible. By avoiding the superposition problem, DG is especially handy for the analyses of such cases.
  * Analyses to residues relation to global dynamics
    * To the best of my knowledge there is no clustering method that relates intuitively and straightforward local residues motion to global dynamics and the proposed method is a completely new tool at the computational structural biologist toolbox.
  * Measurement of protein flexibility
    * Is important to have an absolute measurement of local flexibility, especially one that does not rely on the superposition solution. This new characterization can be a new tool to compare different proteins and a helpful tool on studying the role of sequence-structure-dynamics relationships, such as comparing flexibility on the evolution of proteins  
  * Mathematical representation of conformational phase space
    * 

---
