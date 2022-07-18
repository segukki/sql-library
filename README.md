# sql-library
sql project about library

The task:
Рассмотреть полученный объект и разобрать на возможные сущности внутри объекта, например, классы и учителя в школе или лекарства и фармацевты в аптеке. Составить 4-5 связанных сущностей и реализовать по ним таблицы. Некоторые таблицы могут быть справочными, обязательно нужна связывающая сущности таблица. 

сущности: книги / посетители / филиалы / сотрудники

информация о сущностях:
  книги / books: названиe (name) - varchar / автор (author) - varchar / жанр (genre) - varchar / дата написания (writedate) - data / кол-во раз аренды (numrentdays) - integer / id - integer (6)
  посетители / visitors: фио (name) - varchar / дата рождения (birthdate) - data / кол-во раз аренды (numrent) - integer / кол-во невозврата (nonrefnum) - integer / номер телефона (phonenum) - integer / id - integer (6)
  филиалы / branches: адрес (adress) - varchar / кол-во книг (booknum) - integer / кол-во поситителей в месяц (visitorsnum) - integer (3)
  сотрудники / employees: фио (name) - varchar / дата найма (hiredate) - data / должность (jobtitle) - varchar / зарплата руб-мес (salary) - integer / номер телефона (phonenum) - integer / id - integer (6)

Разработать Create table по придуманным таблицам. Типы данных в таблицах должны быть разнообразными — number, integer, varchar2, date. Наполнить эти таблицы данными. Данные в таблицах должны быть такими, чтобы выводились какие-то результаты по запросам. Файлы с написанными конструкциями create и insert должны прилагаться к проекту. 

Придумать 15 различных запросов к этим таблицам разного уровня сложности. Запрос должен раскрывать какую-то проблематику объекта, чем менее он будет искусственно придуманным, тем лучше. Вспомните, какие у нас были задания на запросы на занятиях и на практике, можно почерпнуть вдохновение из этих примеров. Запрос описать текстом, далее написать select и показать результат его выполнения. Запросы должны включать в себя все разобранные нами темы, кроме xml и json, а именно:
1) простые select с условиями (лаб. 1);
2) однострочные функции, обязательно работа с датами (лаб. 2);
3) групповые функции (лаб. 3);
4) объединения таблиц (лаб. 4 — join, left join) и множеств (лаб. 5 — union, minus, intersect);
5) подзапросы (лаб. 6);
6) аналитические функции (лаб. 7).

Запросы:
1) Выведите название, автора и жанр книг, которые были арендованы более 10 раз.
2)
3)
4)
5)
6)
7)
8)
9)
10)
11)
12)
13)
14)
15)
16)

Оформить проект в презентации, где:
1) рассказать о своем объекте
2) как вы разобрали его на сущности, почему именно такие
3) нарисовать схематично таблицы с указанием полей, первичных и внешних ключей, связей с другими таблицами
4) перечислить 15 разработанных запросов. На слайде должен быть текст запроса (получить список такой-то или вывести таких-то сотрудников/студентов/школьников/пациентов и т.д), сам select и результат выполнения этого select.

Время рассказа о своем проекте фиксированное — 10-15 минут. Презентации приносить в формате pdf, конструкции по созданию и наполнению таблиц — в текстовом документе.
