Маленькая утилитка для скачивания новостей с www.investing.com, для обучения нейросети. Предпологается, что утилита 
будет посылать запрос для получения новостей по США, сохранять на диск список новостей в CSV, затем пробегаться 
по данному списку и вырезать ненужные новости, а в оставшихся менять заголовки на числа. Пока есть только прототипы 
класса отправляющего пост-запрос и выводящего в консоль ответ, и обработчика готового CSV-файла, который вырезает 
ненужные новости, заменяет заголовки на числа и добавляет направление графика для данной новости. Добавлены классы 
Для получения координат по адресам и составления списка точек интереса вокруг этих координат (Новая задача).
Использованы сервисы https://dadata.ru/ и http://openstreetmap.ru/.
На данный момент репозиторий состоит из прототипов классов, никак не связанных между собой, и особого интереса не
представляет. 