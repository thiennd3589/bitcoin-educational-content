---
term: БЛОЧНЫЙ ГИДЕР

---
Заголовок блока - это структура данных, которая служит основным компонентом при создании блока Биткойна. Каждый блок состоит из заголовка и списка транзакций. Заголовок блока содержит важную информацию, которая обеспечивает целостность и достоверность блока в блокчейне. Заголовок блока содержит 80 байт метаданных и состоит из следующих элементов:


- Блочная версия;
- Хэш предыдущего блока;
- Корень дерева Меркла для транзакций;
- Временная метка блока;
- Цель по сложности;
- Нонче.

Например, вот заголовок блока под номером 785 530 в шестнадцатеричном формате, добытого Foundry USA 15 апреля 2023 года:

```text
00e0ff3f5ffe3b0d9247dc437e18edc19252e4517cee941752d501000000000000000000206b
de3a10826e2acb2f28fba70463601c789293d0c9c4348d7a0d06711e97c0bcb13a64b2e00517
43f09a40
```

Если мы разберем этот заголовок, то сможем понять:


- Версия:

```text
00e0ff3f
```


- Предыдущий хэш:

```text
5ffe3b0d9247dc437e18edc19252e4517cee941752d501000000000000000000
```


- Корень Меркле:

```text
206bde3a10826e2acb2f28fba70463601c789293d0c9c4348d7a0d06711e97c0
```


- Временная метка:

```text
bcb13a64
```


- Цель:

```text
b2e00517
```


- Нонче:

```text
43f09a40
```

Чтобы быть действительным, блок должен иметь заголовок, который после хэширования с помощью `SHA256d` дает хэш, меньший или равный целевой сложности.

> ► *На английском языке это называется "Block Header"