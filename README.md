# STYLE OBJECT — Setup Instructions

## Что в этом архиве

```
styleobject-site/
├── index.html              ← главная страница сайта
├── admin/
│   ├── index.html          ← админ-панель (вход через /admin/)
│   └── config.yml          ← настройки полей в админке
├── images/                 ← сюда загружать изображения
└── looks/                  ← страницы образов (создаются через CMS)
```

## Как запустить — 5 шагов (всё бесплатно)

### Шаг 1 — Регистрация на GitHub (5 мин)
1. Идёте на github.com → Sign up
2. Создаёте репозиторий "styleobject-site"
3. Загружаете все файлы из этого архива

### Шаг 2 — Регистрация на Netlify (5 мин)
1. Идёте на netlify.com → Sign up через GitHub
2. New site from Git → выбираете ваш репозиторий styleobject-site
3. Build command: оставить пустым
4. Publish directory: оставить пустым (корневая папка)
5. Deploy site

### Шаг 3 — Включить Identity для логина в админку (3 мин)
1. В Netlify → Site settings → Identity → Enable Identity
2. Registration → Invite only (только вы можете войти)
3. Services → Git Gateway → Enable Git Gateway
4. Identity → Invite users → ваш email → отправить инвайт
5. Получаете email от Netlify → создаёте пароль

### Шаг 4 — Подключить домен (10 мин)
1. Покупаете styleobject.com на Namecheap (~$12/год)
2. Netlify → Domain settings → Add custom domain
3. В Namecheap → DNS settings → меняете на Netlify nameservers
4. Ждёте 1-24 часа пока обновится DNS
5. SSL включается автоматически

### Шаг 5 — Войти в админку
1. Открываете styleobject.com/admin/
2. Логин email + пароль из шага 3
3. Готово — можете добавлять Looks через интерфейс

## Что делать каждый раз когда добавляете новый образ

1. Заходите на styleobject.com/admin/
2. Жмёте "Looks" → "New Look"
3. Заполняете форму:
   - Title, Slug, Date
   - Hero Image (загружаете коллаж)
   - Story (описание лука)
   - Products (добавляете каждый продукт + Amazon ссылку)
   - Styling Tips (3 совета)
4. Жмёте Publish
5. Через 30-60 секунд лук появляется на сайте

## Поддержка

Если что-то не работает — скажите Claude в чате, разберёмся.
