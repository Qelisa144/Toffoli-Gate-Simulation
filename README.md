# Quantum Circuit Equivalence — Toffoli Gate using U3 Parameters

**Made by:** Ana Elisa Franco
**Date:** October,24nd 2025  


## Overview
This project demonstrates how to reproduce the **Toffoli (CCX) gate** using a combination of **U3 gates** and **CNOTs**, proving **circuit equivalence** in quantum using a classical optimizer (SciPy) to train the parameters of a quantum circuit.

The code constructs:
- A reference Toffoli circuit.  
- A parameterized circuit using two U3 gates.  
- An optimization routine that adjusts parameters to minimize the difference between the two.