### Collection of PoC credentials extraction scripts

Credentials storage in local files without encryption is insecure and creates the risk that these credentials will be stolen through malicious campaigns.

This repository contains scripts and macros proving the user credentials extraction from predictable locations is possible.

### MS Office macro

* macros/send_cloud_creds.txt - sends AWS, GCP and Azure cli/sdk credentials through Outlook mail client
* macros/send_vault_creds.txt - sends Hashicorp Vault cli/sdk credentials
* macros/send_localstorage.txt - sends Chrome LocalStorage contents
* macros/send_sessionstorage.txt - sends Chrome SessionStorage contents
* macros/send_indexeddb.txt - sends Chrome SessionStorage contents