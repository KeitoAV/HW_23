# Lesson 23. Functional programming. Homework


Сделать веб-сервер на flask, который: 1) “повторяет” функционал командной строки линукса для обработки файлов. 2) состоит из одного POST метода. Метод должен удовлетворять следующим требованиям:


1. Доступен по пути /perform_query

2. Принимает 5 параметров: где 1, 2, 3, 4 - запрос, 5-ый - имя файла. 

3. Метод должен искать файлы внутри директории data. Папка data должна находиться в одной папке с веб-сервером.
4. Обрабатывать файл, следуя написанному запросу, и возвращать ответ клиенту

