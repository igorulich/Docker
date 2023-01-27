# Docker
# Команди управління:
```builder```  
#### Керувати збірками,
``` buildx*```    
#### Docker Buildx,
```config```     
#### Керувати конфігураціями Docker,
```container ``` 
#### Керування контейнерами,
``` context ```   
#### Керування контекстами,
``` dev* ```
#### Середовища розробників Docker,
``` extension* ```
#### Керує розширеннями Docker,
```  image ```
#### Керування зображеннями,
``` manifest ```
#### Керування маніфестами зображень Docker і списками маніфестів,
``` network ```
#### Керування мережами,
```  node ```
#### Керування вузлами Swarm ,
``` plugin ```
#### Керування плагінами,
``` sbom* ```
#### Перегляд пакетних матеріалів програмного забезпечення (SBOM) для зображення (Anchore Inc., 0.6.0),
``` scan* ```
#### Docker Scan (Docker Inc., v0.23.0),
``` secret  ```
#### Керування секретами Docker,
```service ```
#### Керування послугами,
```stack ```
#### Керування стеками Docker,
``` swarm ```
#### Керувати Swarm ,
```system```
#### Управління системою Docker ,
```trust ```
#### Керуйте довірою до зображень Docker ,
``` volume ``` 
#### Керування томами,
# Керуйте зображеннями,
### команди:
``` build ```
#### Створення образу з Dockerfile,
``` history ```
#### Показати історію зображення,
``` import ```
#### Імпортувати вміст із архіву, щоб створити образ файлової системи,
```  inspect ```
#### Відображення детальної інформації про одне або декілька зображень,
```load ```
#### Завантажити зображення з архіву tar або STDIN,
``` ls ``` 
#### Список зображень,
``` prune ```
#### Видалити невикористані зображення,
``` pull ```
#### Витягнути образ або сховище з реєстру,
``` rm ```
#### Видаліть одне або кілька зображень,
``` save ```
#### Збереження одного або кількох зображень до архіву tar (за замовчуванням передається в STDOUT),
```  tag ```
#### Створіть тег TARGET_IMAGE, який посилається на SOURCE_IMAGE,


# Використання: контейнер докерів COMMAND

## Керуйте контейнерами:

#### команди:
  ``` attach```  
  #### Прикріплення локальних стандартних потоків введення, виведення та помилок до запущеного контейнера,
   ```commit```
   #### Створити нове зображення зі змін контейнера,
   ```cp```
   #### Копіювати файли/папки між контейнером і локальною файловою системою,
   ```create``` 
   #### Створити новий контейнер,
   ```diff``` 
   #### Перевірити зміни файлів або каталогів у файловій системі контейнера,
   ```exec``` 
   #### Виконати команду у запущеному контейнері,
   ```export``` 
   #### Експортувати файлову систему контейнера як архів tar,
   ```inspect ```
   #### Відображення детальної інформації про один або декілька контейнерів,
   ```kill ```
   #### Вбиває один або більше запущених контейнерів,
   ```logs``` 
   #### Отримати журнали контейнера,
   ```ls``` 
   #### Список контейнерів,
   ```pause``` 
   #### Призупинити всі процеси в одному або кількох контейнерах,
   ```port ```
   #### Показує відображення портів або певне відображення для контейнера,
   обрізати Видаліть усі закриті контейнери,
   ```rename``` 
   #### Перейменувати контейнер,
   ```restart``` 
   #### Перезапуск одного або кількох контейнерів,
   ```rm``` 
   #### Вийміть один або кілька контейнерів,
   ```run``` 
   #### Виконати команду в новому контейнері,
   ```start``` 
   #### Запустити один або більше зупинених контейнерів
   ```stats``` 
   #### Показує прямий потік статистики використання ресурсів контейнерів
   ```stop ```
   #### Зупинити один або декілька запущених контейнерів
   ```top``` 
   #### Відображення запущених процесів контейнера
   ```unpause``` 
   #### Розблокувати всі процеси в одному або кількох контейнерах
   ```update``` 
   #### Оновити конфігурацію одного або кількох контейнерів
   зачекайте блокувати, доки один або кілька контейнерів не зупиняться, а потім надрукуйте їхні коди виходу

#### Запустіть 'docker container COMMAND --help', щоб дізнатися більше про команду.
Vykorystannya: konteyner dokeriv COMMAND
