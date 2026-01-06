Aligned KPIs
Incident & Problem Management
Maintain Stable Infrastructure
ITIL4 Incident Management
COBIT DSS01
SFIA ITOP
_____________________________________________________________________________________________________________________________________________________________

Incident Response Checklist
---------------------------

Purpose
-------

This runbook provides a standardised approach for responding to server-related incidents to minimise downtime, restore services within SLA, and ensure proper escalation and documentation.

## KPI & Framework Alignment

| Area | Alignment |
|-----|----------|
| Key Performance Area (KPA) | Incident & Problem Management |
| Supporting KPIs | % incidents resolved within SLA, MTTR |
| ITIL v4 Practice | Incident Management |
| COBIT 2019 Domain | DSS01 – Manage Operations |
| SFIA Skill | ITOP – IT Infrastructure Operations |
| Evidence Produced | Incident logs, escalation records, resolution documentation |


Scope
------

Applies to:

Windows and Linux servers
Virtualised workloads (VMware)
Core infrastructure services (AD, M365, backup, storage)


1. Incident Identification
---------------------------

  Confirm incident source (monitoring alert, Service Desk ticket, user report)
  Identify affected system(s) and services
  Confirm business impact and urgency
_____________________________________________________________________________________________________________________________________________________________

2. Initial Assessment
----------------------

  Check system availability (ping, service status)
  Review recent changes (patches, configuration, deployments)
  Validate scope (single system vs multiple systems)

_____________________________________________________________________________________________________________________________________________________________

3. Immediate Actions
---------------------

  Restart affected services only if approved
  Isolate affected system if security-related
  Apply temporary workaround if available
  Preserve logs and evidence
_____________________________________________________________________________________________________________________________________________________________

4. Escalation
--------------

Escalate to relevant teams if required:

  Network
  Storage
  Security
  Application owners
Notify stakeholders if SLA breach is likely

_____________________________________________________________________________________________________________________________________________________________

5. Resolution & Recovery
-------------------------

  Implement approved fix
  Verify system stability
  Confirm service restoration with stakeholders
  Monitor system post-resolution
_____________________________________________________________________________________________________________________________________________________________

6. Documentation & Closure
---------------------------

  Update incident ticket with:
    Root cause (if known)
    Resolution steps
    Preventive actions

Identify follow-up actions or problem record if required


