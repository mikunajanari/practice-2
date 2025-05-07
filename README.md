# practice-2
Комплексне дослідження структури, конфігурацій та робочого середовища сучасного JavaScript-проєкту на основі бойлерплейта vite-react-boilerplate

## 1. Початкова підготовка середовища
   
   Склонуємо репозиторій та встановимо усі залежнності проєкту за допомогою pnpm install. Запустимо початковий скрипт для налаштування проєкту pnpm run setup.
  ![image](https://github.com/user-attachments/assets/b3b60ffb-6bb1-4c6a-8596-49edc4a6684f)
  
  ![image](https://github.com/user-attachments/assets/7f502ef6-a7ab-4c83-abca-cefdc9185992)
   
## 2. Аналіз структури файлу package.json

   Призначення полів файлу package.json:
   - name - Назва пакету: "vite-react-boilerplate". Має бути унікальною, використовується при публікації.
   - author - Автор проєкту: Ricardo Valdovinos з електронною поштою.
   - description - Короткий опис: production-ready шаблон для Vite + React проектів.
   - keywords - перелік ключових слів, за якими пакет легше знайти у публічних репозиторіях.
   - version - Поточна версія пакету: "1.0.0", дотримується семантичної версії.
   - license - Тип ліцензії: "MIT" - дозволяє вільне використання з мінімальними обмеженнями.
   - type - вказує на тип модульної системи, яку використовує проєкт.
   - repository - Git-репозиторій з кодом проєкту, щоб посилатися на нього.
   - scripts - Набір зручних команд, які можна запускати через npm run або yarn. Наприклад, npm run dev запускає vite.
   - dependencies - Основні залежності (те, що необхідне для роботи додатку в продакшн).
   - devDependencies - Залежності тільки для розробки: тестування, форматування, білдінг.
   - config.commitizen - Конфігурація для commitizen, щоб використовувати conventional commits.

   dependencies - обов’язкове для продакшну (без цих бібліотек код не буде працювати в браузері):
   - react, react-dom - базові бібліотеки React (react - основна бібліотека для створення інтерфейсів користувача на базі компонентів; react-dom - забезпечує інтеграцію React-компонентів з DOM браузера).
   - react-hook-form - бібліотека для створення форм, з мінімальним ререндерингом.
   - @hookform/resolvers - адаптери для інтеграції з бібліотеками валідації, зокрема zod.
   - zod - бібліотека для декларативного опису схем об'єктів та їх валідації, інтегрується з TypeScript, забезпечує безпечну перевірку структури даних.
   - zustand - інструмент глобального стейту. Використовується для  зберігання глобального стану додатку, який може використовуватись у різних компонентах.
   - @tanstack/react-query - інструмент для управління асинхронними запитами (fetch/post тощо).
   - react-table - бібліотека для створення таблиць.
   - react-router - забезпечує обробку маршрутів, параметрів URL, переходів між сторінками.
   - dayjs — бібліотека для роботи з датами.
   - i18next - фреймворк для локалізації текстів.
   - react-i18next - інтеграція i18next з React.
   - i18next-browser-languagedetector - визначення мови користувача з браузера.
   - @nivo/* - компоненти для побудови діаграм.

   devDependencies - не потрапляють у продакшн, використовуються тільки під час розробки або білду:
   - Лінтери/форматтери: eslint, prettier, eslint-plugins, typescript-eslint, shx.
   - Тестування: vitest, playwright, @testing-library/*, jest-dom.
   - Storybook: всі @storybook/* та addon-*.
   - CI/коміти: commitlint, husky, commitizen, cz-conventional-changelog.
   - Devtools: @tanstack/react-query-devtools, react-table-devtools.
   - CSS: tailwindcss, postcss, autoprefixer.
   - Типи: @types/* — для TypeScript.
   - Vite + плагіни: vite, @vitejs/plugin-react-swc, vite-plugin-static-copy.
   - Misc: faker, jsdom, headlessui, heroicons.
   
## 4. Семантичне версіонування (SemVer)
   
## 5. Дослідження додаткових конфігураційних файлів
   
## 6. Аналіз роботи гіт-хуків Husky
   
## 7. Використання змінних оточення
   
