### Определение стоимости автомобилей

Данные: технические характеристики, комплектации и цены автомобилей. Нужно построить модель для определения стоимости.
Цель: Написание модели для быстрого вывода рыночной стоимости автомобиля.

**Заказчику важны:**
- качество предсказания;
- скорость предсказания;
- время обучения.

### Используемые библиотеки: pandas, numpy, matplotlib, catboost, lightgbm, sklearn:(preprocessing, model_selection, metrics, ensemble)


**Этапы:**
1. Подготовка данных и предобработка.
2. Обучение моделей
3. Анализ моделей
4. Вывод

### Основные выводы:

Модели добились хороших результатов по скорости и rmse, в каждой метрике есть свои лидеры. По скорости предсказания – CatBoost; по скорости обучения – LightGBM; rmse – LightGBM. Если по rmse и скорости предсказания модели где-то рядом, то перевес в сторону LightGBM начинается на скорости обучения.

Сравнивая результаты OHE и ОЕ случайного леса, можно сказать, что обучение с кодировкой ОЕ проходит гораздо быстрее.

Для данного проекта лучшей моделью будет являться LightGBM с глубиной в 10.

### Проект завершен.
