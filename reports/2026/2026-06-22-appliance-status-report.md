---
title: Appliance Executive Status Report
report_date: 2026-06-22
prepared_by: Rosa Salih
current_phase: Build
target_go_live: 2027-04-01
forecast_confidence: Medium
exec_decision_needed: No
overall_status: Red
status_key:
  green: On track
  amber: At risk / needs attention
  red: Off track / decision or action required
---

# Appliance Executive Status Report

| Field | Value |
|---|---|
| Report date | 2026-06-22 |
| Prepared by | Rosa Salih |
| Current phase | Build |
| Target go-live | 01/04/2027 |
| Forecast confidence | Medium |
| Exec decision needed | No |
| Overall status | Red |

## Executive Summary

The Firmware/Edge team is on track with core components, but the overall programme is at risk due to external blockers around cloud vendor selection.

## Category Scorecard

| Category | Sub-category | Status | Headline |
|---|---|---|---|
| Edge | Cooling | Green | Basic cooling functionality is progressing well with most core components being ready. |
| Edge | Volume | Green | Volume is in early development. Inputs are required from Product/System teams for the estimation algorithm. |
| Edge | Connectivity | Red | Connectivity is blocked, waiting on cloud layer. |
| Edge | Security | Amber | Security requires clearer ownership and evidence planning. CRA and European certification milestones fall in September so we need clarity to avoid late stage compliance risk. |
| Cloud layer |  | Red | AWS chosen by Business. Procurement requests have been kicked off and the team is currently getting them up to speed. Deadline for cloud layer selection was 08/06. |
| Service layer |  | Red | RFP not created yet. |

## Architecture / Service View

<!-- Add or link to the current architecture/service diagram here. Example: -->
<!-- ![Appliance architecture diagram](../../assets/appliance-architecture.png) -->

## Actions, Decisions, and Risks

| Item | Type | Owner | Due date | Exec ask / next step |
|---|---|---|---|---|
| If the procurement process for AWS takes too long, then there will be a delay in the completion of the cloud layer MVP. | Risk | Richard |  | Stevie and Richard are actively applying pressure on procurement. |
| If the RFP is not created soon, then the service layer might not be ready in time for the beta phase. | Risk | Richard | TBC |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

## Status Notes

### Edge - Cooling

- Status: Green
- Notes: Basic cooling functionality is progressing well with most core components being ready.

### Edge - Volume

- Status: Green
- Notes: Volume is in early development. Inputs are required from Product/System teams for the estimation algorithm.

### Edge - Connectivity

- Status: Red
- Notes: Connectivity is blocked, waiting on cloud layer.

### Edge - Security

- Status: Amber
- Notes: Security requires clearer ownership and evidence planning. CRA and European certification milestones fall in September, so clarity is needed to avoid late-stage compliance risk.

### Cloud Layer

- Status: Red
- Notes: AWS has been chosen by Business. Procurement requests have been kicked off and the team is currently getting them up to speed. The deadline for cloud layer selection was 08/06.

### Service Layer

- Status: Red
- Notes: RFP not created yet.

## Decision Log

| Date | Decision | Owner | Outcome / Rationale |
|---|---|---|---|
| 2026-06-22 | AWS chosen by Business for the cloud layer. | Business | Procurement requests kicked off; cloud layer progress remains at risk pending procurement progress. |

## Change Log

| Date | Change | Made by |
|---|---|---|
| 2026-06-22 | Initial report created from template | Rosa Salih |
| 2026-06-25 | Report added to repository from original PDF source | Rosa Salih |
