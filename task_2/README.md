##Сборка образа
###docker build ./ --tag stocksproducts:0.0.1


##Запуск контейнера
###docker run --name my_stocksproducts -d -p 8000:8000 stocksproducts:0.0.1