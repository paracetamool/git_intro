echo '* Перед коммитом изменений нужно убедиться, что все файлы добавлены в индекс.' >> commmit_help.md
echo '* Посмотреть состояние индекса можно командой `git status.`' >> commmit_help.md
echo '* Используйте `git add filename` для добавления конкретного файла или `git add .` для добавления всех файлов' >> commmit_help.md
echo '* Чтобы одной командой добавить все изменённые файлы и сделать коммит, выполните `git commit -am "commit message"`' >> commmit_help.md
echo '* Новые файлы добавлены не будут' >> commmit_help.md
echo '- [Как сделать новый коммит](./commmit_help.md)' >> README.md


echo '* Список всех коммитов показывает команда `git log`' >> log_help.md
echo '- [Как просмотреть историю](./log_help.md)' >> README.md
echo >> reset_help.md - [Как просмотреть историю](./log_help.md)
- [Как вернуться к прошлой версии](./reset_help.md)
- [Ветвление](./branch_help.md)
- [Слияние веток](./merge_help.md)
