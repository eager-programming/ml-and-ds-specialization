 

Вырезано из https://www.coursera.org/learn/mathematics-and-python/exam/IM9o8/sintaksis-python 

Тест, 7 вопроса 

Поздравляем! Вы прошли тест! 

loading    


Load Error! 

Вопрос 1 

Правильно 

1 из 1 

Баллы 

1. Вопрос 1 

Выберите правильные утверждения про типы данных в Python. 

Массивы в Python представлены типами list и tuple. 

Правильно  

list — изменяемый массив, tuple — неизменяемый. 

Массивы в Python представлены типами dict и tuple. 

правильно, этот вариант не должен быть выбран  

Массивы в Python представлены типами vector и tuple. 

правильно, этот вариант не должен быть выбран  

Тип данных list — это односвязный список. 

правильно, этот вариант не должен быть выбран  

Тип данных list — это неизменяемый массив. 

правильно, этот вариант не должен быть выбран  

Тип данных tuple — это неизменяемый массив. 

Правильно  

В list могут содержаться элементы разных типов данных. 

Правильно  

Вопрос 2 

Правильно 

1 из 1 

Баллы 

2. Вопрос 2 

Выберите правильные утверждения про типы данных в Python 

В tuple могут содержаться элементы разных типов данных 

Правильно  

В dict могут содержаться элементы разных типов данных 

Правильно  

В dict нельзя использовать tuple в качестве ключа 

правильно, этот вариант не должен быть выбран  

В dict нельзя использовать list в качестве ключа 

Правильно  

Потому что list — изменяемый тип данных. 

Разные скобки в Python используются для создания объектов разных типов данных: [ ] - для tuple, { } - для list, ( ) - для dict. 

правильно, этот вариант не должен быть выбран  

Разные скобки в Python используются для создания объектов разных типов данных: ( ) - для tuple, [ ] - для list, { } - для dict и set. 

Правильно  

Вопрос 3 

Правильно 

1 из 1 

Баллы 

3. Вопрос 3 

Выберите верные утверждения про синтаксис Python 2.x 

тело циклов (for, while) и условий (if, elif, else) должно быть взято в фигурные скобки 

правильно, этот вариант не должен быть выбран  

тело циклов (for, while) и условий (if, elif, else) должно быть написано с однотипным отступом 

Правильно  

Каждая строчка в Python должна заканчиваться точкой с запятой 

правильно, этот вариант не должен быть выбран  

Python — язык с жесткой типизацией, поэтому при объявлении каждой переменной надо явно указывать ее тип 

правильно, этот вариант не должен быть выбран  

В Python булевские значения True и False пишутся с большой буквы 

Правильно  

Деление целых чисел по умолчанию целочисленное, для получения в результате деления числа с плавающей точкой нужно либо явно приводить тип хотя бы одного из чисел с помощью float(), либо одно из чисел записать как число с плавающей точкой. 

Правильно  

Вопрос 4 

Правильно 

1 из 1 

Баллы 

4. Вопрос 4 

Что выведет выражение: print " ".join([str(x ** 2 % 2) for x in range(4)]) ? Обратите внимание, что некоторые из вариантов ответа могут совпадать по выводу, но не совпадать по объяснению того, что именно происходило в этой строчке кода. Нужно выбрать самый точный вариант. 

0 1 0 1 (остаток от деления на 2 квадратов чисел от 0 до 3 включительно) 

Правильно  

Правильно! 

0 1 0 1 (остаток от деления на 2 чисел от 0 до 3 включительно) 

MemoryError 

UnicodeError 

0 1 2 3 (числа от 0 до 3 включительно) 

0 1 4 9 (квадраты чисел 0 до 3 включительно) 

[0 1 0 1] (массив из остатков от деления индекса элемента на 2) 

Вопрос 5 

Правильно 

1 из 1 

Баллы 

5. Вопрос 5 

Чем в Python 2.x отличается range от xrange? 

range возвращает генератор, а xrange — массив 

у range два аргумента, а у xrange — один 

у range один аргумент, а у xrange - два 

xrange возвращает генератор, а range — массив 

Правильно  

Правильно! 

Вопрос 6 

Правильно 

1 из 1 

Баллы 

6. Вопрос 6 

Что вернет выражение lambda x, y: x ** 2 

Число, полученное возведением значения переменной x во вторую степень 

Функцию, принимающую на вход один аргумент и возвращающую его квадрат 

Функцию, принимающую на вход два аргумента, и возвращающую квадрат первого аргумента 

Правильно  

Правильно! 

Квадраты первых y целых чисел, если y — целочисленная переменная 

Вопрос 7 

Правильно 

1 из 1 

Баллы 

7. Вопрос 7 

Предположим, что нам необходимо открыть текстовый файл для того, чтобы дописать в его конец несколько строк, оставив при этом исходное содержимое файла (строки, которые в нем уже были) без изменений. В каком режиме (mode) нам следует отрыть файл в этом случае? 

'r' 

'w' 

'a' 

Правильно  

Правильно! 'r' — режим чтения, 'w' — режим записи (перетирает все, что было до этого). 
