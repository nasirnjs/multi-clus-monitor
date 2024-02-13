
`cfssl gencert -ca=ca.pem -ca-key-ca-key.pem -config=ca-config.json -profi le-demo receiver-csr.json | cfssljson -bare receiver`