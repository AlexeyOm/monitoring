Настроенные в Prometheus alert'ы:
  jenkins_down
  jenkins_high_cpu
  jenkins_high_memory
  high_cpu_load 
  high_storage_load
  monitor_service_down

В Grafana 4 dashboard:
  Docker containers
  Docker host
  Monitor services
  Nginx
Предназначенные для мониторинга соответственно контейнеров докера, сервера докера, prometheus и nginx

На дашборде Docker containers выведены следующие метрики:
  Загруженность ЦП в процентах
  Число ядер ЦП
  Загруженность ОЗУ в процентах
  Загруженность ОЗУ в MiB
  Загруженность хранилища в процентах
  Загруженность хранилища в GiB
  Количество работающих контейнеров
  Загруженость системы
  Объем считываемых и записываемых данных, время на ввод и вывод
  Использование ЦП контейнером
  Использование ОЗУ контейнером
  Использование кэша контейнером
  Использование сети контейнером на прием
  Использование сети контейнером на передачу
