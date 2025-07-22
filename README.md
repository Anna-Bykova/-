/* static/css/style.css */

/* Основные стили страницы */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f5f5f5;
  color: #333;
  line-height: 1.6;
}

/* Сетка и контейнер */
header, footer {
  background: #444;
  color: #fff;
  padding: 1rem 2rem;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin-right: 1rem;
}

nav a:hover {
  text-decoration: underline;
}

main {
  max-width: 800px;
  margin: 2rem auto;
  padding: 0 1rem;
  background: #fff;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

/* Сообщения флэш */
ul.flashes {
  list-style: none;
  padding: 0;
  margin: 1rem 0;
}

ul.flashes li {
  background: #fffae6;
  border: 1px solid #ffe58f;
  color: #664d03;
  padding: 0.75rem 1rem;
  border-radius: 3px;
  margin-bottom: 0.5rem;
}

/* Статьи и посты */
article {
  margin-bottom: 2rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #eee;
}

article h2, article h3 {
  margin: 0 0 0.5rem;
}

article p {
  margin: 0.5rem 0;
}

/* Стили для форм */
form p {
  margin-bottom: 1rem;
}

form input[type="text"],
form input[type="password"],
form textarea {
  width: 100%;
  padding: 0.5rem;
  border: 1px solid #ccc;
  border-radius: 3px;
  box-sizing: border-box;
}

form button,
form input[type="submit"] {
  background: #28a745;
  color: #fff;
  border: none;
  padding: 0.6rem 1.2rem;
  border-radius: 3px;
  cursor: pointer;
}

form button:hover,
form input[type="submit"]:hover {
  background: #218838;
}

/* Кнопки-ссылки */
a.button {
  display: inline-block;
  padding: 0.5rem 1rem;
  background: #007bff;
  color: #fff;
  text-decoration: none;
  border-radius: 3px;
  margin: 0.5rem 0;
}

a.button:hover {
  background: #0069d9;
}

/* Комментарии */
.comment {
  padding: 1rem;
  border: 1px solid #ddd;
  border-radius: 3px;
  margin-bottom: 1rem;
  background: #fafafa;
}

/* Пагинация */
.pagination {
  text-align: center;
  margin: 2rem 0;
}

.pagination a {
  color: #007bff;
  text-decoration: none;
  margin: 0 0.5rem;
}

.pagination span {
  margin: 0 0.5rem;
}

/* Футер */
footer {
  text-align: center;
  font-size: 0.9rem;
}
