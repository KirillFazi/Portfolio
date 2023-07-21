# Портфолио | Бирюлин Кирилл | Data Scientist

## Реализованные проекты


| Название проекта                                                                               | Описание                                                                                                                                                                                                                                                                                                                                                        | Используемые технологии                                               |
|:-----------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------|
| [Определение токсичных комментариев](nlp_toxic_comment)                                        | Обучить модель классифицировать токсичные и не токсичные комментарии. Для отправления комментариев на модерацию.                                                                                                                                                                                                                                                | `pandas` `sklearn` `keras` `transformers` `BERT` `PyTorch` `LightGBM` |
| [Определение и перевод японского текста](https://github.com/KirillFazi/jpn_eng_ocr_translator) | Мини веб-сервис, который распознает японский текст с помощью OCR (оптического распознавания символов) и выполняет его перевод на английский язык.                                                                                                                                                                                                               | `pytesseract` `starlette` `transformers` `uvicorn` `docker`           |
| [Анализ для онлайн-магазина игр](online_game_shop)                                             | Проанализировать данные и выявить закономерности, определяющие успешность игры, чтобы сделать ставку на потенциально популярный продукт и спланировать рекламную кампанию.                                                                                                                                                                                      | `pandas` `numpy` `matplotlib` `scipy`                                 |
| [Прототип модели предсказания эффективности предприятия для "Цифра"](gold_recovery_cifra)      | Построить прототип модели машинного обучения для предсказания коэффициента восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. По ходу проекта, нужно было разобраться в бизнес процессе золотодобывающих компаний и ввести собственную метрику качества. | `pandas` `matplotlib` `seaborn`  `Sklearn` `GradientBoosting`         |
| [Прогнозирование заказов такси](taxi_time_series)                                              | Обучить модель для предсказания количества заказов такси на следующий час.                                                                                                                                                                                                                                                                                      | `pandas` `matplotlib` `statsmodels` `sklearn` `CatBoost` `pickle`     |
| [Предсказание стоимости автомобиля](auto_price_predict)                                        | Обучить модель для определения рыночной стоимости автомобиля. Основываясь на исторических данных. В проекте нужно было найти баланс между факторами: качество, скорость предсказания и время обучения моделей. Было сделано сравнение и лучшие модели были помещены в Pipline                                                                                   | `pandas` `sklearn` `CatBoost` `LightGBM` `sklearn.pipeline` `joblib`  |
| [Создание эмбеддинга пользователя и фильма для системы рекомендаций](user_movie_embeddings)    | Построить векторное представление пользователей и фильмов используя нейросетевые подходы, чтобы можно было по эмбеддингу пользователя искать похожие эмбеддинги фильмов и рекомендовать ему их.                                                                                                                                                                 | `pandas` `matplotlib` `keras` `sklearn`                               |
| [Выбор локации для размещения скважины](geo_oil_well_search)                                   | Построить модель для предсказания объёма запасов в новых скважинах. Определить регион добычи нефти с максимальной прибылью. Оценить соотношение рисков и прибыли. Сделать выводы и рекомендации                                                                                                                                                                 | `pandas` `seaborn` `matplotlib` `statsmodels` `sklearn`               |