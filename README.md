# Simple File Encryption/Decryption Tool

## 项目简介
这是一个使用异或（XOR）操作进行文件加密和解密的简单工具。它提供了基本的文件加密功能，通过指定一个密钥（key）来对文件内容进行异或操作，实现加密。使用相同的密钥和相同的操作可以对文件进行解密。

## 使用说明

### 编译
要使用这个工具，您需要先编译源代码。源代码包含两个函数：`encrypt_file` 和 `decrypt_file`，它们分别用于加密和解密文件。

```bash
gcc -o crypto_tool crypto.c


加密：./crypto_tool encrypt input_file output_file key

解密：./crypto_tool decrypt input_file output_file key


Author:Gaosheng
