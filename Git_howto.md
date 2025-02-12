# Подсказка по GIT

### Создание репозитрия
```sh
git init
```
### Просмотр состояния репозитория и их измениние
```sh
git status
```
### Добавление проиндексированного файла (отслеживанию)
```sh
git add
```
### Фиксирует индексуемый файл комментарием (сохраняет текущее состояние)
```sh
git commit -m "Message"
```
### Отображает зафиксированные комиты
```sh
git log
```
### Отобразить хэш коммитов в укороченном виде
```sh
git log --oneline
```
### Отобразить хэш коммитов в виде графика
```sh
git log --graph
```
### Отобразить хэш коммитов в укороченном виде и в виде графика
```sh
git log --oneline --graph
```
### Позволяет переключаться между коммитами
```sh
git checkout <имя ветки или комита>
```
### Отображение всех веток
```sh
git branch
```
### Создание новой метки
```sh
git branch <имя_ветки>
```
### Удаление ненужной ветки
```sh
git branch -d <имя_ветки>
```
### Слияние ветки
```sh
git merge <имя_ветки>
```
### Очистка терминала от всех записей
```sh
clear
```
Создание нарочитой ошибки в git и исправление ее. Запись в branch_issue
> ошибка 1
>> **Исправили ошибку выбрав ветку branch_issue в качетсве Правильной и Верной!** а также добавили эту запись.

### Полужирный
```sh
**Полужирный**
```
### Курсив
```sh
*Курсив.*
```
### Зачеркнутый текст
```sh
~~зачеркнутый~~
```
## Цитаты
```sh
> Первый уровень цитаты
>> Второй уровень цитаты
>>> Третий уровень цитаты
```

## Картинки
```sh
![Текст с описанием картинки](/images/picture.jpg) or (https://www.example.com/image.jpg)
```
## Ссылки
```sh
[Текст ссылки](https://www.example.com)
```

# Списки
## Ненумерованный список
```sh
* Элемент 1
* Элемент 2
* Элемент 3
```
## Нумерованный список
```sh
1. Пункт первый
2. Пункт второй
3. Пункт третий
```



# Урок 6. Семинар. Работа с удалёнными репозиториями
Команда git clone копирует существующий репозиторий Git на локальный репозиторий.
```sh
git clone <URL>
```
Команда git pull используется для извлечения и загрузки содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым.
```sh
git pull
```
Команда git push используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию.
```sh
git push
```
Команда git remote служит для управления списком удалённых репозиториев. Она позволяет сохранять длинные URL репозиториев в виде понятных коротких строк, например «origin»
```sh
git remote add <имя> <URL>.
```
