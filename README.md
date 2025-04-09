**.gitignore** - Этот файл указывает Git, какие файлы и папки не нужно отслеживать и добавлять в репозиторий.

**README.md** - Это документация проекта в формате Markdown.

main.py - Файл с настройками проекта (API-ключи, параметры подключения к БД, пути и т. д.).

config.py - Файл с настройками проекта (API-ключи, параметры подключения к БД, пути и т. д.).

config_template.py - Шаблон конфига, который показывает, какие настройки нужны для работы проекта. Нужен чтобы другие разработчики (или сам автор) могли скопировать его в config.py и заполнить своими значениями.

config.py не коммитят в Git, чтобы не светить секретные данные.

Он делает две вещи:
1. Скачивает изменения из удалённого репозитория (например, с GitHub, GitLab или другого сервера).
2. Обновляет текущую локальную ветку, применяя эти изменения.
