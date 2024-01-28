# Items matching algorithm 
## Алгоритм для подбора наболее похожих товаров из набора данных
## Описание данных
- base.csv анонимизированный набор товаров. Каждый товар представлен как уникальный id и вектор размерностью 72
- train.csv обучающий датасет. Каждая строчка - товар, для которого известен уникальный, вектор признаков и id товаров из base.csv, который максимально поход на него (по мнению экспертов). Т.е. - это файл с размеченными данными
- validation.csv - датасет с товарами, для который нужно было найти похожие (протестировать алгоритм)
- validation_answer - датасет с ответами к validation.csv, необходимый для подсчета метрики accuracy@5
## Задача
- Необходимо было разработать алгоритм подбора наиболее подходящих товаров для выборки validation.csv из датасета base.csv и протестировать алгоритм с помощью метрики accuracy@5
  
