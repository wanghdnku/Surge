# Surge APP Shadowsocks Encrypt Support Module

## Usage
- Download The SSEncrypt Module form URL Below
```url
https://raw.githubusercontent.com/Unbinilium/Surge-SSEncrypt-Module/master/SSEncrypt.module
```

## Example Conf
- It is Only the Proxy Part, and You're Suppose to fill **SeverIP**、**ServerPort**、**EncryptMethod** and **Paddword** Manually
```txt
[Proxy]
Shadowsocks = custom,ServerIP,ServerPort,EncryptMethod,Password,https://raw.githubusercontent.com/Unbinilium/Surge-SSEncrypt-Module/master/SSEncrypt.module
```

## Notice
- Now Only Supported These Encryption Method
```encryption
table
rc4
rc4-md5
salsa20
chacha20
chacha20-ietf
bf-cfb
des-cfb
cast5-cfb
cast5-ofb
aes-128-cfb
aes-128-ofb
aes-192-cfb
aes-192-ofb
aes-256-cfb
aes-256-ofb
camellia-128-cfb
camellia-192-cfb
camellia-256-cfb
```
