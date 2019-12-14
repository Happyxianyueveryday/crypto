# cryptolib

信息安全课程实验作业，修正了部分错误。

cryptolib是一个较为简单的，实验性质的加密算法实现。其中包含网络编程中常用的加密方案与Hash函数等安全机制，例如DES,AES,MD5,SHA-512等常见方案的实现。

本项目基于RFC标准文档和《密码编码学与网络安全》实现，最大程度地保证正确性，各个模块的说明文档请参见各个模块的文件夹内的readme.md文件。

### 目录
#### 1. AES：AES分组加密模块
#### 2. DES：DES分组加密模块
#### 3. MD5：MD5 Hash函数实现
#### 4. SHA512：SHA512 Hash函数实现
#### 5. RSA：RSA公钥加密模块
#### 6. Diffie-Hellman：Diffie-Hellman密钥交换模块
#### 7. Elgamel：Elgamel密钥交换模块
#### 8. DAA：DAA消息认证码(MAC)模块 
#### 9. HMAC：基于MD5和SHA512 Hash函数的消息认证码(MAC)模块
#### 10. Pattern：分组加密集成模块，集成了AES, DES分组加密算法，并支持CBC, ECB, CTR, OCF, CFB五种分组密码的加密模式
#### 11. HashCenter：Hash函数集成模块，集成了MD5, SHA512 Hash函数，并支持文件输入
#### 12. Tradition：传统密码集成模块，集成了Caesar密码，仿射密码和Vigenere密码

