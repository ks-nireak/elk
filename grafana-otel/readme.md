generate self-signed certificate

```bash
openssl req -new -x509 -keyout collector.key -out collector.crt -nodes



openssl x509 -in collector.crt -out collector.pem


```