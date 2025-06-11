
# 🚀 Домашнее задание к занятию "`8.03. GitLab CI/CD`"  
**Автор:** _Расулов Магомед_

---

## 📋 Инструкция по выполнению

1. Сделайте `fork` данного репозитория.
2. Клонируйте его себе на ПК:
   ```bash
   git clone https://github.com/lim0nad-tv/8.03hw.git
   cd 8.03hw
   ```
3. Выполните домашнее задание:
   - Укажите вверху ФИО и тему
   - Используйте Markdown для форматирования
4. После завершения:
   ```bash
   git add .
   git commit -m "Выполнено домашнее задание"
   git push origin main
   ```
5. Прикрепите ссылку на файл в GitHub в Личном кабинете.

---

## ✅ Задание 1

**Создание репозитория и первичный коммит**

1. ✅ Аккаунт на GitHub: [lim0nad-tv](https://github.com/lim0nad-tv)
2. ✅ Репозиторий: [lim0nad-tv/8.03hw](https://github.com/lim0nad-tv/8.03hw)
3. ✅ Конфигурация Git:
   ```bash
   git config --global user.name "Расулов Магомед"
   git config --global user.email "rasulov999@yandex.ru"
   ```
4. ✅ Проверка статуса:
   ```
   On branch main
   nothing to commit, working tree clean
   ```
5. ✅ Добавил изменения:
   ```bash
   git add README.md
   git commit -m "First commit"
   git push origin main
   ```
6. ✅ Ссылка на коммит:  
   🔗 [f902269](https://github.com/netology-code/sys-pattern-homework/commit/f902269efc4ab34226ef8da76d008e7b74286f43)

---

## ✅ Задание 2

**Добавление .gitignore**

1. Создание и редактирование:
   ```bash
   touch .gitignore
   echo "*.pyc\ncache/" > .gitignore
   ```
2. Коммит и пуш:
   ```bash
   git add .gitignore
   git commit -m "Добавлен .gitignore для игнорирования *.pyc и папки cache"
   git push origin main
   ```
3. ✅ Ссылка на коммит:  
   🔗 [b1e97d9f](https://github.com/netology-code/sys-pattern-homework/commit/1e97d9fd374d5ad70e66593aeacfd725ed9c7c0f)

---

## ✅ Задание 3

**Работа с ветками и объединение**

1. Создание ветки `dev`:
   ```bash
   git checkout -b dev
   ```
2. Работа с `test.sh`:
   ```bash
   echo '#!/bin/bash' > test.sh
   echo 'echo "Привет из ветки dev!"' >> test.sh
   chmod +x test.sh
   git add test.sh
   git commit -m "Добавлен файл test.sh с начальным содержимым"
   git push -u origin dev
   ```
3. Дополнение:
   ```bash
   echo 'echo "Ветка dev развивается!"' >> test.sh
   git add test.sh
   git commit -m "Обновлено содержимое test.sh"
   git push origin dev
   ```
4. Переход в `main` и создание `main.sh`:
   ```bash
   git checkout main
   echo '#!/bin/bash' > main.sh
   echo 'echo "Привет из ветки main!"' >> main.sh
   chmod +x main.sh
   git add main.sh
   git commit -m "Добавлен файл main.sh"
   git push origin main
   ```
5. Слияние веток:
   ```bash
   git merge --no-ff dev
   git push origin main
   ```

🔗 **Граф коммитов**:  
[https://github.com/lim0nad-tv/8.03hw/network](https://github.com/lim0nad-tv/8.03hw/network)

---

---

## 📷 Скриншоты

При необходимости вставьте сюда скриншоты с помощью:

```md
![Описание](ссылка-на-изображение)
```

---

