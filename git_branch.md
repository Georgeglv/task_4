[< к содержанию](./readme.md)

# Git Ветвление команды
**Ветвление** - создание различных версий репозиториев отличных друг от друга.

---
## Основные команды
`git branch` [наименование] - команда, которая создаёт новую ветку в репозитории;

`git checkout` [наименование] - команда, которая переключает вас на опр. ветку;

`git checkout - b` [наименование] - создаёт ветку и переключает на нее;

`git merge` [наименование] - вносит коммиты из другой ветки в текущую;

`git rebase` [наименование] - перебазирование, коммиты вашей ветки накладываются поверх текущего состояния ветки

## Git Правила для избежания конфликтов
1. Решайте задачи таким образом, чтобы разработчики не производили изменения в одних и тех же участках кода;
2. Работайте с актуальной версией кода;
3. Выработойте и соблюдайте требования к настройкам редактора кода, оформлению кода, используйте `editorconfig`;
4. Внесите локальные настройки проекта и другие локальные файлы в `editorconfig`;
5. Соблюдайте рекомедации к разделению сущностей в различных файлы;
6. Соблюдайте рекомендации к наименованию и иерархии. 
