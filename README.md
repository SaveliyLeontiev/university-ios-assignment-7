Лабораторные работы выполняются индивидуально. Основной упор делается именно на проходимую тему, но не стоит забывать и прочих аспектах: грамотное разбиение на классы, хороший стиль кодирования, и т.д.


iOS. Лабораторная работа 7
==========================
**Задание**  
Реализовать асинхронное вычисление и вывод на экран последовательности любых "хитрых" (см. http://oeis.org) чисел.


*Требования к реализации:*  
1. Расчёт чисел и работа с UIView должны идти в разных потоках.


**Задание "со звёздочкой"**  
Реализовать аналог игры Pong для двух ботов (пример работы программы: http://www.youtube.com/watch?v=it0sf4CMDeM).


*Требования к функционалу:*  
1. На экране находится три UIView: "шарик" и две "ракетки".  
2. Шарик всегда имеет константную скорость в одном из четырёх направлений движения (NE, SE, SW, NW).  
3. Каждая из ракеток может стоять на месте или двигаться с константной скоростью.  
4. Во время движения шарика влево двигается только левая ракетка, во время движения шарика вправо двигается только правая ракетка.


*Требования к реализации:*  
1. Расчёт координат и работа с UIView должны идти в разных потоках.
