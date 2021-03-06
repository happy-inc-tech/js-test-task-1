# Happy Inc: тестовое задание 1

### Поиск места с наименьшим количеством участников

**Задача**: написать функцию, которая возвращает ID места, в котором
в данный момент зарегистрировано наименьшее количество участников.

**Входные данные**: три массива данных в папке `data`.  
Каждый элемент массива описывает определённое место, куда
записывались участники. Для ровного распределения людей
нужно подготовить функцию, которая поможет записать следующего участника
туда, где людей в данный момент меньше всего. У места есть только
две характеристики: идентификатор (`id`) и количество участников (`peopleCount`). 

Нужно учесть следующее:
* Для массивов, где у всех элементов количество участников разное, должен возвращаться ID элемента, 
у которого участников меньше всего;
* для массивов, где наименьшее количество участников одинаковое
у нескольких элементов, должен возвращаться случайный из 
  этих нескольких.
  
**Оценка результата**: помимо просмотра кода, функция будет
проверена автотестом. Файл теста не включён в репозиторий. 
Просьба писать код в файле `index.js`, 
он должен экспортировать функцию `getRelevantPlace` в синтаксисе CommonJS.
Функция должна принимать в качестве аргумента массив с данными.

В качестве результата выполнения просьба прислать ссылку на репозиторий на GitHub. 
