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
