## Бизнес идеи
- Возможность самостоятельного использования
- Возможность синхронизации нескольких человек
- Возможность использования сервера компании для ведения учета
- Возможность выделять определенные траты в группы
- Возможность ведения совместного учета, но с приватными кошельками
- Возможность группировать расходы по категориям\дате\пользователю
- Возможность просмотра графиков по времени (time spent)
>> для возможности просмотра отчета в какое время наибольшее кол-во трат
- Возможность ведения займов\кредитов
- Уведомление о ежемесячных платежах
- предупреждать пользователей что имеются платежные обязательства
- регистрация доменного имени и решение вопроса хостинга  
> О_о шта?

- учет 
- - доходов денег
- - расходов денег
- - перемещений денег
- - обмен валюты
- - долги (дали, вернули, взяли, вернули)
- по
- - кошелькам и счетам
- - по долгам (контактам)
- - по тегам
- бюджет доходов и расходов по месяцам (или другим периодам)
- отчетность по остаткам, аналитике, сравнение с бюджетом
- автоматическое напоминание о приближающемся, или наступившем превышении бюджета

На подумать вот что у меня есть предложить:

Установка
1. Сервер, бакенд - это setup.php, где создается база, например в майскуле
2. Локальное приложение, оно же веб приложение - тоже setup.php
3. мобильное приложение - плеймаркеты, аппсторы

## Идеи для бэкенда
- Определяемся в языке
- Предлагаю учеть мультиплатформенность - чтобы можно было поставить и на локальный виндовый комп, и на линуховый сервант
>> предлагаю PHP, с ним знаком я и ilius33 и Voltos, + низкий порог вхождения для привлечения khoser
- Необходимо предусмотреть установочник на сторонние хостинги (setup.php)
## Идеи для фронтенда
- JS+HTML+CSS+VUEJS
- Страница ввода операции делится функционально на две:
- - Для вода суммы общего чека, выбирается общая категория, пишется обобщенное название
- - Для ввода стоиомсти каждого товара из чека с возможностью выборка категории под каждый товар
- - Все товары одного чека групируются по id "итерации" что бы в дальнейшем можно было посмотреть сумму затрат итерации
- - Теги расставленные на каждую позицию чека являются суммируютсядля итерации
## Идеи для веб приложения
- Авторизация по одноразовому паролю (отправка на email)
- Кроссбраузерная и адаптивная верстка (bootstrap 3)
- Регистрация email и телефон?
## Идеи для мобильного приложения
- Возможность работы offline
- Чтение смс
- Сканирование чеков с распознаванием
- Возможность синхронизации приложений одной группы пользователей без доступа к сети
>> по средствам Bluetooth или NFC
- Push Уведомление о тратах других участников

>> выделить главное что будет реализовано в v 1.0
