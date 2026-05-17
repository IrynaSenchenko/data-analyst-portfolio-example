# Data Analyst Portfolio Website Example

Цей репозиторій містить приклад простого односторінкового сайту-портфоліо для Junior Data Analyst.

Сайт створений як один HTML-файл і може бути опублікований безкоштовно через GitHub Pages.

## Демо-сайт

Сайт знаходиться у файлі:

```text
docs/index.html
```

Після публікації через GitHub Pages він буде доступний за посиланням:

```text
https://irynasenchenko.github.io/data-analyst-portfolio-example/
```


> Замініть `irynasenchenko` на свій GitHub username.

## Що є в цьому репозиторії

```text
data-analyst-portfolio-example/
│
├── README.md
└── docs/
    └── index.html
```

## Для чого цей приклад

Цей репозиторій можна використовувати як навчальний приклад, щоб зрозуміти:

- як може виглядати сайт-портфоліо Junior Data Analyst;
- які секції варто додати на сайт;
- як зібрати в одному місці CV, LinkedIn, GitHub, Tableau Public та проєкти;
- як за допомогою AI згенерувати HTML-файл для GitHub Pages;
- як опублікувати сайт безкоштовно через GitHub Pages.

## Як використати цей приклад

1. Перегляньте приклад сайту у файлі `docs/index.html`.
2. Скопіюйте промпт нижче.
3. Замініть demo-інформацію на свої дані:
   - ім’я;
   - контакти;
   - LinkedIn;
   - GitHub;
   - Tableau Public;
   - CV;
   - фото;
   - опис проєктів;
   - посилання на портфоліо.
4. Попросіть AI створити ваш власний `index.html`.
5. Завантажте файл у свій GitHub repository.
6. Увімкніть GitHub Pages.
7. Додайте посилання на сайт у CV, LinkedIn та GitHub profile.

## Що підготувати перед створенням сайту

Перед тим як використовувати промпт, підготуйте:

- готове або чернеткове CV;
- посилання на LinkedIn;
- посилання на GitHub;
- посилання на Tableau Public;
- посилання на Google Sheets / Google Drive project;
- посилання на SQL project;
- посилання на Python / Google Colab / HTML report;
- короткі описи 3–4 проєктів;
- фото, якщо хочете додати його на сайт;
- email для контакту;
- 1–3 вакансії, якщо хочете адаптувати сайт під конкретну роль.

> Важливо: AI не має вигадувати ваш досвід, навички або результати. Він допомагає структурувати й красиво подати те, що у вас уже є.

---

# Prompt Template: Data Analyst Portfolio Website

## Role

Ти — UX-розробник і кар'єрний копірайтер у data-сфері який допомагає створити простий, професійний сайт-портфоліо для Junior Data Analyst.

Твоя задача — на основі резюме, LinkedIn, GitHub-профілю, фото, портфоліо-проєктів і, за бажанням, цільових вакансій, створити готовий односторінковий сайт-портфоліо у вигляді одного HTML-файлу `index.html`, який можна опублікувати через GitHub Pages.

## Context

Я проходжу курс з Data Analytics і хочу створити особистий сайт-портфоліо, де буде зібрана інформація про мене, мої навички, проєкти, CV та контакти.

## Input Data

Name: [ім’я кандидата]

Target role: Junior Data Analyst

Location: [місто, країна]

Email: [email]

LinkedIn: [посилання]

GitHub: [посилання]

Tableau Public: [посилання]

Resume: [вставити текст або прикріпити PDF/DOCX]

Additional information: [додати важливу інформацію, якої немає в Master CV: про себе, проєкти, досвід, цілі, бажаний напрям]

Target vacancy: [вставити link 1, link 2, link 3 або написати “no specific vacancy yet”]

Photo: [вставити посилання на фото або написати “no photo”]

Website language: [Ukrainian / English]. Для української версії назви секцій, навички, професійні терміни, назви посад, інструментів і платформ залишай англійською там, де це доречно.

## Portfolio Projects

### Project 1

Title: [назва проєкту]

Tools: [інструменти]

Description: [короткий опис проєкту]

Key result / insight: [ключовий результат або висновок]

Link: [посилання]

### Project 2

Title: [назва проєкту]

Tools: [інструменти]

Description: [короткий опис проєкту]

Key result / insight: [ключовий результат або висновок]

Link: [посилання]

### Project 3

Title: [назва проєкту]

Tools: [інструменти]

Description: [короткий опис проєкту]

Key result / insight: [ключовий результат або висновок]

Link: [посилання]

### Project 4

Title: [назва проєкту]

Tools: [інструменти]

Description: [короткий опис проєкту]

Key result / insight: [ключовий результат або висновок]

Link: [посилання]

## Before Writing Code

1. Якщо Target vacancy надана, проаналізуй її та витягни:
   - must-have та nice-to-have skills;
   - ключові задачі ролі;
   - ключові слова для позиціонування кандидата.

   Якщо вакансій декілька — знайди спільний фокус.

   Якщо вакансія не надана — створи універсальний сайт під Junior Data Analyst / Data Analyst entry-level profile.

2. Перевір відповідність кандидата на основі резюме, GitHub, опису проєктів та досвіду роботи.

   Визнач:
   - сильні сторони кандидата;
   - найрелевантніші проєкти;
   - зони, які поки не покриті досвідом;
   - як чесно компенсувати ці зони акцентом на portfolio projects і transferable skills.

3. Коротко поясни структуру майбутнього сайту та скажи, які секції будуть на сайті.

4. Вкажи, на які проєкти варто зробити найбільший акцент.

5. Якщо якихось даних не вистачає, чесно напиши, чого саме бракує.


## Website Structure

Створи сайт з такими секціями:

1. Hero:
   - фото, якщо надано;
   - ім’я;
   - target role;
   - короткий professional pitch;
   - кнопки: LinkedIn, GitHub, Contact.

2. About:
   - 3–4 абзаци персонального позиціонування під роль;
   - зроби акцент залежно від сильних сторін кандидата: portfolio projects, практичний досвід або transferable skills.

3. Skills:
   - згрупуй навички за категоріями:
     - Data Analysis;
     - SQL & Databases;
     - Python;
     - BI & Visualization;
     - Tools.

4. Projects:
   - створи project cards;
   - кожна картка має містити:
     - назву;
     - опис;
     - tools;
     - 1–2 bullet points про результат або цінність;
     - кнопки з посиланнями.

5. Experience / Background:
   - коротко покажи попередній досвід через transferable skills;
   - якщо немає комерційного досвіду в аналітиці, не подавай попередню роботу як Data Analyst experience.

6. Education & Courses:
   - освіта та релевантні курси.

7. Contact:
   - email через `mailto:`;
   - LinkedIn;
   - GitHub;
   - Tableau Public.

## Section Titles

Use short, clean section titles only:

- About Me
- Skills
- Portfolio Projects
- Experience
- Education & Courses
- Contact

## Design Requirements

- Стиль: мінімалістичний, professional, без AI-look.
- Орієнтири: візуальна логіка `pudding.cool` і чіткість `visualcinnamon.com`. Не копія — тільки натхнення.
- Тема: toggle dark/light, за замовчуванням — світла.
- Фон: `#fafafa`, не чисто білий.
- Палітра: один акцентний колір — насичений, не пастельний, не світло-блакитний.
- Підбери акцентний колір залежно від контексту кандидата: deep navy, teal, indigo або emerald.
- Текст на акцентному фоні має проходити WCAG AA: contrast ≥ 4.5.
- Типографіка: Google Fonts — Inter для основного тексту + Space Grotesk або JetBrains Mono для технічних акцентів.
- Чітка ієрархія: заголовки 48–64px на desktop, line-height ≥ 1.6, max-width тексту ~65ch.
- Адаптивність: mobile-first, breakpoints на 768px і 1024px.
- Анімація: smooth scroll, м'які hover-стани, fade-in секцій через IntersectionObserver.
- Без важких анімацій, без 3D, без каруселей.


## Do Not Do

Не робити:

- градієнтних кнопок “з 2015”;
- генеричних stock icons;
- іконок типу rocket, target, lightbulb;
- emoji типу 🚀🎯💡;
- hero gradient blob;
- фонових градієнтів;
- skill-bars;
- відсотків володіння навичками;
- фейкових метрик.

## Technical Requirements

- Один файл `index.html`.
- Увесь CSS має бути всередині `<style>`.
- JS — всередині `<script>`, якщо потрібен.
- Без CSS-фреймворків: без Tailwind, без Bootstrap.
- Іконки — inline SVG.
- Усі CTA:
  - Contact → `mailto:{email}`;
  - LinkedIn / GitHub / Tableau → прямий URL з `target="_blank"` і `rel="noopener"`.
- Додай `<title>`.
- Додай `<meta name="description">`.
- Додай Open Graph теги з ім'ям і роллю.
- Сайт має без правок працювати на GitHub Pages.

## Content Rules

- Не вигадуй досвід.
- Не перебільшуй рівень кандидата.
- Пиши професійно, але просто.
- Пояснюй проєкти так, щоб рекрутер швидко зрозумів їхню цінність.
- Проєкти мають звучати як portfolio projects, не як домашні завдання.
- Якщо немає комерційного досвіду в аналітиці, зроби основний акцент на portfolio projects.

## Output Format

1. Спочатку коротко поясни:
   - структуру сайту;
   - дизайн-рішення;
   - на які проєкти зроблено акцент.

2. Потім надай повний HTML-код у code block.

3. Якщо ти можеш створювати файли, додатково створи готовий файл `index.html` для скачування.

   Якщо не можеш створити файл, надай HTML-код так, щоб я могла скопіювати його в окремий файл і зберегти як `index.html`.

4. Після коду додай короткий checklist:
   - як зберегти файл як `index.html`;
   - як створити GitHub repository;
   - як завантажити файл;
   - як увімкнути GitHub Pages;
   - що перевірити перед публікацією.

---

# Приклад заповнення Input Data

Нижче наведено приклад заповнення блоків для вигаданої кандидатки Iryna Petrenko.

> Важливо: це demo-приклад. Якщо окремі посилання ведуть на інші профілі або репозиторії, використовуйте їх лише як приклад структури. У реальному сайті замініть усі посилання на власні.

## Input Data

Name: Iryna Petrenko

Target role: Junior Data Analyst

Location: Kyiv, Ukraine

Email: iryna.petrenko@email.com

LinkedIn: https://www.linkedin.com/in/iryna-petrenko-123456789/

GitHub: https://github.com/IrynaPetrenko123

Tableau Public: https://public.tableau.com/app/profile/iryna.petrenko

Resume: CV прикріплено у `.docx` файлі.

Additional information: додаю детальний опис проєктів нижче.

Target vacancy:

1. https://jobs.dou.ua/companies/honeytech/vacancies/348015/
2. https://robota.ua/company14260010/vacancy11195209
3. https://robota.ua/company16255573/vacancy11062411
4. https://robota.ua/company307419/vacancy11135280

Photo: фото прикріпляю.

Website language: Ukrainian. Для української версії назви секцій, навички, професійні терміни, назви посад, інструментів і платформ залишай англійською там, де це доречно.

## Portfolio Projects

### Project 1

Title: Customer Cohort Analysis in Google Sheets

Tools: Google Sheets, formulas, pivot tables, cohort table, conditional formatting

Description:
У межах навчального проєкту я проаналізувала retention і revenue для e-commerce датасету. Мета проєкту — зрозуміти, як утримуються клієнти по місячних когортах і як змінюється їхній дохід упродовж життєвого циклу.

What I did:
- підготувала дані для когортного аналізу;
- розрахувала retention по місячних когортах;
- побудувала cohort table;
- порівняла динаміку revenue і cumulative revenue між когортами.

Key result / insight:
- найбільша когорта за кількістю нових клієнтів — липень 2025: 452 клієнти;
- найсильніша динаміка revenue спостерігалася в липні-серпні;
- у більшості когорт retention після першого місяця становить близько 50–60%, але далі поступово знижується;
- когорта 2025-07 також показала найвищий cumulative revenue.

Next steps:
- проаналізувати причини просідання retention після перших місяців;
- порівняти канали залучення клієнтів;
- дослідити, які сегменти клієнтів формують найсильніші когорти.

Link:
https://docs.google.com/spreadsheets/d/12vaY76hJZ141dA8h4QuCbowGMqDSyLEe3ZqpDpwdR70/edit?gid=715670107

### Project 2

Title: Customer Acquisition & Revenue Analysis

Tools: SQL, SQLite, DBeaver, CSV import, relational database structure

Description:
SQL-проєкт для аналізу каналів залучення клієнтів та revenue в e-commerce dataset. У проєкті дані були імпортовані з CSV у SQLite, підготовлені таблиці для аналізу та написані SQL-запити для порівняння каналів залучення.

What I did:
- імпортовано CSV-дані в SQLite;
- підготовлено таблиці для аналізу в DBeaver;
- використано Primary Key / Foreign Key для логіки зв’язків між таблицями;
- написано SQL-запити для аналізу customer acquisition channels;
- порівняно канали за кількістю клієнтів, revenue та поведінкою клієнтів.

Key result / insight:
Проєкт показує, як за допомогою SQL можна перетворити сирі таблиці на аналітичні висновки щодо каналів залучення клієнтів і revenue.

Links:
- GitHub repository: https://github.com/IrynaSenchenko/customer-acquisition-sql-analysis
- README.md: https://github.com/IrynaSenchenko/customer-acquisition-sql-analysis/blob/main/README.md

### Project 3

Title: Customer Cohort Analysis Dashboard in Tableau

Tools: Tableau Public, calculated fields, filters, CSV dataset, dashboarding

Description:
У межах навчального проєкту я побудувала інтерактивний Tableau dashboard для аналізу retention і revenue клієнтів e-commerce бізнесу. Мета проєкту — зрозуміти, як утримуються клієнти по місячних когортах, які когорти приносять найбільше revenue та як змінюється поведінка клієнтів упродовж життєвого циклу.

What I did:
- побудувала dashboard у Tableau Public;
- створила retention curve, retention heatmap та cohort revenue table;
- побудувала графік Revenue & Order Count;
- додала фільтри за Order Channel, Order Status, Payment Method і Registration Date.

Key result / insight:
- найбільша когорта за кількістю нових клієнтів — липень 2025: 452 клієнти;
- липнева когорта також має найвищий cohort revenue;
- найвища динаміка revenue спостерігалася в липні-серпні;
- серпень мав найбільшу кількість замовлень — 1 409;
- у більшості когорт retention після першого місяця становить близько 49–60%, але далі поступово знижується.

Next steps:
- дослідити, чому липнева когорта виявилася найсильнішою;
- порівняти retention і revenue залежно від order channel;
- перевірити, чи є різниця в поведінці клієнтів за payment method;
- проаналізувати, як статуси замовлень впливають на revenue analysis.

Link:
https://public.tableau.com/app/profile/iryna.senchenko/viz/CustomerCohortAnalysisE-commerce/CohortAnalysis

### Project 4

Title: Python Project: EDA & Customer Cohort Analysis

Tools: Python, pandas, matplotlib, seaborn, Google Colab, GitHub Pages

Description:
Python-проєкт для exploratory data analysis та cohort analysis e-commerce dataset. У проєкті виконано базову перевірку даних, EDA, аналіз customer behavior, retention, revenue dynamics та створено HTML report для публікації.

What I did:
- завантажено та перевірено customer and order datasets;
- виконано перевірку missing values;
- проведено exploratory data analysis;
- побудовано cohort analysis;
- проаналізовано retention і revenue dynamics;
- створено HTML report для GitHub Pages.

Key result / insight:
Проєкт демонструє повний базовий цикл аналізу в Python: від перевірки структури даних до побудови cohort analysis, візуалізації результатів і публікації HTML-звіту.

Links:
- GitHub repository: https://github.com/IrynaSenchenko/python-eda-cohort-analysis
- README.md: https://github.com/IrynaSenchenko/python-eda-cohort-analysis/blob/main/README.md
- HTML dashboard: https://irynasenchenko.github.io/python-eda-cohort-analysis/
