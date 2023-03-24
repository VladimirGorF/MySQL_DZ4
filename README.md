Табличка:
https://drive.google.com/file/d/1TZzW8ZlDdvIfDC9C46bUeILey6opQjdu/view?usp=share_link

Используя JOIN-ы, выполните следующие операции:
Вывести всех котиков по магазинам по id (условие соединения shops.id = cats.shops_id)
<img width="2048" alt="Снимок экрана 2023-03-23 в 18 37 08" src="https://user-images.githubusercontent.com/110591063/227255690-5fa2ada9-dc0b-4a2e-9645-56d7da8a339a.png">


Вывести магазин, в котором продается кот “Мурзик” (попробуйте выполнить 2 способами)
<img width="2048" alt="Снимок экрана 2023-03-24 в 11 22 56" src="https://user-images.githubusercontent.com/110591063/227464435-f90ba24d-23a5-44ac-b75c-81c160dae1a4.png">


Вывести магазины, в котором НЕ продаются коты “Мурзик” и “Zuza”
<img width="2048" alt="Снимок экрана 2023-03-24 в 13 27 03" src="https://user-images.githubusercontent.com/110591063/227496868-b002c3a5-a0b0-4c16-a33a-8ae6f2c1350c.png">


Табличка (после слов “Последнее задание, таблица:”):
https://drive.google.com/file/d/1TZzW8ZlDdvIfDC9C46bUeILey6opQjdu/view?usp=share_link

Вывести название и цену для всех анализов, которые продавались 5 февраля 2020 и всю следующую неделю.

Есть таблица анализов Analysis:

an_id — ID анализа;
an_name — название анализа;
an_cost — себестоимость анализа;
an_price — розничная цена анализа;
an_group — группа анализов.
Есть таблица групп анализов Groups:
gr_id — ID группы;
gr_name — название группы;
gr_temp — температурный режим хранения.
Есть таблица заказов Orders:
ord_id — ID заказа;
ord_datetime — дата и время заказа;
ord_an — ID анализа.
<img width="2048" alt="Снимок экрана 2023-03-24 в 14 23 14" src="https://user-images.githubusercontent.com/110591063/227508794-7ae84449-723b-4fbc-9102-7fb6fd55bab4.png">





Условие основных дз в презентации, дополнительное: 
Табличка:
https://drive.google.com/file/d/1PQn576YVakvlWrIgIjSP9YEf5id4cqYs/view?usp=sharing
1. Вывести на экран сколько машин каждого цвета для машин марок BMW и LADA
2. Вывести на экран марку авто и количество AUTO не этой марки
Задание №3.
Даны 2 таблицы, созданные следующим образом:
create table test_a (id INT, data varchar(45));
create table test_b (id INT);
insert into test_a(id, data) values
(10, 'A'),
(20, 'A'),
(30, 'F'),
(40, 'D'),
(50, 'C');
insert into test_b(id) values
(10),
(30),
(50);
Напишите запрос, который вернет строки из таблицы test_a, id которых нет в таблице test_b, НЕ используя ключевого слова NOT.

