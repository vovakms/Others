Новый вид криптовалюты <p>

<center><h3>IPCOIN</h3> </center>
  
miningIPcoin - является фермой добычи IPCOIN-ов 


IPCOIN - пачка ip-адресов для "ИнтерКат"

<h3>Краткое описание алгоритма. </h3> 

Сканируем Интернет ip-адреса , одна пачка это 254 адреса .

Затем полученные IPCOIN-ы используем для входа на "ИнтерКат".

Подключаемся к "ИнтерКат", на "ИнтерКат" ищем нужную информацию.


<h3>Реализация на bash.</h3>

В папке bash собран проект на bash
Разархивировать и запустить maining.sh, этот скрипт запустит 254 скрипта для генерации ipcoin-ов,
складываться они будут в папку ipcoins.
  В среднем добыча одного IPCOIN занимает от одной до двух минут.

<h3>Реализация на Python.</h3>

Кратко 
Перебираем ip-адреса, 
по каждому ip-шнику делаем запрос резултат записываем в файл,
формат файла 
      название состоит из 3-х октетов ip-адреса, 
      ip-адрес ПолученныйОтвет
если от ip-шника , на который отправили запрос , тишина , то в файл ни чего не пишется.
