# Окошко (Okoshko) — Веб-сайт и Панель управления

Веб-платформа и административная панель для сервиса онлайн-записи в салоны красоты и к мастерам через Telegram Mini App.

## 🚀 Стек технологий

- **Фреймворк:** [Next.js](https://nextjs.org/) (App Router, React 19)
- **Язык:** [TypeScript](https://www.typescriptlang.org/)
- **Стилизация:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Линтинг:** ESLint
- **Интеграции:** Telegram Web Apps API / TMA SDK, REST API

## 📁 Структура проекта

```text
├── design/                 # Макеты, прототипы и дизайн-концепты
├── src/
│   ├── app/                # Next.js App Router (страницы и layouts)
│   │   ├── admin/          # Административная панель управления
│   │   ├── (site)/         # Публичный сайт и лендинг сервиса
│   │   ├── globals.css     # Глобальные стили и Tailwind
│   │   ├── layout.tsx      # Корневой layout
│   │   └── page.tsx        # Главная страница
│   ├── components/         # Переиспользуемые UI-компоненты
│   ├── lib/                # Утилиты, клиенты API, хелперы
│   └── types/              # TypeScript интерфейсы и типы данных
├── public/                 # Статические ресурсы (иконки, изображения)
├── requirements.md         # Технические требования и архитектура
└── package.json            # Зависимости и скрипты
```

## 🛠️ Запуск проекта

### Установка зависимостей
```bash
npm install
```

### Запуск сервера разработки
```bash
npm run dev
```

Приложение будет доступно по адресу [http://localhost:3000](http://localhost:3000).

### Сборка для production
```bash
npm run build
npm run start
```

### Проверка линтером
```bash
npm run lint
```
