# wildberries_client
Клиент для работы с wildberries API

Пока готовы для версии v1.
Все описание смотрите в функциях. Досконально расписаны все поля и параметры для запросов

Для работы необходимо получить ключ x32 или x64 в кл wildberries и вызвать все функции в ноутбуке
Всю информацию по запросам взял с файла ttps://images.wbstatic.net/portal/education/Kak_rabotat'_s_servisom_statistiki.pdf?abc=1612952230000

В ноутбуке можно пострить таблицы по следующим запросам:

GetStocks(dateFrom)#отправляем запрос на информацию по складу
GetSales(dateFrom,flag)#отправляем запрос на список продаж
GetOrders(dateFrom,flag) #отправляем запрос на список заказов
GetReportDetailByPeriod(dateFrom,dateTo,limit,rrdid) #отправляем запрос на получение детального отчета
GetExciseReport(dateFrom) #отправляем запрос на КиЗ. Этот запрос почему то не работает

Результат выводится в виде,которую можно сохранить в файл
