# 🔧 Руководство по Git для студентов

## Основные команды

### Начало работы
```bash
# Клонировать репозиторий
git clone https://github.com/username/repository.git

# Проверить статус
git status

# Посмотреть историю
git log --oneline --graph

# Создать и перейти в ветку
git checkout -b feature/my-feature

# Переключиться между ветками
git checkout main
git checkout feature/my-feature

# Удалить ветку
git branch -d feature/my-feature

# Добавить все изменения
git add .

# Или конкретные файлы
git add file1.py file2.js

# Закоммитить
git commit -m "Описание изменений"

# Отправить на GitHub
git push origin feature/my-feature

# Получить изменения с GitHub
git pull origin main

# Если есть конфликты, разрешить их затем:
git add .
git commit -m "Resolve merge conflicts"

# Финальная подача проекта

# 1. Убедитесь что все закоммичено
git status

# 2. Обновитесь с main
git pull origin main

# 3. Создайте Pull Request на GitHub
# 4. Ссылка появится после push:
git push origin submission/your-project-name

# Получить комментарии менторов
git pull origin submission/your-project-name

# Внести исправления
git add .
git commit -m "fix: исправление по замечанию ментора"

# Отправить изменения
git push origin submission/your-project-name

