---
term: P2PK

---
P2PK 是 *Pay to Public Key* 的缩写。它是比特币上使用的一种标准脚本模型，用于在UTXO上建立消费条件。它允许将比特币直接锁定在公钥上，而不是地址上。

从技术上讲，P2PK 脚本包含一个公钥和一个指令，该指令要求相应的数字签名来解锁资金。当所有者希望使用比特币时，他们必须提供用相关私钥生成的签名。该签名使用 ECDSA（*椭圆曲线数字签名算法*）进行验证。P2PK 经常用于比特币的早期版本，特别是中本聪。如今几乎已不再使用。