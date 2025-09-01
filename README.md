# Combat Strategy Simulation

A Python-based simulation for analyzing optimal combat strategies in group battles using game theory principles. This project explores how different resource allocation and targeting strategies affect battle outcomes.

## Overview

This simulation models combat between two armies with customizable:
- Resource allocation types (balanced, offensive, defensive, special forces, mixed)
- Attack strategies (random, focus high-value, focus low-defense,分散攻击, mixed strategy)
- Unit sizes (from 10 to 100 units)

## Key Features

- **Combat Unit System**: Each unit has attack, defense, and impact attributes
- **Multiple Strategies**: 5 resource allocation types and 5 attack strategies
- **Battle Simulation**: Realistic combat resolution with damage calculation
- **Statistical Analysis**: Large-scale Monte Carlo simulations for reliable results
- **Visualization**: Heatmaps and trend charts to identify optimal strategies

## Installation & Requirements

```bash
pip install numpy matplotlib seaborn tqdm
