# stdflib

Ваш новый начальник -- большой фанат функционального программирования и constexpr вычислений.
Он убедил высшее начальство, что стандартная библиотека C++ не подходит для крупного и уважающего себя бизнеса,
поэтому нужно реализовать свою версию.

Вам поручено портировать несколько функций для работы с числами. Поскольку в функциональном программировании 
данные иммутабельны, а циклы используются редко, нужно написать функции, используя рекурсивный вызов лямбд
("Обычные рекурсивные вызовы -- это прошлый век, так Кнут говорил еще", считает ваш начальник).

Это значит, что функция может вернуть только лямбду. Кроме того, функции принимают только шаблонные параметры.
Реализация функции, вычисляющей числа Фибоначчи, уже есть.