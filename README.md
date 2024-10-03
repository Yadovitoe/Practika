# Practika
## Установка Flutter

После скачивания Flatter, в свойствах системы добавляю переменную среды с указанием пути

![image](https://github.com/user-attachments/assets/c29a224f-af49-4ca0-a8e2-4d387e71094f)

Через настройки Android Studio скачиваю плагин Flatter

![image](https://github.com/user-attachments/assets/219de3ab-4dd2-46dd-a201-435639f89bcb)

Указываю пусть к папке flatter для SDK

![image](https://github.com/user-attachments/assets/42aa3f0b-32c1-481c-aea6-c37e0d6f6c0e)

Использую команду flutter doctor в терминале для проверки установки

![image](https://github.com/user-attachments/assets/984ed95f-09c7-4131-9952-5e224b84a3b5)

Создаю новый проект с Flatter

![image](https://github.com/user-attachments/assets/2f4685ce-2d45-4e5a-b902-627e68a8fb8d)

![image](https://github.com/user-attachments/assets/ee98daa1-a94e-47e2-a54c-b6a9948bd6e2)

## Лекция 2
Данное приложение является счётчиком кликов по кнопке. Счётчик можно сбрасывать, благодаря кнопке слева.
В приложении используются различные виды виджетов, классов из второй лекции.

![image](https://github.com/user-attachments/assets/52ab9344-b4ab-40ff-b73b-bb92799ddbfe)

![image](https://github.com/user-attachments/assets/d20e3310-501e-4149-9bb9-01f14f20b820)

![image](https://github.com/user-attachments/assets/0a92dd1d-7c7c-4c3d-934c-53134ee1dcad)

## Лекция 3
Имеется список строк с названиями элементов. При нажатии на кнопку первый элемент списка перемещается в конец. Для каждого элемента списка используется ValueKey, что позволяет Flutter правильно обновлять состояние элементов при их перемещении.

![image](https://github.com/user-attachments/assets/f0b1eae6-32fd-46f1-93ca-5ce847f73c05)

![image](https://github.com/user-attachments/assets/4a8a44f6-6afd-4806-b093-c643b9492902)

## Лекция 4
Использовала Row, Column, Stack для организации виджетов по горизонтали, вертикали и по слоям. Добавила отступы вокруг текста и элементов с помощью Padding. Выравнила виджеты внутри Stack и Row с помощью Align.
Использовала Center для центровки текста внутри Container. Создала различные контейнеры с разными цветами и размерами.
Использовала Expanded для растягивания и гибкого использования пространства внутри Column.
А также создала прокручиваемый список с элементами, созданными с помощью ListView.builder().

![Снимок экрана 2024-09-26 182450](https://github.com/user-attachments/assets/4771eee9-e18e-4778-bab6-bb29304f1644)

## Лекция 5
В данном приложении при нажатии кнопки "Submit" данные из текстовых полей сохраняются в переменные, с учетом Null Safety. В текстовом виджете отображается приветствие в зависимости от введенных данных, учитывая случаи, когда имя или возраст могут быть null.

![image](https://github.com/user-attachments/assets/7d4bc062-5d8d-4c3c-a361-2daa4ad63b30)

![image](https://github.com/user-attachments/assets/89a6ed29-23ee-48d0-ab41-316b17d73782)

![image](https://github.com/user-attachments/assets/ef6f8b67-2397-4890-821a-8087a0570e9f)

## Лекция 6
Экраны определены в маршрутах, что позволяет переходить к ним по их именам. На третий экран передаются данные через URL (/third/пример данных). Передача данных с onGenerateRoute используется для обработки именованных маршрутов, которые начинаются с /third/, и извлечение данных из пути. Такой же маршрут добавлен для четвёртого экрана. Третий и четвертый экраны возвращают данные на главный экран.

![image](https://github.com/user-attachments/assets/db610354-a473-4f00-840b-fea3dea51e0d)

![image](https://github.com/user-attachments/assets/8f11e439-d63a-432a-8dc3-553929bcfd3c)

![image](https://github.com/user-attachments/assets/b78b32a8-3c2d-4831-90c3-b3e2cef6062a)

![image](https://github.com/user-attachments/assets/d1d270ab-ffd1-485a-a31a-2ba4973a0788)

## Лекция 7
Приложение содержит форму с полями ввода имени и возраста, а также выпадающий список для выбора пола. Если данные не введены, появляется ошибка. При нажатии на кнопку отправки формы отображается SnackBar с сообщением об успешной отправке. Отображается AlertDialog при нажатии на отдельную кнопку. Использован жест для скрытия клавиатуры при нажатии на любое место вне полей ввода.

![image](https://github.com/user-attachments/assets/af61b050-a9ca-4ef5-aaf9-72f0a1e8257a)

![image](https://github.com/user-attachments/assets/416ef17c-b6f3-4d39-8280-ec73e29e62ec)

![image](https://github.com/user-attachments/assets/c7f41fe8-3f76-474e-b4ba-a44d6a391ba2)

![image](https://github.com/user-attachments/assets/a828879a-8e71-4c0a-af19-851abbb820b4)

## Лекция 8
На экране две кнопки: одна для отображения альбома (с ручной сериализацией JSON), а другая — для отображения информации о пользователе (с автогенерацией JSON).

![image](https://github.com/user-attachments/assets/58d8fa2a-146a-4d03-aa11-702fb1b79771)

![image](https://github.com/user-attachments/assets/6978463d-b8cd-4de0-b0b9-2d0a8582d212)

![image](https://github.com/user-attachments/assets/85addd20-8917-4f1a-b349-9e9f2d003dfb)

## Лекция 9
Локальное состояние _isSwitchOn управляется через setState в виджете HomePage. Состояние приложения управляется через Provider. setState используется для управления локальным состоянием переключателя. Виджет BackgroundColorWidget может передавать данные о цвете фона дочерним виджетам, но в данном примере он лишь демонстрирует структуру. AppData хранит и изменяет цвет фона, и этот цвет обновляется во всех местах, где используется watch(), в данном примере это куб.

![image](https://github.com/user-attachments/assets/873e8a38-88e2-4ba7-9146-b5d96e536c05)

![image](https://github.com/user-attachments/assets/a7f3aeb4-33a9-400a-92e6-d4e08d729a90)

![image](https://github.com/user-attachments/assets/404f6e34-e285-4ca6-b7c6-0c57c1013ecc)

## Лекция 10
ColorEvent: Абстрактный класс для событий блока.
ColorChangePressed: Конкретное событие для изменения цвета.
ColorBloc: Основной блок для управления состоянием. Он обрабатывает событие изменения цвета и эмитирует новый цвет, используя Util.randomColor().
BlocProvider: Предоставляет блок в дереве виджетов, чтобы его можно было использовать дочерними виджетами.
BlocBuilder: Отслеживает изменения состояния блока и перестраивает виджеты при изменении состояния.

При нажатии на кнопку цвет контейнера изменяется на случайный, и текст отображает текущий цвет.

![image](https://github.com/user-attachments/assets/b137446c-aa53-429b-b78f-da59026f1193)

![image](https://github.com/user-attachments/assets/808a79f4-fdc0-4e37-8051-7b5f2ac9e2da)

![image](https://github.com/user-attachments/assets/3b67b3ea-d1c7-4d1b-b089-567b7bf26cd5)

## Лекция 11
Использую path_provider для получения директории для хранения файлов. Запись и чтение данных происходит с помощью класса File из библиотеки dart:io.
Использую пакет shared_preferences для сохранения и загрузки счетчика.
Использую пакеты sqflite и path для создания и работы с базой данных SQLite. БД хранит список пользователей с возможностью добавления новых пользователей.

В приложении можно ввести текст и сохранить его в файл. Увеличивать значение счетчика, используя shared_preferences. Добавлять пользователей в базу данных SQLite и отображать их список.

![image](https://github.com/user-attachments/assets/74c6d64b-d866-4545-8031-c6fdec055324)

## Лекция 12
Data Layer отвечает за сохранение данных.
Domain Layer обрабатывает бизнес-логику.
Presentation Layer строит UI и управляет состоянием.

![image](https://github.com/user-attachments/assets/baa4d959-9a87-410a-b9ba-a62042cc57d5)

![image](https://github.com/user-attachments/assets/9c87c49c-53e0-4bf8-8f2b-94edbccc8729)

## Лекция 13

![image](https://github.com/user-attachments/assets/e0f27374-3b8a-4c66-b231-f910fda79e88)

## Лекция 14

![image](https://github.com/user-attachments/assets/566c4488-3f69-4f96-bdf0-ff0896572d41)

![image](https://github.com/user-attachments/assets/2a1d7b2c-4f49-4a6f-91c9-93ae29b1c00d)

![image](https://github.com/user-attachments/assets/911e2282-e1b4-4dac-8440-188dbc00c11f)

![image](https://github.com/user-attachments/assets/21f944df-25be-4adf-b75e-ce8b945ea1eb)

![image](https://github.com/user-attachments/assets/2af66413-03dd-4c64-99ec-67b98234c155)

![image](https://github.com/user-attachments/assets/bb8e402b-6e13-45a2-9699-f150c506da48)
