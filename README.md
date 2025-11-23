# ansible-stig-rocky9  
DISA STIG-hardened Rocky Linux 9 golden image – fully automated with Ansible + OpenSCAP

Perfect for DoD IL4/IL5/IL6, Platform One, Big Bang, and tactical-edge / air-gapped deployments.

### One-command demo
```bash
vagrant up                  # builds Rocky 9 VM + applies full STIG
vagrant ssh -c "cat /etc/system-fips"   # proves FIPS enabled
open report.html            # beautiful compliance report
Features

180+ DISA STIG controls applied automatically
FIPS 140-2 enabled
Root login disabled, 15-char complex passwords
Full OpenSCAP scan + HTML report
100% offline capable
