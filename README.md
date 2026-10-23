# Книжный рекомендательный сервис

Сравнение четырёх моделей на Goodbooks-10k: Popularity, Content-Based, Item-Based CF и SVD.

В `homework_books.ipynb` выполнены анализ данных, обучение моделей и сравнение по RMSE, Precision@10, Recall@10 и nDCG@10. Дополнительно проверены число оценённых соседей у CF и влияние личных предпочтений на выдачу SVD. Результаты, графики и выводы сохранены в ноутбуке.

Данные разделены на train/validation/test в пропорции 80/10/10. Параметры SVD выбраны на validation; итоговое сравнение проведено на test. Уже оценённые книги исключены из рекомендаций.

Для просмотра нужно открыть ноутбук. Для повторного запуска нужен Python с пакетами `numpy`, `pandas`, `scipy`, `scikit-learn`, `matplotlib`, `scikit-surprise` и `threadpoolctl`.

Данные: [Goodbooks-10k](https://github.com/zygmuntz/goodbooks-10k), лицензия [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
