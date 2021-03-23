# Symmetric key cryptography

## Types
* Stream Ciphers
* Block Ciphers

## Steam Ciphers 
Use a fix length key to produce a pseudo random stream of bits
` Same key gets you same stream`
XOR those bits with your PT/CT in order to encrypt

The Goal: tries to approximate a one-time-pad

### Real word
* RC4 `example WEP wireless network security`
* A5/1 `example GSM phone data`

## Block Ciphers
Use a fix length key to encrypted a fixed length block of data.
### Real word
* DES `using 64-bit for the blocksize and 56-bit key size`
* AES `using 128-bit for the blocksize and verity of key size 128, 192 or 256 bit key size`
* 
