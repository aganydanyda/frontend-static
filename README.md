
# Простое фронтенд-приложение (сборка статики)

Минимальный фронтенд-проект на Node.js, который собирается в статику и отображает текст:

> **Виртуализация и контейнеризация**

## Требования

- Node.js 18+ (рекомендуется 20+)
- npm 9+

## Установка

```bash
npm install
````

## Запуск в режиме разработки

```bash
npm run dev
```

Открой в браузере: `http://localhost:5173`

## Сборка статики

```bash
npm run build
```

Результат сборки появится в папке `dist/`.

## Локальная проверка собранной статики

```bash
npm run preview
```

Открой в браузере: `http://localhost:4173`

## Структура проекта

* `index.html` — точка входа
* `src/main.js` — логика приложения
* `src/style.css` — стили
* `dist/` — результат сборки (генерируется)
# frontend-static

  ## Docker

### Сборка образа

```bash
docker build -t daniil_v/frontend:1.0.0 -t daniil_v/frontend:latest .
```

### Запуск контейнера

```bash
docker run --rm -p 8080:80 daniil_v/frontend:1.0.0
```

### Результаты

#### Успешная сборка
<img width="1082" height="578" alt="photo_2026-05-25_07-24-34" src="https://github.com/user-attachments/assets/8c45c4fb-cdc7-414a-835b-a29b3377afb8" />

#### Приложение в браузере
<img width="1280" height="687" alt="photo_2026-05-25_07-25-06" src="https://github.com/user-attachments/assets/41a07e20-be7a-438b-873c-a2e44d31e69b" />

#### Размер образа
<img width="1099" height="134" alt="photo_2026-05-25_07-25-46" src="https://github.com/user-attachments/assets/452fc479-b12b-43cb-ad4a-39affe0d90e2" />
