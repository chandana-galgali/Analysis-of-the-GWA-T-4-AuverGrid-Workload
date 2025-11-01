# Analysis-of-the-GWA-T-4-AuverGrid-Workload

## GWA-T-4 AuverGrid Workload Analysis

This repository contains Python scripts for analyzing the GWA-T-4 AuverGrid workload trace (anon_jobs.db3). This analysis replicates standard workload characterization techniques used in systems and high-performance computing (HPC) research.

Using pandas for data manipulation and matplotlib for visualization, the scripts load the SQLite database and investigate two key areas:

- **Workload Characterization:** Plots the distribution of job runtimes and wait times on a log-log scale to understand the nature of the submitted jobs.
- **Resource Efficiency:** Calculates and plots the "memory utilization ratio" (requested vs. actual used memory) to quantify resource over-provisioning and system efficiency.
