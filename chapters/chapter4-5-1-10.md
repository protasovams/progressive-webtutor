# StrLongDate()

```js
/**
 * Преобразует дату в строку в "длинном" формате (со словесным написанием месяца). Если в качестве аргумента передается null или пустая строка, функция возвращает пустую строку.
 * @param {Date, null, ""} Объект Date
 * @return {String}
 */
function StrLongDate(date) {...}

// Пример
StrLongDate(Date('06.10.2009 11:44:37'));
// '6 октября 2009 г.'; 
```