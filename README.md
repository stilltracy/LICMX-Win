# LICMX-Win

LICMX is a system to boost inter-domain communication between Xen domains.  LICMX-Win is a virtual Network Interface Driver for Windows HVM domains.  After installing LICMX-Win on a Windows HVM domains, inter-domain communication traffic on the same node no longer needs domain0 to coordinate, thus greatly improving thoughput.

According to our evaluation results, Windows HVM domains with LICMX-Win enabled can achieve up to 13x thoughput improvement over PV-on-HVM driver. 


