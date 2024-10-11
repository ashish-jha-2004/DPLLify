# DPLLify

# SAT Solver Using DPLL Algorithm

This project is an implementation of a SAT (Boolean Satisfiability Problem) solver using the DPLL (Davis-Putnam-Logemann-Loveland) algorithm. The solver processes Boolean formulas in Conjunctive Normal Form (CNF) and determines whether they are satisfiable (SAT) or unsatisfiable (UNSAT).

## Table of Contents

- [Overview](#overview)
- [Features](#features)


## Overview

The SAT Solver implemented here uses the DPLL algorithm to recursively simplify and solve CNF formulas. It reads the input in DIMACS format, which is commonly used for SAT problems. The solver performs unit propagation and applies heuristic-based decisions to find a satisfying assignment for the formula or prove its unsatisfiability.

## Features

- **DPLL Algorithm**: Efficient SAT solving using recursive backtracking and unit propagation.
- **Unit Propagation**: Simplifies clauses and reduces problem size.
- **Literal Frequency Heuristics**: Chooses the next literal based on frequency and polarity to improve efficiency.
- **Handles DIMACS Format**: Can read standard CNF formula format.
- **Satisfiability Check**: Outputs either SAT or UNSAT, along with the satisfying assignment for literals if SAT is found.

