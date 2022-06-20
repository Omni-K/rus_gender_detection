# Определитель пола по имени (RU)

Определяет пол человека по полному русскому имени. К регистру не чувствителен.

## Использование

```python
from rusgenderdetection import get_gender

print(get_gender("Николай"))                    # prints 1
print(get_gender("светлана", use_strings=True)) # prints "female" 
```

Функция `get_gender` Возвращает одно из трёх значений.
0 - если имя женское;
1 - если имя мужское;
-1 - если не удалось определить.