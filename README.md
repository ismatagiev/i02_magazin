# i02_magazin
# Типы данных

## Число 
>let n = 123;
>
>n = 12.3456;

Числовой тип ('number') представляет как целочисленные значения так и числа с плавающей запятой.

Существует множество операций над числами, например '+', '*', '.', '-' и тд.

Кроме обычных чисел - существуют езе и специальные числовые значения, которые относятся к числам: 'Infinity', '-Infinity' и 'NaN'.

* 'Infinity' представляет собой математическую бесконечность. Это особое значение, которое больше любого числа. Мы можем получить его в результате деления на ноль.
> console.log('1 / 0');
* 'NaN' означает вычислительную ошибку. Это результат неправильной или неопределенной математической операции, например?
> console.log('строка / 2');

Если где-то в математическом выражении есть 'NaN', то результатом вычислений с его участием будет 'NaN'.

## BigInt
Тип 'number' не может содержать числа больше чем 2^53-1. Для большинства случаев это достаточно, но не всегда. Для этого можно использовать тип 'BigInt'.

Чтобы создать значение типа 'BigInt', необходимо добавить 'n' в конец числового литерала:
> const big = 123456789010111213141516n;

## Строка
Строка ('string') должна быть заключена в кавычки.
> let str = "Привет";
>  
> let str2 = "Привет";
> 
> let str3 = \'эти кавычки позволяют встраивать переменные ${str}\';

## Булевый (логический) тип
Тип 'boolean' может принимать только 2 значения: 'true' и 'false'.

Такой тип, как правило, используется для хранения значений да/нет.

Булевы значения также могут быть результатом сравенния:
> let isGrater = 4\>1;
> 
> console.log(isGreater);

## Значение null
Специальное значени 'null' не относится ни к одному из типов, описанных выше. Он формирует отдельный тип, который содержит только значение 'null':
> leg age = null;

Это специальное значение, которое представляет собой "ничего", "пусто", или "значение неизвестно".

## Значение underfined
специальное значение 'underfined' формирует тип из самого себя, также как и 'null'.
Оно означает, что значение не было присвоено. Если переменная объявлена, но ей не присвоено никакого значения, то её значением будет 'underfined'.
> leg age;
>
> console.log(age);
