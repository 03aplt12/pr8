# Журнал событий

Выпуск	Windows 10 Домашняя для одного языка  
Версия	22H2  
Дата установки	‎22.‎10.‎2021  
Сборка ОС	19045.3086  


Для открытия журнала событий в операционной системе Windows нужно следовать этой инструкции:

1. Нажмите клавишу Win (клавиша с логотипом Windows) + R на клавиатуре. Это откроет окно "Выполнить".

2. В окне "Выполнить" введите `eventvwr.msc` и нажмите Enter или нажмите кнопку "OK". Это запустит "События Windows".

3. Откроется окно "События Windows" с панелью навигации слева и основной областью событий.

4. В левой панели навигации выберите журнал событий, который вас интересует, например:
   - "Журнал приложений и служб" для отслеживания событий, связанных с приложениями и службами.
   - "Журнал системы" для отслеживания системных событий и ошибок.
   - "Журнал безопасности" для отслеживания событий безопасности.

5. Щелкните на выбранном журнале событий, и в основной области будут отображаться связанные события и записи.

6. Вы можете просмотреть детали каждого события, дважды щелкнув на нем, или использовать функции фильтрации и поиска, чтобы найти конкретные события или записи.

Вот описание журналов Система, Приложение и Безопасность в операционной системе Windows и типы информации, которую можно найти в каждом из них:

1. Журнал Система (System):
   - В журнале Система регистрируются системные события и ошибки, связанные с аппаратными компонентами, драйверами и ядром операционной системы.
   - В этом журнале можно найти информацию о сбоях и ошибочных ситуациях, связанных с оборудованием, загрузкой системы, драйверами устройств и другими системными компонентами.
   - Примеры событий, которые можно найти в журнале Система, включают ошибки драйверов, проблемы с памятью, сетевыми соединениями или важными службами, сбои во время загрузки системы и т. д.

2. Журнал Приложение (Application):
   - Журнал Приложение содержит информацию о событиях и ошибках, связанных с установленными на компьютере приложениями и службами.
   - В этом журнале можно найти информацию о запущенных приложениях, сообщениях об ошибках, предупреждениях и других событиях, связанных с работой приложений.
   - Примеры событий, которые можно найти в журнале Приложение, включают сбои приложений, исключительные ситуации, сообщения о работе служб, информацию о запланированных заданиях и т. д.

3. Журнал Безопасность (Security):
   - Журнал Безопасность содержит информацию о событиях, связанных с безопасностью операционной системы, аутентификацией, учетными записями пользователей и аудитом системы.
   - В этом журнале можно найти информацию о попытках входа в систему, доступе к защищенным ресурсам, изменениях политик безопасности, аудите событий и других безопасностных событиях.
   - Примеры событий, которые можно найти в журнале Безопасность, включают удачные и неудачные попытки входа, создание и удаление учетных записей, изменение прав доступа к файлам и папкам, аудит действий и т. д.

Каждый из этих журналов предоставляет важную информацию для отслеживания и анализа различных аспектов работы операционной систем и приложений в Windows. Они могут быть полезны при решении проблем, выявлении ошибок, мониторинге безопасности и анализе производительности системы.