# Java_Api_2
Урок 2. Почему вы не можете не использовать API
Задание

1) Дана строка sql-запроса "select * from students WHERE ". Сформируйте часть WHERE этого запроса, используя StringBuilder. Данные для фильтрации приведены ниже в виде json-строки.
Если значение null, то параметр не должен попадать в запрос.
Пример данной строки {"name":"Ivanov", "country":"Russia", "city":"Moscow", "age":"null"}
Вывод: select * from students WHERE name=Ivanov AND country=Russia AND city=Moscow

2) Реализуйте алгоритм сортировки пузырьком числового массива, результат после каждой итерации запишите в лог-файл.
1 3 4 2
1 3 2 4
1 2 3 4
