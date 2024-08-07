# Карьерный навигатор HH
# Описание проекта

Проект направлен на создание карьерного навигатора, который поможет пользователям находить вакансии на hh.ru, анализировать данные по ним и получать рекомендации на основе введенных ключевых навыков или текста резюме. Это включает:

Парсинг вакансий с hh.ru по ряду условий.
Агрегацию данных для анализа различий между различными наборами вакансий.
Создание рекомендательной системы для поиска подходящих вакансий на основе пользовательских навыков.

Парсинг вакансий с hh.ru:

Сбор информации по вакансиям с hh.ru через API.
Обработка данных для извлечения ключевой информации о вакансиях.
Вычисление средней зарплаты и анализ частоты биграмм в названиях вакансий.
Агрегация данных:
Сравнение двух наборов данных с вакансиями для выявления различий.

Рекомендательная система:

Создание системы, которая на основе пользовательских навыков рекомендует подходящие вакансии.

# Навыки и инструменты
Библиотеки Python:
requests для выполнения HTTP-запросов к API hh.ru.
pandas для обработки и анализа данных.
collections.Counter для частотного анализа биграмм.
sklearn.feature_extraction.text.TfidfVectorizer и sklearn.metrics.pairwise.cosine_similarity для создания рекомендательной системы.
API hh.ru: Получение данных о вакансиях.
Google Sheets и gdown: Загрузка и работа с данными, предоставленными в формате Excel.

# Вывод:
Проект успешно демонстрирует автоматизированный сбор и анализ данных о вакансиях с hh.ru, а также создание прототипа рекомендательной системы для поиска подходящих вакансий на основе навыков пользователя. Реализованный скрипт собирает информацию о вакансиях по четырем специальностям и сохраняет её в удобном для анализа формате. Выполнен анализ средней зарплаты по каждой специальности и выявлены 10 самых частых биграмм в названиях вакансий. Сравнены два набора данных с вакансиями интернет-маркетологов, что позволило выявить вакансии, присутствующие в одном наборе, но отсутствующие в другом. Разработан прототип рекомендательной системы, который на основе введенных ключевых навыков пользователя рекомендует 10 наиболее подходящих вакансий. Проект может служить основой для более сложных систем анализа и рекомендаций вакансий, упрощая процесс поиска работы для соискателей.
