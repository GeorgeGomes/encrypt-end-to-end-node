# Encriptação ponta a ponta com Node

Com o openssl crie as chaves publicas e privadas

$ openssl genrsa -out ./private_key.pem 2048
$ openssl rsa -in ./private_key.pem -pubout -out ./public_key.pem


Utilize o index.js para brincar com a criptografia das chaves.


Fontes que podem ajudar:
https://coolaj86.com/articles/asymmetric-public--private-key-encryption-in-node-js
