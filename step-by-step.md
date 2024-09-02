# 1 Создать локальный репозиторий
```bash
git init
```

# 2 Создать удаленный репозиторий на GitHub
```bash
gh auth login

gh repo create <my-project> --private
```

# 3 Связать локальный и удаленный репозитории
```bash
git remote add origin https://github.com/ValyaSHmelev/<my-project>.git
```

# 4 Первоначальная настройка и отправка изменений

```bash
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

Репозитории успешно созданы, дальше можно просто использовать команды *git push* и *git pull*