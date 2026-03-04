# Stochastic Supply Chain Optimization using Markov Decision Processes

## Overview

This project studies a stochastic inventory control problem in supply chain management using Markov Decision Processes (MDP). The objective is to determine optimal ordering policies under uncertain demand.

The model compares an optimized policy obtained through dynamic programming with a naive inventory policy.

## Methods

The following methods are implemented:

- Stochastic demand modeling using Poisson distribution
- Markov Decision Process formulation
- Value iteration for policy optimization
- Monte Carlo simulation for policy evaluation
- Service level analysis

## Model

State:
Inventory level

Action:
Order quantity

Demand:
Random demand following Poisson distribution

Transition:
Inventory evolves based on order and realized demand.

## Results

The optimized policy significantly reduces inventory cost compared to naive ordering strategies.

Key outputs include:

- Optimal ordering policy
- Policy cost comparison
- Monte Carlo cost distribution
- Service level performance

## Repository Structure
