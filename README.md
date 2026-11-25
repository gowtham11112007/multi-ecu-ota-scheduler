# Multi-ECU OTA Update Scheduler

A web-based simulator and scheduler for Multi-ECU Over-The-Air (OTA) firmware updates.

## Features
- **Partial-Order Scheduling**: Models dependencies across ECUs as a directed acyclic graph (DAG).
- **Resource Constraints**: Dynamically allocates tasks within maximum concurrent flash sessions ($k$).
- **Critical-Path Prioritization**: Optimizes makespan using critical-path ranking for ready tasks.
- **Atomic Grouping & Rollback**: Groups ECUs that must commit together, generating an automated rollback plan in reverse completion order.
- **Interactive Gantt Chart**: Visualizes parallel flash slots and execution timelines.

## Getting Started
Open `index.html` in any modern web browser or deploy as a static site.
