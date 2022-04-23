# SaaS Shop

## Репозитории проекта

* Сервис продуктов - https://github.com/AnyaGl/saas-shop-service-product
* Сервис заказов - https://github.com/kelvionald/saas-shop-service-order-js
* Сервис клиентов - https://github.com/IrinaZagaynova/saas-shop-service-client
* ЛК клиента - https://github.com/Desire4sorrow/saas-shop-frontend
* Мок сайт - https://github.com/Chicony/saas-shop-site
* Админка бухгалтера - https://github.com/VladimirSovkov/saas-shop-billing-admin
* DevOps - https://github.com/gstaizer/saas-shop-dev-ops
* n8n - https://github.com/kelvionald/saas-shop-service-flow

## Полезные команды

* Docker Compose
    * Запуск ```docker-compose up -d```
    * Остановка ```docker-compose down```
    * Логи ```docker-compose logs```
* Keycloak
    * Запуск ```docker run —net=host -e PROXY_ADDRESS_FORWARDING=true —restart always -d —name optimized_keycloak prebuilt_keycloak```
    * Остановка ```docker stop optimized_keycloak && docker rm optimized_keycloak```