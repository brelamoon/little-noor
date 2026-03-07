# Как включить GitHub Pages (чтобы ссылки не давали 404)

1. Откройте репозиторий на GitHub: **Settings** (вкладка настроек).
2. В левом меню выберите **Pages**.
3. В блоке **Build and deployment**:
   - **Source**: выберите **Deploy from a branch** (не GitHub Actions).
   - **Branch**: выберите **gh-pages** (или main, если сайт в корне).
   - **Folder**: выберите **/ (root)**.
4. Нажмите **Save**.
5. Подождите 1–2 минуты. После деплоя ссылки заработают:
   - https://brelamoon.github.io/little-noor/privacy-policy/
   - https://brelamoon.github.io/little-noor/terms/
