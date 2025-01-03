# Итоговый проект "Java-разработчик" (Skillbox).

## Задача

- реализовать поисковый движок по сайту — приложение, которое позволяет индексировать страницы и осуществлять по ним быстрый поиск.

## Описание

- Поисковый движок должен представлять из себя Spring-приложение (JAR-файл, запускаемый на любом сервере или компьютере),работающее с локально установленной базой данных MySQL, имеющее простой веб-интерфейс и API, через который им можно управлять и получать результаты поисковой выдачи по запросу. 

## Принципы работы поискового движка:

1. В конфигурационном файле перед запуском приложения задаются адреса сайтов, по которым движок должен осуществлять поиск.
2. Поисковый движок должен самостоятельно обходить все страницы заданных сайтов и индексировать их (создавать так называемый индекс) так, 
чтобы потом находить наиболее релевантные страницы по любому поисковому запросу.
3. Пользователь присылает запрос через API движка. Запрос — это набор слов, по которым нужно найти страницы сайта.
4. Запрос определённым образом трансформируется в список слов, переведённых в базовую форму. 
5. В индексе ищутся страницы, на которых встречаются все эти слова.
6. Результаты поиска ранжируются, сортируются и отдаются пользователю.
