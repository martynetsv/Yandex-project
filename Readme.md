Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет

Цель- Построить модель с предельно большим значением F1-меры. (более 0.59)

Были использованы модели: DummyCl, DecisionTreeCl и RandomForest Cl

Так как по условию задачи цель f1-мера не ниже, чем 0.59 лес решений показал лучший результат (При 12 деревьях, 20 ветвях, и увеличению сэмпла в 4 раза для балансировки). Лучшая метрика была получена при увеличиении сэмпла f1-score: f1-score: 0.64905 roc-auc: 0.84698
