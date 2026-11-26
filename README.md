# Ресурспак Chorux

Независимое зеркало под управлением аккаунта luckyohmygod. GitLab и организация ChoruxNetwork не участвуют в раздаче.

## Скачать

[ChoruxResources.zip — последняя версия](https://github.com/luckyohmygod/chorux-resourcepack/releases/latest/download/ChoruxResources.zip)

## Для администраторов

1. Загрузите собранный ZIP в /opt/chorux-site/frontend/public/rp/ под временным именем.
2. По завершении переименуйте его в ChoruxResources.zip. В корне архива должен быть pack.mcmeta.
3. GitHub Actions автоматически проверяет прод примерно раз в 15 минут. Возможны задержки очереди GitHub.
4. При изменении SHA-256 появляется новый релиз. Предыдущий релиз остаётся доступным, если прод недоступен или новый ZIP повреждён.

[Статус и ручной запуск](https://github.com/luckyohmygod/chorux-resourcepack/actions/workflows/sync-pack.yml) — Run workflow на main.

Личные токены на компьютерах админов не нужны. Workflow использует временный токен GitHub только для публикации релиза в этом репозитории. Тестовый пак в rp/test хранится отдельно и сюда не копируется.
