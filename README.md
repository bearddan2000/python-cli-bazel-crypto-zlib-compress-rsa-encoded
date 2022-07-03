# python-cli-bazel-crypto-zlib-compress-rsa-encoded

## Description
Compare hashed passwords. RSA
is an asymmetric algorithm that
uses a 3072 bit key. Encryption is
done by public key while decryption
is by private key.

Since RSA generates a long encryption we use compression to store and/or transport.

## Tech stack
- bazel
- python 3.8

## Docker stack
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
https://cryptobook.nakov.com/asymmetric-key-ciphers/rsa-encrypt-decrypt-examples
