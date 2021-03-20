# cryptogrphy
## rsa1024
```
$ openssl speed rsa1024
```
```
Doing 1024 bits private rsa's for 10s: 116571 1024 bits private RSA's in 10.02s
Doing 1024 bits public rsa's for 10s: 1557346 1024 bits public RSA's in 10.00s
OpenSSL 1.1.1g  21 Apr 2020
built on: Tue Apr 21 14:29:21 2020 UTC
options:bn(64,64) rc4(16x,int) des(long) aes(partial) idea(int) blowfish(ptr)
compiler: cl.exe /Zi /Fdossl_static.pdb /Gs0 /GF /Gy /MD /W3 /wd4090 /nologo /O2 -DL_ENDIAN -DOPENSSL_PIC -DOPENSSL_CPUID_OBJ -DOPENSSL_IA32_SSE2 -DOPENSSL_BN_ASM_MONT -DOPENSSL_BN_ASM_MONT5 -DOPENSSL_BN_ASM_GF2m -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DKECCAK1600_ASM -DRC4_ASM -DMD5_ASM -DAESNI_ASM -DVPAES_ASM -DGHASH_ASM -DECP_NISTZ256_ASM -DX25519_ASM -DPOLY1305_ASM
                  sign    verify    sign/s verify/s
rsa 1024 bits 0.000086s 0.000006s  11638.9 155734.6
```
## AES128
```
$ openssl speed -evp aes-128-cbc
```
