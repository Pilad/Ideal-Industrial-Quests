# Ideal-Industrial-Quests
### 1) Инструкция по установке:
- Скачать и распаковать архив
- Папки config & mods закинуть в корневую папку игры с заменой.
- Если вы ходите играть с квестами в уже существующей игре, то в консоле прописать
- ```/bq_admin default load``` (без ковычек). Это загрузит квесты в вашу текущую игру. В случае
создания новой игры квесты уже будут активны и ничего дополнительно прописывать не
нужно.
- По умолчанию кнопка для открытия квестов - ` ~ ` или `ё`

### 2) Для обновления квестов:
```/bq_admin default load``` (естественно только после замены всех файлов квестов в папке с игрой)
```/updateQuest``` (если читы выключены)

### 3) Как вручную пометить квесты пройденными:
- переключится на режим креатива  ```/gamemode 1```
- прописать ```/bq_admin edit true```
- открыть главное окно квестов, зайти в квесты, снизу жёлкнуть по `edit`
- в левой колонке выбрать главу, а в правой нажать по кнопке desing
- слева, на панели инструментов щёлкнуть по кнопке с галочкой
- пощёлкать по квестам, помечаяя их пройденными
- выйти из режима редактирования щёлкая по кнопкам `back`
- прописать, чтоб выключить режим редактирования  ```/bq_admin edit true```
- прописать, чтоб выйти из режима креатива ```/gamemode 0```
- Если вы играете в одиночной игре `без читов` (а значит и без доступа к режиму креатива), то
можно их включить, открыв игру для локальной сети, и в опциях выбрав `включить читы`.

### 4) Для тех, кто перешёл на BQ из HQM:
- удалить мод и конфиги HQM из папки с игрой (это не обязательно но желательно)
- после удаления, при загрузке мира, подтвердите удаление предметов из мира, которые относились к моду HQM.

5) [`gambiarra-1.0.jar`](https://github.com/IdealIndustrial/Ideal-Industrial-Quest-Book/releases/tag/FixThermos) - Фикс для сервера термос. Закинуть в папку модов только для сервера.
