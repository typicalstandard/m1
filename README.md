# Pandas
"""
### 1. Предварительная подготовка данных
**Сортировка**
   - Для `merge_asof`, данные должны быть отсортированы по столбцу с датами (например, `update_date` и `order_date`).
**Уменьшение типов данных**
**Индексация**

### 2. Оптимизация операций
**Векторизация**
   - Использование векторизированных операций pandas с помощью NumPy вместо циклов.
**Использование категориальных данных**

### 3. Проблемы с памятью и масштабирование 
**Кэширование промежуточных результатов**
**Разделение на чанки**
   - Если данные не помещаются в память, можно разбивать их на части с помощью numpy (`numpy.array_split`) или метода `cut`.

### 4. Переход на распределённые вычисления
   - Можно использовать Dask или PySpark, если данные не помещаются в память и нужна параллельная обработка данных.
"""
