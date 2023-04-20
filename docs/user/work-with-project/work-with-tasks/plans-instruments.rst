Инструменты для работы на плане
===============================

Откройте необходимый вам чертеж.
В правом верхнем углу доступны две панели с инструменты для работы с чертежом (Рис. 1).

..  thumbnail:: images/plans-instruments/plans-instrument-1-plan-with-panels.png
    :alt: Чертёж
    :align: center
    :class: framed
    :title: Рис. 1. Чертеж с панелями инструментов
    :show_caption: True

На верхней панели расположены управляющие элементы, а на правой --- выделяющие.

Панель с управляющими элементами
--------------------------------

..  thumbnail:: images/plans-instruments/plans-instrument-2-manage-panel.png
    :alt: Панель с управляющими элементами
    :align: center
    :width: 50%

----

Рассмотрим каждый инструмент на панели:

#.  |Genplan-Button| --- работа с Генпланом. Позволяет преобразовать чертеж в Генплан. Описание работы функционала в следующем разделе.
#.  |Favorite-Button| --- добавление в избранное. После нажатия на эту кнопку чертеж будет добавлен в раздел «Избранное». 
#.  |Task-Registry-Button| --- реестр замечаний. Нажатие кнопки переместит вас в реестр замечаний, относящихся к данному чертежу.
    Нажав на любое замечание, вы можете перейти к его редактированию.
#.  |Layers-Button| --- слои. При нажатии кнопки «Слои» открывается меню выбора слоев для последующего отключения/включения.
 
    У всех планов можно отключить **слой аннотаций** --- это слой нарисованных фигур на плане: линий, кругов, стрелок и тому подобное, ---
    и слой замечаний (Рис. 2). Для DWF-чертежей, в которых сохранились слои плана, есть доступ к включению и выключению некоторых из них.

    ..  thumbnail:: images/plans-instruments/plans-instrument-6-manage-panel-layers.png
        :alt: Работа со слоями
        :class: framed
        :width: 50%
        :title: Рис. 2. Работа со слоями
        :show_caption: True

#.  |Settings-Button| --- настройки плана. Позволяет перейти в настройки чертежа (Рис. 3).

    ..  thumbnail:: images/plans-instruments/plans-instrument-7-manage-panel-settings.png
        :alt: Настройки чертежа
        :align: center
        :class: framed
        :title: Рис. 3. Окно настроек чертежа
        :show_caption: True

#.  |Exit-Button| --- закрыть чертеж.

Панель с выделяющими элементами
-------------------------------

Панель справа состоит из 6 кнопок (Рис. 4):

..  thumbnail:: images/plans-instruments/plans-instrument-9-selection-panel.png
    :alt: Работа со слоями
    :width: 40%
    :class: framed
    :title: Рис. 4. Инструменты для работы с чертежом
    :show_caption: True

#.  |Selection-Button| --- режим выделения. Позволяет выделить несколько замечаний и аннотаций на чертеже.
    Необходим для совершения действия сразу с несколькими элементами на чертеже (Рис. 5).

    ..  only:: html

        ..  thumbnail:: images/plans-instruments/plans-instrument-10-selection-panel-selection.gif
            :alt: Работа со слоями
            :align: center
            :class: framed
            :title: Рис. 5. Панель выделения
            :show_caption: True

    ..  only:: latex

        ..  figure:: images/plans-instruments/plans-instrument-10-selection-panel-selection.png
            :alt: Работа со слоями
            :align: center

            Рис. 5. Панель выделения.

#.  |Choose-Button| --- режим выбора. Позволяет перемещать чертеж на экране, выбирать и открывать контекстное меню замечания.
#.  |Scale-Button| --- масштабирование. Позволяет изменить масштаб чертежа.
    Вам доступно несколько заданных коэффициентов увеличения и приближения:
    50%, 100%, 150%, 200% и **Fit** (Рис. 6).

    ..  thumbnail:: images/plans-instruments/plans-instrument-12-selection-panel-scale.png
        :alt: Масштабирование
        :width: 50%
        :class: framed
        :title: Рис. 6. Заданные коэффициенты масштабирование.
        :show_caption: True

    ..  note:: **Fit** --- масштабирование размера чертежа в соответствие с размером экрана устройства.

#.  |Drawing-Button| --- рисование фигур, иконка может отличаться в зависимости от того, какую фигуру вы используете чаще всего.
    
    При нажатии на данную кнопку программа предложит пользователю набор инструментов для создания меток (Рис. 7):
    
    *   стрелка,
    *   линия,
    *   прямоугольник,
    *   круг,
    *   крест,
    *   ручка (свободное рисовании),
    *   облако,
    *   текст на чертеже.

    ..  thumbnail:: images/plans-instruments/plans-instrument-13-selection-panel-drawing.png
        :alt: Метки
        :width: 70%
        :class: framed
        :title: Рис. 7. Набор инструментов для создания меток
        :show_caption: True

    После выбора любого инструмента, внизу всей панели появляются две дополнительные кнопки:
    
    *   |Width-Button| --- настройка толщины линии,

        ..  thumbnail:: images/plans-instruments/plans-instrument-10-selection-panel-width.png
            :alt: Толщина линии
            :width: 50%
            :class: framed
            :title: Рис. 8. Настройка толщины линии
            :show_caption: True

    *   |Color-Button| --- настройка цвета.

        ..  thumbnail:: images/plans-instruments/plans-instrument-10-selection-panel-color.png
            :alt: Цвет линии
            :width: 40%
            :class: framed
            :title: Рис. 9. Настройка цвета
            :show_caption: True

#.  |Measurements-Button| --- измерения. Позволяет измерить, отметить, задать расстояния между объектами.
    Символ на кнопке меняется в зависимости от последнего используемого инструмента (Рис. 10).

    ..  thumbnail:: images/plans-instruments/plans-instrument-14-selection-panel-measurements.png
        :alt: Работа со слоями
        :width: 40%
        :class: framed
        :title: Рис. 10. Набор инструментов для измерения
        :show_caption: True

#.  |Tasks-Creating-Button| --- работа с замечаниями. При двойном нажатии появляется следующая панель работы с замечанием: 

    ..  thumbnail:: images/plans-instruments/plans-instrument-15-selection-panel-tasks.png
        :alt: Работа со слоями
        :width: 40%
        :class: framed
        :title: Рис. 11. Панель замечаний
        :show_caption: True

    *   |Tasks-Creating-Button| --- создает замечание. 
    *   |Tasks-Bim-Button| --- доступна только при работе с BIM моделями. Позволяет создать замечание в BIM-модели.
    *   |Tasks-Button| --- кнопка клонирования замечаний. Позволяет копировать однотипные замечания.
        
        Подробнее в разделе :doc:`./cloning-typical-tasks-on-plan`.

..  note:: Все созданные замечания можно удалить прямо на чертеже, предварительно выделив их |Selection-Button| и нажав на кнопку
    «Удалить», если у вас есть на это права.

..  |Genplan-Button| image:: images/plans-instruments/plans-instrument-3-manage-panel-genplan.png
            :alt: Генплан
            :class: framed
            :scale: 70%

..  |Favorite-Button| image:: images/plans-instruments/plans-instrument-4-manage-panel-favorite.png
            :alt: Избранное
            :class: framed
            :scale: 70%

..  |Task-Registry-Button| image:: images/plans-instruments/plans-instrument-5-manage-panel-tasks-registry.png
            :alt: Реестр замечаний
            :class: framed
            :scale: 70%

..  |Layers-Button| image:: images/plans-instruments/plans-instrument-6-manage-panel-layers-button.png
            :alt: Реестр замечаний
            :class: framed
            :scale: 70%

..  |Settings-Button| image:: images/plans-instruments/plans-instrument-7-manage-panel-settings-button.png
            :alt: Настройки
            :class: framed
            :scale: 70%

..  |Exit-Button| image:: images/plans-instruments/plans-instrument-8-manage-panel-exit.png
            :alt: Выход из чертежа
            :class: framed
            :scale: 70%

..  |Selection-Button| image:: images/plans-instruments/plans-instrument-10-selection-panel-selection-button.png
            :alt: Выход из чертежа
            :class: framed
            :scale: 70%

..  |Choose-Button| image:: images/plans-instruments/plans-instrument-11-selection-panel-choose-button.png
            :alt: Выход из чертежа
            :class: framed
            :scale: 70%

..  |Scale-Button| image:: images/plans-instruments/plans-instrument-12-selection-panel-scale-button.png
            :alt: Выход из чертежа
            :class: framed
            :scale: 70%
            
..  |Drawing-Button| image:: images/plans-instruments/plans-instrument-13-selection-panel-drawing-button.png
            :alt: Выход из чертежа
            :class: framed
            :scale: 70%

..  |Width-Button| image:: images/plans-instruments/plans-instrument-10-selection-panel-width-button.png
            :alt: Выход из чертежа
            :class: framed
            :scale: 70%

..  |Color-Button| image:: images/plans-instruments/plans-instrument-10-selection-panel-color-button.png
            :alt: Выбор цвета
            :class: framed
            :scale: 70%

..  |Measurements-Button| image:: images/plans-instruments/plans-instrument-14-selection-panel-measurements-button.png
            :alt: Измерения
            :class: framed
            :scale: 70%

..  |Tasks-Button| image:: images/plans-instruments/plans-instrument-15-selection-panel-tasks-button.png
            :alt: Работа с чертежами
            :class: framed
            :scale: 70%

..  |Tasks-Creating-Button| image:: images/plans-instruments/plans-instrument-15-selection-panel-tasks-creating.png
            :alt: Создание замечаний
            :class: framed
            :scale: 70%

..  |Tasks-Bim-Button| image:: images/plans-instruments/plans-instrument-15-selection-panel-tasks-bim.png
            :alt: BIM
            :class: framed
            :scale: 70%

..  |Tasks-Clone-Button| image:: images/plans-instruments/plans-instrument-15-selection-panel-tasks-clone.png
            :alt: Клонирование
            :class: framed
            :scale: 70%