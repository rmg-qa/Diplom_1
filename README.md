<h1>Unit-тесты для проверки программы, которая помогает заказать бургер в Stellar Burgers</h1> 

Реализованные сценарии:  
Созданы юнит-тесты, покрывающие классы Bun, Burger, Ingredient, Database

>Процент покрытия операторов составил 100% (отчет: htmlcov/index.html)

Структура проекта:

/praktikum - пакет, содержащий код программы  

/tests - пакет, содержащий тесты, разделенные по классам  

Например, test_set_buns.py, test_available_buns.py и т.д.  

Установка зависимостей:
``` bash
  pip install -r requirements.txt
```
Запуск автотестов и создание HTML-отчета о покрытии операторов:
``` bash
  pytest --cov=praktikum --cov-report=html
```