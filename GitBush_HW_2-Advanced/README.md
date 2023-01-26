Termial. HW_2
1. Сделать папку dir_1 `mkdir dir_1`
2. Зайти в папку dir_1 `cd dir_1`
3. Создать папку inner_dir_1 `mkdir inner_dir_1`
4. Посмотреть где ты находишься `pwd`
5. Находясь в папке dir_1 создать пустой текстовый файл tf_1.txt `touch tf_1.txt`
6. Находясь в папке dir_1 через команду cat создать текстовый файл tf_2.txt со следующими строками:
- the first 1
- the second 2
- the third 3
```sh
 cat>tf_2.txt
 the first 1
 the second 2
 the third 3
```
 7. Зайти в папку inner_dir_1 `cd inner_dir_1`
 8. Через cat сделать текстовый файл tf_3.txt  c любыми строками
```sh
 cat>tf_3.txt
 pervaya stroka
 vtoraya stroka
 tretya stroka
```
 9. Через cat добавить в текстовый файл tf_3.txt строку “the second 2”
 ```sh
 cat>>tf_3.txt
 the second 2
 ```
 10. Через cat добавить в текстовый файл tf_3.txt строку “the sec 2”
 ```sh
 cat>>tf_3.txt
 the sec 2
 ```
 11. Через cat добавить в текстовый файл tf_2.txt строку “the sec 3”
 ```sh
 cat>>tf_2.txt
 the sec 3
 ```
 12. Через cat добавить в текстовый файл tf_3.txt строку “the SeCoNd 2”
 ```sh
 cat>>tf_3.txt
 the SeCoNd 2
 ```
 13. Через cat добавить в текстовый файл tf_2.txt строку “the seConD 2”
 ```sh
 cat>>tf_2.txt
 the seConD 2
 ```
 14. Сделать текстовый файл tf_4.txt в котором будет 15 строк.
 ```sh
 cat>tf_4.txt
 string 1
 string 2
 string 3
 string 4
 string 5
 string 6
 string 7
 string 8
 string 9
 string 10
 string 11
 string 12
 string 13
 string 14
 string 15
 ```
 15. Сделать текстовый файл tF_5.txt в котором будет 13 строк.
  ```sh
 cat>tF_5.txt
 string 1
 string 2
 string 3
 string 4
 string 5
 string 6
 string 7
 string 8
 string 9
 string 10
 string 11
 string 12
 string 13
 ```
 16. Вывести список всех файлов в папке.
 ```sh
 ls -la
 ```
 17. Выйти из папки inner_dir_1
 ```sh
 cd ..
 ```
 18. Вывести содержимое файла tf_3.txt в терминал.
 ```sh
 cat inner_dir_1/tf_3.txt
 ``` 
 19. Найти путь к файлу tf_4.txt
 ```sh
 find . -name 'tf_4.txt'
 ```
 20. Отчистить файл tf_4.txt от содержимого без удаления самого файла.
 ```sh
 cat>inner_dir_1/tf_4.txt
 ```
 21. Найти путь к файлам у которых есть  “tf” в названии.
 ```sh
 find . -name 'tf*.*'
 ```
 22. Найти путь к файлам у которых есть  “tf” в названии и буквы в любом регистре.
 ```sh
 find . -iname 'tf*.*'
 ```
 23. Найти строки в файлах где есть комбинация букв “sec” в текущей папке
 ```sh
 grep -r sec .
 ```
 24. Найти строки в файлах где есть комбинация букв “sec” в любом регистре в текущей папке
  ```sh
 grep -ir sec .
 ```
 25. Найти строки в файлах где есть только комбинация букв “sec” в текущей папке
 ```sh
 grep -rw sec
 ```
 26. Найти строки в файлах где есть только комбинация букв “sec” в любом регистре в текущей папке
 ```sh
 grep -rwi sec
 ```
 27. Найти строки в файлах где есть комбинация букв “second” в текущей папке
 ```sh
 grep -r second
 ```
 28. Найти строки в файлах где есть комбинация букв “second” в любом регистре в текущей папке
 ```sh
 grep -ri second
 ```
 29. Найти строки в файлах где есть комбинация букв “second” во всех папках ниже уровнем
 ```sh
 grep -r second ./inner_dir_1
 ```
 30. Найти только путь и название файла в строках которых есть комбинация букв “second” в текущей папке
 ```sh
 grep -lr second
 ```
 31. Найти все строки во всех файлах где нет комбинации “second”
 ```sh
 grep -rv second
 ```
 32. Найти только название и путь к файлам где нет комбинации “second”
 ```sh
 grep -rvl second
 ```
 33. Вывести в терминал 4 последних строк любого текстового файла
 ```sh
 tail -n 4 tf_2.txt
 ```
 34. Вывести в терминал 4 первые строки любого текстового файла.
 ```sh
 head -n 4 tf_2.txt
 ```
 35. Команда в одну строку. Создать папку и создать текстовый файл с содержиммым.
 ```sh
 mkdir te | cat>te/te.txt |"da">>te.txt
 ```
 36. Команда в одну строку. Переместить в любую одну папку текстовые файлы у которых в содержимом есть слово “sec”
 
 37. Команда в одну строку. Скопировать в любую одну папку текстовые файлы у которых в содержимом есть слово “sec”
 38. Команда в одну строку. Найти все строки c “sec” во всех текстовых файлах, скопировать и вставить эти строки в один новый созданный текстовый файл.
 39. Команда в одну строку. Удалить текстовые файлы у которых в содержимом есть слово “sec”
 40. Просто вывести в терминал строку “Good job!!”
## 🚏 Navigate:
[![Flutter](https://img.shields.io/badge/🏠-GITBASH_BRANCH-00A98F)](https://github.com/Pavlik1100/QA_practice_welcom_again/tree/Linux_terminal_GitBash_comands)  [![Flutter](https://img.shields.io/badge/🏠-QA_PRACTICE_BANCH-orange)](https://github.com/Pavlik1100/QA_practice_welcom_again/tree/main)
## 📫 How to reach me:  
[![Flutter](https://img.shields.io/badge/-Pavel_Simonov-000000?style=social&logo=LinkedIn)](https://www.linkedin.com/in/pavel-simonov-7a8b1119a/)  [![Flutter](https://img.shields.io/badge/-Pavel_Simonov-000000?style=social&logo=Telegram)](https://t.me/NuiSaiman)  [![Flutter](https://img.shields.io/badge/-simonovpavlik@gmail.com-000000?style=social&logo=Gmail)](mailto:simonovpavlik@gmail.com)
