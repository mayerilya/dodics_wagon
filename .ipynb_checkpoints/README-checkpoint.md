# Чек-ап вагона

Модель для предсказания даты отправления вагонов в ремонт

## Описание проблемы 
Отправка вагона в плановый ремонт может происходить по разным причинам - как по регламенту (срок/пробег), так и из-за того, что накопились мелкие дефекты(было много текущих ремонтов), не было вариантов на погрузку и т.д. Этих причин много, и все они влияют на возможность осуществления ремонта

# Состав репозитория
* [preds](./preds) - csv-файлы с предсказаниями
* [Data_prep_and_predicting](./Data_prep_and_predicting) - основный ноутбук с обработкой данных, созданием признаков и моделей
* [Linear_regression_pred](./Linear_regression_pred) - csv-файлы и ноутбук с моделью линейной регрессии, предсказывающей остаточный пробег на конец предсказываемого месяца
* [train](./train) - данные для обучения