# Portfolio_RU

В этом репозитории собраны мои проекты связанные с DS/DA. Основы для проектов взяты с Яндекс.Практикума, Kaggle и других источников.

Избранные проекты:
- [Создание модели для предсказания выручки с проката фильмов](https://github.com/dmakhazen/portfolio/tree/main/movies_revenue_prediction), так как он был одним из наиболее интересным с точки зрения инженерии признаков, в нем не работали решения вроде "закодировать все признаки" и лишь ухудшали метрики модели. На странице проекта есть графический абстракт, в котором можно увидеть логику работы и характеристики модели. Данный проект я взял за основу для дальнейшей разработки и вывода модели в продакшн, от создания парсера IMDB до сайта-странички с показом предсказаний выручки от новых фильмов (пока в разработке).
- [Предсказание температуры сплава в литьевом ковше](https://github.com/dmakhazen/portfolio/tree/main/steelmaking#readme). Один из самых интересных проектов. В этом проекте понадобилось вникнуть в основы процесса происходящего в литейном ковше, использовать данные из разных источников, а также я воспользовался optuna для подбора гиперпараметров и shap для анализа итоговой модели.

А еще есть мини-игра [Breakout!](https://codeinplace.stanford.edu/cip3/share/HxMNul1cmaTTNyLUXD6Y)[.](https://codeinplace.stanford.edu/cip3/share/M3fZDX4z8CeNFPEtVQk7)

| #    | Имя проекта                | Описание                                                         | Стек                                                          |
| ---- | --------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------- |
| 1.   | [Sentiment analysis toxic comments](https://github.com/dmakhazen/portfolio/tree/main/NLP_sentiment_analysis#readme) | Анализ тональности комментариев при помощи TF-IDF и предобученных BERT моделей | python, pandas, NLP, sklearn, BERT |
| 2.   | [Taxi orders prediction](https://github.com/dmakhazen/portfolio/tree/main/taxi_orders_prediction#readme)  | Предсказание заказов такси во временном ряду при помощи различных моделей ML | python, pandas, matplotlib, numpy, statsmodels, sklearn, gradient boosting |
| 3.   | [EDA analysis games dataset](https://github.com/dmakhazen/portfolio/tree/main/EDA_games#readme) | Исследовательский анализ данных о продажах комьютерных игр в различных регонах | python, pandas, matplotlib, seaborn, scipy |
| 4.   | [Movie revenue prediction](https://github.com/dmakhazen/portfolio/tree/main/movies_revenue_prediction#readme) | Создание модели для предсказания выручки с проката фильмов | python, pandas, matplotlib, seaborn, sklearn, catboost |
| 5.   | [Bank customer churn](https://github.com/dmakhazen/portfolio/tree/main/bank_customer_churn#readme) | Создание модели для предсказания оттока клиентов из банка | python, pandas, sklearn |
| 6.   | [CV age prediction](https://github.com/dmakhazen/portfolio/tree/main/CV_age_prediction#readme) | Определение возраста по фотографии | python, pandas, keras, ResNet |
| 7.   | [Oil location profit prediction](https://github.com/dmakhazen/portfolio/tree/main/oil_location_profit_prediction#readme) | Поиск наиболее прибыльного региона для нефтедобычи | python, pandas, sklearn, matplotlib |
| 8.   | [Car price prediction](https://github.com/dmakhazen/portfolio/tree/main/car_price_prediction#readme) | Оценка цены автомоболиля при помощи ML модели | python, pandas, sklearn, catboost, lightgbm |
| 9.   | [Ore recovery prediction](https://github.com/dmakhazen/portfolio/tree/main/ore_recovery_prediction#readme) | Создание модели ML для оценки коэффициента востановление золота из руды | python, pandas, sklearn, matplotlib, seaborn |
| 10.   | [Steelmaking temp prediction](https://github.com/dmakhazen/portfolio/tree/main/steelmaking#readme) | Предсказание температуры сплава в литьевом ковше | python, pandas, sklearn, matplotlib, seaborn, optuna, shap |
