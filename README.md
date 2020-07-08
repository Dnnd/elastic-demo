## Запуск

```
docker-compose up -d
```
## Перезапуск без удаления данных
```
docker-compose restart
```
## Перезапуск с удалением данных

```
docker-compose down
docker volume rm elastic-demo_es-storage 
docker-compose up -d
```

## Параметры
Порт - `9200`

