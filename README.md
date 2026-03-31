# Домашнее задание к занятию "`ELK`" - `Федюнин Р.Ю.`

---

### Задание 1. Elasticsearch

`Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.`

`Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.`


![elk_1.jpg](https://github.com/rfedyunin/hw_elk/blob/main/img/elk_1.jpg)


---

### Задание 2. Kibana

`Установите и запустите Kibana.`

`Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.`


![elk_2.jpg](https://github.com/rfedyunin/hw_elk/blob/main/img/elk_2.jpg)


---

### Задание 3. Logstash

`ПУстановите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.`

`Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.`


![elk_3.jpg](https://github.com/rfedyunin/hw_elk/blob/main/img/elk_3.jpg)


### Задание 4. Filebeat.

`Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.`

`Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.`


![elk_4.jpg](https://github.com/rfedyunin/hw_elk/blob/main/img/elk_4.jpg)
