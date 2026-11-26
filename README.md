# Our Movie Gallery 💗

Сайт для нашего киноклуба: списки фильмов, блокнот с фото и гифками, лента активности и фоновая музыка.

## Публикация на GitHub Pages
1. Загрузите в репозиторий `index.html`, `.nojekyll` и `README.md` (в корень).
2. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
3. Сайт откроется по адресу `https://<логин>.github.io/<репозиторий>/`.

## Общий список
Данные синхронизируются через Supabase (таблица `kino_state`, bucket `photos`). Ключ в начале скрипта публичный, доступ задают правила RLS.
