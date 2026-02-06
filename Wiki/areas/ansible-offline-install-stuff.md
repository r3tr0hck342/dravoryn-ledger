# ansible-offline-install-stuff

## Purpose
Describe the offline Ansible controller bundle for Ubuntu 22.04 and how it should be used when present.

## Prereqs
- Access to the `ansible-offline-install-stuff/` directory (not present in this repo snapshot).
- Offline installation media and a target Ubuntu 22.04 controller.

## Steps
1. Obtain the `ansible-offline-install-stuff/` folder from the authoritative source or another branch.
2. Review included README or scripts in that folder for installation steps.
3. Execute the offline installation steps on the controller host.

## Verification
- Ansible is installed and executable on the controller host.
- Any bundled dependencies are present and correctly versioned.

## Troubleshooting
- If the directory is missing, confirm whether it exists on a different branch or in a private submodule.
- If installation fails, re-check the offline bundle integrity and OS compatibility.

## References
- [README.md](../../README.md)
