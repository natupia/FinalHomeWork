Задача

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Решение

Объявляются два массива: изначальный и вторый пустой такой же длины. Заием метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ): если да, то элемент первого массива становится элементом второго массива. Затем возврат к циклу с перходом к следующему элементу массива. И так проверяется до конца. Блок-схема алгоритма и программа в C# приложены.