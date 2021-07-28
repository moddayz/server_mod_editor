Place the ServerListModSIB.pbo file in the server files
Let's move the ServerListMod folder to the server root

the ServerListMod folder contains files that are connected via ServerListModSIB.pbo
1_Core_modded.txt
2_GameLib_modded.txt
3_Game_modded.txt
4_World_modded.txt
5_Mission_modded.txt

and now you can simply insert text into these files to connect server-side mods or edit the code without using pbo

I also as an example in 3_Game_modded.txt

//#include "$CurrentDir:\\ServerListMod\\3\\stamina.txt" 
posted a ready-made example of editing stamina

the ServerListMod file ServerListMod\3\stamina.txt

to enable remove the // sign

do not forget that if you want to edit some kind of code, for example a stamina, then it belongs to 3_Game, so you need to connect it to 3_Game_modded.txt

if you want to edit for example the player's spawn then you need 5_Mission_modded.txt


>>>>>>>>>>>>>>>>>>>>>the file is only for server folders, it cannot be put in the workshop if put I will file DMCA ^ _ ^



Помещяем файл ServerListModSIB.pbo в серверные файлы
Помешяем папку ServerListMod в корень сервера

в папке ServerListMod содержится файлы которые через  ServerListModSIB.pbo подключаются 
1_Core_modded.txt
2_GameLib_modded.txt
3_Game_modded.txt
4_World_modded.txt
5_Mission_modded.txt

и теперь можно простым вставлянием текст в эти файлы подключать серверный моды или редактировать код без использования pbo

Так же я как пример в 3_Game_modded.txt

//#include "$CurrentDir:\\ServerListMod\\3\\stamina.txt" 
поместил готовый пример редактирования стамины

сам файл ServerListMod\3\stamina.txt

чтоб включить уберите // знак

не забывайте что если вы хотите отредактровать какой то код например стамину, то она относиться к 3_Game по этому её нужно подключать в 3_Game_modded.txt

если вы хотите отредактировать например спавн игрока то вам нужен 5_Mission_modded.txt


>>>>>>>>>>>>>>>>>>>>>файл только для папок сервера, его нельзя поместить в мастерскую, если поместите я подам DMCA ^ _ ^
