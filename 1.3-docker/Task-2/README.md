## Сборка docker image

docker build ./ --tag stocks_products_project:1.0

## Запуск контейнера

docker run -d -p 8000:8000 stocks_products_project:1.0
