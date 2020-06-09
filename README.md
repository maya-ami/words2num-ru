# words2num_ru
Код для преобразования чисел, записанных прописью на русском языке.

## Пример

Грамматически верное текстовое представление числительного:
```python
from words2num_ru import form_number
print(form_number("тысяча пятьсот десять"))

shell
1510
```

Преобразование числительного, написанного/произнесенного на английский манер:
```python
from words2num_ru import form_number
print(form_number("пятнадцать десять"))
```
```shell
1510
```
