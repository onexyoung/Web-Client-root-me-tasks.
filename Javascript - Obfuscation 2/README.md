Нас встречает пустая страница. 
Просматриваем код страницы сочетанием клавиш cmd+option+u -> (1).
Нужно выполнить действия с pass, чтобы найти флаг. 
С помощью сайта https://playcode.io/online-javascript-editor выполняем внешний unescape. 
Затем внутренний unescape, результатом которого будет строка вида pass = String.fromCharCode(104, 68, 117, 102, 106, 100, 107, 105, 49, 53, 54).
Выполняем эту команду и получаем резудльтат - hDufjdki156, что и является флагом.
