# Галерея этапов

Статический HTML-сайт с галереей изображений этапов.

## Структура проекта

```
├── index.html          # Главная страница с галереей
├── public/
│   └── stages/         # Папка с изображениями этапов
│       ├── stage1.jpg
│       ├── stage2.jpg
│       └── ...
├── vercel.json         # Конфигурация для Vercel
└── package.json        # Метаданные проекта
```

## Развертывание на Vercel

1. Установите Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Войдите в аккаунт:
   ```bash
   vercel login
   ```

3. Разверните проект:
   ```bash
   vercel
   ```

## Локальный запуск

```bash
npm install
npm start
```

Сайт будет доступен по адресу http://localhost:3000