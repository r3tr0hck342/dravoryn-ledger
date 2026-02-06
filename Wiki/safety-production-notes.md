# Safety / Production Notes

## Purpose
Capture operational cautions and guardrails for production usage.

## Prereqs
- Access to production change-management or approvals processes.
- Familiarity with the repository’s intended usage (see README).

## Steps
1. **Change control:** Ensure any automation or scripts are executed under your organization’s change-approval process.
2. **Dry runs first:** If tooling supports dry runs or linting, use them to validate changes before production execution.
3. **Least privilege:** Run automation with the minimum required privileges and access scopes.
4. **Backups and rollback:** Verify backups exist and rollback steps are documented before modifying production systems.
5. **Audit logging:** Capture logs of executions and retain them per policy.

## Verification
- Confirm there is a rollback or remediation path for each production change.
- Confirm logs are available for all production runs.

## Troubleshooting
- If a run fails in production, stop further changes and triage using logs and test environments first.
- If policy constraints block a run, coordinate with security and operations teams to resolve.

## References
- [README.md](../README.md)
