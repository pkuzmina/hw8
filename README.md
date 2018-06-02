# Домашнее задание 

Введение
------

Так как я пользуюсь MacOS, работа была выполнена с помощью одного из аналогов Notepad++ – Sublime (и сайта [regex101.com](https://regex101.com) для проверки и сопоставления результатов). 

Задание 1
------

Использовала регулярное выражение: ^\n, не заменяя вхождения.

![alt text](https://raw.githubusercontent.com/pkuzmina/hw8/master/удаление%20пустых%20строк_1.jpeg)

Результат

![alt text](https://raw.githubusercontent.com/pkuzmina/hw8/master/удаление%20пустых%20строк_2.jpeg)

Задание 2
------

Использовала регулярное выражение: [А-Я]{1}[а-яѣ]*слав[а-яѣ]. 

Всего упоминаний в Sublime: 598 (как я заметила, лишние слова тоже оказались включены). 

![alt text](https://raw.githubusercontent.com/pkuzmina/hw8/master/имена%20и%20названия.png) 

В Regex 101 зафикисировано меньше упоминаний: 564 (раздел с информацией о нахождениях заставляет больше доверять сайту, нежели программе). 

![alt text](https://raw.githubusercontent.com/pkuzmina/hw8/master/имена%20и%20названия%202.png)

Задание 3
------

Использовала регулярное выражение: Нов[а-яѣ]город[а-яѣ]*. 

В Sublime найдено упоминаний: 64.

![alt text](https://raw.githubusercontent.com/pkuzmina/hw8/master/новгород.png)

Количество упоминаний в Regex 101 снова меньше: 58. Но, по сравнению с Заданием 2, это небольшое расхождение.

![alt text](https://raw.githubusercontent.com/pkuzmina/hw8/master/новгород%202.png). 
