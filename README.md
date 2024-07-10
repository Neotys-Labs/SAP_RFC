# SAP_RFC

It’s a protocol used by SAP systems to  communicate and execute functions in remote systems (sap/external). Mainly used for dataexcahnge , system integartions & distributed computing.Its classified in to four types, synchronous RFC ,Assynchronus RFC , Transactional RFC & Queued RFC​.

## Overview

This repository contains NeoLoad Advanced Actions that allows performance testers using NeoLoad to connect SAP Server Server & make RF calls.
Implemeation is in progress.

| Property           | Value                                                                         |
|--------------------|-------------------------------------------------------------------------------|
| Maturity           | Experimental                                                                  |
| Support            | Supported by Neotys                                                           |
| Author             | Neotys                                                                        |
| License            | [BSD Simplified](https://www.neotys.com/documents/legal/bsd-neotys.txt)       |
| NeoLoad            | 6.5.1 (Enterprise or Professional Edition w/ Integration & Advanced Usage)    |
| Bundled in NeoLoad | No                                                                          |
| Download Binaries  | See the [latest release](https://github.com/Neotys-Labs/Ldap/releases/tag/ldap-0.0.1) |


## Installation

1. Download the [latest release](https://github.com/Neotys-Labs/Ldap/releases/tag/ldap-0.0.1)
1. Read the NeoLoad documentation to
   see [How to install a custom Advanced Action](https://www.neotys.com/documents/doc/neoload/latest/en/html/#25928.htm)

## Advanced Actions definitions
### SAP_RFC

This Advanced Action establishes a connection with server & make RF calls based on your inputs
Example:
<p align="center"><img src="/screenshot/sap_rfc_reqdesign.PNG" alt="sap_rfc" /></p>
<p align="center"><img src="/screenshot/sap_rfc_response.PNG" alt="sap_rfc_response" /></p>


## ChangeLog

* Version 0.0.2 (June 10st 2024): perform Simple function calls Table & structure yet to implement

