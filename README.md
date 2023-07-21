
c2-user@ip-172-31-34-177 vert-app % brew unlink openssl && brew link openssl --
force
Unlinking /usr/local/Cellar/openssl@3/3.1.1_1... 5548 symlinks removed.
Linking /usr/local/Cellar/openssl@3/3.1.1_1... 5548 symlinks created.
ec2-user@ip-172-31-34-177 vert-app % npm install -g npm 
npm ERR! code UNABLE_TO_GET_ISSUER_CERT_LOCALLY
npm ERR! errno UNABLE_TO_GET_ISSUER_CERT_LOCALLY
npm ERR! request to https://registry.npmjs.org/npm failed, reason: unable to get local issuer certificate

npm ERR! A complete log of this run can be found in: /Users/ec2-user/.npm/_logs/2023-07-21T18_25_22_701Z-debug-0.log
