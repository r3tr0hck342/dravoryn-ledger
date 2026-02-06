# offline_ssh_setup

## Purpose
Document offline OpenSSH bundles and bootstrap automation for passwordless SSH when the directory exists.

## Prereqs
- Access to `offline_ssh_setup/` (not present in this repo snapshot).
- Target hosts that need offline OpenSSH setup.

## Steps
1. Obtain the `offline_ssh_setup/` folder from the authoritative source or another branch.
2. Review any bootstrap scripts (e.g., `bootstrap_passwordless_ssh.sh`) for required parameters.
3. Run the bootstrap script against the target hosts as instructed.

## Verification
- Passwordless SSH works between the controller and target hosts.
- OpenSSH packages match expected versions.

## Troubleshooting
- If the directory is missing, verify it exists in a different branch or repository.
- If SSH setup fails, confirm host keys, permissions, and network access.

## References
- [README.md](../../README.md)
