По структурам таблиц

* users
* authors
* books
* readings
* achievements (etc)

Login - what kind of?

Problems
* **circular import**
* 

Ссылка на пидарасов у которых пиздим книги
https://bookscloud.ru/

Телеграм авторизация
https://habr.com/ru/articles/801121/
https://habr.com/ru/articles/889270/


По задачам:
Книги по жанрам + теги
Выкачать все книги через селениум с сайта (https://bookscloud.ru/books/12782#download) приоритет -- средний (Кирилл)
Скрипт парсинга метаданных книги ()
создание бота (низкий)

Авторизация/аутентификация
Два варианата:
1. Работать с InitData и проверять ее при каждом запросе, реализовав проверку через Depends
2. Создавать jwt и валидировать jwt при запросах.




