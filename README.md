 # Docker
**Команди управління:**
```
docker builder
```  
*Керувати збірками*
``` 
docker buildx*
```    
*Docker Buildx*
```
docker config
```     
*Керувати конфігураціями Docker*
```
docker container
``` 
#### Керування контейнерами,
``` 
docker context 
```   
#### Керування контекстами,
``` 
docker dev* 
```
#### Середовища розробників Docker,
``` 
docker extension* 
```
#### Керує розширеннями Docker,
```  
docker image 
```
#### Керування зображеннями,
``` 
docker manifest 
```
#### Керування маніфестами зображень Docker і списками маніфестів,
``` 
docker network 
```
#### Керування мережами,
```  
docker node 
```
#### Керування вузлами Swarm ,
``` 
docker plugin 
```
#### Керування плагінами,
``` 
docker sbom*
```
#### Перегляд пакетних матеріалів програмного забезпечення (SBOM) для зображення (Anchore Inc., 0.6.0),
``` 
docker scan* 
```
#### Docker Scan (Docker Inc., v0.23.0),
``` 
docker secret  
```
#### Керування секретами Docker,
```
docker service
```
#### Керування послугами,
```
docker stack 
```
#### Керування стеками Docker,
``` 
docker swarm
```
#### Керувати Swarm ,
```
docker system
```
#### Управління системою Docker ,
```
docker trust 
```
#### Керуйте довірою до зображень Docker ,
``` 
docker volume 
``` 
#### Керування томами,
# Керуйте зображеннями,
### команди:
``` 
docker build 
```
#### Створення образу з Dockerfile,
``` 
docker history
```
#### Показати історію зображення,
``` 
docker import 
```
#### Імпортувати вміст із архіву, щоб створити образ файлової системи,
```  
docker inspect 
```
#### Відображення детальної інформації про одне або декілька зображень,
```
docker load 
```
#### Завантажити зображення з архіву tar або STDIN,
``` 
docker ls 
``` 
#### Список зображень,
```
docker prune 
```
#### Видалити невикористані зображення,
``` 
docker pull 
```
#### Витягнути образ або сховище з реєстру,
``` 
docker rm 
```
#### Видаліть одне або кілька зображень,
``` 
docker save 
```
#### Збереження одного або кількох зображень до архіву tar (за замовчуванням передається в STDOUT),
``` 
docker tag 
```
#### Створіть тег TARGET_IMAGE, який посилається на SOURCE_IMAGE,


# Використання: контейнер докерів COMMAND

## Керуйте контейнерами:

#### команди:
  ``` 
  docker attach
  ```  
  #### Прикріплення локальних стандартних потоків введення, виведення та помилок до запущеного контейнера,
   ```
   docker commit
   ```
   #### Створити нове зображення зі змін контейнера,
   ```
   docker cp
   ```
   #### Копіювати файли/папки між контейнером і локальною файловою системою,
   ```
   docker create
   ``` 
   #### Створити новий контейнер,
   ```
   docker diff
   ``` 
   #### Перевірити зміни файлів або каталогів у файловій системі контейнера,
   ```
  docker  exec
   ``` 
   #### Виконати команду у запущеному контейнері,
   ```
   docker export
   ``` 
   #### Експортувати файлову систему контейнера як архів tar,
   ```
   docker inspect 
   ```
   #### Відображення детальної інформації про один або декілька контейнерів,
   ```
  docker  kill
   ```
   #### Вбиває один або більше запущених контейнерів,
   ```
   docker logs
   ``` 
   #### Отримати журнали контейнера,
   ```
   docker ls
   ``` 
   #### Список контейнерів,
   ```
   docker pause
   ``` 
   #### Призупинити всі процеси в одному або кількох контейнерах,
   ```
   docker port 
   ```
   #### Показує відображення портів або певне відображення для контейнера,
   обрізати Видаліть усі закриті контейнери,
   ```
   docker rename
   ``` 
   #### Перейменувати контейнер,
   ```
   docker restart
   ``` 
   #### Перезапуск одного або кількох контейнерів,
   ```
   docker rm
   ``` 
   #### Вийміть один або кілька контейнерів,
   ```
   docker run
   ``` 
   #### Виконати команду в новому контейнері,
   ```
   docker start
   ``` 
   #### Запустити один або більше зупинених контейнерів
   ```
   docker stats
   ``` 
   #### Показує прямий потік статистики використання ресурсів контейнерів
   ```
   docker stop 
   ```
   #### Зупинити один або декілька запущених контейнерів
   ```
   docker top
   ``` 
   #### Відображення запущених процесів контейнера
   ```
  docker  unpause
   ``` 
   #### Розблокувати всі процеси в одному або кількох контейнерах
   ```
  docker  update
   ``` 
   #### Оновити конфігурацію одного або кількох контейнерів
   зачекайте блокувати, доки один або кілька контейнерів не зупиняться, а потім надрукуйте їхні коди виходу

#### Запустіть 'docker container COMMAND --help', щоб дізнатися більше про команду.
Vykorystannya: konteyner dokeriv COMMAND
