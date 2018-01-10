---
### Title: install-splunk-uf.yml
#### Description: A playbook to install the Splunk UF on a Debian-based Linux machine
---

The following playbook makes a few assumptions:

  1. A hosts file contains a group called splunk-uf with the relevant machines defined
  2. The user account with which the playbook is being run under (in this example, root) has sudo rights
  3. a folder called 'files' is created which contains the source binaries
  4. The variables defined in the vars section applies to your environment
