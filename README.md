# Machine Learning Fundamentals: Classification, Regression & Clustering

[English](#english) | [Русский](#русский)

---

## English

A hands-on **Machine Learning** project built with **Python 3** and **scikit-learn**, covering the core workflows of supervised and unsupervised learning on user activity logs. The notebooks progress from feature engineering and binary classification to decision boundary visualization, multiclass encoding, cross-validation, regression modeling, and user behavioral clustering.

### Tech Stack & Tools
* **ML & Data Processing:** `scikit-learn`, `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook

### Project Structure (`src/`)

* **`ex00/00_binary_classifier_logreg.ipynb`** — **Feature Engineering & Binary Classification:** Extracting intraday commit features (commits before and after midday) from raw timestamps and training a Logistic Regression classifier to distinguish weekdays from weekends.
* **`ex01/01_binary_classifier_svm_tree.ipynb`** — **Decision Boundaries & Model Comparison:** Training and comparing Logistic Regression, Support Vector Machines (`SVM`), and Decision Trees, and plotting 2D decision boundaries to inspect how each algorithm partitions the feature space.
* **`ex02/02_multiclassi_one-hot.ipynb`** — **Multiclass Classification & Feature Encoding:** Applying One-Hot Encoding to categorical variables, predicting the exact day of the week across multiple algorithms (including Random Forest), and analyzing feature importances.
* **`ex03/03_split_crossval.ipynb`** — **Overfitting Prevention & Validation:** Addressing model overfitting by implementing `train_test_split` and $k$-fold cross-validation (`cross_val_score`) to obtain reliable out-of-sample performance metrics.
* **`ex04/04_regression.ipynb`** — **Regression Modeling:** Predicting continuous target values (average time-to-deadline delta per user) based on Newsfeed pageviews and total commit counts.
* **`ex05/05_clustering.ipynb`** — **Unsupervised Learning & User Segmentation:** Applying clustering algorithms to segment users into homogeneous behavioral groups for targeted product engagement.

### Usage
* Place the required datasets inside `src/data/` and open any notebook in Jupyter Lab / Jupyter Notebook or VS Code: `jupyter notebook src/ex01/01_binary_classifier_svm_tree.ipynb`

---

## Русский

Практический проект по основам **машинного обучения** на **Python 3** и библиотеке **scikit-learn**, охватывающий ключевые задачи обучения с учителем и без учителя на логах активности пользователей. Ноутбуки последовательно раскрывают конструирование признаков, бинарную и мультиклассовую классификацию, визуализацию границ решений, кросс-валидацию, регрессию и кластеризацию пользователей.

### Стек и инструменты
* **ML и обработка данных:** `scikit-learn`, `pandas`, `numpy`
* **Визуализация:** `matplotlib`, `seaborn`
* **Среда разработки:** Jupyter Notebook

### Структура проекта (`src/`)

* **`ex00/00_binary_classifier_logreg.ipynb`** — **Конструирование признаков и бинарная классификация:** Извлечение дневных признаков активности (число коммитов до и после полудня) из временных меток и обучение логистической регрессии для разделения рабочих и выходных дней.
* **`ex01/01_binary_classifier_svm_tree.ipynb`** — **Границы решений и сравнение моделей:** Обучение и сравнение логистической регрессии, метода опорных векторов (`SVM`) и дерева решений с визуализацией двумерных границ решений (decision boundaries).
* **`ex02/02_multiclassi_one-hot.ipynb`** — **Мультиклассовая классификация и кодирование признаков:** Применение One-Hot Encoding для категориальных переменных, предсказание конкретного дня недели с помощью различных алгоритмов (включая Random Forest) и анализ важности признаков.
* **`ex03/03_split_crossval.ipynb`** — **Борьба с переобучением и валидация:** Оценка обобщающей способности моделей с помощью разбиения `train_test_split` и $k$-блочной кросс-валидации (`cross_val_score`).
* **`ex04/04_regression.ipynb`** — **Задачи регрессии:** Прогнозирование непрерывной целевой переменной (средней дельты времени между первым коммитом и дедлайном) на основе просмотров ленты новостей и числа коммитов пользователя.
* **`ex05/05_clustering.ipynb`** — **Обучение без учителя и сегментация:** Применение алгоритмов кластеризации для выделения однородных поведенческих групп пользователей с целью настройки продуктовых триггеров.

### Запуск
* Поместите необходимые датасеты в директорию `src/data/` и откройте нужный ноутбук в Jupyter Notebook / Jupyter Lab или VS Code: `jupyter notebook src/ex01/01_binary_classifier_svm_tree.ipynb`
