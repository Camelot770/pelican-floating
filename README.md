# 🦩 Pelican Frontend (Vercel)

Telegram Mini App для флоатинг-студии.

## Деплой на Vercel:

### Способ 1: Через GitHub
1. Создай репозиторий на GitHub
2. Загрузи эти файлы
3. Зайди на [vercel.com](https://vercel.com)
4. Import → выбери репозиторий → Deploy

### Способ 2: Через CLI
```bash
npm i -g vercel
vercel login
vercel
```

## После деплоя:

### 1. Получи URL
Vercel даст тебе URL, например:
`pelican-floating.vercel.app`

### 2. Обнови API_URL
В файле `index.html` замени на свой URL бекенда:
```javascript
const API_URL = 'https://pelican-backend-xxx.amvera.io';
```

### 3. Настрой бота
1. Открой @BotFather
2. Выбери бота → Bot Settings → Menu Button → Configure
3. URL: `https://pelican-floating.vercel.app`
4. Название: `🦩 Записаться`

## Файлы:
- `index.html` — Mini App интерфейс
- `vercel.json` — конфигурация Vercel
