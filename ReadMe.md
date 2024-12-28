Запилим обработку метрик со всех приложений

1. Создадим неймспейс в кубере для графаны и прометеуса
[namespace.yaml](namespaces/monitoring.yaml) и применим его `kubectl apply -f namespace.yml`

2. Создадим конфиг для подика прометеуса [prometheus-config.yaml](monitoring/prometheus-cfg.yaml)
3. Создадим сам деплоймент юнит для прометеуса 
4. Прокинем порты с помощью сервиса ноды