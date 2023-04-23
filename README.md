# Лабораторная работа 3 - Групповой проект
## Задание
Цель заключалась в изучении предназначения и различных способов организаций систем контроля версий
(Version Control System, VCS) Git, а также ознакомлением с операциями над файлами в репозитории и
с приемами групповой работы над проектом.
Итогом работы является проект с единым интерфейсом, выполняющий несколько
различных задач (по количеству участников команды). 
## Описание хода разработки
### Этап первый
Был создан общий репозиторий и придуман интерфейс для проекта.
Пользователю доступен выбор из трех кнопок, каждая из которых отвечает за вывод новой формы,
созданной специально для выполнения варианта по конкретному заданию.
На данном этапе в проекте создана только основная форма, чтобы в дальнейшей работе
каждый участник сам создавал форму для своего задания.
![image](https://user-images.githubusercontent.com/105740494/233864699-eaf9e06f-65c1-4baf-9550-c4d4f6a8bf4d.png)

*Основная форма*

![image](https://user-images.githubusercontent.com/105740494/233864795-1c254a8f-adbc-4c5a-a84a-240a0a8efa22.png)

*Заготовки событий нажатия кнопок для вывода определенных форм*

### Этап второй
На данном этапе участники проекта начинают самостоятельную работу.
Каждый создает локальную копию репозитория и свою ветку, а далее реализует то, что необходимо по заданию варианта,
создавая при этом свою форму. В ходе работы участники делают коммиты, сохраняя изменения в своих классах.

Далее будут описаны процессы выполнения каждого их трех вариантов участников.


**Вариант 8**
*Выполнила Мария Порошина под ником @MollyPor. Имя ветки - Masha*

Формулировка задания: 
Пользователь открывает файл с данными о медианной заработной плате в России за
последние 15 лет. Вывести эту информацию на экран в удобном формате. Также по этим
данным построить графики. Вычислить процент роста зарплат у мужчин и у женщин.



**Вариант 10**
*Выполнила Смирнова Александра под ником @Alexonderia. Имя ветки - Alexandra*

Формулировка задания: 
Пользователь открывает файл с данными об инфляции в России за последние 15 лет.
Вывести эту информацию на экран в удобном формате. Также по этим данным построить
графики. По среднему значению спрогнозировать инфляцию на ближайшие 3 года, рассчитать
возможную стоимость какого-либо товара или услуги

Для выполнения задания был создан класс Inflation, в котором производятся рассчеты
для прогноза инфляции.

![image](https://user-images.githubusercontent.com/105740494/233865934-3e4b0c82-0c69-4e07-9fa7-10cf5fb2b022.png)

*Код класса Inflation*

Также была создана форма для вывода таблицы с данными об инфляции в России за последние 15 лет, построения графика
по выведенной таблице и ввода стоимости продукта или услуги, для которой необходимо спрогнозировать изменения
на ближайшие три года.

![image](https://user-images.githubusercontent.com/105740494/233865833-9fcad3e2-e956-44ac-ba62-4c50da84b113.png)

*Вид формы при выводе пользователю*

![image](https://user-images.githubusercontent.com/105740494/233865879-6bbef7aa-c43c-40b3-8035-5b6b8fce834d.png)

*Вид формы в процессе взаимодействия с пользователем*


**Вариант 14**
*Выполнил Крылов Евгений под ником @Galeria596. Имя веток - master/var-14*

Формулировка задания: 
Пользователь открывает файл с данными о численности населении по субъектам в
России за последние 15 лет. Вывести эту информацию на экран в удобном формате. Также по 
этим данным построить графики. Вычислить в каком субъекте РФ за 15 лет численность
снизилась больше всего.


### Этап третий
После того, как каждый участник проекта выполнил своё задание и закончил обновлять локальные ветки, необходимо провести слияние
этих веток с веткой master. 

## Итоги
Исходное задание было выполнено.
Результатом стал проект, позволяющий пользователю получить статистические данные по трем сферам, указанным в 8, 10 и 13 вариантах
(медианная заработная плата, инфляция и численность населения  за последние 15 лет в России). Для любой выбранной сферы
можно вывести таблицу с данными, график и результаты определенны вычислений.

