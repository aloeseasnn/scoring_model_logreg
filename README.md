# Скоринговая модель

Проект реализует модель логистической регрессии для задачи кредитного скоринга

Содержимое папки:

- **scoring_model_logreg.ipynb** - ноутбук с обучением модели  
- **scoring_dataset.csv** - тренировочные данные  
- **new_data_for_scoring.csv** - новые данные для предсказаний  
- **scoring_logreg.pkl** - файл обученной модели для импорта
- **requirements.txt** - файл для установки зависимостей
- **README.md** - readme

## Запуск
```bash
pip install -r requirements.txt
jupyter notebook scoring_model_logreg.ipynb
