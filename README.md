# OpenSSLCert
openssl req -x509 -out localhost.crt -keyout localhost.key -newkey rsa:2048 -nodes -sha256 <br/>
openssl pkcs12 -export -out nadir.p12 -inkey localhost.key -in localhost.crt
