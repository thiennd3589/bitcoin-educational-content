---
term: HRP (ЧЕЛОВЕКОЧИТАЕМАЯ ЧАСТЬ)

---
HRP, что означает "Human Readable Part", - это компонент адресов приема bech32 и bech32m (SegWit v0 и SegWit v1). HRP - это часть адреса, которая специально отформатирована так, чтобы ее мог легко прочитать и интерпретировать человек. Возьмем, к примеру, биткойн-адрес bech32:

```text
bc1qar0srrr7xfkvy5l643lydnw9re59gtzzwfqx5
```

В этом адресе начальный `bc` представляет собой HRP. Этот префикс позволяет быстро определить, что представленная строка символов является адресом Bitcoin, а не чем-то другим.