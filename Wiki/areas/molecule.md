# molecule

## Purpose
Describe role testing via Molecule when a `molecule/` directory exists.

## Prereqs
- Access to `molecule/` (not present in this repo snapshot).
- Molecule and its dependencies installed on the controller.

## Steps
1. Obtain the `molecule/` directory from the authoritative source or another branch.
2. Run Molecule test scenarios as defined in that folder.
3. Review logs and artifacts for failures.

## Verification
- Molecule scenarios complete successfully.
- Role changes are validated in ephemeral or test environments.

## Troubleshooting
- If the directory is missing, verify if Molecule tests were moved into role folders.
- If tests fail, inspect scenario configuration and dependencies.

## References
- [README.md](../../README.md)
