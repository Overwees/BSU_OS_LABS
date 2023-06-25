# OS_LAB_2_CREATING_THREADS

## Задача

Написать программу для консольного процесса, который состоит из трех потоков: _main_,
_min_max_ и _average_.

Поток _main_ должен выполнить следующие действия:
1. Создать массив целых чисел, размерность и элементы которого вводятся с консоли.
2. Создать потоки _min_max_ и _average_.
3. Дождаться завершения потоков _min_max_ и _average_.
4. Заменить максимальный и минимальный элементы массива на среднее значение элементов
массива. Вывести полученные результаты на консоль.
5. Завершить работу.

Поток _min_max_ должен выполнить следующие действия:
1. Найти минимальный и максимальный элементы массива и вывести их на консоль. После
каждого сравнения элементов «спать» 7 миллисекунд.
2. Завершить свою работу.

Поток _average_ должен выполнить следующие действия:
1. Найти среднее арифметическое значение элементов массива и вывести его на консоль.
После каждой операции суммирования элементов «спать» 12 миллисекунд.
2. Завершить свою работу.