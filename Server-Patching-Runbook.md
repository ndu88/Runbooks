Server Patching Runbook
------------------------

Purpose
--------

This runbook defines the standard process for patching servers to maintain security, stability, and compliance while minimising service disruption.
_____________________________________________________________________________________________________________________________________________________________

Scope
------

Applies to:
  Windows Server environments
  Linux servers
  Virtualised infrastructure

_____________________________________________________________________________________________________________________________________________________________

1. Pre-Patching Preparation
-----------------------------

  Review patch advisories and security bulletins
  Confirm patch scope and applicability
  Validate backups are current
  Identify maintenance window and stakeholders
  Obtain change approval (CAB)

_____________________________________________________________________________________________________________________________________________________________

2. Testing
-----------

  Apply patches to test or non-production systems
  Validate application and service functionality
  Document test results

_____________________________________________________________________________________________________________________________________________________________

3. Production Deployment
-------------------------

  Apply patches according to approved schedule
  Monitor patch installation progress
  Reboot systems if required (as per change approval)

_____________________________________________________________________________________________________________________________________________________________

4. Post-Patching Validation
----------------------------


  Verify system availability
  Check service and application status
  Review logs for errors
  Confirm user-facing services are operational

_____________________________________________________________________________________________________________________________________________________________

6. Rollback & Remediation
---------------------------

  Execute rollback plan if required
  Escalate unresolved issues
  Perform root cause analysis for failures

  _____________________________________________________________________________________________________________________________________________________________
