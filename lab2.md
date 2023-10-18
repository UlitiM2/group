Выполнение лабораторной: \
Группа: Бакланова Анастасия, Борисов Игнат, Крылов Дан, Улитина Мария  
Для контейнеризации решили использовать Django Framework. \
На рисунке приведено создание "плохого" докера:
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/0349423c-7aea-4bfd-a31b-0d71de5a81f6">
Содержатся следующие "bad practice": \
1.Не указана конкретная версия python \
2.Использовано ADD, а не COPY \
3.Нет строки ENV Pythomunbuffered \
На рисунке два запуск "плохого" докера:
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/7c05b21e-fc1a-451d-97db-ac7a79e8ec18">
И видим запуск докера:
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/08875fbe-ebaa-46a9-a0a3-4ae874e016b6">
