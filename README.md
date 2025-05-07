# practice-2
Комплексне дослідження структури, конфігурацій та робочого середовища сучасного JavaScript-проєкту на основі бойлерплейта vite-react-boilerplate

## 1. Початкова підготовка середовища
   
   Склонуємо репозиторій та встановимо усі залежнності проєкту за допомогою pnpm install. Запустимо початковий скрипт для налаштування проєкту pnpm run setup.
  ![image](https://github.com/user-attachments/assets/b3b60ffb-6bb1-4c6a-8596-49edc4a6684f)
  
  ![image](https://github.com/user-attachments/assets/7f502ef6-a7ab-4c83-abca-cefdc9185992)
   
## 2. Аналіз структури файлу package.json

   - name - Назва пакету: "vite-react-boilerplate". Має бути унікальною, використовується при публікації.
   - author - Автор проєкту: Ricardo Valdovinos з e-mail'ом.
   - description - Короткий опис: production-ready шаблон для Vite + React проектів.
   - version - Поточна версія пакету: "1.0.0", дотримується семантичної версії.
   - license - Тип ліцензії: "MIT" — дозволяє вільне використання з мінімальними обмеженнями.
   - repository - Git-репозиторій з кодом проєкту, щоб посилатися на нього.
   - scripts - Набір зручних команд, які можна запускати через npm run або yarn. Наприклад, npm run dev запускає vite, npm run test — vitest + playwright.
   - dependencies - Основні залежності (те, що необхідне для роботи додатку в продакшн).
   - devDependencies - Залежності тільки для розробки: тестування, форматування, білдінг.
   - config.commitizen - Конфігурація для commitizen, щоб використовувати conventional commits.
   
## 4. Семантичне версіонування (SemVer)
   
## 5. Дослідження додаткових конфігураційних файлів
   
## 6. Аналіз роботи гіт-хуків Husky
   
## 7. Використання змінних оточення
   
