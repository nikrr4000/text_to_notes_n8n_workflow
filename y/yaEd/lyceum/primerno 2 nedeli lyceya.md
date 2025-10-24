## SPEC

- privoz ballov
- registraciya

## Selfpaced 

- registaciya

## devcodecontest

sobirayem xml from high => sozdayem ticket iz xml
So storoni vishki uchastniki mogut otkazatsya ot uchastiya
esli 

- remove_out_user - prohodimsya po ticketam=> esli ne nahodim n/s raz => esli ne nashli s raz otchislyaem
- move_data_from_yql
- lm_register_user
- lms_change_group_status_user
- create_tickets_from_xml

## kb AI (AI)

### Alerts

- raz v den otpravlyaetsa alert o nesostikovke v ticketfh (tracker and course)

### otchisleniya - zachisleniya - vipusk

- manager creates xlsx
- mi prinimaem 
- and validate it

#### upast mogut:

- izmenyaetsa version of api
	- Manager prihodit
	- process padaet
	- RESHENIYE – pomenyat version
	- В апараметрах обязательны "Публикация 2035" и "ApplicationId"
- cyber sled
	- V dvux mestax
		- tracker
		- yt
- ochered kb_ai – polnost'u kostilnaya
	- Poluchaem dannie ot gosuslug
		- AI_create_tickets_and_move_new_data
	- AI_move_data
		- zapolnil li chelovek ofertu
		- soedinyaem dannie polzovatelei po snilsu
		- Esli u cheloveka ne priexali danni mb nepravilno zapolnil snils

## Lyceum

- Prom stopnuli
- new place ne dolzhen poyavitsya
	- esli companii rukami обновляет данными и робот меняет на старые, данные вероятно невалидны
	- docs generation – вне набора доп площадки маловероятны => не должен понадобиться
- Motivation
	- тикет в очереди + тикет в очереди контакст = соединяем их вместе
- groups
	- shedule 
		- таблица для сайта чтобы компании нормально обозначались
		- Если компании новые не появляются – никто не приходит чекать процесс
		- Если компании где-то нет нужно смотреть по джоинам. Если нет, они куда-то выпала
	- groups
		- close_group
		- connect_group
		- connect_prep
		- create_group
		- make table for group plan (2 sht)
			- все формы находятся в доке в арке
		- move_data_from_yql
		- Сломаться не должны:
			- union_group
			- update_group
- contacts
	- новых препов быть не должно
- company
	- не должен использоваться
- admission
	- create_tmp_table_from_yql
		- создает таблицы для процесса второго тура
- create_admission_table – создание тикетов в admission
	- оно должно ~~сломаться~~ работать
	- class ADMISSION
		- create admission ticket
			- работает на основе ticekt_to_report
			- на основе obair-594 (файлов внутри) создает тикеты
	- Поменять в конфиге create_tickets на true
	- Может понадобятся тесты
		- Код не упал
		- Данные похожи на правду 
		- Круто
		- даже создаст логи
- second tour 
	- проходится по тикетам и проверяет все ли условия ок
	- методисты чекают тикеты
- Возможные ошибки-поломки
	- нестыковки данных между yt и скриптомё


## Obshie

- Esli kod ne padaet => govno v dannix
- Esli kod upal => dezurnii reshaet pochemu upal
- 