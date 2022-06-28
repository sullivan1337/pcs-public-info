## Used to test Prisma Cloud DNS based Anomaly polcies.

### Usage

#### To just run script
Example `bash <(curl -s http://mywebsite.example/myscript.txt)`

DGA:
```
bash <(curl -s https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/dga-domains.sh)
```

Crypto:
```
bash <(curl -s https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/crypto-mining.sh)
```

#### To download script and run
**DGA**:
Download:
```
wget https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/dga-domains.sh
```
Run: 
`bash dga-domains.sh`

**Crypto**: 
Download:
```
wget https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/crypto-mining.sh
```
Run:
`bash crypto-mining.sh`