### Playbook производит скачивание, установку и запуск сервисов ''Clickhouse'' и ''Vector'', версии которых заданы в переменных, размещенных в соответствующем файле `group_vars/clickhouse/vars.yml`:
- `clickhouse_version:` - версия Clickhouse;
- `vector_version:` - версия Vector;
- `clickhouse_packages:` - состав скачаиваемых пакетов Clickhouse.

### Для двух имеющихся Play заданы соответствующие теги:
- `clickhouse` - для обработки Play с установкой и запуском Clickhouse;
- `vector` - для обработки Play с установкой и запуском Vector.
