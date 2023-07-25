# Users CRUD Application

### ****Создание таблицы базы данных****

Создайте таблицу с именем `users` в своей базе данных `db-users` в MySQL, используя следующий код.

```sql
CREATE TABLE `users` (
  `id` int(255) NOT NULL AUTO_INCREMENT,
  `name` varchar(255) NOT NULL,
  `email` varchar(255) NOT NULL,
  `age` int(255) NOT NULL,
  PRIMARY KEY (`id`)
)
```

### ****Скопируйте файлы в папку htdocs****

Загрузите вышеуказанные файлы. Создайте папку с именем *users* внутри папки *htdocs* в каталоге *xampp*. Наконец, скопируйте папку *users* в папку *htdocs*. Теперь посетите [localhost/users](http://localhost/users) в своем браузере, и вы должны увидеть приложение.
