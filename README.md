# ОГЭ 19 — Тренажёр (PWA)

## Как запустить локально
Открой `index.html` через любой локальный сервер (важно для Service Worker):
- VS Code → расширение Live Server
- или `python -m http.server`

## GitHub Pages
1. Залей репозиторий
2. Settings → Pages → Deploy from branch → `main` / root
3. Открой URL GitHub Pages
4. На телефоне: “Поделиться” → “На экран Домой” (iOS) или кнопка “Установить” (Android/Chrome)

## Если после обновления «сломалось»
Service Worker мог закэшировать старые файлы:
- Chrome DevTools → Application → Service Workers → Unregister
- Clear storage → Clear site data
