# Linux Users, Groups, and Permissions

## Objective
Learn Linux account management, group membership, file ownership, permissions, and least privilege.

## Environment
- Operating system: Ubuntu Server
- Virtualization: VirtualBox
- Lab user: `labuser`
- Lab group: `securitylab`

## Tasks Completed
- Inspected user IDs and group membership using `id`
- Created a separate Linux user
- Created a security lab group
- Assigned group ownership using `chown`
- Changed file permissions using `chmod`
- Tested access as a separate user
- Observed how Linux denies unauthorized file access

## Security Findings
File ownership, group membership, and permission settings determine who can access a resource. Restricting access helps protect confidential information and supports the principle of least privilege.

## Evidence to Collect
- Output of `id labuser`
- Output of `ls -ld /srv/securitylab`
- Output of `ls -l /srv/securitylab/test.txt`
- Successful and unsuccessful file-access tests

## Remediation
Apply the minimum permissions necessary, avoid unnecessary administrative privileges, and verify file ownership and permissions regularly.
