Выполнение лабораторной: \
Группа: Бакланова Анастасия, Борисов Игнат, Крылов Дан, Улитина Мария  
Для контейнеризации решили использовать Django Framework. \
На рисунке приведено создание "плохого" докера: \
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/0349423c-7aea-4bfd-a31b-0d71de5a81f6"> \
Содержатся следующие "bad practice": \
1.Не указана конкретная версия python \
2.Использовано ADD, а не COPY \
3.Нет строки ENV Pythomunbuffered \
На рисунке два запуск "плохого" докера: \
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/7c05b21e-fc1a-451d-97db-ac7a79e8ec18"> \
Докер in use:
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/08875fbe-ebaa-46a9-a0a3-4ae874e016b6"> \
И видим запуск докера: \
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/04efac88-bf67-4350-b55b-0fcd0534e2a7"> \
Создадим "хороший" докер: \
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/a8d7b018-0329-40e2-8cc0-f2e942eaddf2"> \
В нем исправлены все "bad practice". Можем увидеть запуск "хорошего" докера \
<img width="547" alt="photo1695137667" src="https://github.com/UlitiM2/group/assets/113083737/c2c0735e-86c2-458f-aa94-73c0dcbe0822"> \
Таким образом, лабораторная работы выполнена.
