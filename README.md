# it_interview_plan
Document created for interviewing backend developers (RUSSIAN LANGUAGE)

Документ для проведения собеседований бекенд разработчиков (НА РУССКОМ ЯЗЫКЕ)

## Общее
- Расскажи в целом о своем опыте
- Расскажи о достижениях
- Расскажи о факапах твоих или которые ты видел. Ты их решал? Как?

## В целом про веб
- я нажал кнопку в браузере. Что происходит дальше? 
- На стороне сервера?
- на стороне клиента?
- в интернете?
- сети? Протоколы? В чем разница udp/tcp? 
- Что из себя представляет HTTP?
- Какие знаешь методы и когда они используются?

## Computer science
- Какие знаешь структуры данных? массивы, стэки, очереди, связанные списки, деревья, хэш таблицы
- Что такое алгоритмическая сложность?

## Дизайн кода
- rails приложение - как организовывается код? 
- Какие знаешь паттерны?
- Что такое SOLID? Примеры?
- Как боролись со сложностью?
- Query object? service object и тд? Колбэки?
- Dry stack? Monads?
- Что такое REST?

## Тесты
- Как относишься к тестам? Пишите ли на текущем месте тесты? Какие тесты пишешь ты? Rspec?

## Code
https://www.toptal.com/ruby-on-rails/interview-questions

## Настройка приложения
- Приходилось настраивать сервак - application server, sidekiq, выбирать количество нод и тд?
- Пользовался newrelic, prometheus, appsignal? Как-то мониторил производительность, собирал собирал ошибки?
- Что такое GIL? Работал ли с потоками на рубях? Юзал ли мутексы?
- event machine?

## Базы данных SQL
- СУБД sql - с какими работал?
- Приходилось писать SQL вне active record? 
- Приходилось работать с другими либами ORM?
SQL:
 - left vs inner join?
 - having? Агрегаты? 
 - Что такое нормализация? Знаешь нормальные формы?
 - Приходилось писать подзапросы? Зачем?
 - знаешь что такое CTE?
- Что такое индекс? Преимущества и недостатки индексов, когда следует юзать? 
- Какие знаешь типы индексов?
- Что такое и как работает многоколоночный индекс?
- Подводный камень построения индекса на огромную таблицу?

## Базы данных SQL highload
- Вот у тебя есть веб приложение, там развернут rails application, puma, бд например psql. Приложение тормозит и тебя попросили посмотреть в чем дело и предложить варианты. Что бы ты сделал? (Правильного ответа нет)
- вообще какой был самый большой хайлоад? 
- Как приходилось оптимизировать?
- Оптимизация запросов? explain?
- Что такое реплики? 
- Что такое шардинг? Партиции?
- Что такое блокировки?
- Какие бывают виды блокировок?
- Какие знаешь стратегии блокировок?
- Что такое дедлок?
- Что такое multiversion concurrency control (MVCC)?
- Какие бывают уровни изоляции?

## Базы данных nosql
- Nosql? с какими работал? 
- Зачем?
- Какие юзал кеши? Что хранил там и зачем? 
- Как инвалидировал?
- Подготавливал/прогревал кэш?

## Message brokers
- Rabbitmq?
- Kafka?

## Devops
- devops - приходилось ли работать? Что делал?
- Docker?
- CI?
- Линукс в целом?


