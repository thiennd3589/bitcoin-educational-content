---
term: TXID (ИДЕНТИФИКАТОР ТРАНЗАКЦИИ)

---
Уникальный идентификатор, связанный с каждой транзакцией Bitcoin. Он генерируется путем вычисления `SHA256d` хэша данных транзакции. TXID служит ссылкой для поиска конкретной транзакции в блокчейне. Он также используется для обозначения UTXO, который, по сути, представляет собой конкатенацию TXID предыдущей транзакции и индекса назначенного вывода (также называемого "vout"). Для транзакций, проведенных после СегВита, TXID больше не учитывает свидетеля транзакции, что исключает возможность подделки.