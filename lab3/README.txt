Датасети по завданням:
1) https://www.kaggle.com/datasets/sujithmandala/credit-score-classification-dataset
2) https://www.kaggle.com/datasets/gpiosenka/iconic-wwii-aircraft-imagesclassification?select=airplanes.csv
3) https://www.kaggle.com/datasets/pashupatigupta/emotion-detection-from-text

1. Повнозв'язані нейронні мережі (FCNN)
Вирішіть завдання класифікації даних, з якими ви працювали в лабораторній № 1 за допомогою повнозв’язаної нейромережі прямого поширення (fully connected feed-forward network). Результати порівняйте з одержаними раніше.

2. Згорткові нейронні мережі (CNN)
Вирішіть завдання класифікації зображень за допомогою згорткової (convolutional) нейромережі (якщо в обраному датасеті класів забагато, достатньо залишити 3-5).

3. Рекурентні нейронні мережі (RNN)
Вирішіть задачу класифікації текстів (з якими ви працювали в лабораторній № 2) за допомогою рекурентної нейромережі. Результати порівняйте з одержаними раніше. 



Imports:
$ pip install matplotlib
$ pip install pandas
$ pip install scikit-learn
$ pip install nltk
$ pip install tensorflow

In case you want to print ANN:
1) Install graphviz:
$ pip install graphviz

Use winget or choco:
$ winget install graphviz

Add graphviz /bin folder to your system PATH:	C:\Program Files\Graphviz\bin


2) Install ann_visualizer:
$ pip install ann_visualizer

Replace all "keras.layers.core." with " keras.layers." in visualize.py: C:\Users\lol19\AppData\Local\Programs\Python\Python310\Lib\site-packages\ann_visualizer\visualize.py

