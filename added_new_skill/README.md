# Составные команды Git и запись логов
## 16) Сохранить поток логов за указанную минуту в отдельный файл
```sh
tail -f anything_1.txt | grep --line-buffered 16.08 >> test_log1.txt
```
## 17) Сохранить поток логов за указанную минуту в отдельный файл транслируя ход логов в gitbash
```sh
tail -f anything_1.txt | grep --line-buffered 16.13 >> test_log2.txt | tail -f test_log2.txt
```
[Директория с логами](https://github.com/Pavlik1100/GitBash-Practice_Linux_Terminal_commands/tree/main/added_new_skill)

###

1) Создать три папки 
```sh
mkdir l1 l2 l3
```
2) Войти в одну из созданных папок
```sh
cd l1
```
3) Создать файл с записями в нем
```sh
cat > f1.txt
qwerty1
qwerty2
qwerty3
qwerty4
```
4) Перезаписать созданный выше файл его повторным созданием с записями
```sh
cat > f1.txt
zxcvb1
zxcvb2
zxcvb3
zxcvb4
```
5) Добавить заиси в файл
```sh
cat >> f1.txt
zxcvb5
zxcvb6
```
6) Подняться в каталоге на уровень выше
```sh
cd ..
```
7) Вывести содержиое папки l1
```sh
ls l1
```
8) Вывести содержиое файоа f1.txt
```sh
cat f1.txt
```
9) Вывести содержиое файоа f1.txt пронумеровав присутствующие не пустые строки
```sh
cat -b f1.txt
```
10) Вывести содержиое файоа f1.txt пронумеровав все строки
```sh
cat -b f1.txt
```
11) Вывести два файла
```sh
cat f1.txt f1.txt
```
12) Найти файл в конкретной папке
```sh
find \l1 -name *.txt
```
13) Найти по содержимому в файле
```sh
grep 3 f1.txt
```
14) Вывести последние три строки файла
```sh
tail -n 3 f1.txt
```
## 🚏 Navigate:
[![Flutter](https://img.shields.io/badge/🏠-GITBASH_BRANCH-00A98F)](https://github.com/Pavlik1100/QA_Practice/tree/GitBash)  [![Flutter](https://img.shields.io/badge/🏠-QA_PRACTICE_BANCH-orange)](https://github.com/Pavlik1100/QA_Practice/tree/main)
## 📫 How to reach me:  
[![Flutter](https://img.shields.io/badge/-Pavel_Simonov-000000?style=social&logo=LinkedIn)](https://www.linkedin.com/in/pavel-simonov-7a8b1119a/)  [![Flutter](https://img.shields.io/badge/-Pavel_Simonov-000000?style=social&logo=Telegram)](https://t.me/NuiSaiman)  [![Flutter](https://img.shields.io/badge/-simonovpavlik@gmail.com-000000?style=social&logo=Gmail)](mailto:simonovpavlik@gmail.com)
