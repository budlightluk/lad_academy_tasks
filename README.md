# Проекты

## Проект 1: Анализ вакансий IT-специалистов с сайта hh.ru

**Описание проекта:**

В этом проекте разработан алгоритм для получения данных о количестве вакансий по направлениям Data Analyst, Data Scientist и Data Engineer в разрезе уровней квалификации (Junior, Middle, Senior) с сайта hh.ru. Алгоритм позволяет анализировать рынок труда в IT-сфере в выбранных регионах России.

### Основные компоненты:

- **Сбор данных:**
  - Использование API hh.ru для получения актуальной информации о вакансиях.
  - Параметризованный сбор данных по направлениям, уровням и регионам.

- **Предобработка данных:**
  - Обработка и структурирование полученных данных для анализа.

- **Анализ данных:**
  - Вычисление количества вакансий по заданным направлениям и уровням.

- **Визуализация:**
  - Построение графиков с использованием Matplotlib и Seaborn для наглядного представления результатов.

### Запуск проекта:

1. Установите необходимые библиотеки из файла `requirements.txt`.
2. Запустите Jupyter Notebook и откройте файл `it_vacancies_analysis.ipynb`.
3. Следуйте инструкциям в ноутбуке для воспроизведения анализа.

### Результаты проекта:

- Табличные данные с количеством вакансий по направлениям и уровням.
- Графики, отображающие распределение вакансий по регионам и специализациям.
- Выводы о текущих тенденциях на рынке труда IT-специалистов.

---

## Проект 2: Кластеризация и классификация текстовых документов

**Описание проекта:**

В данном проекте разработана система для обработки текстовых документов, получения их эмбеддингов, выполнения кластеризации и классификации новых документов по ближайшему кластеру. Это позволяет автоматически группировать документы по тематикам и классифицировать новые тексты.

### Основные компоненты:

- **Чтение и предобработка текстов:**
  - Считывание `.txt` файлов из заданной директории.
  - Очистка текста, токенизация, удаление стоп-слов с использованием NLTK.

- **Преобразование текстов в эмбеддинги:**
  - Использование модели `SentenceTransformer` для получения векторных представлений текстов.

- **Кластеризация документов:**
  - Применение алгоритма `KMeans` для кластеризации эмбеддингов.
  - Определение оптимального количества кластеров с помощью метода локтя и коэффициента силуэта.

- **Классификация новых документов:**
  - Преобразование нового документа в эмбеддинг.
  - Поиск ближайшего кластера с использованием косинусного расстояния.

### Запуск проекта:

1. Установите необходимые библиотеки из файла `requirements.txt`.
2. Убедитесь, что в папке `texts/` находятся текстовые файлы для анализа.
3. Запустите Jupyter Notebook и откройте файл `text_clustering_classification.ipynb`.
4. Следуйте инструкциям в ноутбуке для выполнения кластеризации и классификации.

### Результаты проекта:

- Кластеры документов, сгруппированных по тематикам.
- Функционал для классификации новых текстовых документов.
- Визуализации распределения документов по кластерам.

---

## Проект 3: Прогнозирование цен и спроса на вторичном автомобильном рынке России

**Описание проекта:**

Цель проекта — разработать модели для прогнозирования цен и вероятности продажи подержанных автомобилей на российском рынке. Проект сочетает анализ технических характеристик автомобилей и экономических показателей регионов с методами машинного обучения.

### Основные компоненты:

- **Сбор и загрузка данных:**
  - Данные о подержанных автомобилях: марка, модель, год выпуска, пробег, цена и др.
  - Макроэкономические показатели регионов.

- **Предобработка данных:**
  - Очистка данных и обработка пропущенных значений.
  - Кодирование категориальных признаков (`LabelEncoder`) и масштабирование числовых признаков (`StandardScaler`).

- **Моделирование:**
  - Регрессия: Модель `RandomForestRegressor` для прогнозирования цены автомобиля.
  - Классификация: Модель `RandomForestClassifier` для прогнозирования вероятности продажи.

- **Оценка моделей:**
  - Использование метрик `MAE`, `MSE`, `RMSE`, `R²` для регрессии.
  - Отчёт классификации, матрица ошибок для классификации.

- **Анализ результатов:**
  - Определение важности признаков.
  - Визуализация фактических vs предсказанных значений.

- **Классификация новых данных:**
  - Функция для предсказания цены и вероятности продажи нового автомобиля.

### Запуск проекта:

1. Установите необходимые библиотеки из файла `requirements.txt`.
2. Подготовьте датасет с реальными данными или используйте предоставленный синтетический пример.
3. Запустите Jupyter Notebook и откройте файл `car_price_prediction.ipynb`.
4. Следуйте инструкциям в ноутбуке для воспроизведения результатов и применения модели к новым данным.

### Результаты проекта:

- Предсказанные цены автомобилей с определённой точностью.
- Оценка вероятности успешной продажи автомобиля.
- Инсайты о наиболее влиятельных факторах на цену и спрос.

---



