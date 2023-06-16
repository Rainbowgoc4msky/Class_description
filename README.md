# Class_description
Составить описание класса для определения одномерных массивов строк фиксированной длины. Предусмотреть возможность обращения к отдельным строкам массива по индексам, контроль выхода за пределы массива, выполнения операций поэлементного сцепления двух массивов с образованием нового массива, слияния двух массивов с исключением повторяющихся элементов, вывод на экран элемента массива по заданному индексу и всего массива.
Класс FixedLengthStringArray предназначен для работы с одномерными массивами строк фиксированной длины. Массив состоит из N элементов, каждый из которых представляет собой строку фиксированной длины L. Класс предоставляет следующие методы:

- `__init__(self, n, l, values=None)`: конструктор класса, который принимает три аргумента: n - количество элементов в массиве; l - длина каждой строки в массиве; values - значения элементов массива (по умолчанию None).
- `__getitem__(self, index)`: возвращает строку-элемент массива по индексу index.
- `__setitem__(self, index, value)`: устанавливает значение value элемента массива по индексу index.
- `__str__(self)`: возвращает строковое представление всего массива.
- `concat(self, other_array)`: выполняет операцию поэлементного сцепления массива с другим массивом other_array той же длины L, возвращает новый массив получившихся строк.
- `merge(self, other_array)`: выполняет операцию слияния двух массивов с исключением повторяющихся элементов, возвращает новый массив.
- `print_element(self, index)`: выводит строку-элемент массива по индексу index на экран.
- `print_array(self)`: выводит все элементы массива на экран.
