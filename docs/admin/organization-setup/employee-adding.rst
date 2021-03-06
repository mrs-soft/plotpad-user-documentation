Добавление сотрудников
======================

Сотрудников организации добавляем в разделе **Сотрудники** (Рис. 1).

..  thumbnail:: images/employee-adding-1-overview.png
    :alt: Раздел «Сотрудники»
    :align: center
    :title: Рис. 1. Раздел «Сотрудники»
    :show_caption: True

Вы можете добавить сотрудников двумя способами: 

#.  По одному пользователю через интерфейс приложения.
#.  Сразу несколько пользователей через импорт текстового файла. 

Добавление сотрудников через интерфейс приложения
-------------------------------------------------

Для добавления нового сотрудника нажмите на кнопку **Добавить** в разделе **Сотрудники**.
Далее появится окно ввода данных о новом сотруднике. Заполните все поля. В завершении нажмите кнопку **Добавить** (рис. 2). 

..  thumbnail:: images/employee-adding-2-employee-menu.png
    :alt: Добавление нового сотрудника через интерфейс приложения
    :width: 60%
    :title: Рис. 2. Добавление нового сотрудника через интерфейс приложения
    :show_caption: True

Если вы поставили галочку напротив поля «Без использования лицензионного места», этот сотрудник будет создан в приложении, 
но он не будет иметь доступа в нее, не будет получать уведомления и так далее.

..  note:: Его можно будет добавить на проект, работы, назначить ответственным на замечание, его профиль будет участвовать 
    в аналитике, отчетах и так далее.
    
    Это дает возможность формировать предписания, в которых есть все участники строительства.
    Даже те, на которых нет смысла тратить лицензию приложения.
    
    Например, для передачи нарушений компании-исполнителю.

Добавление сотрудников через импорт файла
-----------------------------------------

Для добавления новых сотрудников списком из имеющегося файла подготовьте текстовый документ (``.txt``) со списком пользователей.
Информацию по каждому пользователю необходимо занести в одну строку, при этом нужно соблюдать следующую последовательность:

..  raw:: html

    <p style="text-align:center;">Почта<b>Tab</b>Фамилия<b>Пробел</b>Имя<b>Пробел</b>Отчество<b>Tab</b>Пароль<b>Tab</b>Телефон</p>

----

..  thumbnail:: images/employee-adding-3-txt-example.png
    :alt: Пример содержимого файла для двух пользователей
    :title: Рис. 3. Пример содержимого файла для двух пользователей
    :show_caption: True

Колонки таблицы соответствуют следующим полям:

#.  E-mail.
#.  ФИО (в именительном падеже).
#.  Пароль.
#.  Телефон.

..  attention:: **Требования к паролям:**

    #.  Неповторимость паролей. Хранение 24 вариантов старых паролей пользователя, с запретом задавать такой же новый.
    #.  Минимальная длина пароля 8 символов.
    #.  Пароль не должен содержать значение имени учетной записи пользователя: почту или ФИО пользователя.
        Например, если ФИО пользователя = Филипченко Антон Сергеевич, а желаемый пароль QW12Антон, то создать его нельзя.

    #.  Пароль должен содержать символы из всех четырех следующих категорий:

        *   заглавные буквы латинского алфавита,
        *   строчные буквы латинского алфавита,
        *   основные 10 цифр (0-9),
        *   специальные символы (например,!, $, #, %).

..  only:: latex

    Далее нажмите на кнопку **Импорт сотрудников** (Рис. 4.1).

    ..  figure:: images/employee-adding-4-txt-employee-adding.png
        :alt: Добавление сотрудников через импорт текстового файла
        :align: center

        Рис. 4.1. Добавление сотрудников через импорт текстового файла

    Выберите необходимый файл и нажмите на кнопку **Открыть** (Рис. 4.2).
    
    ..  figure:: images/employee-adding-5-txt-employee-adding.png
        :alt: Добавление сотрудников через импорт текстового файла
        :align: center
    
        Рис. 4.2. Добавление сотрудников через импорт текстового файла

..  only:: html

    Далее нажмите на кнопку **Импорт сотрудников**, выберите необходимый файл и нажмите на кнопку **Открыть** (Рис. 4).

    ..  thumbnail:: images/employee-adding-6-txt-employee-adding.gif
        :alt: Добавление сотрудников через импорт текстового файла
        :title: Рис. 4. Добавление сотрудников через импорт текстового файла
        :show_caption: True



..  warning:: Исправлять электронный адрес сотрудника в программе нельзя!
    Обязательно проверьте введенную информацию по каждому сотруднику.
    Адрес электронной почты должен быть индивидуальным для каждого сотрудника.
    
    Двух сотрудников с одинаковыми адресами электронной почты зарегистрировать в программе нельзя.
    На указанный адрес будут приходить уведомления о ходе реализации проекта.

..  attention:: Если при регистрации вы ввели в программе ошибочные данные электронной почты сотрудника,
    то придется удалить его профиль и создать заново.

..  note:: Все сотрудники, добавленные через импорт текстового файла, автоматически назначаются на лицензионное место в программе.
    
    Нельзя добавить сотрудников через импорт текстового файла без использования лицензионного места!

Выгрузка списка сотрудников через экспорт файла
-----------------------------------------------

В программе предусмотрена возможность выгрузки архива с информацией в формате:
где, на каком проекте и в какой роли назначены пользователи.
Для выгрузки списка нажмите «Экспорт данных» (Рис.5).

..  only:: html
        
    ..  thumbnail:: images/employee-adding-7-employee-exporting.gif
        :alt: Выгрузка списка сотрудников
        :title: Рис. 5. Выгрузка списка сотрудников
        :show_caption: True

..  only:: latex

    ..  figure:: images/employee-adding-8-employee-exporting.png
        :alt: Выгрузка списка сотрудников
        :align: center

        Рис. 5. Выгрузка списка сотрудников

При экспорте формируется файл в формате ``.csv``. Для прочтения его нужно импортировать, например в Microsoft Excel 2021.

..  note:: Для старых версий Microsoft Excel инструкция тоже подходит, но внешний вид программы будет отличаться.

Для импорта в Excel перейдите в меню «Данные» --- «Получить данные» --- «Из файла» --- "Из текстового/CSV-файла" (Рис.6). 

..  thumbnail:: images/employee-adding-9-exporting-excel-importing.png
    :alt: Меню "Данные" в Excel
    :width: 70%
    :title: Рис. 6. Меню "Данные" в Excel
    :show_caption: True

Найдите файл, который вы выгрузили и нажмите «Импорт» (Рис.7).

..  thumbnail:: images/employee-adding-10-exporting-excel-importing-from-pc.png
    :alt: Поиск CSV файла на компьютере
    :width: 70%
    :title: Рис. 7. Поиск CSV файл на компьютере
    :show_caption: True

После загрузки откроется мастер по импорту текстовых документов (Рис.8).

#.  В поле «Источник файла» выберите::
    
        65001: Юникод (UTF-8)

#.  "Разделитель" установите --Пользовательский-- и выберете "$" в качестве разделителя для строчек.

#.  "Обнаружение типов данных" по умолчанию стоит на значении "На основе первых 200 строк" --- его можно не менять.
    
    Если таблица после импорта отображается некорректно, то поменяйте значение на "На основе всего набора данных".
    В этом случае импорт может занять больше времени, если у вас много сотрудников в приложении.

..  thumbnail:: images/employee-adding-11-exporting-excel-set-up.png
    :alt: Настройка мастера импорта
    :width: 70%
    :title: Рис. 8 Настройка мастера импорта
    :show_caption: True

Удаление сотрудников
--------------------

В разделе «Сотрудники» реализован механизм архивирования/удаления сотрудников.
Для этого нажмите на кнопку «Архивировать» (Рис. 9).

..  thumbnail:: images/employee-adding-12-deleting.png
    :alt: Удаление сотрудника
    :width: 70%
    :title: Рис. 10. Удаление сотрудника
    :show_caption: True

Вы увидите красные «крестики» напротив элементов списка.
Архивируйте элемент, нажав на «крестик». Чтобы вернуться в обычный режим, нажмите на кнопку «Вернуться в просмотр».

После удаления сотрудника из раздела «Сотрудники», он будет помечен, как удаленный.
При этом его данные останутся в программе, и сохранится возможность формирования статистики по нему (Рис. 11).

..  thumbnail:: images/employee-adding-13-deleted.png
    :alt: Удаленный сотрудник
    :width: 70%
    :title: Рис. 11. Удаленный сотрудник
    :show_caption: True