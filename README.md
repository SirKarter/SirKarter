<!--
Это README для ТВОЕГО ПРОФИЛЯ на GitHub.

Как его установить:
1. Создай на GitHub публичный репозиторий с именем, точно совпадающим с твоим username
   (например, если ты anton-matyuha — то репо anton-matyuha/anton-matyuha).
2. Положи этот файл внутрь как README.md (переименуй profile_README.md → README.md).
3. Замени все вхождения <username> на свой реальный GitHub username
   (быстрая команда на Mac: sed -i '' 's/<username>/anton-matyuha/g' README.md).
4. Заполни или удали плейсхолдеры (Telegram/LinkedIn/Kaggle) по вкусу.
-->

<h1 align="center">Привет, я Антон 👋</h1>
<h3 align="center">Data Scientist · Python · Machine Learning · Deep Learning</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SirKarter&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
  <a href="https://github.com/SirKarter?tab=repositories"><img src="https://img.shields.io/badge/Projects-16-blue?style=flat&logo=github" /></a>
</p>

---

## 🧠 Обо мне

Прикладной **Data Scientist**: превращаю сырые данные в рабочие модели и понятные бизнес-выводы. Собрал портфолио из 16 end-to-end проектов, которые покрывают полный цикл DS-работы — от EDA и проверки гипотез до продакшен-моделей на градиентном бустинге и нейросетях.

- 🔭 Работаю с **табличными данными, временными рядами, текстами (NLP) и изображениями (CV)**
- 🧰 Основной стек: **Python, pandas, scikit-learn, CatBoost / LightGBM, TensorFlow / Keras**
- 📚 Закончил курс «Специалист по Data Science» (Яндекс.Практикум)
- 🎯 Интересуюсь ML-инженерией, интерпретируемостью моделей и задачами на стыке ML и бизнеса
- 📫 Связаться: **anton.matyuha@gmail.com**

---

## 🛠 Технологический стек

**Языки и среды**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)

**Работа с данными и визуализация**

![Pandas](https://img.shields.io/badge/-pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logoColor=white)
![Seaborn](https://img.shields.io/badge/-Seaborn-4C72B0?style=flat&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)

**Классический ML**

![Scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![CatBoost](https://img.shields.io/badge/-CatBoost-FFCC00?style=flat&logoColor=black)
![LightGBM](https://img.shields.io/badge/-LightGBM-2E6C22?style=flat&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-006400?style=flat&logoColor=white)

**Deep Learning / NLP / CV**

![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white)
![NLTK](https://img.shields.io/badge/-NLTK-3776AB?style=flat&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

---

## 🚀 Избранные проекты

<table>
  <tr>
    <td width="50%">
      <h3>🏭 Прогноз температуры стали</h3>
      <p>Капстоун-проект: регрессия финальной температуры на металлургическом комбинате. Интеграция 7 источников, feature engineering, CatBoost.</p>
      <p><b>Стек:</b> pandas · CatBoost · scikit-learn · Plotly</p>
      <a href="https://github.com/SirKarter/steel-temperature-prediction"><img src="https://img.shields.io/badge/repo-steel--temperature--prediction-181717?logo=github" /></a>
    </td>
    <td width="50%">
      <h3>💬 NLP-классификатор токсичных комментариев</h3>
      <p>Бинарная классификация комментариев по токсичности: TF-IDF, лемматизация NLTK, LightGBM. Целевая F1 ≥ 0.75.</p>
      <p><b>Стек:</b> NLTK · scikit-learn · LightGBM</p>
      <a href="https://github.com/SirKarter/toxic-comments-nlp-classifier"><img src="https://img.shields.io/badge/repo-toxic--comments--nlp--classifier-181717?logo=github" /></a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🚗 Оценка стоимости авто</h3>
      <p>Регрессия рыночной цены подержанных автомобилей: сравнение LightGBM, CatBoost и линейных моделей по RMSE и скорости.</p>
      <p><b>Стек:</b> pandas · LightGBM · CatBoost</p>
      <a href="https://github.com/SirKarter/used-car-price-prediction"><img src="https://img.shields.io/badge/repo-used--car--price--prediction-181717?logo=github" /></a>
    </td>
    <td width="50%">
      <h3>📷 Оценка возраста по фото (CNN)</h3>
      <p>CNN-регрессия возраста покупателей: transfer learning ResNet50, аугментации, метрика MAE.</p>
      <p><b>Стек:</b> TensorFlow · Keras · ResNet50</p>
      <a href="https://github.com/SirKarter/customer-age-estimation-cnn"><img src="https://img.shields.io/badge/repo-customer--age--estimation--cnn-181717?logo=github" /></a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🏦 Отток клиентов банка</h3>
      <p>Несбалансированная классификация: class_weight, oversampling, undersampling; подбор порога вероятности; F1 = 0.63, ROC-AUC = 0.79.</p>
      <p><b>Стек:</b> scikit-learn · pandas · Random Forest</p>
      <a href="https://github.com/SirKarter/bank-customer-churn-prediction"><img src="https://img.shields.io/badge/repo-bank--customer--churn--prediction-181717?logo=github" /></a>
    </td>
    <td width="50%">
      <h3>🛢 Выбор локации для скважин</h3>
      <p>Регрессия объёма запасов + Bootstrap-анализ прибыли и риска убытков для выбора оптимального региона.</p>
      <p><b>Стек:</b> scikit-learn · NumPy · Bootstrap</p>
      <a href="https://github.com/SirKarter/oil-well-location-profit-analysis"><img src="https://img.shields.io/badge/repo-oil--well--location--profit--analysis-181717?logo=github" /></a>
    </td>
  </tr>
</table>

### 📚 Полный список репозиториев

| № | Проект | Направление | Стек |
|---|--------|-------------|------|
| 1 | [music-streaming-user-behavior](https://github.com/SirKarter/music-streaming-user-behavior) | EDA пользовательского поведения | pandas |
| 2 | [borrower-creditworthiness-analysis](https://github.com/SirKarter/borrower-creditworthiness-analysis) | Предобработка, категоризация | pandas |
| 3 | [real-estate-market-analysis](https://github.com/SirKarter/real-estate-market-analysis) | Исследовательский анализ | pandas, matplotlib, seaborn |
| 4 | [telecom-tariff-statistical-analysis](https://github.com/SirKarter/telecom-tariff-statistical-analysis) | Статистический анализ, проверка гипотез | pandas, scipy |
| 5 | [video-game-market-research](https://github.com/SirKarter/video-game-market-research) | EDA, проверка гипотез | pandas, scipy, plotly |
| 6 | [mobile-tariff-recommendation-classifier](https://github.com/SirKarter/mobile-tariff-recommendation-classifier) | Классификация | scikit-learn |
| 7 | [bank-customer-churn-prediction](https://github.com/SirKarter/bank-customer-churn-prediction) | Несбалансированная классификация | scikit-learn |
| 8 | [oil-well-location-profit-analysis](https://github.com/SirKarter/oil-well-location-profit-analysis) | Регрессия, Bootstrap | scikit-learn, NumPy |
| 9 | [gold-recovery-efficiency-model](https://github.com/SirKarter/gold-recovery-efficiency-model) | Регрессия, метрика sMAPE | scikit-learn |
| 10 | [personal-data-encryption-linear-algebra](https://github.com/SirKarter/personal-data-encryption-linear-algebra) | Линейная алгебра | NumPy, scikit-learn |
| 11 | [used-car-price-prediction](https://github.com/SirKarter/used-car-price-prediction) | Градиентный бустинг | LightGBM, CatBoost |
| 12 | [taxi-demand-timeseries-forecasting](https://github.com/SirKarter/taxi-demand-timeseries-forecasting) | Временные ряды | statsmodels, CatBoost |
| 13 | [toxic-comments-nlp-classifier](https://github.com/SirKarter/toxic-comments-nlp-classifier) | NLP, TF-IDF | NLTK, LightGBM |
| 14 | [computer-vision-deep-learning-tasks](https://github.com/SirKarter/computer-vision-deep-learning-tasks) | CNN, ResNet | TensorFlow, Keras |
| 15 | [customer-age-estimation-cnn](https://github.com/SirKarter/customer-age-estimation-cnn) | CNN-регрессия, transfer learning | TensorFlow, Keras, ResNet50 |
| 16 | [steel-temperature-prediction](https://github.com/SirKarter/steel-temperature-prediction) | Промышленная регрессия | CatBoost, scikit-learn |
| 17 | [real-estate-mle-airflow-dvc](https://github.com/SirKarter/real-estate-mle-airflow-dvc) | **MLOps**: ETL + ML-пайплайн | Airflow, DVC, Docker, S3 |

---

## 📊 GitHub-статистика

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=SirKarter&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SirKarter&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SirKarter&theme=github-dark&hide_border=true" />
</p>

---

## 📫 Контакты

<p>
  <a href="mailto:anton.matyuha@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://t.me/SirKarter">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/anton-matyukha-43b75a2a2/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center"><i>Открыт к интересным задачам и сотрудничеству.</i></p>
