# Supply Chain Optimization in High-Tech Manufacturing

## Motivation
High-tech manufacturers face increasing pressure to build 
resilient supplier networks under uncertainty — balancing 
cost, lead time, quality and supply chain risk. This project 
applies data-driven optimization to supplier portfolio 
selection in a high-tech manufacturing context, inspired by 
real operational challenges in the semiconductor equipment 
industry.

## Research Question
How can Mixed Integer Linear Programming help identify optimal 
supplier portfolios that minimize supply chain risk within 
budget and coverage constraints?

## Project Structure
- `01_dataset_creation.ipynb` — Synthetic supplier dataset 
   (50 suppliers, 10 attributes including lead time, defect 
   rate, cost and criticality)
- `02_optimization_model.ipynb` — MILP optimization model 
   built with PuLP: minimizes total risk score subject to 
   budget and component coverage constraints
- `03_results_analysis.ipynb` — Results visualization and 
   analysis including supplier selection charts and risk 
   profile comparison

## Methods
| Element | Detail |
|---|---|
| Dataset | Synthetic supplier data — 50 suppliers, 10 attributes |
| Optimization | Mixed Integer Linear Programming (MILP) |
| Library | PuLP (Python) |
| Visualization | Matplotlib |
| Objective | Minimize supply chain risk (lead time × defect rate) |
| Constraints | Budget ≤ €500,000 · All component types covered |

## Key Results
- Optimal supplier portfolio identified from 50 candidates
- 4 suppliers selected covering all component types
- Mathematically proven optimal solution (PuLP CBC solver)
- Clear risk vs cost tradeoff visualized across full portfolio

The model demonstrates how data-driven optimization can support 
repair-or-replace decisions and supplier portfolio resilience — 
directly relevant to circular economy transitions in high-tech 
manufacturing.

## Relevance to Current Research
This work connects directly to circular supply chain design 
challenges in high-tech manufacturing — where supplier network 
decisions impact repairability, reuse potential and return 
logistics. The optimization and simulation approaches applied 
here align with active research into integrated product and 
chain design for circular high-tech ecosystems.

## Tools & Libraries
- Python 3.x
- Pandas — data manipulation
- NumPy — numerical operations  
- PuLP — linear and integer programming
- Matplotlib — visualization

## Author
Kuntay Akca

Supply Chain Project Manager, ASML

MSc Industrial Engineering

PhD Candidate Applicant - AI & Optimization in Supply Chain
