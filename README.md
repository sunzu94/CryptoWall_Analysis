# CryptoWall Analysis
## Download
1. Packed Version -> `47363b94cee907e2b8926c1be61150c7`
2. Unpacked Version -> `919034c8efb9678f96b47a20fa6199f2`
  - Unpacking CryptoWall will be posted about either on my medium account or on here :)

## Decrypt C2 IP Addresses
```
➜  CryptoWall git:(master) python decrypt_c2_ip_addrs.py
[+] Got plaintext key: 6hehbz4fp

[+] Generated key bytes from plaintext:
bytearray(b'6L]\x84\x80\x8b\x0c,-&"\n\x8cu3A\xb6\x18\xeajs\xe5h\x95n\xc4\xc6\x9c4\x9ag\x12Fz(*\xd3dQX\x92Y\x97\xa9PB\x8e\xd0T\x1f\x1ep\xa8M\x83\xfc\x99:\xd5\t\xdc\\\x85\xb2\xc5\x9ek\xf9)\xaa\x1c\x19\xcc\xc7I\x00\xc1\xec\x1blJ\xb3m~\xa0\'K\xf8\xafc\xb9r>$i!\x98o\x93\x0fS\xeb1\x86\x90\xcd\x9dx\x0eG\xa4\xee=\xc3\xd4fZ\xe6\xda\x10\x89%\xe2/\x91C\x1d\xac\xd7\x02\xa3\xdfqaD\xd1|y\xd2V\xf6w2H\x16\xa7_\xddR\x0b\xc0\xe8\xca \xa5\x05t\xe7\xff\xb7\xe1\xef\xc9\xe3.\xde\xe0\xb4#\r7\xbbU\xfb\xb8`\xdb\xd9\xa1\xab\xf5^\xe9\xed\x1a8\x14\xb0\x04\xbf\x019\xd6\x17\x82\xc8\xae\x13N}\xb5\xd8\xce\xfaW\xbc\xe4@\xf2\xb1e\x15\x88E\xfeO\xfdb\x9f\x085\x96\xa6\xf3\x030\x9b\x87\xad\xf7\x11\xcb\xbe{\x7f?;\xa2\x8f\xba\xf1\x06v\x07\x8a<\x94\xf0\x81\x8d+\xbd[\xc2\xf4\xcf')

Decrypted data:
209.148.85.151:8080
94.247.28.26:2525
94.247.31.19:8080
91.121.12.127:4141
94.247.28.156:8081
```

## Retrieve Ransomware Note from Unpacked binary
```
➜  CryptoWall git:(master) python2 decompress_ransomwarenote.py
[!] Searching PE sections for .data
[+] Found ransomware note
[+] Decompressed successfully
[+] Finished writing to file
```
![Ransomware Note](https://i.ibb.co/r2mk1fc/Screen-Shot-2020-03-21-at-12-43-42-PM.png)
