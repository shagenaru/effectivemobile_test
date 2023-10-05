# effectivemobile_test
playbook состоит из трех ролей:
nginx - генерирует nginx конфигурацию и отправляет файл на хост
php - отправляет файл php и dockerfile на хост
compose - генерирует docker-compose файл, где через перменную передаются доступы для mysql и запускает контейнеры
