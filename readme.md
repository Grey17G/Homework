**Инструкция по применению git**

1. Открыла VScode

2. Создала папку homework_seminar на компьютере, сохранила

3. Кнопкой Open Folder открыла эту папку в VS code

4. Создала файл readme.md

5. Открыла терминал во вкладке View

6. Инициализировала репозиторий (git init)

7. Индексировала репозиторий (git add .)

8. Проверила состояние репозитория (git status)

9. Сделала первый коммит (git commit -m"Initial_commit")

10. Проверила состояние репозитория (git status)

11. Сделала коммит (git commit =m"Создали файл readme.md")

12. Проверила состояние репозитория (git status)

13. Внесла текст в файл readme.md

14. Сохранила (Ctrl+S)

15. Индексировала файл (git add readme.md)

16. Убедилась в изменениях (git status)

17. Закоммитила изменения (git commit -m"Добавила инструкцию по использованию git")

18. Проверила состояние репозитория (git status)

# Инструкция по работе с удаленными репозиториями

## Как поместить свой репозиторий в GitHub?

1. Создать папку в локальной машине, открыть ее в VS code.

2. В папке создать файл, сделать необходимые изменения, закоммитить.

3. Создать аккаунт в GitHub

4. В VS code набрать команду git push для того, что поместить созданный локальный репозиторий в аккаунте GitHub. При первом push потребуется авторизация.

5. Командой git pull можно выкачать актуальное состояние из удаленного репозитория в локальную машину.

## Как работать с "чужим" репозиторием в GitHub?

1. С помощью кнопки fork в свой аккаунт на GitHub копируем репозиторий с аккаунта , который нам интересен.

2. Создаем локальный репозиторий командой git clone.

3. Командой cd "название папки" входим внутрь клонированного репозитория.

4. Создаем ветку, делаем в ней изменения, которые хотим предложить владельцу репозитория, делаем коммиты.

5. Направляем изменения в свой аккаунт на GitHub (git push).

6. Кнопка pull pequest позволяет отправить наши изменения.