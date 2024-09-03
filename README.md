# Отказоустойчивый сайт с балансировкой нагрузки через Yandex Network Load Balancer

Вы создадите облачную сеть [Yandex Virtual Private Cloud](https://yandex.cloud/ru/docs/vpc/), развернете группу ВМ [Yandex Compute Cloud](https://yandex.cloud/ru/docs/compute/) и настроите балансировку между двумя зонами доступности для защиты веб-сайта от сбоев с помощью [Network Load Balancer](https://yandex.cloud/ru/docs/network-load-balancer/).

Для создания веб-сайта используется стек [LAMP](https://ru.wikipedia.org/wiki/LAMP) (Linux, Apache HTTP Server, MySQL, PHP) или LEMP (веб-сервер Apache заменяется на [Nginx](https://www.nginx.com/)).

Подготовка инфраструктуры для отказоустойчивого сайта с балансировкой нагрузки через Yandex Network Load Balancer с помощью Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/web/load-balancer-website), необходимый для настройки конфигурационный файл `load-balancer.tf` расположен в этом репозитории.
