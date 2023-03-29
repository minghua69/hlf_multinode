- host2
	- ssh duck@140.123.179.50
- host3
	- ssh duck-2@140.123.179.23
    extra_hosts:
      - "orderer.example.com:140.123.179.50"
      - "peer0.org1.example.com:140.123.179.50"
      - "peer0.org2.example.com:140.123.179.23"
