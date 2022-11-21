Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Использовались модели: RandomForestClassifier, DecisionTreeClassifier, LogisticRegression с разными подходами к устранению дисбаланса классов. 

Построена модель с предельно большим значением F1-меры - RandomForestClassifier(class_weight='balanced', max_depth=16, n_estimators=130, random_state=12345), с метрикой ~0.63338.
