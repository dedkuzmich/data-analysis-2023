Датасет: https://www.kaggle.com/datasets/sujithmandala/credit-score-classification-dataset

Робота з Jupyter:
$ pip3 install jupyter
$ jupyter notebook

Додаткові модулі:
$ pip3 install pandas
$ pip3 install numpy
$ pip3 install matplotlib
$ pip3 install seaborn
$ pip3 install scikit-learn


Виконати наступне: 
1) Завантажити дані, вивести назви колонок і розмір датасета
2) Опрацювати пропуски (по можливості заповнити їх або видалити)
3) Візуалізувати дані: побудувати графік (heatmap), що відображає кореляції
ознак між собою і з цільовою змінною (розміткою); побудувати гістограми
розподілу ознак і boxplot-и ознак відносно цільової змінної (якщо ознак занадто багато
обмежитися декількома)
4) Нормалізувати дані
5) Провести навчання наступних класифікаторів:
    kNN
    дерево ухвалення рішень
    SVM
    Random Forest
    AdaBoost

Підібрати оптимальні параметри
• для kNN
• для SVM за допомогою GridSearch підібрати оптимальні «C» і «gamma»
Серед обраних оптимальних моделей кожного класу вибрати найкращу.
Відобразити
sklearn.metrics.classification_report і sklearn.metrics.confusion_matrix
