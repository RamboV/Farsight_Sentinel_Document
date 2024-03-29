# Farsight DNSDB Connector

Farsight Security DNSDB® is the world’s largest DNS intelligence database that provides a unique, fact-based, multifaceted view of the configuration of the global Internet infrastructure. DNSDB leverages the richness of Farsight’s Security Information Exchange (SIE) data-sharing platform and is engineered and operated by leading DNS experts. Farsight collects Passive DNS data from its global sensor array. It then filters and verifies the DNS transactions before inserting them into the DNSDB, along with ICANN-sponsored zone file access download data. The end result is the highest-quality and most comprehensive DNS intelligence data service of its kind - with more than 100 billion DNS records since 2010.

## Pre-requisites
You will need the following to proceed:
* A Microsoft Power Apps or Power Automate plan with custom connector feature
* An Azure subscription
* Farsight DNSDB API Key

## Supported Operations
The connector supports the following operations:
* `Retrieve DNSDB’s RRset index information for domain`: The “rrset” lookup queries DNSDB’s RRset index, which supports “forward” lookups based on the owner name of an RRset.
* `Retrieve DNSDB’s Rdata index information for IP address`: The “rdata” lookup queries DNSDB’s Rdata index, which supports “inverse” lookups based on Rdata record values.
* `Retrieve DNSDB’s Rdata index information for domain`: The “rdata” lookup queries DNSDB’s Rdata index, which supports “inverse” lookups based on Rdata record values.

## Support and documentation: 
For all the support requests and general queries you can contact support@farsight.com or visit [contact-us](https://www.farsightsecurity.com/about-farsight-security/contacts/)
