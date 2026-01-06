Purpose
-------

This runbook ensures that backups are successfully completed, verifiable, and auditable to support disaster recovery and business continuity objectives.

_____________________________________________________________________________________________________________________________________________________________

## KPI & Framework Alignment

| Area | Alignment |
|-----|----------|
| Key Performance Area (KPA) | Backup & Recovery |
| Supporting KPIs | Backup success rate, restore test completion |
| ITIL v4 Practice | IT Service Continuity Management |
| COBIT 2019 Domain | DSS04 – Manage Continuity |
| SFIA Skill | ITOP – IT Infrastructure Operations |
| Evidence Produced | Backup reports, restore test results, audit evidence |


Scope
-----
Applies to:

  Servers protected by Commvault
  Critical application servers
  File servers and databases (as applicable)
  _____________________________________________________________________________________________________________________________________________________________

1. Daily Backup Verification
-----------------------------

Review Commvault backup job status

Check Windows Event Logs for:
    Backup completion
    Warnings or errors
Confirm last successful backup timestamp

_____________________________________________________________________________________________________________________________________________________________

2. Weekly Review
-----------------

  Identify repeated backup warnings or failures
  Confirm backup coverage for newly deployed servers
  Validate backup retention policies

_____________________________________________________________________________________________________________________________________________________________

3. Monthly Audit Evidence
--------------------------

  Export backup verification results
  Store evidence securely for audit purposes
  Review backup trends and failure patterns

_____________________________________________________________________________________________________________________________________________________________

4. Restore Testing (Quarterly)
------------------------------

  Select representative systems for test restores
  Validate data integrity
  Document restore outcomes
  Address gaps or failures

  _____________________________________________________________________________________________________________________________________________________________

5. Escalation & Remediation
---------------------------

  Escalate unresolved failures to backup administrators or vendors
  Track remediation actions
  Confirm resolution

_____________________________________________________________________________________________________________________________________________________________
