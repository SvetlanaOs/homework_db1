# Задание
## Обязательная часть
Будем развивать схему для музыкального сервиса.
Ранее существовало ограничение, что каждый исполнитель поёт строго в одном жанре, пора его убрать. Исполнители могут петь в разных жанрах, как и одному жанру могут принадлежать несколько исполнителей.
Аналогичное ограничение было и с альбомами у исполнителей — альбом мог выпустить только один исполнитель. Теперь альбом могут выпустить несколько исполнителей вместе. Как и исполнитель может принимать участие во множестве альбомов.
С треками ничего не меняем, всё так же трек принадлежит строго одному альбому.
Но появилась новая сущность — сборник. Сборник имеет название и год выпуска. В него входят различные треки из разных альбомов.
Обратите внимание: один и тот же трек может присутствовать в разных сборниках.

### Задание состоит из двух частей
Спроектировать и нарисовать схему, как в первой домашней работе. Прислать изображение со схемой.
Написать SQL-запросы, создающие спроектированную БД. Прислать ссылку на файл, содержащий SQL-запросы.
Примечание: можно прислать сначала схему, получить подтверждение, что схема верная, и после этого браться за написание запросов.

# Дополнительное (необязательное) задание
Спроектировать отношение или схему из нескольких отношений «Сотрудник». У каждого сотрудника есть следующие параметры:
Имя.
Отдел.
Начальник (ссылка на начальника).
Примечание: начальник — тоже сотрудник. Отдел можно хранить строкой, можно идентификатором — не принципиально.
Необходимо написать SQL-запрос, создающий таблицу «Сотрудник», и прислать ссылку на файл с этим запросом.
