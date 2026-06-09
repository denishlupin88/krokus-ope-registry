# Реестр обращений ОПЭ Крокус

Публичная страница для просмотра реестра обращений на этапе ОПЭ.

**Ссылка:** https://denishlupin88.github.io/krokus-ope-registry/

Обновлено: 2026-06-09

## Для команды БИТ

Исходники и редактирование — в основном репозитории проекта КУРСОР.
Публикация:

Локально: правки в реестре → «Сохранить» → `publish_github_pages.bat` → push.

```bash
cd projects/Крокус/1С/ОПЭ_и_обучение
python publish_github_pages.py
cd ../../../../krokus-ope-registry
git add -A && git commit -m "Обновление реестра 2026-06-09" && git push
```

GitHub Pages: Settings → Pages → Branch `main` / folder `/ (root)`.
