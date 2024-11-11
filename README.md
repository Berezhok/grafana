## Обязательные задания
## Задание 1
### Используя директорию help внутри этого домашнего задания, запустите связку prometheus-grafana.
### Зайдите в веб-интерфейс grafana, используя авторизационные данные, указанные в манифесте docker-compose.
### Подключите поднятый вами prometheus, как источник данных.
### Решение домашнего задания — скриншот веб-интерфейса grafana со списком подключенных Datasource.
### ------------------------------------------------------------------
### Ответ:
### Prometheus вроде подключил, он появился в data sourse
### ![](https://github.com/Berezhok/grafana/blob/main/img/grafana1.png)
### Но он не работает, prometheus не стартует выходит ошибка, прочитал всякие форумы , пытался запустить не из контейнера, все равно какие-то ошибки
### ![](https://github.com/Berezhok/grafana/blob/main/img/dockerError.png)
## Задание 2
### Изучите самостоятельно ресурсы:
### 
### PromQL tutorial for beginners and humans.
### Understanding Machine CPU usage.
### Introduction to PromQL, the Prometheus query language.
### Создайте Dashboard и в ней создайте Panels:
### 
### утилизация CPU для nodeexporter (в процентах, 100-idle);
### CPULA 1/5/15;
### количество свободной оперативной памяти;
### количество места на файловой системе.
### Для решения этого задания приведите promql-запросы для выдачи этих метрик, а также скриншот получившейся Dashboard.
### 
## Задание 3
### Создайте для каждой Dashboard подходящее правило alert — можно обратиться к первой лекции в блоке «Мониторинг».
### В качестве решения задания приведите скриншот вашей итоговой Dashboard.
## Задание 4
### Сохраните ваш Dashboard.Для этого перейдите в настройки Dashboard, выберите в боковом меню «JSON MODEL». Далее скопируйте отображаемое json-содержимое в отдельный файл и сохраните его.
### В качестве решения задания приведите листинг этого файла.