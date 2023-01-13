# Инструкция по работе с *MarkDown*


## Заголовки в *MarkDown*
Для создания заголовка используется символ #. Для этого в начале строки необходимо написать несколько символов #. Количество символов # обозначает уровень заголовка: одна - первого уровня, два 0 второго и так далее. Чем выше уровень заголовка, тем ***меньше*** текст. Заголовок первого уровня - самый ***большой***.

Попробуем без добавления - без *git add* не получается сделать *commit*

## Форматирование текста в *MarkDown*
Для того, чтобы написать *курсивный текст*, используется символ звёздочка. Для этого заданный текст необходимо написать между двумя звёздочками. Для создания **жирного текста** используется символ две звёздочки. Для этого необходимо написать текст между двумя парами звёздочек. Для создания ***жирного курсивного текста*** используется символ три звёздочки. Для этого необходимо текст написать между двумя тройками звёздочек. Для того, чтобы написать ~~зачеркнутый текст~~ используется символ ~~ (две тильды). Для этого текст необходимо написать между двумя парами символов тильда.

## Списки

### Неупорядоченные списки

Для того, чтобы преобразовать текст в неупорядоченный список 
используются символы звездочка (*), тире (-) и плюс (+). При выборе любого знака элементы неупорядоченного списка будут иметь в начале жирную точку:

- элемент 1
- элемент 2
- ...
- элемент n

### Вложенные списки 
Для добавления вложенного списка первого уровня нужно добавить 4 пробела или 1 табуляцию перед нужным пунктом. Для добавления вложенного пункта следует добавить дополнительно либо 4 пробела, либо 1 табуляцию:

* элемент 1
* элемент 2
    * вложенный элемент 2.1
        * вложенный элемент 2.1.1
* элемент n

### Упорядоченный список
Для создания упорядоченного списка перед элементом списка требуется добавить любую цифру с точкой (ex, 1.). Важно, какое число будет присвоено первому элементу списка. От него пойдет дальнейшая нумерация. Это касается и вложенных списков.

1. элемент 1
30. элемент 2
    1. элемент 2.1
        1. вложенный элемент 2.1.1
            1. вложенный элемент 2.1.1.1
            2. вложенный элемент 2.1.1.2
        1. вложенный элемент 2.1.2
    2. элемент 2.2
0. элемент n