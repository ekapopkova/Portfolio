# Портфолио

## Здесь собраны pet-project, хакатоны, проекты выполненные во время соревнований на Kaggle

| №  | Наименование проекта | Описание | Используемые библиотеки |
| -- | -------------------- | -------- | ------------------------|
| 1. | [Прогнозирование стоимости автомобилей на вторичном рынке (соревнования на Kaggle)](https://github.com/ekapopkova/Predict_car_price) | Разработка модели предсказания стоимости автомобиля на вторичном рынке | pandas, seaborn, matplotlib, sklearn, catboost |
| 2. | [Решение задачи сопоставления и поиска наиболее похожих товаров](https://github.com/ekapopkova/Matching) | Разработка ML решения по задаче метчинга товаров | pandas, numpy, matplotlib, faiss, catboost, scikit-learn, joblib |
| 3. | [Хакатон кормпании Ренью. Сортировка твердых бытовых отходов](https://github.com/ekapopkova/Tracking_object) | Разработка решения для отслеживания и сортировки мусора на конвейере – выделять пластиковые бутылки в общем потоке предметов, трекинг объектов | pandas, numpy, opencv, YOLO, Pillow, motmetrics, matplotlib, scikit-learn |
| 4. | [Классификация видеороликов по описанию (соревнование на Kaggle)](https://github.com/ekapopkova/Classification-video) | Разработка решения для определения принадлежности видеороликов к проектам на основе анализа текстового описания и другой доступной информации | pandas, numpy, scikit-learn, spacy, googletrans, nltk, re, BERT, matplotlib, pytorch |

## Здесь собраны учебные проекты, выполненные в Яндекс Практикуме

Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Специалист по Data Science".

| Наименование проекта | Задача проекта | Описание проекта | Используемые библиотеки |
| -------------------- | -------------- | ---------------- | ----------------------- |
| [Выпускной проект - Прогноз температуры стали во время плавки](https://github.com/ekapopkova/Steel_temperature) | Прогноз температуры стали во время плавки | Для оптимизации производственных расходов, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. На основе данных предоставленных комбинатом была построена модель, которая предсказывает температуру стали с заданной точностью. | Python, SQL, pandas, matplotlib, seaborn, numpy, torch, skorch, scikit-learn, lightgbm, catboost, random, sqlalchemy |
| [Поиск по изображению](https://github.com/ekapopkova/Search_image) | Разработать простой поиск картинок по запросу | На основе предоставленных данных была разработана модель соединяющая текстовые данные и изображения. При разработке были учтены законодательные ограничения. | Python, pandas, matplotlib, seaborn, numpy, pytorch, pathlib, transformers, scikit-learn, lightgbm, torchvision, random, glob, PIL, Bert, statistics |
| [Обработка фотографий покупателя](https://github.com/ekapopkova/Comp_vision) | Определение возраста по фотографии | Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Для этого была построена модель, которая по фотографии определит приблизительный возраст человека. В распоряжении был набор фотографий людей с указанием возраста. | Python, Keras, pandas, matplotlib |
| [Обучение модели классификации комментариев](https://github.com/ekapopkova/Text_classification) | Определение токсичности комментариев. | Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Для решения данной задачи была разработана модель, которая определяет тональность текста (токсичный комментарий или нет). | Python, pandas, BERT, nltk, tf-idf, matplotlib, scikit-learn, lightgbm, pytorch, transformers, optuna |
| [Прогнозирование количества заказов такси на следующий час](https://github.com/ekapopkova/Project_taxi) | Разработка системы предсказания объема заказа. | Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Была разработа модель для такого предсказания. | Python, pandas, matplotlib, scikit-learn, lightgbm, catboost, statsmodels |
| [Разработка системы предупреждения аварий на каршеринге](https://github.com/ekapopkova/Prediction_crash) | Построить систему предупреждения об аварии клиентам каршеринга | На основе исторических данных из базы данных выявить причины возникновения аварий и создать оповещение для безопасного вождения. | Python, SQL, PostgreSQL, sqlalchemy, pandas, matplotlib, seaborn, scikit-learn, lightgbm, catboost, phik |
| [Прогнозирование температуры звезды](https://github.com/ekapopkova/Stars_temperature) | Прогнозирование температуры на поверхности звезды | На основе косвенных данных необходимо разработать нейронную сеть, которая поможет предсказывать абсолютную температуру на поверхности звезды. | Python, pandas, matplotlib, seaborn, scikit-learn, numpy, torch, random |
| [Построение модели определения стоимости автомобиля](https://github.com/ekapopkova/Car_price) | Разработка системы рекомендации стоимости автомобиля на основе его описания | Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля. | Python, pandas, matplotlib, seaborn, scikit-learn, numpy, lightgbm, catboost, phik |
| [Защита данных клиентов страховой компании](https://github.com/ekapopkova/Project_person_data) | Разработка модели анонимизации персональных данных | Необходимо защитить данные клиентов страховой компании. Необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию, обосновать корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется. | Python, pandas, matplotlib, seaborn, scikit-learn, numpy |
| [Прогнозирование стоимости жилья в жилом массиве](https://github.com/ekapopkova/Project_pyspark) | Определить медианную стоимость квартиры | Сервис по продаже квартир заказал разработку модели по прогнозированию стоимости квартиры. Для выполнения данного проекта использовали ситему обработки больших данных | Python, pandas, Spark |
| [Система прогнозирования продажи отелей](https://github.com/ekapopkova/Project_hotel) | Система прогнозирования продажи отелей | Строится модель прогнозирования отказа от брони клиента. В качестве метрики предлагается использовать величину выручки, которая получится после внедрения модели машинного обучения. |Python, pandas, matplotlib, seaborn, scikit-learn |
| [Определение наиболее выгодного региона нефтедобычи](https://github.com/ekapopkova/Choosing_location) | На основе данных геологической разведки выбрать район добычи нефти | Были предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Необходимо построить модель для определения региона, где добыча принесёт наибольшую прибыль. Для анализа прибыли и возмоных рисков применялась техника Bootstrap |Python, pandas, scikit-learn, техника Bootstrap |
| [Прогнозирование оттока клиента Банка](https://github.com/ekapopkova/Project_bank) | На основе данных из банка определить клиентов, которые могут уйти | Из банка каждый месяц стали уходить клиенты. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. |Python, pandas, scikit-learn, matplotlib |
| [Классификаиция клиентов телеком компании](https://github.com/ekapopkova/Project_tarif_mobile) | На основе данных предложить клиенту тариф | Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тарифов.|Python, pandas, scikit-learn, matplotlib |
| [Определение выгодного тарифа для телеком компании](https://github.com/ekapopkova/Project_stat_analys_mob_tarif) | На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.|Python, pandas, matplotlib, seaborn, scipy, numpy |
| [Исследование рынка российского кинопроката](https://github.com/ekapopkova/Project_films) | Выполнить исследование рынка российского кинопроката | Изучить рынок российского кинопроката и выявить текущие тренды. Сделать аналих насколько фильмы, которые получили государственную поддержку, интересны зрителю. |Python, pandas, matplotlib |
| [Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](https://github.com/ekapopkova/Project_flat_price) | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Проведена визуализация данных. | Python, pandas, matplotlib |
| [Исследование надёжности заёмщиков — анализ банковских данных](https://github.com/ekapopkova/Bank_credit) | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок | На основе данных кредитного отдела банка исследовала влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. | Python, pandas, seaborn |
| [Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов](https://github.com/ekapopkova/Project_music) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница) | Проведен обзор и предобработка данных, исследованы три гипотезы о поведении пользователей в Москве и Санкт_Петербурге | Python, pandas |
