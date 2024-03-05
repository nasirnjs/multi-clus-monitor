`cfssl gencert -initca ca-csr.json | cfssljson -bare ca`
`cfssl gencert -ca=ca.pem -ca-key=ca-key.pem -config=ca-config.json -profile=demo receiver-csr.json | cfssljson -bare receiver`
`cfssl gencert -ca=ca.pem -ca-key=ca-key.pem -config=ca-config.json -profile=demo prometheus-csr.json | cfssljson -bare prometheus`


`cfssl gencert -ca=ca.pem -ca-key-ca-key.pem -config=ca-config.json -profi le-demo receiver-csr.json | cfssljson -bare receiver`