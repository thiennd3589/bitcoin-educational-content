---
term: SIGHASH_ALL (0X01)

---
Тип флага SigHash, используемого в подписях транзакций Биткойна для указания того, что подпись применяется ко всем компонентам транзакции. Используя `SIGHASH_ALL`, подписывающий охватывает все входы и все выходы. Это означает, что ни входы, ни выходы не могут быть изменены после подписи, не аннулируя ее. Этот тип SigHash Flag наиболее распространен в транзакциях Биткойна, так как он обеспечивает полную завершенность и целостность транзакции.