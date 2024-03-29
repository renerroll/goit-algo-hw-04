порівняльня табличка 


 Algorithm       | Numbers Sorting Time    | Words Sorting Time  |
|----------------|-------------------------|---------------------|
| Insertion sort | 1.939487 sec            | 2.189035 sec        |
| Merge sort     | 0.146300 sec            | 0.153094 sec        |
| Timsort-1      | 0.008300 sec            | 0.015091 sec        |
| Timsort-2      | 0.007418 sec            | 0.014493 sec        |


Висновки:

У даному дослідженні було порівняно три алгоритми сортування: сортування злиттям, сортування вставками та Timsort, вбудований алгоритм сортування в Python. Дослідження проводилося шляхом вимірювання часу виконання на різних наборах даних.

За результатами експериментів було виявлено, що алгоритм Timsort виявився значно ефективнішим у порівнянні зі сортуванням злиттям та сортуванням вставками. Його ефективність забезпечується поєднанням переваг обох підходів та оптимізаціями, що роблять його придатним для широкого спектру задач сортування.

Отже, програмісти віддають перевагу використанню вбудованих алгоритмів сортування в Python, таких як Timsort, через їх високу ефективність та готовність до використання. Ручне кодування алгоритмів сортування, хоча і може бути корисним для освоєння основ сортування, часто не є доцільним у виробничих середовищах через наявність оптимізованих вбудованих рішень.
