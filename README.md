# chill-app

Веб-приложение на Next.js (App Router) и TypeScript.

## Стек

- [Next.js](https://nextjs.org) 16 (App Router)
- [React](https://react.dev) 19
- [TypeScript](https://www.typescriptlang.org)
- CSS Modules
- ESLint

## Требования

- Node.js 20.9+
- npm

## Запуск

```bash
npm install
npm run dev
```

Приложение будет доступно на [http://localhost:3000](http://localhost:3000).

## Скрипты

| Команда         | Описание                        |
| --------------- | ------------------------------- |
| `npm run dev`   | dev-сервер с hot reload         |
| `npm run build` | продакшен-сборка                |
| `npm run start` | запуск продакшен-сборки         |
| `npm run lint`  | проверка кода ESLint            |

## Структура проекта

```
app/      — маршруты, страницы и layout'ы (App Router)
public/   — статические файлы
```
