# Privacy Policy — FaceType (GitHub Pages)

В этом архиве находятся минимальные файлы для публикации Privacy Policy через GitHub Pages.

Файлы:
- `index.html` — готовая страница с текстом политики (на русском).
- `README.md` — этот файл с инструкцией.

## Быстрая инструкция — загрузка через веб-интерфейс GitHub

1. Создайте публичный репозиторий, например `facetype-privacy-policy`.
2. В репозитории нажмите **Add file → Upload files**.
3. Загрузите `index.html` из этого архива.
4. Commit changes.
5. В настройках репозитория (Settings → Pages) включите GitHub Pages:
   - Branch: `main`
   - Folder: `/ (root)`
6. Через минуту сайт будет доступен по адресу:
   `https://<ваш-логин>.github.io/facetype-privacy-policy/`

## Инструкция через Git (если удобно)

```bash
git clone https://github.com/<ваш-логин>/facetype-privacy-policy.git
cd facetype-privacy-policy
cp /path/to/index.html .
git add index.html
git commit -m "Add Privacy Policy"
git push origin main
```

Затем включите GitHub Pages в Settings → Pages, как указано выше.

## Проверка и вставка в Play Console

1. Откройте опубликованный URL в браузере и убедитесь, что страница открывается по HTTPS.
2. В Play Console вставьте URL в поле `Privacy policy` в разделе Store presence / Main store listing.
3. В разделе App content → Data safety укажите, что изображения обрабатываются локально и не передаются.

Если хотите, могу подготовить английскую версию страницы и добавить её в репозиторий.
