Генплан
=======

В программе реализована возможность увидеть все замечания проекта на одном плане.

На верхнем уровне структуры объекта определяем или загружаем чертеж, который мы хотим использовать как **Генплан**,
затем клонируем либо подгружаем этот чертеж на внутренние элементы структуры объекта.

Генплан образуется путем наложения чертежей, поэтому чтобы информация была корректна, необходимо связывать одинаковые чертежи.

..  only:: html

    Создание генплана (Рис. 1):

    #.  В чертеже, который вы определили как генплан, в верхней панели нажмите на кнопку привязки чертежей |Genplan-Button|.
    #.  Далее откроется окно привязки подпланов. Нажмите на кнопку |Creating-Button|, чтобы добавить новые чертежи.
    #.  В появившемся списке выбираем необходимые чертежи.
    #.  Для каждого чертежа в появившемся окне выбираем номера страниц для добавления в генплан.

    ..  thumbnail:: images/general-plan/general-plan-1-creating.gif
        :alt: Создание генплана
        :align: center
        :title: Рис. 1. Создание генплана
        :show_caption: True

..  only:: latex

    ..  figure:: images/general-plan/general-plan-1-creating.png
        :alt: Создание генплана
        :align: center

        Рис. 1. Создание генплана

    Откроется окно привязки подпланов. Нажимаем на |Creating-Button| (Рис. 1.2).

    ..  figure:: images/general-plan/general-plan-1-2-creating.png
        :alt: Создание генплана
        :align: center

        Рис. 1.2. Создание генплана

    В появившемся списке выбираем необходимые чертежи (Рис. 1.3).

    ..  figure:: images/general-plan/general-plan-1-2-creating.png
        :alt: Создание генплана
        :align: center

        Рис. 1.3. Создание генплана

    Для каждого чертежа в появившемся окне выбираем номера страниц для добавления в генплан (Рис. 1.4).

    ..  figure:: images/general-plan/general-plan-1-2-creating.png
        :alt: Создание генплана
        :align: center

        Рис. 1.4. Создание генплана

После этого все замечания и аннотации с чертежей на внутренних элементах структуры будут показаны на едином плане. (Рис. 2).

Визуально генплан можно отличить от обычного чертежа по голубой верхней панели инструментов.

.. note:: Функционал программы позволяет связать между собой несколько генпланов в один основной.

..  thumbnail:: images/general-plan/general-plan-2-working.png
    :alt: Создание генплана
    :align: center
    :title: Рис. 2. Работа с генпланом
    :show_caption: True

Чтобы открепить чертежи от генплана нужно вновь нажать на |Genplan-Button| и в открывшемся окне удалить ненужные чертежи.

.. attention:: На генплане можно поставить замечание. При этом данное замечание будет относиться только к генплану и
    не будет фигурировать на подпланах.

.. note:: Реестр замечаний генплана содержит только замечания, привязанные к нему, замечания подпланов вы там не увидите.

..  |Genplan-Button| image:: images/plans-instruments/plans-instrument-3-manage-panel-genplan.png
            :alt: Генплан
            :scale: 65%

..  |Creating-Button| image:: images/general-plan/general-plan-1-creating-button.png
            :alt: Генплан
            :scale: 65%
