- CREATE DATABASE "имя"; - создает базу данных с заданным именем
- DROP DATABASE "имя"; - удаляет базу данных с заданым именем
- CREATE TABLE users (
id INT
) - создает таблицу users в выбранной БД с полем id типа int
- DROP TABLE users - удаляет таблицу users в выбранной БД
- CREATE TABLE users (
id INT NOT NULL AUTO_INCREMENT,
name VARCHAR(30)
PRIMARY KEY(id);
) - создает таблицу users, в которой поле id не может быть равно null и каждый раз, при добавлении записи в таблицу будет увеличивать значение в поле id на 1. PRIMARY KEY (id); делает каждую запись уникальной, не позволяет ей повторяться. Также создает поле name, в котором будет храниться текст длинной не более 30 символов
- ALTER TABLE users ADD pass VARCHAR(30) - добавляет к таблице users текстовое поле pass длинной не более 30 символов

