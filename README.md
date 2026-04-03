# Kostyantyn Ovsiannykov — Portfolio
## Automation Engineer & AI Builder

[![GitHub](https://img.shields.io/badge/GitHub-Kostyaov-181717.svg?style=flat&logo=github)](https://github.com/Kostyaov)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2.svg?style=flat&logo=linkedin)](https://www.linkedin.com/in/костянтин-овсянников-85306838b/)

A collection of real-world tools and automations developed with a **Privacy-First** approach and **AI-assisted** workflows. From browser extensions to cross-platform utilities, every project solves a specific problem.

---

## 🌐 Live Demo
Visit the portfolio at: **[https://Kostyaov.github.io/portfolio/](https://Kostyaov.github.io/portfolio/)**

---

## 🚀 Key Features

- **Bilingual Interface**: Full support for both Ukrainian (UK) and English (EN).
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices.
- **Privacy-First**: Focus on local data processing (IndexedDB, LocalStorage) with zero cloud dependencies where possible.
- **Aesthetic UI**: Modern, glassmorphism-inspired design with smooth animations.

---

## 🛠️ Project Showcase

1.  **macOS Keyboard Layout Sound Notifier**
    *   *Stack*: Python, macOS API, pyobjc.
    *   Utility that voices keyboard layout changes to prevent typing errors.
2.  **YouTube Bookmarks Saver v3.1**
    *   *Stack*: JavaScript, Chrome API, IndexedDB.
    *   Browser extension for local bookmarking with exact timestamps.
3.  **VLC Video Bookmarks Extension**
    *   *Stack*: Python, VLC Lua API.
    *   Cross-platform navigation for video markers inside VLC.
4.  **Quiz Builder Pro v2.0**
    *   *Stack*: HTML/JS, Google Apps Script, Sheets API.
    *   Generate anonymous surveys with automated Google Sheets integration.
5.  **Web-DLP — Media Dashboard**
    *   *Stack*: Python (Flask/FastAPI), HTML/JS, FFmpeg, yt-dlp.
    *   4K video downloader with automatic subtitle embedding.
6.  **Smart PDF Converter & Cleaner**
    *   *Stack*: JavaScript, PDF.js, Canvas API, JSZip.
    *   Local SPA for cleaning watermarks and converting NotebookLM PDFs.
7.  **QuizNLM — Offline Tests**
    *   *Stack*: JavaScript, Chrome Extension API, postMessage.
    *   Parses and saves NotebookLM quizzes for offline practice.

---

## 🧠 Technical Stack

- **Languages**: Python, JavaScript, HTML5/CSS3, Bash/Batch.
- **Platforms**: macOS, Windows, Linux.
- **Tools**: FFmpeg, yt-dlp, VLC Lua, Google Apps Script.
- **AI Workflow**: Claude, ChatGPT, Cursor (Daily use for dev & debugging).

---

## ➕ How to Add New Projects

Adding a new project is automated via a script in `index.html`. Follow these steps:

1.  **Prepare the Image**:
    *   Capture a screenshot of your project.
    *   Save it as `N.png` (where `N` is the next project number, e.g., `8.png`).
    *   Place it in the root directory.
2.  **Edit `index.html`**:
    *   Find the `<div class="projects-grid">` section.
    *   Copy an existing `<div class="project-card reveal">...</div>` block.
    *   Paste it as the last item in the grid.
    *   Update the **Title**, **Description** (use `data-i18n` for bilingual support), and **Tech Tags**.
    *   Keep the `src=""` in `<img>` empty; the script will automatically assign `#N` and `N.png` based on the card's position.
3.  **Add Translations**:
    *   Scroll down to the `<script>` tag at the bottom.
    *   In the `translations` object, add your new project description keys for both `uk` and `en` (e.g., `project8_desc`).

---

## 🖼️ Image Optimization & Guidelines

For the best visual results on the portfolio:

- **Format**: **PNG** (recommended for sharp UI elements) or **WebP** (better compression).
- **Resolution**: Aim for **1200x800 px** or higher (aspect ratio **3:2** or **16:9**).
- **Style**: Use clean, high-resolution screenshots. The portfolio adds rounded corners and shadows automatically.
- **File Name**: Must be strictly `N.png` (e.g., `1.png`, `2.png`) for the automation script to work.

---

## 🌐 Making the Site Public (GitHub Pages Setup)

To make your portfolio visible to everyone on the web:
1.  **Repository Settings**: Go to your repository on GitHub.
2.  **Pages Tab**: In the left sidebar, click on **Settings** > **Pages**.
3.  **Build and Deployment**: 
    - Under **Source**, select `Deploy from a branch`.
    - Under **Branch**, select `main` (or the branch where your files are) and folder `/ (root)`.
4.  **Save**: Click the **Save** button.
5.  **Access Link**: After a few minutes, GitHub will provide a link (usually `https://username.github.io/repository-name/`) where your site is live.

---

## 🛠️ Deployment Algorithm

This portfolio is a static web application hosted via **GitHub Pages**.

### How to Deploy/Update:
1.  **Git Commit**:
    ```bash
    git add .
    git commit -m "Update portfolio content"
    ```
2.  **Push to GitHub**:
    ```bash
    git push origin main
    ```
3.  **Wait for Deployment**: GitHub Actions will automatically rebuild the site. Check the progress in the **Actions** tab of your repository.

---

## 📉 Development Status

- **Stage**: Active & Growing.
- **Next Steps**: Adding new automation projects as they are completed.
- **Maintenance**: Regular updates to CV and project descriptions.

---

## 📧 Contact

- **Email**: [kinstintin38@gmail.com](mailto:kinstintin38@gmail.com)
- **Location**: Zhytomyr, Ukraine

---

<br>

# Костянтин Овсянников — Портфоліо
## Automation Engineer & AI Builder

[![GitHub](https://img.shields.io/badge/GitHub-Kostyaov-181717.svg?style=flat&logo=github)](https://github.com/Kostyaov)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2.svg?style=flat&logo=linkedin)](https://www.linkedin.com/in/костянтин-овсянников-85306838b/)

Колекція реальних інструментів та автоматизацій, розроблених з фокусом на **Конфіденційність (Privacy-First)** та з використанням **AI-assisted** воркфлоу. Від браузерних розширень до кросплатформних утиліт — кожен проект вирішує конкретну задачу.

---

## 🌐 Живе Демо
Відвідайте портфоліо за посиланням: **[https://Kostyaov.github.io/portfolio/](https://Kostyaov.github.io/portfolio/)**

---

## 🚀 Основні особливості

- **Двомовний інтерфейс**: Повна підтримка української (UK) та англійської (EN) мов.
- **Адаптивний дизайн**: Оптимізовано для десктопів, планшетів та мобільних пристроїв.
- **Privacy-First**: Акцент на локальній обробці даних (IndexedDB, LocalStorage) без зайвих хмарних залежностей.
- **Естетичний UI**: Сучасний дизайн у стилі Glassmorphism з плавними анімаціями.

---

## 🛠️ Огляд проектів

1.  **macOS Keyboard Layout Sound Notifier**
    *   *Стек*: Python, macOS API, pyobjc.
    *   Утиліта, що озвучує зміну розкладки клавіатури для запобігання помилкам друку.
2.  **YouTube Bookmarks Saver v3.1**
    *   *Стек*: JavaScript, Chrome API, IndexedDB.
    *   Розширення для локального створення закладок з точними тайм-штампами.
3.  **VLC Video Bookmarks Extension**
    *   *Стек*: Python, VLC Lua API.
    *   Кросплатформна навігація по відео-маркерах всередині VLC.
4.  **Quiz Builder Pro v2.0**
    *   *Стек*: HTML/JS, Google Apps Script, Sheets API.
    *   Генератор анонімних опитувань з автоматичною інтеграцією в Google Таблиці.
5.  **Web-DLP — Media Dashboard**
    *   *Стек*: Python (Flask/FastAPI), HTML/JS, FFmpeg, yt-dlp.
    *   Завантажувач відео у 4K з автоматичним вшиванням субтитрів.
6.  **Smart PDF Converter & Cleaner**
    *   *Стек*: JavaScript, PDF.js, Canvas API, JSZip.
    *   Локальний SPA додаток для видалення ватермарок та конвертації PDF з NotebookLM.
7.  **QuizNLM — Offline Tests**
    *   *Стек*: JavaScript, Chrome Extension API, postMessage.
    *   Парсить та зберігає квізи з NotebookLM для проходження офлайн.

---

## 🧠 Технічний стек

- **Мови**: Python, JavaScript, HTML5/CSS3, Bash/Batch.
- **Платформи**: macOS, Windows, Linux.
- **Інструменти**: FFmpeg, yt-dlp, VLC Lua, Google Apps Script.
- **AI Воркфлоу**: Claude, ChatGPT, Cursor (Щоденне використання для розробки та дебагінгу).

---

## ➕ Як додавати нові проекти

Додавання нового проекту автоматизовано через скрипт в `index.html`. Виконайте наступні кроки:

1.  **Підготуйте зображення**:
    *   Зробіть скріншот вашого проекту.
    *   Збережіть його як `N.png` (де `N` — це наступний номер проекту, наприклад, `8.png`).
    *   Покладіть файл у корінь репозиторію.
2.  **Редагуйте `index.html`**:
    *   Знайдіть секцію `<div class="projects-grid">`.
    *   Скопіюйте існуючий блок `<div class="project-card reveal">...</div>`.
    *   Вставте його останнім елементом у сітці.
    *   Оновіть **Заголовок**, **Опис** (використовуйте `data-i18n` для підтримки обох мов) та **Теги технологій**.
    *   Залиште `src=""` в тезі `<img>` порожнім; скрипт автоматично призначить `#N` та файл `N.png` відповідно до позиції картки.
3.  **Додайте переклади**:
    *   Прокрутіть до тегу `<script>` внизу файлу.
    *   В об'єкті `translations` додайте ключі для нового опису проекту для `uk` та `en` (наприклад, `project8_desc`).

---

## 🖼️ Оптимізація та вимоги до зображень

Для досягнення найкращого вигляду в портфоліо:

- **Формат**: **PNG** (рекомендовано для чітких UI-елементів) або **WebP** (краще стиснення).
- **Роздільна здатність**: Мінімум **1200x800 px** (співвідношення сторін **3:2** або **16:9**).
- **Стиль**: Використовуйте чіткі скріншоти високої якості. Портфоліо автоматично додає закруглені кути та тіні.
- **Ім'я файлу**: Має бути строго `N.png` (наприклад, `1.png`, `2.png`), щоб скрипт автоматизації зміг його підтягнути.

---

## 🌐 Як зробити сайт видимим для всіх (Налаштування GitHub Pages)

Щоб ваше портфоліо було доступне всім в інтернеті:
1.  **Налаштування репозиторію**: Перейдіть у ваш репозиторій на GitHub.
2.  **Вкладка Pages**: У лівому меню оберіть **Settings** > **Pages**.
3.  **Build and Deployment**: 
    - У розділі **Source** оберіть `Deploy from a branch`.
    - У розділі **Branch** оберіть `main` (або ту гілку, де знаходяться ваші файли) та папку `/ (root)`.
4.  **Зберегти**: Натисніть кнопку **Save**.
5.  **Посилання**: Через кілька хвилин GitHub надасть посилання (зазвичай `https://username.github.io/repository-name/`), за яким ваш сайт буде доступний у мережі.

---

## 🛠️ Алгоритм розгортання

Портфоліо — це статичний веб-додаток, що хоститься через **GitHub Pages**.

### Як оновити/розгорнути:
1.  **Git Commit**:
    ```bash
    git add .
    git commit -m "Оновлення контенту портфоліо"
    ```
2.  **Push на GitHub**:
    ```bash
    git push origin main
    ```
3.  **Зачекайте розгортання**: GitHub Actions автоматично перезбере сайт. Скул за прогресом у вкладці **Actions** вашого репозиторію.

---

## 📈 Статус розробки

- **Стадія**: Активний розвиток та наповнення.
- **Наступні кроки**: Додавання нових проектів автоматизації по мірі їх завершення.
- **Підтримка**: Регулярне оновлення резюме та описів проектів.

---

## 📧 Контакти

- **Email**: [kinstintin38@gmail.com](mailto:kinstintin38@gmail.com)
- **Локація**: Житомир, Україна

---
*Розроблено Костянтином Овсянниковим © 2026*
