# PoCs to own CVEs

## CVE-2021-27568 - json-smart DoS

All known versions of json-smart, to be more precise json-smart-v1 till v.1.3.1 (Oct 23, 2015)  and json-smart-v2 till v.2.4 (Mar 26, 2017)
have an Uncaught Exception leading to a Denial-of-Service (DoS) in Applications which are not build to catch the NumberFormatException on their own.

Known Affected (other) Products:

[jsonrpc2-base](https://bitbucket.org/thetransactioncompany/json-rpc-2.0-base)
till Version 1.38.2.

[json-rpc-2.0-server](https://bitbucket.org/thetransactioncompany/json-rpc-2.0-base)
 till Version 1.12.
 
[json-rpc-2.0-client](https://bitbucket.org/thetransactioncompany/json-rpc-2.0-base)
 till Version 1.16.5.
