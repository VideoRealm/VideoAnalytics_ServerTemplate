# VideoAnalytics_ServerTemplate
Analytics-running server template code for a [ultimately censored] app - just another bit of trash on Github      

### Шаблон ПО обработки и анализа видеопотока (контроллера сервера аналитики) 
### Функции
1.	Получение и аналитическая обработка потоков с камер путём выполнения специализированных аналитических алгоритмов;
2.	Извлечение и сохранение в БД метаданных, связанных с входными потоками; 
3.	Формирование и сохранение в БД записей, фиксирующих значимые события в потоке данных, поступающих с камер;
4.	Выдача потока в реальном времени по запросу медиасервера (с достижением  чёткости видеоизображения, установленной конкретным пользователем в рамках набора доступных опций).

Компоненты ПО в структуре интерфейсов прямого взаимодействия:
- медиасервер;
- видеокамера;
- БД записей (с видеокамер).

Рис. 1. Схема генерации и передачи видеопотока в реальном времени (live stream).
![livestream-Page-1](https://user-images.githubusercontent.com/55311053/80383614-19f93d00-88a4-11ea-9b00-16620c020dd8.jpg)

