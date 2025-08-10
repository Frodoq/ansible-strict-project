1. Создан файл "requirements.yml" с ролью ClickHouse
2. Роль ClickHouse скачана с помощью "ansible-galaxy"
3. Созданы роли для Vector  и LightHouse с помощью "ansible-galaxy role init"
4. Роли заполнены задачами, переменными (разделены между vars и default) и шаблонами
5. Конфиги перенесены в директорию templates
6. Созданы README.md для обеих ролей с описанием параметров
7. Шаги 3-6 повторены для lightHouse
8. Роли выложены в репозитории с семантической нумерацией (тег 1.0.0)
9. Playbook  переработан на использование ролей
10. Playbook выложен в репозиторий
11.
## Ссылки на репозитории

1. Роль Vector:  
   https://github.com/Frodoq/vector-role  
   Версия: 1.0.0

2. Роль LightHouse:  
   https://github.com/Frodoq/lighthouse-role  
   Версия: 1.0.0
