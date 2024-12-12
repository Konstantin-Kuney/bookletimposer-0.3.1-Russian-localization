## Русская локализация для bookletimposer 0.3.1
-----------------------------------------------
bookletimposer 0.3.1 Russian localization

## О программе:
---------------

Bookletimposer - это утилита для выполнения некоторых базовых операций верстки PDF-документов, специально разработанная для работы с буклетами.

Bookletimposer реализован в виде командной строки и интерфейса GTK+ для pdfimposer, многоразового модуля python, построенного на основе pyPdf2.

Bookletimposer является свободной программой, выпущенной под лицензией GNU General Public License, либо версии 3, либо (по вашему выбору) любой более поздней версии.

Программа присутствует в стандартных репозиториях [Debian](https://packages.debian.org/search?keywords=bookletimposer). Установка:
```
$ sudo apt-get install bookletimposer
```

## Содержимое:
--------------

* bookletimposer.po - файл переводов для bookletimposer 0.3.1 (текстовый)
* bookletimposer.mo - файл переводов для bookletimposer 0.3.1 (скомпилированный)
* install.sh - скрипт для установки русификатора bookletimposer 0.3.1
* uninstall.sh - скрипт для удаления русификатора bookletimposer 0.3.1
* README.md - Данный файл описания

## Установка/Удаление русификатора:
-----------------------------------

### 1.С помощью скриптов:

Делаем скрипты исполняемыми:
```
$ sudo chmod +x *.sh
```

Установка:
```
$ sudo sh ./install.sh
```

Удаление:
```
$ sudo sh ./uninstall.sh
```

### 2.Вручную:

Установка:

Создаем папку для русской локализации, если она отсутствует:
```
$ sudo mkdir -p /usr/share/locale/ru/LC_MESSAGES/
```

Копируем в нее скомпилированный файл русской локализации:
```
$ sudo cp -f bookletimposer.mo /usr/share/locale/ru/LC_MESSAGES/bookletimposer.mo
```

Удаление:

Удаляем файл русской локализации:
```
$ sudo rm -f /usr/share/locale/ru/LC_MESSAGES/bookletimposer.mo
```

## Дополнительная информация:
-----------------------------

[Официальный сайт программы bookletimposer](http://kjo.herbesfolles.org/bookletimposer/)

[Git репозиторий программы bookletimposer](https://git.codecoop.org/kjo/bookletimposer)


