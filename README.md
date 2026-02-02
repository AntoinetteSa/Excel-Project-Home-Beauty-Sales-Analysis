# Excel Project: Home & Beauty Sales Analysis

[🇺🇦 Українська версія](#ukrainian-version) | [🇺🇸 English Version](#english-version)

---

<a name="ukrainian-version"></a>
## 🇺🇦 Українська версія

### Excel Home & Beauty Sales

### 📌 Огляд проекту
Цей проект присвячений аналізу ключових факторів, що впливають на ефективність продажів товарів мережі «Home and Beauty».

**Мета аналізу:**
* Виявити закономірності продажів за регіонами та категоріями продукції.
* Визначити топ-менеджерів за показниками прибутку.
* Проаналізувати часову динаміку та стабільність доходів протягом 2015-2017 років.

### 🛠 Етапи роботи

#### 1. Очищення даних
* Проведено перевірку на наявність дублікатів.
* Проведено перевірку на некоректні дані: наявність скорочення, заповнень та видалення пустих значень для забезпечення точності звітності.

#### 2. Аналіз даних
* **Зведені таблиці (Pivot Tables):** Побудовано архітектуру даних для порівняння прибутку в розрізі регіонів та менеджерів з динамікою по роках.
* **Інтерактивна звітність:** Створено таблицю з використанням Sparklines (міні-діаграм), що дозволяє відстежувати помісячний прибуток та загальні підсумки без перевантаження інтерфейсу.

#### 3. Візуалізація
* Розроблено інтерактивний дашборд із використанням зрізів (Slicers) за регіонами, роками та категорією продукції. Це дозволяє миттєво фільтрувати дані для прийняття управлінських рішень.

![Dashboard Preview](https://github.com/AntoinetteSa/Excel-Project-Home-Beauty-Sales-Analysis/blob/main/Dashboard%20Home%20%26%20Beauty%20Sales.png)

### 📊 Детальний аналіз продажів

#### 1. Оптимізація товарної сітки:
* Продажі категорії «Товари для дому» становлять лише 22% від загального доходу.
* **Рекомендація:** Розглянути доцільність зміни асортименту в цій категорії, або перерозподілити маркетинговий бюджет на користь лідерів: Косметика (41%) та Побутова хімія (37%).

#### 2. Ефективність менеджерів та локацій:
* Виявлено низьке охоплення ринку в Запоріжжі та Бердянську (продажі < 1 млн грн).
* Певні менеджери стабільно знаходяться внизу рейтингу незалежно від категорії.
* **Рекомендація:** Провести опитування клієнтів у слабких регіонах та впровадити програму менторства (досвідчений менеджер + новачок) для підвищення кваліфікації персоналу.

#### 3. Динаміка та прогнозованість:
* Протягом 2015-2017 років продажі демонструють "аномальну стабільність" (щомісячний внесок ~8-9%).
* **Рекомендація:** Відсутність піків у святкові періоди свідчить про брак активних стимулюючих акцій. Рекомендовано розробити систему сезонних знижок.

### 💻 Технології
* **Microsoft Excel:** зведені таблиці, складні формули, спарклайни (міні-графіки), умовне форматування.
* **Візуалізація даних:** дизайн дашбордів, зрізи, інтерактивні діаграми.

---

<a name="english-version"></a>
## 🇺🇸 English Version

### Excel Home & Beauty Sales

### 📌 Project Overview
This project analyzes the key factors influencing the sales performance of the "Home and Beauty" retail chain.

**Analysis Goals:**
* Identify sales patterns by region and product category.
* Determine top-performing managers based on profit indicators.
* Analyze time dynamics and revenue stability from 2015 to 2017.

### 🛠 Work Stages

#### 1. Data Cleaning
* Performed a duplicate check.
* Verified data for inconsistencies: handled abbreviations, filled and removed empty values to ensure reporting accuracy.

#### 2. Data Analysis
* **Pivot Tables:** Built data architecture to compare profit across regions and managers with yearly dynamics.
* **Interactive Reporting:** Created a table using Sparklines (mini-charts) to track monthly profit and totals without interface clutter.

#### 3. Visualization
* Developed an interactive dashboard using Slicers (region, year, category). This allows for instant data filtering for management decision-making.

### 📊 Detailed Sales Analysis

#### 1. Product Grid Optimization:
* "Home Goods" category sales account for only 22% of total revenue.
* **Recommendation:** Consider changing the product assortment in this category or reallocating the marketing budget toward leaders: Cosmetics (41%) and Household Chemicals (37%).

#### 2. Manager and Location Efficiency:
* Identified low market coverage in Zaporizhzhia and Berdyansk (sales < 1 million UAH).
* Certain managers consistently remain at the bottom of the rankings regardless of the category.
* **Recommendation:** Conduct customer surveys in underperforming regions and implement a mentorship program (experienced manager + newcomer) to improve staff skills.

#### 3. Dynamics and Predictability:
* Throughout 2015-2017, sales show "abnormal stability" (monthly contribution of ~8-9%).
* **Recommendation:** The lack of peaks during holiday periods suggests a deficiency in active promotional campaigns. It is recommended to develop a seasonal discount system.

### 💻 Technologies
* **Microsoft Excel:** Pivot tables, advanced formulas, sparklines, conditional formatting.
* **Data Visualization:** Dashboard design, slicers, interactive charts.
