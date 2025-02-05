---
term: BIP143

---
Представляет новый способ хэширования транзакции для проверки подписи в пост-SegWit скриптах. Цель - минимизировать избыточные операции при проверке и включить значение UTXOs во входные данные в подпись. Это решает две основные проблемы оригинального алгоритма хеширования транзакций:


- Квадратичный рост хеширования данных с увеличением количества подписей;
- Отсутствие включения входного значения в подпись, что представляло риск для аппаратных кошельков, особенно в отношении знания о понесенных комиссиях за транзакции.

Поскольку обновление SegWit, о котором говорилось в BIP141, вводит новую форму транзакций, чей сценарий не будет проверяться старыми узлами, BIP143 использует эту возможность, чтобы решить эту проблему, не требуя хард форка. Таким образом, BIP143 является частью мягкого форка SegWit.