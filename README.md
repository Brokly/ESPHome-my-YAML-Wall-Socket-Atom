# ESPHome-my-YAML-Wall-Socket-Atom
Файл конфигурации ESPHome, для настенной розетки на ESP8285+SCE7766+Custom DS18B20

https://aliexpress.ru/item/1005004568734241.html?

https://aliexpress.ru/item/1005004568724538.html?

Возможности:
  - Контроль электрических параметров
  - Контроль внутренней температуры (требует доустановки DS18B20)
  - Кнопка вкл-выкл на корпусе
  - Дополнительная защита по току и температуре (при наличии DS18B20)
  - Восстановление режима после падения питания

У меня версия TASMOTA, прошить удаленно не получилось, пришлось подключаться проводами.
При этом пришлось времмено снимать c платы CSE7766, правда, думаю, что если, при прошивке
подавать питание в точку 5 вольт, то возможно прошьется. За одно припаял датчик 
температуры, который у меня, почему то немного греется и показывает завышенную 
(аж не 15грудусов) температуру, вот такие детали в Чип и Дипе :)
