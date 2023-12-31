# Теоретическое задание №2
## Вариант 4
## Условие задания:
Какие есть способы экономить в облаке? Объясните подробно разницу между моделью
использования по требованию (on demand) и резервацией мощностей (reserved). Есть ли другие модели использования облака?

**Способы экономить в облаке:**

- На этапе тестирования (пробного периода) внимательно сравнить информацию о загрузке ресурсов, которая предоставляется бесплатно из сервиса мониторинга, с данными Биллинга в денежном выражении. Это поможет определить, когда были запущены и оплачены лишние виртуальные машины (ВМ), как запускаются сервисы, на какие дни приходятся пики и плато нагрузки.
	
- Используя выгрузку в CSV и возможности сервисов анализа и визуализации данных, посмотрите, на что именно ушли деньги. На графиках хорошо видны всплески потребления баз данных.
	
- Использовать прерываемые ВМ, которые будут принудительно остановлены в течение 24 часов. Данные при этом сохраняются. Они оптимально подходят для тестовых задач или для обсчёта большого количества данных за короткое время. При этом скидка может достигать 70%. Сервис управления виртуальными машинами Instance Groups позволяет автоматизировать запуск прерываемых ВМ, и таким образом экономить
	
- Автоматизация масштабирования в Instance Groups помогает при волатильном спросе на ВМ. Вы просто настраиваете правила и задаёте условия, и сервис автоматически включает или выключает машины. Снижается риск человеческой ошибки, вероятность что-либо недоглядеть или забыть запустить.
 
- Используйте объектное хранилище для определённых типов данных вместо хранения на дисках ВМ. В частности,подобные сервисы позволяют сократить затраты на хранение бэкапов, видео- и аудиофайлов.
	

**Разница между моделью использования по требованию (on demand) и резервацией мощностей (reserved):** 
	
Модель использования по требованию (on demand) предполагает оплату только за использованные ресурсы в определенный период времени. Пользователь может мгновенно масштабировать свои ресурсы в зависимости от текущих потребностей.
	
В то время как резервация мощностей (reserved) предполагает оплату заранее за определенное количество ресурсов на определенный период времени. Это позволяет пользователю получить скидку на стоимость ресурсов в обмен на обязательство использовать их в течение определенного времени.
	
Таким образом, основное различие между этими моделями заключается в гибкости оплаты и использования ресурсов. В модели по требованию пользователь платит только за то, что использует, в то время как в модели резервации пользователь получает скидку за предварительное обязательство использования определенного объема ресурсов.

**Есть ли другие модели использования облака?**

Помимо моделей использование по требованию (on demand) и резервацией мощностей (reserved) существует модель spot instances. Spot Instances предполагает оплату по типу аукциона. Пользователи устанавливают цену, которую готовы платить за Spot Instance, и сервер уходит к тому, кто заплатил больше. Система не самая надёжная, однако скидки могут достигать 90%. Spot Instance подходит для отложенного выполнения задач, когда скорость обработки не так важна, как стоимость.

