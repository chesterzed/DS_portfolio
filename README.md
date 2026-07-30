# 📊 DS Portfolio

Портфолио с проектами по анализу данных: от RFM-сегментации клиентов и финансовой отчётности до разведочного анализа данных (EDA).

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4c72b0)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/license-CC0%201.0-lightgrey)

---

## 📁 Проекты

### 1. [RFM-модель для клиентов банка (кредитные карты)](<1. RFM model for Bank Credit card customers/Credit_Customer_Analitics.ipynb>)

Анализ клиентской базы банка по кредитным картам с целью понять, какие признаки влияют на итоговый кредитный лимит клиента.

- Построена сводная метрика `Total_Credit_Limit` и исследованы корреляции между признаками (`Avg_Credit_Limit`, `Total_Credit_Cards`, `Total_visits_bank`, `Total_visits_online`, `Total_calls_made`)
- Данные нормализованы и приведены к единой шкале для построения скоринга (`score`)
- Оценено качество ранжирования клиентов через `uplift` и cumulative gain curve

**Стек:** `pandas`, `seaborn`, `scikit-learn`, `scikit-plot`

📎 [Открыть в Google Colab](https://colab.research.google.com/drive/1-F7bv5cEA0jH54go-X-bPm23B1a6grfW?usp=sharing)

---

### 2. [Финансовый отчёт по продажам за год (E-Commerce UK)](<2. Finance report for 1 year/E_Commerce_UK_Data_Analysis_report.ipynb>)

Обработка транзакционных данных интернет-магазина и построение помесячного отчёта по выручке.

- Очистка данных: обработка пропусков, приведение `InvoiceDate` к формату `datetime`
- Расчёт выручки (`revenue`) по каждому клиенту в разрезе месяцев
- Объединение таблиц выручки и дат регистрации пользователей, отсев некорректных строк (месяц отчёта раньше даты регистрации)
- Итоговый график динамики выручки и среднего чека на активного клиента по месяцам

**Стек:** `pandas`, `seaborn`

📎 [Открыть в Google Colab](https://colab.research.google.com/drive/1gwgxGMecy_Q62CjgzmoGQv_Uba_gG9tt?usp=sharing)

---

### 3. [Разведочный анализ данных (EDA) — рынок недвижимости](<3. Exploratory data analysis/for_EDA.csv>)

Датасет объявлений о продаже квартир (Санкт-Петербург и область): площадь, этаж, планировка, удалённость от центра, парков и водоёмов, срок экспозиции объявления и другие параметры — база для разведочного анализа и поиска факторов, влияющих на цену жилья.

---

## 🛠 Технологии

| Категория | Инструменты |
|---|---|
| Язык | Python |
| Обработка данных | pandas |
| Визуализация | seaborn, matplotlib |
| ML / метрики | scikit-learn, scikit-plot |
| Среда разработки | Jupyter Notebook, Google Colab |

## 📄 Лицензия

Материалы репозитория распространяются под лицензией [CC0 1.0 Universal](LICENSE).
