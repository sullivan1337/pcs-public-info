## Used to test Prisma Cloud DNS based Anomaly polcies.

### Usage

From a monitored instance execute the following instructions to generate Prisma Cloud DNS anomalies.

#### To just run script

DGA domain request activity:
```
bash <(curl -s https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/dga-domains.sh)
```

Cryptomining domain request activity:
```
bash <(curl -s https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/crypto-mining.sh)
```

AWS metadata rebind
```
bash <(curl -s https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/aws-metadata-rebind.sh)
```

#### To download script and run
**DGA domain request activity**:

Download:
```
wget https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/dga-domains.sh
```
Run: 
`bash dga-domains.sh`

**Cryptomining domain request activity**: 

Download:
```
wget https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/crypto-mining.sh
```
Run:
`bash crypto-mining.sh`

**AWS metadata rebind**: 

Download:
```
wget https://raw.githubusercontent.com/sullivan1337/pcs-public-info/main/Testing%20DNS%20Anomaly%20Policies/aws-metadata-rebind.sh
```
Run:
`bash aws-metadata-rebind.sh`
