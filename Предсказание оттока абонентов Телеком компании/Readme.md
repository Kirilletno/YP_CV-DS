# Предсказание оттока абонентов Телеком компании

## Цель исследования — 
Обучить модель, способную предсказать, разорвет ли клиент договор с компанией.

## Описание проекта
Оператор связи хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, оператору нужна модель, которая будет предсказывать, разорвёт ли абонент договор. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и услугах. Задача — обучить на этих данных модель для прогноза оттока клиентов. 

## Итоги исследования:

Лучший итог по обучению, показала модель полносвязной нейронной сети на 4300 эпох
При этом, модель согласно интерпретации матрицы ошибок, лучше предсказывает то продолжит ли клиент пользоваться услугами компании, что также важно учитывать при дальнейшем использовании системы

Основным фактором, влияющим на решение клиента явлются его расходы. И исходя из того, что по видимому изначально на момент подключения клиентов устраивала цена, затем спутся несколько месяцев использования они отказываются от услуги, причиной этому может быть повышение стоимости в ходе использования. К такому выводу можно прийти исхдя из того, что помимо суммы платежа, одним из самых важных факторов является вариант работы с оператором и именно среди тех, кто оплачивает счета связи ежемесячно, процент отказов наибольший. Это может происходить именно из-за того, что в случае других оплат клиент фиксирует на год, единую цену, в то время как, в случае ежемесячных платежей, эта сумма может расти. В качестве одним из способов решения этой проблемы, может помочь фиксация единого тарифа для клиента, по крайней мере на первые месяцы его подключения.

Также, дополнтиельно стоит обратить внимание на следующие факторы
- Наибольшее количество ушедших клиентов, есть среди пользователей, использующих тип интернет подключения- Fiber optic, компании явно стоит обратить более пристальное внимание на качество данной услуги
- Заметна явная кореляция между количеством услуг и уходом клиента из компании, чем больше у клиента доп услуг, тем меньше вероятность что он уйдет из компании

Также, в качестве бизнез рекомендации заказчику, считаю важным, обратить внимание на улучшение качества основных услуг и подключения к доп услугам большего числа пользователей. Так как насколько мы видим, большинство пользователей не пользуются доп услугами оператора, но при этом среди использующих доп услуги, число отказников значительно меньше и этот процент снижается по мере роста числа доп услуг, подключенных у клиентов, из чего можно сделать вывод, что клиент более погруженный в доп сервисы оператора, с мерньшей вероятностью уйдет от него, нежели другие клиенты.
