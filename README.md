# GEOnaut

**GEOnaut** — агентство по GEO-оптимизации и AI Visibility для рынка Казахстана.

GEOnaut помогает брендам понимать, как они представлены в ответах генеративных систем — ChatGPT, Gemini, Google AI, Perplexity и других AI-платформах — и системно увеличивать вероятность упоминания и рекомендации.

## Что такое GEO

**GEO — Generative Engine Optimization.**

Если классическое SEO помогает сайту занимать позиции в поисковой выдаче, GEO работает с тем, насколько хорошо генеративные системы:

* понимают бренд;
* находят достоверную информацию о компании;
* используют бренд в ответах;
* цитируют его источники;
* рекомендуют его пользователям;
* правильно описывают продукты, услуги и преимущества.

## Что делает GEOnaut

Основной подход GEOnaut строится вокруг измеримого AI Visibility:

* AI Visibility Score;
* Share of Voice относительно конкурентов;
* Recommendation Rate;
* анализ коммерческих prompts;
* анализ источников и цитирований;
* Brand Accuracy;
* поиск устаревшей или некорректной информации;
* competitor analysis;
* GEO-аудит сайта и цифрового присутствия;
* roadmap по увеличению AI Visibility.

Подход строится по принципу:

**Baseline → Analysis → Optimization → Remeasure**

Мы не обещаем гарантированный «TOP-1 в ChatGPT», поскольку ответы генеративных систем не являются полностью детерминированными. Вместо этого GEOnaut использует повторные измерения и сравнение с конкурентами.

## Kazakhstan-first

GEOnaut создаётся с фокусом на рынок Казахстана.

В перспективе методология должна учитывать:

* русский язык;
* казахский язык;
* английский язык;
* локальные казахстанские источники;
* местные каталоги и площадки;
* особенности конкурентной среды Казахстана;
* специфику локальных коммерческих запросов.

## Пример задач

GEOnaut анализирует запросы типа:

* «Какую стоматологию выбрать в Алматы?»
* «Какой банк Казахстана лучше для ИП?»
* «Лучшие ЖК бизнес-класса в Алматы»
* «Какое агентство недвижимости выбрать?»
* «Какая CRM лучше для компании в Казахстане?»
* «Какую частную школу выбрать в Алматы?»

Цель — понять, какие бренды AI рекомендует пользователю и почему.

## Kazakhstan AI Visibility Index

Одна из будущих инициатив GEOnaut — **Kazakhstan AI Visibility Index**.

Это исследовательский рейтинг казахстанских компаний и брендов по их представленности в генеративных системах.

Планируемые показатели:

* AI Visibility;
* Share of Voice;
* Recommendation Rate;
* Citation Rate;
* Brand Accuracy;
* конкурентная позиция.

В перспективе накопленные данные могут стать основой отдельного аналитического продукта GEOnaut Intelligence.

## Технологии

Текущая версия лендинга максимально простая:

* HTML5;
* CSS3;
* Vanilla JavaScript;
* Schema.org structured data;
* Open Graph metadata;
* GitHub Pages.

Проект не требует Node.js, frontend framework или backend для отображения лендинга.

## Запуск локально

Достаточно открыть файл:

```text
index.html
```

в браузере.

Также можно запустить простой локальный HTTP-сервер:

```bash
python -m http.server 8000
```

После этого сайт будет доступен по адресу:

```text
http://localhost:8000
```

## Deployment

Production-версия публикуется через **GitHub Pages**.

Схема:

```text
GitHub Repository
       ↓
    main branch
       ↓
    index.html
       ↓
  GitHub Pages
       ↓
   GEOnaut website
```

Для публикации:

1. Открыть `Settings`.
2. Перейти в `Pages`.
3. Выбрать `Deploy from a branch`.
4. Выбрать ветку `main`.
5. Выбрать `/root`.
6. Сохранить настройки.

После этого GitHub автоматически публикует сайт.

## Custom domain

В дальнейшем к GitHub Pages можно подключить:

```text
geonaut.kz
```

или:

```text
geonaut.ai
```

После подключения домена необходимо заменить в `index.html` значения:

```text
YOUR_DOMAIN_HERE
```

на реальный адрес сайта.

Это относится к:

* canonical URL;
* Open Graph URL;
* Schema.org;
* OG image.

## Lead form

Текущая форма **Free AI Visibility Scan** работает как frontend-прототип.

Она пока не отправляет данные на сервер.

Для production можно подключить:

* Formspree;
* Telegram Bot;
* Google Forms;
* CRM webhook;
* собственный backend/API.

## Roadmap

Ближайшие направления развития:

* [ ] подключение рабочего lead form;
* [ ] регистрация и подключение собственного домена;
* [ ] RU / KZ версии сайта;
* [ ] реальные GEO-кейсы;
* [ ] AI Visibility dashboard;
* [ ] автоматизированный сбор AI mentions;
* [ ] competitor monitoring;
* [ ] citation tracking;
* [ ] GEOnaut Visibility Score;
* [ ] Kazakhstan AI Visibility Index;
* [ ] GEOnaut Intelligence;
* [ ] переход от агентской модели к собственному SaaS-продукту.

## Статус

**MVP / Early Stage**

Проект находится на стадии формирования продукта, методологии и первых пилотных GEO-аудитов.

---

**GEOnaut**

*Navigate AI Search.*

**Get found. Get cited. Get recommended.**
