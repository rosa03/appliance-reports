---
title: Appliance Executive Status Report
report_date: 2026-07-08
prepared_by: Rosa Salih
current_phase: Build
target_go_live: 2027-04-01
forecast_confidence: Medium
exec_decision_needed: No
overall_status: Amber
status_key:
  green: On track
  amber: At risk / needs attention
  red: Off track / decision or action required
---

# Appliance Executive Status Report

| Field | Value |
|---|---|
| Report date | 2026-07-08 |
| Prepared by | Rosa Salih |
| Current phase | Build |
| Target go-live | 01/04/2027 |
| Forecast confidence | Medium |
| Exec decision needed | No |
| Overall status | Amber |

## Executive Summary

The Edge layer is progressing well and is entering validation for the core components. The programme remains at risk due to delays and uncertainty within the cloud layer, especially around AWS procurement timelines. Senior stakeholders are engaged to help accelerate progress.

## Category Scorecard

| Category | Sub-category | Status | Headline |
|---|---|---|---|
| Edge | Cooling | Green | Basic cooling functionality is progressing well with control now integrated across the main cooling components, putting the system in a strong position for end-to-end validation. |
| Edge | Volume | Green | Volume is in early development. We can read pressure and activate the pump to keep keg pressure around 120 kPa, but inputs are still required from the Product/System team for the estimation algorithm. |
| Edge | Connectivity | Red | Connectivity is blocked, waiting on the cloud layer. |
| Edge | Security | Amber | Meeting scheduled on 2026-07-13 with the Solutions team to confirm key priorities, status, and ownership of compliance work. |
| Cloud layer |  | Red | AWS is going through procurement, and VPs are involved to accelerate the process. |
| Service layer |  | Red | RFP not created yet. |

## Architecture / Service View

<!-- Add or link to the current architecture/service diagram here. Example: -->
<!-- ![Appliance architecture diagram](../../assets/appliance-architecture.png) -->

## Actions, Decisions, and Risks

| Item | Type | Owner | Due date | Exec ask / next step |
|---|---|---|---|---|
| If the procurement process for AWS takes too long, then there will be a delay in the completion of the cloud layer MVP. | Risk | Richard |  | Stevie to try to get Amazon to pay for the first stages in credits so that the work can start earlier. VPs to accelerate the process. |
| If the RFP is not created soon, then the service layer might not be ready in time for the beta phase. | Risk | Richard | TBC |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

## Status Notes

### Edge - Cooling

- Status: Green
- Notes: Basic cooling functionality is progressing well with control now integrated across the main cooling components, putting the system in a strong position for end-to-end validation.

### Edge - Volume

- Status: Green
- Notes: Volume is in early development. We can read pressure and activate the pump to keep keg pressure around 120 kPa, but inputs are still required from the Product/System team for the estimation algorithm.

### Edge - Connectivity

- Status: Red
- Notes: Connectivity is blocked, waiting on the cloud layer.

### Edge - Security

- Status: Amber
- Notes: Meeting scheduled on 2026-07-13 with the Solutions team to confirm key priorities, status, and ownership of compliance work.

### Cloud Layer

- Status: Red
- Notes: AWS is going through procurement, and VPs are involved to accelerate the process.

### Service Layer

- Status: Red
- Notes: RFP not created yet.

## Decision Log

| Date | Decision | Owner | Outcome / Rationale |
|---|---|---|---|
| 2026-07-08 | Escalate AWS procurement through VP engagement. | Richard / leadership | Intended to accelerate cloud layer progress and reduce risk to the MVP timeline. |

## Change Log

| Date | Change | Made by |
|---|---|---|
| 2026-07-08 | Report added to repository from original PDF source | Rosa Salih |
