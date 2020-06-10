# Introduction

The following advisories cover security issues discovered, or contributed, by
the team at [F-Secure](https://foundry.f-secure.com) Hardware Security Team,
previously known as [Inverse Path](https://inversepath.com).

| CVEs                                                                            | Description                                                      | Advisory
|---------------------------------------------------------------------------------|------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [CVE-2020-12789](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-12789) | ATSAMA5 hardcoded keys are used for protecting applets           | [Security_Advisory-Ref_FSC-HWSEC-VR2020-0003-ATSAMA5_code_authentication_issues.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2020-0003-ATSAMA5_code_authentication_issues.txt)                 |
| [CVE-2020-12788](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-12788) | ATSAMA5 CMAC verification susceptible to side channel attacks    | [Security_Advisory-Ref_FSC-HWSEC-VR2020-0003-ATSAMA5_code_authentication_issues.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2020-0003-ATSAMA5_code_authentication_issues.txt)                 |
| [CVE-2020-12787](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-12787) | ATSAMA5 improper applet verification                             | [Security_Advisory-Ref_FSC-HWSEC-VR2020-0003-ATSAMA5_code_authentication_issues.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2020-0003-ATSAMA5_code_authentication_issues.txt)                 |
| [CVE-2020-11684](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-11683) | AT91bootstrap code authentication bypass via key leak            | [Security_Advisory-Ref_FSC-HWSEC-VR2020-0002-AT91Bootstrap_code_authentication_issues.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2020-0002-AT91Bootstrap_code_authentication_issues.txt)     |
| [CVE-2020-11683](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-11684) | AT91bootstrap timing side channel in CMAC verification           | [Security_Advisory-Ref_FSC-HWSEC-VR2020-0002-AT91Bootstrap_code_authentication_issues.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2020-0002-AT91Bootstrap_code_authentication_issues.txt)     |
| [CVE-2020-10648](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-10648) | U-Boot verified boot bypass via improper signature verification  | [Security_Advisory-Ref_FSC-HWSEC-VR2020-0001-U-Boot_verified_boot_bypass.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2020-0001-U-Boot_verified_boot_bypass.txt)                               |
| [CVE-2019-5478](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-5478)   | Xilinx ZU+ Encrypt Only Secure boot bypass via partition header  | [Security_Advisory-Ref_FSC-HWSEC-VR2019-0001-Xilinx_ZU+-Encrypt_Only_Secure_Boot_bypass.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2019-0001-Xilinx_ZU+-Encrypt_Only_Secure_Boot_bypass.txt) |
| [CVE-2019-5478](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-5478)   | Xilinx ZU+ Encrypt Only Secure boot bypass via boot header       | [Security_Advisory-Ref_FSC-HWSEC-VR2019-0001-Xilinx_ZU+-Encrypt_Only_Secure_Boot_bypass.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_FSC-HWSEC-VR2019-0001-Xilinx_ZU+-Encrypt_Only_Secure_Boot_bypass.txt) |
| [CVE-2018-18440](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-18440) | U-Boot verified boot bypass via network load                     | [Security_Advisory-Ref_IPVR2018-0001-U-Boot_verified_boot_bypass.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_IPVR2018-0001-U-Boot_verified_boot_bypass.txt)                                               |
| [CVE-2018-18439](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-18439) | U-Boot verified boot bypass via filesystem load                  | [Security_Advisory-Ref_IPVR2018-0001-U-Boot_verified_boot_bypass.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_IPVR2018-0001-U-Boot_verified_boot_bypass.txt)                                               |
| [CVE-2017-7936](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-7936)   | NXP High Assurance Boot SDP protection bypass                    | [Security_Advisory-Ref_QBVR2017-0001-NXP_HAB_bypass.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_QBVR2017-0001-NXP_HAB_bypass.txt)                                                                         |
| [CVE-2017-7932](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-7932)   | NXP High Assurance Boot X.509 parsing error                      | [Security_Advisory-Ref_QBVR2017-0001-NXP_HAB_bypass.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_QBVR2017-0001-NXP_HAB_bypass.txt)                                                                         |
| [CVE-2016-8672](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-8672)   | Siemens SIMATIC missing cookie protection                        | [SSA-603476](https://github.com/inversepath/advisories/blob/master/ssa-603476.pdf)                                                                                                                                                             |
| [CVE-2016-8673](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-8673)   | Siemens SIMATIC cross-site request forgery                       | [SSA-603476](https://github.com/inversepath/advisories/blob/master/ssa-603476.pdf)                                                                                                                                                             |
| [CVE-2016-1734](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-1734)   | AppleUSBNetworking memory corruption                             | [Security_Advisory-Ref_IPVR2016-0001_AppleUSBNetworking_memory_corruption.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_IPVR2016-0001_AppleUSBNetworking_memory_corruption.txt)                             |
| [CVE-2008-3908](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2008-3908)   | WordNet stack and heap overflows                                 | [Security_Advisory-Ref_oCERT-2008-014-WordNet_stack_overflows.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_oCERT-2008-014-WordNet_stack_overflows.txt)                                                     |
| [CVE-2008-1530](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2008-1530)   | GnuPG memory corruption                                          | [Security_Advisory-Ref_oCERT-2008-001-GnuPG_memory_corruption.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_oCERT-2008-001-GnuPG_memory_corruption.txt)                                                     |
| [CVE-2003-0962](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2003-0962)   | rsync heap-based buffer overflow                                 | [Security_Advisory-Ref_GLSA200312-03-rsync_heap_overflow.txt](https://github.com/inversepath/advisories/blob/master/Security_Advisory-Ref_GLSA200312-03-rsync_heap_overflow.txt)                                                               |
