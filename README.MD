# Чтение crontab-строки

Пригодится для строкового описания параметров периодического события: например, для регламентного задания.

Результатом работы является массив значений типа Дата, соответствующих параметрам, внутри заданного диапазона, с точностью до минуты.

В отличие от знаменитой багофичи оригинального Cron'а, 
условие по совпадению дня месяца и дня недели обрабатываются не по ИЛИ, а по И, как и остальные условия,
так что можно задавать события на Пятницу, 13-е.

