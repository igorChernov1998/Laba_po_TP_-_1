# Laba-1
## Вариант 31 - Вычисление MurMurHash бинарной строки
### Алгоритм, реализованный в библиотеке состоит из следующих этапов:
1) Формируем массив char*, равный ключу (параметр, переданныйв функцию)
2) В цикле формируем наш хеш, который хранится в переменной h. За одну иттерацию Действие выполняется над 4 символами исходного ключа
Формируется число k посредством использования оператора логического или, побитового сдвига, логического и, и умножения, а также число h (хэш код)
3) Далее рассматриваем случае, когда после выполнения иттераций цикла осталось 3, 2 или 1 символа
4) Окончательно формируем хеш код с использовнием побитового сдвига и умножения
