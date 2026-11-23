# INKA SENSE: Cattle Health Monitoring and Early Disease Alert System

**Name:** Oganze Venusse 

**Student ID:** 28518

**Course:** INSY 8311, Database Development with PL/SQL

**Instructor:** Eric Maniraguha

## Problem statement
Rising meat and milk prices make every lost cow costly. Farmers often notice disease late, so it spreads through the herd before treatment starts. Sensor readings exist but are not stored, linked to treatments, or used to trigger early alerts.

## Objectives
**Main:** Build an Oracle PL/SQL database that stores cattle sensor readings, diagnoses, and treatments, and raises early disease alerts.

**Specific:**
1. Store readings per cow and per device in a normalized (3NF) schema.
2. Calculate a disease-risk score with a PL/SQL function.
3. Raise automatic alerts with triggers when readings are abnormal.
4. Block milk sales during antibiotic withdrawal periods.

## Data source
MmCows: A Multimodal Dataset for Dairy Cattle Monitoring (Vu et al., NeurIPS 2024). https://github.com/neis-lab/mmcows. Licence: CC BY-NC-SA 4.0 (non-commercial, educational use allowed).

## Innovation
Advanced analytics: a risk score from sensor data, shown on <tool, e.g. Python/Streamlit or Power BI>.

## Planned tables
farm, cow, sensor_device, reading, disease, diagnosis, treatment, medication, vet, milk_collection, alert

## Planned PL/SQL features
- Trigger: blocks milk collection from a cow in antibiotic withdrawal.
- Trigger: creates an alert when a reading is out of range.
- Function: calculates the disease-risk score.
- Procedure: records a diagnosis and starts a treatment.
- Cursor: per-farm health report.
- Package: groups the cattle health procedures and functions.
- Scheduled job: flags at-risk cows each night.

## References
<APA references, only sources you have actually read>
