# SSL or TLS in Plain English

----

## Introduction

Applications require security in our digital world. This is where certificates come into use. Secure Sockets Layer (SSL) and its successor Transport Layer Security are digital documents that encrypt traffic between a client and server. Although SSL and TLS are used interchangeably, TLS is the successor to SSL and issued by Certificate Authorities (CA) or can be self-signed, which is used primarly for testing purposes. CAs are the entities which provision certificates, and gurantee TLS certificates are distributed for specific uses cases and  validation layers as listed below:

----
- Domain Validation (DV)
 -confirms control of a domain name not the website itself
- Organization Validated (OV)
 - company is vetted to prove legitimacy.
-Extend Validation
 - Highest level of validation, used by finanical institutions to prove legitimacy, ===green lock=== displayed on browser page
