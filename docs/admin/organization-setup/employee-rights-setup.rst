Настройка прав сотрудников организации
======================================

Для каждого сотрудника организации можно настроить индивидуальные права на работу с программой. 
Настройка прав сотрудников осуществляется в панели администрирования.
Зайдите в интересующую вас организацию, далее в раздел «Сотрудники».
Нажмите на значок шестеренки напротив сотрудника.

Появится меню «Настройки» (Рис. 1). В данном меню доступно несколько разделов для настройки, рассмотрим каждый из них. 

..  thumbnail:: images/employee-rights-setup-1-overview.png
    :alt: Общий вид меню «Настройки» сотрудника
    :width: 60%
    :title: Рис. 1. Общий вид меню «Настройки» сотрудника
    :show_caption: True

..  attention:: Права, которые вы настроили для конкретного сотрудника в разделе «Сотрудники» в панели администрирования,
    имеют приоритет над правами, определенными ролью данного сотрудника на проекте.
    
    Например, у сотрудника есть право удалять замечания, а в роли, на которую он назначен, такого права нет.
    В таком случае он сможет архивировать замечания, так как права сотрудников дополняют права роли. 

Сотрудник
---------

В разделе «Редактировать» вы можете изменить данные сотрудника: ФИО, пароль и телефон.

..  note:: Адрес электронной почты сотрудника изменить нельзя.

Вы можете заблокировать сотрудника поставив галочку в поле "Заблокировать сотрудника".
При блокировке лицензия, закреплённая за пользователем, сохраняется и в списке сотрудников у человека появляется значок |Lock-Icon|.

Для восстановления пользователя достаточно снять галочку.

..  |Lock-Icon| image:: images/employee-rights-setup-2-lock-icon.png
                :alt: Значок блокировки


..  note:: После блокировки сотрудника, ему придёт уведомление на электронную почту.
    
    Также заблокированному пользователю будут приходить уведомления из приложения, например о назначении на замечание.
    
    При восстановлении на электронную почту пользователя придёт уведомление с паролем для входа в приложение.

Права
-----

Права на организацию
++++++++++++++++++++

В разделе «Права на организацию» сотруднику можно присвоить права на работу с панелью администрирования.

..  warning:: Данный раздел настраивается только для администратора системы.
    Администратору системы необходимо присвоить все права в данном разделе.
    У остальных сотрудников напротив данных прав надо убрать все галочки.

Рассмотрим подробно каждое из предложенных прав:

Права на организации
````````````````````

*   Просмотр организаций — даёт право работать в панели администрирования.
*   Изменение реквизитов — даёт право вносить изменения в реквизиты основной организации и контрагентов.    
*   Создание контрагентов — даёт право создавать контрагентов.
*   Удаление контрагентов — даёт право на архивирование контрагентов.
*   Восстановление контрагентов — даёт право на восстановление заархивированных контрагентов.

Права на панель администрирования
`````````````````````````````````

*   Доступ к панели администрирования --- даёт доступ к панели администрирования.

..  Права на шаблоны
..  ````````````````
..      
..  *   Чтение шаблонов 
..  *   Создание шаблонов 
..  *   Изменение шаблонов
..  *   Удаление шаблонов 
..  
..  Право на выгрузку данных
..  ````````````````````````
..  
..  *   Выгрузка списка контрольных карт

Права на сотрудников
````````````````````

*   Импорт сотрудников — дает право добавлять сотрудников через импорт файла.
*   Экспорт данных сотрудников — дает право на экспорт данных сотрудников (ФИО, mail, телефон, на какие элементы структуры и роли назначен сотрудник)
*   Добавление сотрудников — дает право добавлять сотрудников и изменять его данные (ФИО, номер телефона, пароль).
*   Удаление сотрудников — дает право архивировать сотрудников.
*   Изменение прав сотрудников — дает право изменять права сотрудников. 
*   Редактирование данных сотрудника — дает право изменять данные сотрудника (ФИО, номер телефона, пароль). 
*   Восстановление сотрудников — дает право восстанавливать архивированных сотрудников.
*   Блокировка сотрудника – даёт право на блокировку сотрудника.

Права на роли
`````````````

*   Создание ролей — дает право на создание роли, изменение названия роли. Работает в паре с правами «Изменение прав ролей» и «Чтение прав ролей».
*   Удаление ролей — дает право на архивирование/удаление роли. 
*   Редактирование ролей — дает право на изменение настроек роли.
*   Изменение прав у ролей — дает право на изменение прав у ролей. Работает в паре с правом «Чтение прав ролей».

Права на категории
``````````````````
    
*   Изменение категорий — дает право на редактирование названия категорий.
*   Создание категорий — дает право создавать категории.
*   Удаление категорий — дает право архивировать/удалять категории.

Права на типовые замечания
``````````````````````````

*   Изменение типовых замечаний — дает право на изменение типовых замечаний.
*   Создание типовых замечаний — дает право на создание типовых замечаний.
*   Удаление типовых замечаний — дает право на удаление типовых замечаний.

Права на перенос
````````````````

*   Перенос элементов структуры — дает право на перенос элементов структуры в рамках одного проекта.

Права на шаблоны документов
```````````````````````````

*    Просмотр шаблона – дает право просматривать раздел “Шаблоны документов”.
*    Создание шаблона – дает право на создание шаблонов.
*    Изменение шаблона – дает право на редактирование шаблонов.
*    Удаление шаблона – дает право на архивирование шаблонов.
*    Восстановление шаблона – дает право восстанавливать архивированные шаблоны.

Права на проекты
++++++++++++++++

В разделе «Права на проекты» можно присвоить для отдельных сотрудников права, которые описаны в разделе :doc:`roles-setup`. 
Настройка прав отдельных сотрудников позволяет подстраивать работу приложения "СтройКонтроль" под ваш рабочий процесс.

Рекомендуем использовать эти настройки только если не можете подобрать для сотрудника какую-то типичную роль.

..  note:: В разделе «Права на проекты» мы рекомендуем НЕ настраивать права для инженера строительного надзора, 
    заказчика, подрядчика, администратора системы и других типовых сотрудников.
    
    Эти настройки мы произвели для ролей, на которые назначили данных сотрудников в разделе :doc:`roles-setup`.

Остальные настройки
-------------------

Далее заполните разделы:

*   «Должность»,
*   «Должность для отчета»,
*   «ФИО для отчета».

Данная информация может участвовать в формировании предписаний и отчетов. 

Разделы «Должность для отчета» и «ФИО для отчета» заполните в дательном падеже: `Инженеру строительного контроля`, `Петрову Ивану Фёдоровичу`.

Это необходимо для корректного отображения информации в отчете, формируемом в разделе «Замечания» пользовательской части. 

..  attention:: Не забудьте после настройки прав сотрудника нажать кнопку "Применить" (Рис. 2)

..  thumbnail:: images/employee-rights-setup-3-accept.png
    :alt: Применить настройки
    :width: 60%
    :title: Рис. 2. Применить настройки
    :show_caption: True