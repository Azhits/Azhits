# Андрей Жиц — ML-инженер

> Computer Vision · Классический ML · NLP · Clean Architecture

Привет! Я ML-инженер из Архангельска, выпускник САФУ по направлению «Интеллектуальные системы и машинное обучение». Решаю прикладные задачи: от повышения разрешения спутниковых снимков до классификации диалогов голосового робота и CV-агентов для игр.

---

## 🛰 Ключевые проекты

### [Arctic SAR Super-Resolution](https://github.com/Sergei703/SR_SAR)
> ВКР по заказу **Гринатом** (дочерняя структура Росатома) · 2024–2025

Каскад из 5 генераторов Real-ESRGAN для повышения разрешения спутниковых SAR-снимков Арктики в **×32** (32 → 1024 пкс).  
Итог: **PSNR = 29.88 дБ**, SSIM = 0.774 (гибридная схема Real-ESRGAN + дообученный диффузионный PDM_SAR_inSAR).  
Веса 5 моделей опубликованы на 🤗 [Hugging Face](https://huggingface.co/Azhits/arctic-sar-sr-models).

`PyTorch` `Real-ESRGAN` `DDPM/DDIM` `OpenCV` `GeoTIFF` `FastAPI`

---

### [Genshin Impact Auto-Fight Bot](https://github.com/Azhits/Team-DED-)
> Командный проект Team-DED · 2025

Real-time CV-агент для автономного прохождения подземелий: захват экрана → ROI-анализ → детекция событий → управление персонажем.  
Ключевое архитектурное решение — симуляция **нативных устройств ввода** (pynput) вместо memory injection.  
Полный рефакторинг MVC → **Clean Architecture** (Core / Infrastructure / Presentation).

`Python` `OpenCV` `mss` `pynput` `Clean Architecture`

---

### [T2 Churn Prediction](https://github.com/Azhits/t2-churn-hackathon)
> Хакатон T2 · 2025

Классификация исходов звонков голосового робота «Ольга» для предсказания оттока абонентов.  
Переформулировал 48 классов → 3 бизнес-категории, применил TF-IDF + BayesSearchCV.  
Итог: **accuracy = 0.97, macro F1 = 0.97** (XGBoost).

`scikit-learn` `XGBoost` `TF-IDF` `BayesSearchCV` `feature engineering`

---

### [Drivee Analytics](https://github.com/Front3ndy/mpit2026)
> Гранд-финал МПИТ 2026 «Моя профессия — ИТ»

LLM-пайплайн на GPT-4o-mini: генерация и верификация SQL по запросу на русском языке.  
Безопасная генерация (EXPLAIN-анализ, retry-логика, блокировка DELETE/UPDATE/DROP), UI с автографиками.

`GPT-4o-mini` `FastAPI` `PostgreSQL` `Docker` `prompt engineering`

---

## 🧰 Стек

| Область | Инструменты |
|---|---|
| Deep Learning | PyTorch, Hugging Face Transformers, Real-ESRGAN, DDPM/DDIM |
| Classic ML | scikit-learn, XGBoost, CatBoost, Optuna, BayesSearchCV |
| Computer Vision | OpenCV, YOLO, U-Net, mss, Roboflow |
| NLP / LLM | Hugging Face, spaCy, NLTK, GPT-4o-mini, RAG |
| Data & EDA | pandas, numpy, matplotlib, seaborn, Plotly |
| Infra | FastAPI, Docker, Git, PostgreSQL, Jupyter, MLflow |

---

## 🏆 Достижения

- 🥇 Участник Гранд-финала **Моя профессия — ИТ** III сезон (2026)
- 🏅 Сертификат с отличием — **Samsung Innovation Campus**, трек ИИ (136 ак. ч.)
- 🥇 Диплом I степени — Хакатон **«Северное сияние»**, трек ИИ (2025)
- 🏆 Победитель **НЕЙМАРК.Хакатона** «Умный кампус 2025», диплом 3 степени
- 🏆 Победитель международного хакатона **НИУ ВШЭ — НН** «ИИ и экология» (2024)

---

## 📬 Контакты

[![Telegram](https://img.shields.io/badge/Telegram-@Azhits-2CA5E0?style=flat&logo=telegram)](https://t.me/Azhits)
[![Email](https://img.shields.io/badge/Email-a.zhits@yandex.ru-red?style=flat&logo=yandex)](mailto:a.zhits@yandex.ru)
[![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-Azhits-yellow?style=flat)](https://huggingface.co/Azhits)
