### Отчет по первой лабораторной работе  

### Задание1  
Команда:  
ls  
cat diary.txt  
Получили: ZGFpejZhaFJhZVNhZXhhaWJ1YWYK  
 
### Задание2  
Команда:  
ls  
cat *.txt  
for i in /home/suzen/*; do echo $i; tail $i; echo ' '; done;  
Получили: dGhlaWxpM2FoWm9odGFpM2VldzMK  
“for i in /home/suzen/*; do echo $i; tail $i; echo ' '; done;” – выводит содержимое файло в папке  
 
### Задание3  
Команда: while IFS= read -r line; do echo $line; done <-diary.txt-  
Получили: Y284ZWlxdXVlMmllTDNpZXBoNWUK  
«while IFS= read -r line; do echo $line; done <-diary.txt-» - команда read читает файл построчно, присваивая каждую строку переменной line. Как только все строки обработаны, цикл while прекратится. Внутренний разделитель полей (IFS) устанавливается в пустую строку, чтобы сохранить начальные и конечные пробелы, что является поведением команды по умолчанию read.  
 
### Задание14
Команда:  
исследования места с помощью lsи cd  
Получили:d2FodmFoMWFlV2FpYmVlaG9vMmIK  
 
### Задание15  
Команда:pwd  
Получили:TWVlMXdvaDJ6YWVoZWoyamllNm8K  
Pwd - указывает полный путь к текущему каталогу  
 
### Задание16  
Команда:id  
Получили:ZXVsb29naG91MFBob2g4T2hkYWkK  
Id - Вывод идентификатора пользователя и группы.  
 
### Задание17  
Команда:ls -a  
Получили:bmVlNm1lMEhhaU11M2thaGVpNmEK  
ls -a – флаг -aуказывает показывать все файлы  
 
### Задание18  
Команда:    
используем команду man(manual) diary и получаем руководство по diary в flag пароль  
Получили:Y2hpZWNoM2VpRzRJZWtlaXNlbGUK  
### Задание19  
Команда:  
/home/suzen # mkdir -p Documents/projects/lab19/using/simple/bash/commands  
/home/suzen # cd Documents/projects/lab19/using/simple/bash/commands  
/home/suzen/Documents/projects/lab19/using/simple/bash/commands # ls -a  
Получили:V2VpMGNvaHNoZWlxdWE0YWhnaG8K    
### Задание20  
Команда:  
cd .  
rm -r john - удалил всю папку  
mkdir john - создал папку с тем же названием :)))  
Получили:YW1pZWhpaW0yb2h5NW9vRjZlaXcK  
### Задание21  
Команда:  
1)rm [0-9].txt  
2)rm [a-z].png  
3)rm test-*.log  
ls  
Получили:aWU0b29XdWxlaXBodXBpZWZveW8K  
### Задание22  
Команда:  
i=1; while [ $i -lt 999 ];do touch $i.txt;let i++;done;  
touch - создает файл, let i++ увеличивает счетчик на единицу. -lt == <;  
Получили:aTc1Z3g3aVNvYk9CZmd6ZWF5TXh4WFBXNUJ3UG94aXBkMjYvekl0QWRWbz0KdXI2dXNhaDNvaFQxaWV2MGNobzgK  
  
### Задание23  
Команда:  
cd destination  
for i in /home/suzen/destination/*; do mv $i $i.back.log;done;  
cd ..  
cd source/  
mv * ../destinaton/  
cd ..  
ls  
Получили:dmVlc2VpQzVBb2dlaXI1cmVlM2YK  
  
### Задание24  
Команда:  
mkdir Music  
cd Desktop  
cp -r music/* ../Music  
ls  
Получили:YWVnaG9venVvejd2b292OHNvaEwK  
### Задание25  
Команда:  
cat file  
Получили:dGhlZThhcXVpZUNpTGFpdGhlZTkK  
   
### Задание26  
Команда:  
lessflag - открываетфайл  
/FLAG – ищет  
Получили: WWVpc2gxYWlndXVrZWl5ZWloaWUK  
   
### Задание27    
Команда: tail -fdiary   
Получили: dGVlMUtleThhUXVvaDFnZTFiaWkK  
Tail -f – это команда выдачи хвостовой части файла. Флаг -f добавляет возможность не завершаться по достижении конца вывода, а ожидать появления новых данных  
 
### Задание28  
Команда:   
cat<<EOF>diary  
<ввод текста без последней строки>  
EOF  
echo -n "11:32pm: Нассал под кресло. Еееееееее!" >>diary – для решени проблем непечатных знаков  
Получили: ZWV4b1g1WnVkMm9oZnVjYWhkdTMK  
cat<<EOF>diary - это команда, позволяющая ввести сразу многострочный текст в документ   
   
### Задание29  
Команда: просмотр старых команд  
Получили: dmFvbmcwcGFlMWlodUJvaFppZWQK  
 



