Для чего нужен этот проект?

Проект для парсинга компаний и их вакансий с платформы HeadHunter через API и последующим сохранением в базу данных. Используемая СУБД в проекте PostgreSQL.

Для работы с проектом необходимо: Создать файл с названием database.ini, который заполняется следующим образом: 
[postgresql] 
host=имя_компьютера или localhost 
user=database_user 
password=database_password 
port=database_server_port

Для запуска необходимо запустить модуль main.py в каталоге src