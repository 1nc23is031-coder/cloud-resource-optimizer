# Automated Cloud Resource Optimization System

## Overview
This project simulates a cloud resource monitoring and optimization system.
It analyzes virtual machine (VM) activity and recommends actions to reduce idle cloud costs.

## Phase 1
- Single VM monitoring
- Idle time analysis
- STOP / KEEP RUNNING decision logic

## Phase 2
- Multi-VM handling
- Dashboard-style console output
- Summary statistics

## Technologies Used
- Python
- Google Cloud Platform
- Command Line Interface

## Purpose
To demonstrate cloud automation logic and resource optimization strategies.


## Sample Output

```
CLOUD RESOURCE OPTIMIZATION DASHBOARD
=================================================================
VM NAME        STATUS         IDLE TIME           RECOMMENDATION
-----------------------------------------------------------------
gcp-vm-1       RUNNING        0:45:00             STOP
gcp-vm-2       RUNNING        0:10:00             KEEP RUNNING
gcp-vm-3       STOPPED        N/A                 KEEP STOPPED
=================================================================
SUMMARY
VMs to STOP        : 1
VMs KEEP

