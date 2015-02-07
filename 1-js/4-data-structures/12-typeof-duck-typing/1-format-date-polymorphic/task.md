# Полиморфная функция formatDate

[importance 5]

Напишите функцию `formatDate(date)`, которая возвращает дату в формате `dd.mm.yy`. 

Ее первый аргумент должен содержать дату в одном из видов:
<ol>
<li>Как объект `Date`.</li>
<li>Как строку в формате `yyyy-mm-dd`.</li>
<li>Как число *секунд* с `01.01.1970`.</li>
<li>Как массив `[гггг, мм, дд]`, месяц начинается с нуля</li>
</ol>
Для этого вам понадобится определить тип данных аргумента и, при необходимости, преобразовать входные данные в нужный формат.

Пример работы:

```js
function formatDate(date) { /* ваш код */ }

alert( formatDate( '2011-10-02' ) );  // 02.10.11
alert( formatDate( 1234567890 ) );  // 14.02.09
alert( formatDate( [2014,0,1] ) ); // 01.01.14
alert( formatDate( new Date(2014,0,1) ) ); // 01.01.14
```
