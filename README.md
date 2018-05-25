

# Проект команды Next Team

## Запуск сборки проекта
В адресе вашего проекта на ПК не должно быть кириллицы. Идеально — создайте с корне диска С: или D: папку "projects" и разместите в нее папку вашего проекта. У вас может получится что то похожее на это: C:\projects\wdtest

1. Клонирование проекта к себе на ПК               

    git clone https://github.com/thebestday/wdtest.git


2. Переходим в созданную папку

    cd wdtest


3. Устанавливаем все зависимости
 
    npm install


### code guide

Соглашение по написанию кода. Общие правила которых будут придерживаться все члены команды:

* [less] - CSS препроцессор
* [Flexbox] - Для построения структуры страниц спользуем флексы
* [Bootstrap grid 4] - В сборке уже есть сетка от bootstrap-4
* [Табы] - Проверьте, что бы настройки отступов в редакторе были сделаны табами (это важно для PUG файлов)
* [Bem] - При написании кода используем BEM naming (Блок, Элемент, Модификатор)