# 1. Диаграмма активностей
## 1.1 Парсинг игровых данных
Если пользователь нажимает одну из кнопок поиска информации, происходит получения JSON данных, после чего их обработка и анализ, а затем отображение пользователю.

![](https://github.com/ParkhomenkoArtyom750504/Stat2Dota/blob/master/Diagrams/Activity/Parser.png)
## 1.2 Поиск информации
Если пользователь нажимает на кнопку поиска данных, то отправляется запрос на получение этих данных, а после того, как они буду найдены, они отобразятся пользователю.

![](https://github.com/ParkhomenkoArtyom750504/Stat2Dota/blob/master/Diagrams/Activity/Search%20.png)
## 1.3 Сохранение получение игровой статистики в базу данных
Если пользователь отправляет запрос на получение игровой статистики, то изначально идет проверка на наличие этой информации в базе данных. Если она есть в БД, то происходит отображение этой информации пользователю. Если ее нет, сервер получает данных, после чего добавляет их в базу данных, а потот эти данных отображаются пользователю.

![](https://github.com/ParkhomenkoArtyom750504/Stat2Dota/blob/master/Diagrams/Activity/Database.png)
## 1.4 Отображение информации
Если пользователь запрашивает какие-либо данные, то после их сбора системой они отобразятся.

![](https://github.com/ParkhomenkoArtyom750504/Stat2Dota/blob/master/Diagrams/Activity/View%20.png)
