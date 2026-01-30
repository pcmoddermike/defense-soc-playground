# KQL Detections

This directory contains Kusto Query Language (KQL) detection queries designed for SOC and detection engineering use cases.

## Scope
- Endpoint and process execution detections
- Script-based activity (PowerShell, command-line)
- Living-off-the-Land (LOLBins) abuse
- Behavioral detections based on Microsoft Defender telemetry

## Assumptions
- Queries are written with Microsoft Defender and Sentinel-style logs in mind
- Log availability and schema may vary by environment
- Detections focus on logic clarity and explainability over environment-specific tuning

## Detection Standards
Each detection should include:
- A clear detection objective
- Associated MITRE ATT&CK technique(s)
- Notes on expected false positives
- Tuning or evasion considerations

