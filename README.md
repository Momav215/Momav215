# Владислав Окин

**Senior Frontend Developer / Tech Lead**  
Москва · [Telegram: @VladislavOkin](https://t.me/VladislavOkin) · [vladislausokin@yandex.com](mailto:vladislausokin@yandex.com)

---

Senior Frontend-разработчик с 5+ годами коммерческого опыта в проектировании и разработке высоконагруженных SPA и SSR-приложений на React, TypeScript и Next.js. Специализируюсь на frontend-архитектуре, сложных enterprise-интерфейсах, оптимизации производительности (Web Vitals), сквозной observability, надёжности и внедрении инженерных практик в команде.

Опыт роли Tech Lead: архитектурный надзор, code review (правило двух аппрувов, чеклисты), настройка CI/CD quality gates, менторинг, проектирование отказоустойчивых сценариев, стандартизация контрактов взаимодействия с бэкендом.

---

### Технологический стек

- **Core & Languages:** TypeScript, JavaScript (ESNext), HTML5, CSS3/PostCSS
- **Frameworks & Libraries:** React 18/19, Next.js (App Router, SSR/SSG), Redux Toolkit, Redux, Zustand
- **Архитектура & Паттерны:** Feature-Sliced Design (FSD), Domain-Driven modularity, микрофронтенды, Web Workers, WebSocket
- **Тестирование & Качество:** Jest, Playwright, React Testing Library, Storybook, ESLint, TypeScript Strict
- **Инфраструктура & CI/CD:** Vite, Webpack, Docker, GitHub Actions, GitLab CI, rollback strategies
- **Observability & Perf:** Web Vitals (LCP, INP, CLS), structured logging, correlation IDs, Sentry, Zabbix, Grafana

---

### Опыт работы

#### **Группа компаний «Аквариус»**
*Апрель 2024 — настоящее время · Senior Frontend Developer / Tech Lead*

- Руководство frontend-архитектурой и инженерными практиками команды веб-интерфейса enterprise-систем хранения данных и виртуализации.
- Проектирование модульной SPA-архитектуры на React, TypeScript и Redux Toolkit с изолированными доменными модулями (storage, network, replication, telemetry).
- Разработка интерфейсных модулей управления СХД: интерактивные конфигураторы пулов и дисковых групп, дашборды мониторинга сотен томов (LUN), визуализация топологии и отказоустойчивых сценариев.
- Оптимизация клиентской производительности: виртуализация массивных списков и таблиц, мемоизация селекторов, профилирование рендеринга.
- Внедрение инженерного контура: обязательные quality gates в CI/CD, автотестирование доменной логики (Jest) и критических пользовательских путей (Playwright), снижение риска регрессий при прод-релизах.
- Настройка наблюдаемости (observability): сквозное structured-логирование, correlation IDs, мониторинг метрик Web Vitals и JS/API error rates.

#### **Концерн ВКО «Алмаз - Антей»**
*Январь 2021 — Апрель 2024 (3 года 4 месяца) · Frontend-разработчик*

- Разработка защищённых веб-интерфейсов и внутренних систем с повышенными требованиями к надёжности, отказоустойчивости и предсказуемости поведения.
- Проектирование сложных сценариев с многошаговыми формами, таблицами телеметрии, валидацией состояний и безопасным взаимодействием с API.
- Внедрение практик клиентской безопасности, стандартизация процессов code review и модульного тестирования.

---

### Образование

- **НИУ «МЭИ»** — Безопасность компьютерных систем (2020)
- **ООО «1Т»** — Дизайн графических и пользовательских интерфейсов, UI/UX (2022)

---

### Публичные проекты

- **[infra-console](https://github.com/Momav215/infra-console)** — Архитектурный демо-проект веб-консоли управления инфраструктурой хранения данных: React 18, TypeScript, Redux Toolkit, виртуализация списков томов, валидаторы конфигураций пулов, компонентная схема топологии, unit-тесты и GitHub Actions CI.
- **[web-vitals-lab](https://github.com/Momav215/web-vitals-lab)** — Лаборатория frontend observability и Web Vitals на Next.js (App Router): сбор и визуализация метрик LCP/INP/CLS, structured logging с correlation ID, синтетические сценарии нагрузки и E2E smoke-тесты Playwright.
