------

# Целочисленный сумматор с AXI-Stream интерфейсами

------

### Зависимости

- make
- Icarus Verilog
- GTK Wave

------

### Структура каталогов

- src - исходники сумматора
- tests - исходник тестового окружения
- docs - документация

------

### Ветки репозитория

- main - TODO
- comb-adder - комбинационный сумматор
- reg-adder - сумматор с регистровыми входами и выходом
- validi-adder - сумматор с входным сигналом валидности данных
- validio-adder - сумматор с выходным сигналом валидности данных
- axis-adder-v1 - сумматор с AXI-Stream интерфейсами. Блок управления состоит из одного автомата
- axis-adder-v2 - сумматор с AXI-Stream интерфейсами. Блок управления состоит трех отдельных автоматов
  
------

### Цели в Makefile

- all - сборка, моделирование и вывод waveforms

- build - сборка исходников сумматора и тестового окружения
- sim - запуск моделирования
- wave - отображение дампа waveforms через GTK Wave 
- clean - очистка репозитория

 

------

