# Практична робота №3

## Варіант
6

Гілка: `lab3/variant-6-Merkova`

Репозиторій: https://github.com/el1eonorrA/git-lab-3

## 1. stash list рядок із вашим -m
`чернетка статусу v6`

## 2. cherry-pick два хеші і чому вони різні
Коміт було перенесено за допомогою `cherry-pick`.

Хеші відрізняються, оскільки Git створив новий коміт в іншій гілці.

## 3. reflog два рядки до і після amend
До amend: `0c6efb0`

Після amend: `0c6efb0` (перевірити точні хеші за допомогою `git reflog`).

## 4. revert log --oneline, видно обидва коміти
`44137b4 Зіпсувати рядок`

`fc4f7fd Revert "Зіпсувати рядок"`

## 5. тег фрагмент git show: tag, Tagger, повідомлення
Тег: `v0.1-Merkova`

Повідомлення: `Перший зріз варіанта 6`

## 6. rebase -i pick / squash і підсумкове повідомлення
`pick 35d953a WIP: чернетка`

`squash 0bcd4a7 fix typo`

Підсумкове повідомлення: `Оновити статус роботи`

## 7. blame один рядок
`0c6efb0 Підготовка практичної роботи №3`

## 8. fork origin, upstream, куди push і куди PR
`origin` — мій власний репозиторій (fork).

`upstream` — оригінальний репозиторій викладача.

Push виконується в `origin`, Pull Request створюється з моєї гілки в `upstream/main`.