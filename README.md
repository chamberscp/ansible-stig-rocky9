# DISA STIG-Hardened Rocky Linux 9 – Ansible + OpenSCAP

Fully automated hardening of Rocky Linux 9 to the latest **DISA STIG** using Ansible and validated with OpenSCAP.

Perfect for **IL4/IL5/IL6**, **Platform One**, **Big Bang**, **tactical edge**, and **air-gapped** deployments.

## One-command demo
```bash
vagrant up          # Spins up Rocky 9 + runs full STIG playbook
vagrant ssh -c "sudo cat /etc/system-fips"   # Prove FIPS enabled
open report.html    # Beautiful compliance report
