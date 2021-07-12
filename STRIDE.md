David Armstrong 10-29-2020

Threat modeling is a good practice for any situation where security is a concern. And with the prevalence of cyber attacks high and on the rise, it should be a concern to any organization, small or large. One of the methods is STRIDE. This stands for the following:

**Spoofing:** This is the act of purporting to be someone, or something, that you are not. This is commonly done through authentication. While this is simplest with a single key authentication, it is also possible (while less feasible) with access tokens and signature based authentication.

**Tampering:** This is the altering of data in some way (dealing with integrity). This could be logged, although one form of tampering actually involves the altering of log files themselves, thus making it hard to determine if tampering has actually taken place.

**Repudiation:** Repudiation refers to techniques which are implemented to ensure that an attack cannot be proven. These actions are targeted at auditing and tracing.

**Information Disclosure:** ID or loss of data is a concern for any organization, whether that be proprietary information or PII. This can be due to poor care for the safety of data in offsite locations, or possibly lack of security through firewall or encryption.

**Denial of Service:** Flooding a computer or system with a large number of requests, effectively bringing down the system. 

**Elevation of Privilege:** not to be confused with authentication, elevation has to do with authorization. With an elevated status, an attacker can perform more tasks which will produce more data or render a more severe attack on the system.
