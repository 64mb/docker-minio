# minio 🦩

S3 совместимое self-hosted объектное хранилище файлов

### Переменные среды

- `DOMAIN` - основной домен хоста, на котором происходит развертывание и проксирование minio контейнера
- `HT_PASSWD` - пароль в формате HTPASSWD для защиты панели traefik 
- `IP_FILTER` - список доступных IP-адресов для защиты панели, через запятую
- `ACCESS_KEY` - ключ доступа к S3 хранилищу
- `SECRET_KEY` - пароль доступа к S3 хранилищу
- `REGION` - регион работы объектного хранилища
- `CORS_ALLOW_ORIGIN` - CORS заголовки доступа с других ресурсов
- `BROWSER` - веб-панель minio S3 для работы с файлами в браузере
- `DATA_FOLDER` - точка монитрования с хост машины для хранения файлов
- `ACME_EMAIL` - Email адрес администратора для выписывания Let`s Ecnrypt сертификатов