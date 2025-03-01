### Collection of PoC credentials extraction scripts

Credentials storage in local files without encryption is insecure and creates the risk that these credentials will be stolen through malicious campaigns.

This repository contains scripts and macros proving the user credentials extraction from known/predictable locations is possible. 

Scripts are deliberately not optimised for prod to avoid usage in the real attacks, but only as the PoC to encourage the secure implementation of user credentials storages.

#### MS Office macro

* macros/send_cloud_creds.txt - sends AWS, GCP and Azure cli/sdk credentials in mail body via Outlook
* macros/send_vault_creds.txt - sends Hashicorp Vault cli/sdk credentials in mail body via Outlook
* macros/send_localstorage.txt - zips Chrome LocalStorage contents and sends the zipped folder via Outlook
* macros/send_sessionstorage.txt - zips and sends Chrome SessionStorage contents
* macros/send_indexeddb.txt - zips and sends Chrome IndexedDB contents