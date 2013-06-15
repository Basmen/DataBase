DataBase
========

Student's practice

Instructions
============

Скачиваем программу msysgit версии 1.8.3
Устанавливаем и запускаем консоль GitBash
Прописываем в консоли свои данные и настройки переносов строк:
 
git config --global user.name "ваше имя"
git config --global user.email "ваша почта"
git config --global core.autocrlf true
git config --global core.safecrlf true


Находим нужную папку для скачки репозитория командами как в терминале линукса (ls, cd, mkdir)
Чтобы наконец скачать содержимое репозитория, вбиваем в консоль следующее:

git clone https://github.com/Basmen/DataBase

Чтобы залить в репозиторий то, что вы сделали и сочли правильным, вводите следующее:

git add "название файла/папки"
git commit -m "Тут вы должны написать свой комментарий относительно того, что вы залили, это важно!"
git push

При запросе введите свои данные (login, pass)

Чтобы скачать изменения основного репозитория к себе, введите в консоль: 
 
git pull


Good Luck!
==========