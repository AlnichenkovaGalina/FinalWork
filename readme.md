Первоначальный массив имеет значение: ["hello", "2", "world", ":-)", "1234", "1567", "-2", "computer science"].

Переменная lengthLimit - согласно заданию равна 3.


### CheckArray - метод подсчёта количества элементов, размер которых меньше lengthLimit. #
Подсчёт осуществляется перебором элементов массива arrayOfStrings и сравнением количества их элементов с переменной lengthLimit.
Результат выводится в переменную numbersItems.
Инициализируется новый массив строк newArrayOfStrings, размером, равным переменной numbersItems.

### FillNewArray - метод формирования нового массива строк.
Формирование осуществляется перебором элементов массива arrayOfStrings, сравнением количества их элементов с переменной lengthLimit и добавлением в массив newArrayOfStrings элемента, удовлетворяющего условию.
На выходе метода получается заполненный массив строк newArrayOfStrings, удовлетворяющий условию, что и является решением задачи.