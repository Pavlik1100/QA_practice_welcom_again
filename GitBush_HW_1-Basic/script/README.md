## *2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

3) Зайти в папку `cd fold`
4) Создать 3 папки `mkdir folder_1 folder_2 folder_3` или `mkdir {0..2}`  
5) Зайти в любоую папку `cd folder_2`  
6) Создать 5 файлов (3 txt, 2 json) `touch 1.txt 2.txt 3.txt 4.json 5.json`  
7) Создать 3 папки `mkdir dir_1 dir_2 dir_3`  
8) Вывести список содержимого папки `la -la`  
13) Переместить любые 2 файла, которые вы создали, в любую другую папку `mv 4.json 5.json dir_1/` 
   
запуск файла "script" с готовым скриптом командой `bush script.sc`
```sh
#!/bin/bash  
mkdir fold
cd fold   
mkdir {00..02}  
cd 00  
touch 01.txt 02.txt 03.txt 04.json 05.json  
mkdir fold1 fold2 fold3  
ls -la  
mv -v 04.json 05.json fold3  
```
## [Скриптом для задания *2](https://github.com/Pavlik1100/QA_practice_welcom_again/blob/Linux_terminal_GitBash_comands/GitBush_HW_1-Basic/script/script.sc)
## 🚏 Navigate:
[![Flutter](https://img.shields.io/badge/🏠-GITBASH_BRANCH-00A98F)](https://github.com/Pavlik1100/QA_practice_welcom_again/tree/Linux_terminal_GitBash_comands)  [![Flutter](https://img.shields.io/badge/🏠-QA_PRACTICE_BANCH-orange)](https://github.com/Pavlik1100/QA_practice_welcom_again/tree/main)
## 📫 How to reach me:  
[![Flutter](https://img.shields.io/badge/-Pavel_Simonov-000000?style=social&logo=LinkedIn)](https://www.linkedin.com/in/pavel-simonov-7a8b1119a/)  [![Flutter](https://img.shields.io/badge/-Pavel_Simonov-000000?style=social&logo=Telegram)](https://t.me/NuiSaiman)  [![Flutter](https://img.shields.io/badge/-simonovpavlik@gmail.com-000000?style=social&logo=Gmail)](mailto:simonovpavlik@gmail.com)
