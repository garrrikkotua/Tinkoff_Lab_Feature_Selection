# Tinkoff_Lab_Feature_Selection
 Tinkoff_Lab_Feature_Selection
 
 Это репозиторий проекта лаборатории финансовых технологий Тинькофф.
# Цель проекта
Используя данные партнеров компании, отобрать самые важные признаки для улучшения моделей предсказания дефолтности и грейсовости     клиентов.

# Использованные методы отбора признаков
    1. Univariate selection 
    <https://scikit-learn.org/stable/auto_examples/feature_selection/plot_feature_selection.html>
    2. Backward elimination with p-value 
    <https://medium.com/@mayankshah_85820/machine-learning-feature-selection-with-backward-elimination-955894654026>
    3. Forward selection 
    [http://rasbt.github.io/mlxtend/user_guide/feature_selection/SequentialFeatureSelector/]
    4.  L1-based feature selection 
    [https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html#sklearn.linear_model.Lasso]
    5. PCA
    [https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html]
    6. Feature importance используя XgBoost
    [https://machinelearningmastery.com/feature-importance-and-feature-selection-with-xgboost-in-python/]
    7. Feature importance используя Catboost
    [https://catboost.ai/docs/concepts/fstr.html]
    
 # Описание файлов
    1. working_with_grace.ipynb, working_with_pd.ipynb - сравнение методов 1, 2, 4 и 5 для grace и pd соответсвенно
    2. Trying_xgboost_grace.ipynb, Trying_xgboost_pd.ipynb - 6 и 7 для grace и pd соответсвенно
    3. Forward_selection.ipynb - 3 метод для grace и pd
    4. Combining_models_pd.ipynb, Combining_models_grace.ipynb - комбинирование моей и текущей модели для сравнения (используя метод 2)
    5. Combining_models_pd_fs.ipynb, Combining_models_grace_fs.ipynb  комбинирование моей и текущей модели для сравнения (используя метод 3)
    6. comparison_methods.xlsx - итоговая таблица сравнения всех методова 1-7
    7. comparison_tinkoff.xlsx - итоговая таблица сравнения моей модели и текущей (на методах 2 и 3)
    8. Отчет_по_проделанной_работе.docx - описание проделанной работы
    9. autoencoder.ipynb - попытка понижения размерности датасета с помощью нейронной сети
    10. все остальное - данные и служебные файлы

 # Смотрите файл "Отчет_по_проделанной_работе.docx", чтобы узнать подробности.
