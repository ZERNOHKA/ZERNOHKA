# Никита Шестернин

**JavaScript / TypeScript Developer · React / Node.js**

Разрабатываю веб-приложения на JavaScript и TypeScript. На стажировке в BLACKCLOUD работал над Kanban-доской для Redmine на React. В ZERNIX Dungeon Assistant занимаюсь интерфейсом, серверной логикой и интеграцией с данными.

Екатеринбург · удалённо  
[Telegram](https://t.me/ZERNOHKA) · [Email](mailto:sesterninn69@gmail.com)

## Избранные проекты

| Проект | Что сделал | Технологии |
| --- | --- | --- |
| **[ZERNIX Dungeon Assistant](https://github.com/ZERNOHKA/ZERNIX-Dungeon-Assistant)** | Развиваю помощник для мастеров D&D с генерацией персонажей, сцен и наград. [Веб-приложение](https://zernix.ru) · [Ранняя публичная версия](https://github.com/ZERNOHKA/ZERNIX-Dungeon-Assistant) | React, TypeScript, Node.js, Express, Electron, SQLite |
| **[Legacy PHP CRM Lab](https://github.com/ZERNOHKA/legacy-php-crm-lab)** | Воссоздал окружение PHP 5.3.3, настроил загрузку `php.ini` для CGI и добавил автоматические проверки. Демостенд использует вымышленные данные. | Docker Compose, Apache/CGI, MariaDB, Playwright |
| **[ZERNIX NEXUS](https://github.com/ZERNOHKA/ZERNIX-NEXUS)** | Разработал Windows-утилиту с пресетами, мониторингом и восстановлением настроек. В репозитории есть деморежим. | Python, CustomTkinter, Windows API |

### ZERNIX Dungeon Assistant — генерация и сохранение награды

**Fullstack.** Мастер задаёт параметры награды и запускает генерацию в React-интерфейсе. В desktop-версии запрос идёт через Electron IPC, а генератор подбирает предметы из SQLite. Интерфейс показывает карточку, которую можно добавить в избранное. Избранное сохраняется в `localStorage`.

**Backend.** Node.js, Express, REST API и SQL (SQLite). [Обработчик генерации наград](https://github.com/ZERNOHKA/ZERNIX-Dungeon-Assistant/blob/b78142ede849bd4fb98e2828a3916c83972eadd4/electron/zernix-api-server.cjs#L43-L65) проверяет API-ключ, передаёт параметры генератору и возвращает JSON.

## Опыт работы

**BLACKCLOUD — Frontend Developer Intern** · июнь — сентябрь 2026

- Разрабатывал внутреннюю Kanban-доску для Redmine на React и TypeScript.
- Реализовывал фильтрацию, статусы задач и логику рабочих процессов; интегрировал интерфейс с Redmine REST API.
- Исправлял ошибки, проверял функциональность и разбирался с существующим кодом и Docker-окружением.

*Код и внутренние материалы компании не публикую.*

## Технологии

- **Frontend:** React, TypeScript, JavaScript, HTML, CSS, Tailwind CSS, Vite
- **Backend и данные:** Node.js, Express, REST API, SQL, SQLite; Python
- **Инструменты и тестирование:** Git, Docker, Docker Compose, Postman, Playwright, GitHub Actions
- **Desktop и системы:** Electron, Windows API, Linux; опыт работы с legacy PHP/Apache

## Образование

**Хекслет Колледж** · 2023–2027  
09.02.07 «Информационные системы и программирование», 4-й курс.
