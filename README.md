# Основные команды Git
```
- git init  # Создать новый репозиторий
- git clone <URL>  # Склонировать существующий репозиторий
- git config --global user.name "Ваше Имя"  # Установить имя пользователя
- git config --global user.email "your@email.com"  # Установить email пользователя
- git config --list  # Посмотреть текущие настройки
- git status  # Проверить статус изменений
- git add <файл>  # Добавить конкретный файл в индекс
- git add .  # Добавить все файлы в индекс
- git commit -m "Описание коммита"  # Закоммитить изменения
- git remote add origin <URL>  # Добавить удалённый репозиторий
- git remote -v  # Посмотреть список удалённых репозиториев
- git push origin <ветка>  # Отправить изменения в удалённый репозиторий
```
## Настройка SSH для работы с GitHub
- ``` 
  ssh-keygen -t rsa -b 4096 -C "your@email.com"  # Создать SSH-ключ
- ```
  cat ~/.ssh/id_rsa.pub  # Посмотреть публичный ключ
