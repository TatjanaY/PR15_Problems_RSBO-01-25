## 🟦 Задание 3.1 (тематика: **Медицина / страхование**)

### Условие

1. Скачайте файл `insurance.csv` с платформы Kaggle
   ([Medical Cost Personal Datasets](https://www.kaggle.com/mirichoi0218/insurance)).

2. Загрузите данные в объект `DataFrame`:

   * разделитель `,`,
   * корректная кодировка (при необходимости).

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `sex`, `smoker`, `region` в тип `category`.

5. Создайте объект `insurance_filtered`, отобрав строки, где:

   * возраст > 30,
   * регион = `"southeast"`,
   * застрахованный не курит.

6. Добавьте столбец **Налог** = 5% от `charges` (тип `float`).

7. Отсортируйте по `charges` по убыванию.

8. Сохраните результат в файл `insurance_change.csv` без индексов.

---

## 🟦 Задание 3.2 (тематика: **Медицина / страхование**)

### Условие

1. Скачайте `ushealthinsurancedataset.csv`
   ([US Health Insurance Dataset](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных.

4. Преобразуйте столбцы `Gender`, `Insurance_Type`, `Region` в `category`.

5. Отберите строки, где:

   * возраст ≥ 40,
   * регион = `"West"`,
   * Insurance_Type = `"HMO"`.

6. Добавьте столбец **Premium Tax** = 10% от `Premium` (`float`).

7. Сортировка: по `Premium` по убыванию.

8. Сохраните в `usinsurance_filtered.csv`.

---

## 🟦 Задание 3.3 (тематика: **Медицина / страховые случаи**)

### Условие

1. Скачайте `insurance-claims.csv`
   ([Insurance Claims](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропусках.

4. Преобразуйте столбцы `Policy_Type`, `Claim_Status`, `Region` в `category`.

5. Отберите строки, где:

   * Claim_Amount > 10000,
   * Region = `"North"`,
   * Claim_Status = `"Approved"`.

6. Добавьте столбец **Tax** = 7% от `Claim_Amount`.

7. Сортировка: по `Claim_Amount` по убыванию.

8. Сохраните в `insurance_claims_filtered.csv`.

---

## 🟦 Задание 3.4 (тематика: **Медицина / предсказание страховых выплат**)

### Условие

1. Скачайте `prediction-of-insurance-charges.csv`
   ([Prediction of Insurance Charges](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных.

4. Преобразуйте столбцы `sex`, `smoker`, `region` в `category`.

5. Отберите строки, где:

   * age > 35,
   * region = `"southwest"`,
   * smoker = `"no"`.

6. Добавьте столбец **Tax** = 5% от `charges`.

7. Сортировка: по `charges` по убыванию.

8. Сохраните в `insurance_prediction_filtered.csv`.

---

## 🟦 Задание 3.5 (тематика: **Медицина / растения (Iris)**)

### Условие

1. Скачайте `iris.csv` ([Iris Dataset](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных.

4. Преобразуйте столбец `species` в `category`.

5. Отберите строки, где:

   * `sepal_length` > 5.0,
   * `species` = `"setosa"`.

6. Добавьте столбец **Sepal Ratio** = sepal_length / sepal_width (`float`).

7. Сортировка: по `Sepal Ratio` по убыванию.

8. Сохраните в `iris_filtered.csv`.

---

## 🟦 Задание 3.6 (тематика: **Медицина / пассажиры** – Titanic)

### Условие

1. Скачайте `Titanic-Dataset.csv` ([Titanic Dataset](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропусках.

4. Преобразуйте столбцы `Sex`, `Embarked` в `category`.

5. Отберите строки, где:

   * Age > 18,
   * Pclass = 1,
   * Survived = 1.

6. Добавьте столбец **Ticket Tax** = 5% от `Fare`.

7. Сортировка: по `Fare` по убыванию.

8. Сохраните в `titanic_filtered.csv`.

---

## 🟦 Задание 3.7 (тематика: **Медицина / рукописные цифры (MNIST)**)

### Условие

1. Скачайте `mnist-in-csv.csv` ([MNIST in CSV](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных.

4. Преобразуйте столбец `label` в `category`.

5. Отберите строки, где:

   * label = 7,
   * pixel0 > 50.

6. Добавьте столбец **Pixel Sum** = сумма всех пикселей (float).

7. Сортировка: по `Pixel Sum` по убыванию.

8. Сохраните в `mnist_filtered.csv`.

---

## 🟦 Задание 3.8 (тематика: **Медицина / диабет**)

### Условие

1. Скачайте `diabetes.csv` ([Diabetes Dataset](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропусках.

4. Преобразуйте столбец `Outcome` в `category`.

5. Отберите строки, где:

   * Age > 40,
   * Glucose > 120.

6. Добавьте столбец **Risk Factor** = 0.1 * Glucose (`float`).

7. Сортировка: по `Risk Factor` по убыванию.

8. Сохраните в `diabetes_filtered.csv`.

---

## 🟦 Задание 3.9 (тематика: **Медицина / спам-почта**)

### Условие

1. Скачайте `email-spam-classification.csv` ([Email Spam Classification](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных.

4. Преобразуйте столбец `spam` в `category`.

5. Отберите строки, где:

   * spam = 1,
   * word_freq_free > 0.5.

6. Добавьте столбец **Spam Score** = sum(word frequencies) (`float`).

7. Сортировка: по `Spam Score` по убыванию.

8. Сохраните в `email_spam_filtered.csv`.

---

## 🟦 Задание 3.10 (тематика: **Медицина / здравоохранение**)

### Условие

1. Скачайте `healthcare-dataset.csv` ([Healthcare Dataset](https://www.kaggle.com/datasets)).

2. Загрузите данные в `DataFrame`.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропусках.

4. Преобразуйте столбцы `Gender`, `Diabetic`, `Region` в `category`.

5. Отберите строки, где:

   * Age > 50,
   * Diabetic = `"Yes"`,
   * Region = `"East"`.

6. Добавьте столбец **Insurance Tax** = 0.05 * Insurance_cost (`float`).

7. Сортировка: по `Insurance_cost` по убыванию.

8. Сохраните в `healthcare_filtered.csv`.

---

## 🟦 Задание 3.11 (тематика: **Медицина / винные исследования**)

### Условие

1. Скачайте файл `winequality-red.csv` с платформы Kaggle
   ([https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)).

2. Загрузите данные в объект `DataFrame`:

   * разделитель `;`,
   * корректная кодировка (при необходимости).

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбец `type` в тип `category`.

5. Создайте новый объект `wine_filtered`, где:

   * `quality` ≥ 7,
   * `alcohol` > 10.

6. Добавьте столбец **Налог**:

   * значение — **2% от `alcohol`**;
   * тип данных `float`.

7. Отсортируйте по столбцу `quality` по убыванию.

8. Сохраните результат в файл **wine_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.12 (тематика: **Образование / успеваемость студентов**)

### Условие

1. Скачайте файл `students-performance.csv` с Kaggle
   ([https://www.kaggle.com/spscientist/students-performance-in-exams](https://www.kaggle.com/spscientist/students-performance-in-exams)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка (при необходимости).

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `gender`, `race/ethnicity`, `parental level of education` в тип `category`.

5. Создайте объект `students_filtered`, где:

   * `math score` > 70,
   * `gender` = `"female"`.

6. Добавьте столбец **Бонус**:

   * значение — **5% от `reading score`**;
   * тип данных `float`.

7. Отсортируйте по `writing score` по убыванию.

8. Сохраните результат в файл **students_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.13 (тематика: **Спорт / FIFA игроки**)

### Условие

1. Скачайте файл `fifa-21-complete-player-dataset.csv` с Kaggle
   ([https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset](https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Nationality`, `Club` в тип `category`.

5. Создайте объект `players_filtered`, где:

   * `Overall` ≥ 85,
   * `Age` < 30.

6. Добавьте столбец **Налог**:

   * значение — **3% от `Wage`**;
   * тип данных `float`.

7. Отсортируйте по `Overall` по убыванию.

8. Сохраните результат в файл **players_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.14 (тематика: **Развлечения / Netflix**)

### Условие

1. Скачайте файл `netflix-shows.csv` с Kaggle
   ([https://www.kaggle.com/shivamb/netflix-shows](https://www.kaggle.com/shivamb/netflix-shows)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `type`, `rating`, `country` в тип `category`.

5. Создайте объект `netflix_filtered`, где:

   * `release_year` ≥ 2015,
   * `type` = `"Movie"`.

6. Добавьте столбец **Налог**:

   * значение — **1% от `duration`**;
   * тип данных `float`.

7. Отсортируйте по `release_year` по убыванию.

8. Сохраните результат в файл **netflix_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.15 (тематика: **Социальные сети / YouTube**)

### Условие

1. Скачайте файл `youtube-new.csv` с Kaggle
   ([https://www.kaggle.com/datasnaek/youtube-new](https://www.kaggle.com/datasnaek/youtube-new)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `channelTitle`, `categoryId` в тип `category`.

5. Создайте объект `youtube_filtered`, где:

   * `views` > 1_000_000,
   * `country` = `"US"`.

6. Добавьте столбец **Налог**:

   * значение — **2% от `likes`**;
   * тип данных `float`.

7. Отсортируйте по `views` по убыванию.

8. Сохраните результат в файл **youtube_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.16 (тематика: **Медицина / COVID-19**)

### Условие

1. Скачайте файл `covid19-global-dataset.csv` с Kaggle
   ([https://www.kaggle.com/imdevskp/corona-virus-report](https://www.kaggle.com/imdevskp/corona-virus-report)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Country_Region`, `Province_State` в тип `category`.

5. Создайте объект `covid_filtered`, где:

   * `Confirmed` > 10_000,
   * `Date` ≥ '2021-01-01'.

6. Добавьте столбец **Налог**:

   * значение — **0.5% от `Confirmed`**;
   * тип данных `float`.

7. Отсортируйте по `Deaths` по убыванию.

8. Сохраните результат в файл **covid_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.17 (тематика: **Климат / глобальные температуры**)

### Условие

1. Скачайте файл `global-land-temperatures.csv` с Kaggle
   ([https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Country`, `City` в тип `category`.

5. Создайте объект `temperature_filtered`, где:

   * `AverageTemperature` > 15,
   * `Year` ≥ 2000.

6. Добавьте столбец **Налог**:

   * значение — **0.1 × AverageTemperature**;
   * тип данных `float`.

7. Отсортируйте по `AverageTemperature` по убыванию.

8. Сохраните результат в файл **temperature_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.18 (тематика: **Музыка / Spotify топ-50**)

### Условие

1. Скачайте файл `spotify-top-50.csv` с Kaggle
   ([https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-dataset](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-dataset)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Artist`, `Genre` в тип `category`.

5. Создайте объект `spotify_filtered`, где:

   * `Streams` > 1_000_000,
   * `Genre` = `"Pop"`.

6. Добавьте столбец **Налог**:

   * значение — **0.02 × Streams**;
   * тип данных `float`.

7. Отсортируйте по `Streams` по убыванию.

8. Сохраните результат в файл **spotify_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.19 (тематика: **Рестораны / Zomato**)

### Условие

1. Скачайте файл `zomato-bangalore-restaurants.csv` с Kaggle
   ([https://www.kaggle.com/rajathkmp/bangalore-restaurants](https://www.kaggle.com/rajathkmp/bangalore-restaurants)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Cuisines`, `City` в тип `category`.

5. Создайте объект `zomato_filtered`, где:

   * `Average_Cost_for_two` > 500,
   * `City` = `"Bangalore"`.

6. Добавьте столбец **Налог**:

   * значение — **5% от `Average_Cost_for_two`**;
   * тип данных `float`.

7. Отсортируйте по `Aggregate_rating` по убыванию.

8. Сохраните результат в файл **zomato_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.20 (тематика: **Недвижимость / House Prices**)

### Условие

1. Скачайте файл `house-prices-advanced-regression-techniques.csv` с Kaggle
   ([https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Neighborhood`, `HouseStyle` в тип `category`.

5. Создайте объект `house_filtered`, где:

   * `GrLivArea` > 2000,
   * `OverallQual` ≥ 7.

6. Добавьте столбец **Налог**:

   * значение — **2% от `SalePrice`**;
   * тип данных `float`.

7. Отсортируйте по `SalePrice` по убыванию.

8. Сохраните результат в файл **house_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.21 (тематика: **Отзывы / Amazon Reviews**)

### Условие

1. Скачайте файл `amazon-product-reviews.csv` с Kaggle
   ([https://www.kaggle.com/bittlingmayer/amazonreviews](https://www.kaggle.com/bittlingmayer/amazonreviews)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `product_category`, `reviewer_name` в тип `category`.

5. Создайте объект `amazon_filtered`, где:

   * `star_rating` ≥ 4,
   * `helpful_votes` > 10.

6. Добавьте столбец **Налог**:

   * значение — **1% от `helpful_votes`**;
   * тип данных `float`.

7. Отсортируйте по `star_rating` по убыванию.

8. Сохраните результат в файл **amazon_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.22 (тематика: **Транспорт / Airlines Delay**)

### Условие

1. Скачайте файл `airline-delay.csv` с Kaggle
   ([https://www.kaggle.com/giovamata/airlinedelay](https://www.kaggle.com/giovamata/airlinedelay)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Airline`, `Origin`, `Dest` в тип `category`.

5. Создайте объект `delay_filtered`, где:

   * `Delay` > 30,
   * `Month` ≥ 6.

6. Добавьте столбец **Налог**:

   * значение — **5% от `Delay`**;
   * тип данных `float`.

7. Отсортируйте по `Delay` по убыванию.

8. Сохраните результат в файл **delay_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.23 (тематика: **Транспорт / Uber NYC Rides**)

### Условие

1. Скачайте файл `uber-nyc-for-hire-vehicles.csv` с Kaggle
   ([https://www.kaggle.com/fivethirtyeight/uber-pickups-in-new-york-city](https://www.kaggle.com/fivethirtyeight/uber-pickups-in-new-york-city)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Dispatching_base_number`, `PUlocationID` в тип `category`.

5. Создайте объект `uber_filtered`, где:

   * `Trip_distance` > 5,
   * `Fare_amount` > 20.

6. Добавьте столбец **Налог**:

   * значение — **10% от `Fare_amount`**;
   * тип данных `float`.

7. Отсортируйте по `Trip_distance` по убыванию.

8. Сохраните результат в файл **uber_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.24 (тематика: **Развлечения / Amazon Prime Movies**)

### Условие

1. Скачайте файл `amazon-prime-movies.csv` с Kaggle
   ([https://www.kaggle.com/praveengovi/amazon-prime-movies](https://www.kaggle.com/praveengovi/amazon-prime-movies)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Genre`, `Language` в тип `category`.

5. Создайте объект `prime_filtered`, где:

   * `Year` ≥ 2015,
   * `IMDb` ≥ 7.0.

6. Добавьте столбец **Налог**:

   * значение — **1% от `IMDb`**;
   * тип данных `float`.

7. Отсортируйте по `IMDb` по убыванию.

8. Сохраните результат в файл **prime_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.25 (тематика: **Образование / Alcohol Consumption**)

### Условие

1. Скачайте файл `student-alcohol-consumption.csv` с Kaggle
   ([https://www.kaggle.com/uciml/student-alcohol-consumption](https://www.kaggle.com/uciml/student-alcohol-consumption)).

2. Загрузите данные в `DataFrame`:

   * разделитель `;`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `school`, `sex` в тип `category`.

5. Создайте объект `alcohol_filtered`, где:

   * `age` > 16,
   * `Dalc` ≥ 3.

6. Добавьте столбец **Налог**:

   * значение — **2% от `G3`**;
   * тип данных `float`.

7. Отсортируйте по `G3` по убыванию.

8. Сохраните результат в файл **alcohol_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.26 (тематика: **Транспорт / Cars Dataset**)

### Условие

1. Скачайте файл `cars.csv` с Kaggle
   ([https://www.kaggle.com/anderas/car-dataset](https://www.kaggle.com/anderas/car-dataset)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Make`, `Fuel_Type` в тип `category`.

5. Создайте объект `cars_filtered`, где:

   * `Horsepower` > 150,
   * `MPG_City` > 15.

6. Добавьте столбец **Налог**:

   * значение — **5% от `Price`**;
   * тип данных `float`.

7. Отсортируйте по `Horsepower` по убыванию.

8. Сохраните результат в файл **cars_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.27 (тематика: **Кафе / Starbucks Menu**)

### Условие

1. Скачайте файл `starbucks-menu.csv` с Kaggle
   ([https://www.kaggle.com/starbucks/starbucks-menu](https://www.kaggle.com/starbucks/starbucks-menu)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Beverage_category`, `Beverage_prep` в тип `category`.

5. Создайте объект `starbucks_filtered`, где:

   * `Calories` > 200,
   * `Beverage_category` = `"Coffee"`.

6. Добавьте столбец **Налог**:

   * значение — **2% от `Calories`**;
   * тип данных `float`.

7. Отсортируйте по `Calories` по убыванию.

8. Сохраните результат в файл **starbucks_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.28 (тематика: **Спорт / Олимпийские игры**)

### Условие

1. Скачайте файл `olympics-history.csv` с Kaggle
   ([https://www.kaggle.com/heesoo37/120-years-of-olympic-history](https://www.kaggle.com/heesoo37/120-years-of-olympic-history)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `City`, `Country` в тип `category`.

5. Создайте объект `olympics_filtered`, где:

   * `Year` ≥ 2000,
   * `Medal` != `"NA"`.

6. Добавьте столбец **Налог**:

   * значение — **5% от `Age`**;
   * тип данных `float`.

7. Отсортируйте по `Medal` по убыванию.

8. Сохраните результат в файл **olympics_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.29 (тематика: **Кино / IMDb Movies**)

### Условие

1. Скачайте файл `imdb-5000-movie-dataset.csv` с Kaggle
   ([https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Genre`, `Director` в тип `category`.

5. Создайте объект `imdb_filtered`, где:

   * `imdb_score` ≥ 7.5,
   * `duration` > 90.

6. Добавьте столбец **Налог**:

   * значение — **2% от `budget`**;
   * тип данных `float`.

7. Отсортируйте по `imdb_score` по убыванию.

8. Сохраните результат в файл **imdb_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.30 (тематика: **Экономика / World Happiness Report**)

### Условие

1. Скачайте файл `world-happiness-report.csv` с Kaggle
   ([https://www.kaggle.com/unsdsn/world-happiness](https://www.kaggle.com/unsdsn/world-happiness)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Country`, `Region` в тип `category`.

5. Создайте объект `happiness_filtered`, где:

   * `Score` ≥ 6.5,
   * `Year` = 2019.

6. Добавьте столбец **Налог**:

   * значение — **5% от `Score`**;
   * тип данных `float`.

7. Отсортируйте по `Score` по убыванию.

8. Сохраните результат в файл **happiness_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.31 (тематика: **Медицина / Heart Disease UCI**)

### Условие

1. Скачайте файл `heart.csv` с Kaggle
   ([https://www.kaggle.com/ronitf/heart-disease-uci](https://www.kaggle.com/ronitf/heart-disease-uci)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `sex`, `cp`, `thal` в тип `category`.

5. Создайте объект `heart_filtered`, где:

   * `age` > 50,
   * `target` = 1.

6. Добавьте столбец **Налог**:

   * значение — **3% от `chol`**;
   * тип данных `float`.

7. Отсортируйте по `thalach` по убыванию.

8. Сохраните результат в файл **heart_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.32 (тематика: **Транспорт / NYC Taxi Trip Duration**)

### Условие

1. Скачайте файл `train.csv` с Kaggle
   ([https://www.kaggle.com/c/nyc-taxi-trip-duration/data](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `store_and_fwd_flag` в тип `category`.

5. Создайте объект `taxi_filtered`, где:

   * `trip_duration` > 1000,
   * `passenger_count` > 2.

6. Добавьте столбец **Налог**:

   * значение — **1% от `trip_duration`**;
   * тип данных `float`.

7. Отсортируйте по `trip_duration` по убыванию.

8. Сохраните результат в файл **taxi_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.33 (тематика: **Развлечения / Spotify Tracks**)

### Условие

1. Скачайте файл `top50.csv` с Kaggle
   ([https://www.kaggle.com/edumucelli/spotify-top-50-songs-in-2019](https://www.kaggle.com/edumucelli/spotify-top-50-songs-in-2019)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Genre`, `Artist.Name` в тип `category`.

5. Создайте объект `spotify_filtered`, где:

   * `Popularity` ≥ 80,
   * `Streams` > 5000000.

6. Добавьте столбец **Налог**:

   * значение — **2% от `Streams`**;
   * тип данных `float`.

7. Отсортируйте по `Streams` по убыванию.

8. Сохраните результат в файл **spotify_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.34 (тематика: **Образование / Student Performance**)

### Условие

1. Скачайте файл `StudentsPerformance.csv` с Kaggle
   ([https://www.kaggle.com/spscientist/students-performance-in-exams](https://www.kaggle.com/spscientist/students-performance-in-exams)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `gender`, `race/ethnicity`, `parental level of education` в тип `category`.

5. Создайте объект `students_filtered`, где:

   * `math score` ≥ 70,
   * `reading score` ≥ 70.

6. Добавьте столбец **Налог**:

   * значение — **5% от `writing score`**;
   * тип данных `float`.

7. Отсортируйте по `math score` по убыванию.

8. Сохраните результат в файл **students_filtered.csv** без сохранения индексов.

---

## 🟦 Задание 3.35 (тематика: **Экономика / Global Energy Consumption**)

### Условие

1. Скачайте файл `Global Energy Consumption.csv` с Kaggle
   ([https://www.kaggle.com/robikscube/global-energy-consumption](https://www.kaggle.com/robikscube/global-energy-consumption)).

2. Загрузите данные в `DataFrame`:

   * разделитель `,`,
   * корректная кодировка.

3. Выведите:

   * размер таблицы,
   * информацию о типах данных и пропущенных значениях.

4. Преобразуйте столбцы `Country` и `Energy_Type` в тип `category`.

5. Создайте объект `energy_filtered`, где:

   * `Year` ≥ 2010,
   * `Consumption` > 1000.

6. Добавьте столбец **Налог**:

   * значение — **3% от `Consumption`**;
   * тип данных `float`.

7. Отсортируйте по `Consumption` по убыванию.

8. Сохраните результат в файл **energy_filtered.csv** без сохранения индексов.

