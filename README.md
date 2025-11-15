# Добавляем папку для чтения файла
Открой фаил docker-compose.yml и впиши разделе services в volumes путь к своей папке на локальном компьютере где будут храниться файлы для чтения
Пример - "Путь к твоей папки":/var/lib/clickhouse/user_files/dsw-ammend
# Задаем параметры для входа
в docker-compose.yml уже прописаны логин и пароль, ты можешь их изменить
CLICKHOUSE_USER: admin
CLICKHOUSE_PASSWORD: admin
# Входим в clickhouse через DBever
Запускаем докер и входим в DBever
Порт - 8123
БД/Схема - raw_layer
Пользовател - admin (или свое значение, если менял в docker-compose.yml)
Пароль - admin (или свое значение, если менял в docker-compose.yml)