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

### Setting up the NeoLoad Tricentis Tosca Add-on

1. Download the latest Advance Action jar [latest release](https://github.com/Neotys-Labs/SAP_RFC/releases/tag/sap_RFC-0.0.2).
   Keept the Jar file in the extlib folder of yor Neoload Project

3. Download the External Refereces files from floder (https://github.com/Neotys-Labs/SAP_RFC/tree/main/ExternalReferences)
   keep sapjco3.jar in Jar file in the extlib folder of yor Neoload Project
   keep sapjco3.dll file <Neoload Installation folder>\lib\x64

4. restart neoload
## Advanced Actions definitions
### SAP_RFC

This Advanced Action establishes a connection with server & make RF calls based on your inputs
Example:
<p align="center"><img src="/screenshot/sap_rfc_reqdesign.PNG" alt="sap_rfc" /></p>
<p align="center"><img src="/screenshot/sap_rfc_response.PNG" alt="sap_rfc_response" /></p>


## ChangeLog

* Version 0.0.2 (June 10st 2024): perform Simple function calls Table & structure yet to implement

