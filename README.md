# Проект по алгоритмам анализа цифровых изображений
Подготовил Лепехин И.С.
# Описание проекта
Необходимо написать алгоритм по обработке анкет голосования (анкеты представлены в виде цифрового изображения), с дальнейшим применением OCR для считывания текста из нужных диапазонов таблиц анкеты.
# План реализации проекта
1) Подготовить и разметить анкеты голосования в количестве 20-25 штук, разметку произвести в CVAT, затем представить разметку в необходимом формате YOLO;
2) Обучить нейросетевой детектор YOLOv8, для определения нужных участков таблицы на изображении;
3) Далее произвести предобработку изображений с помощью библиотеки opencv;
4) Произвести считывание текстовых и числовых данных из таблицы с применением OCR;
5) Занести полученную информацию в таблицу Excel.
